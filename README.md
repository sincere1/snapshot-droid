# snapshot-droid
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo and used boto3 to manage AWS instance snapshots

##Configuring

The script uses the Configuration file created by AWS cli, e.g

`aws configure --profile snapshotter`

##Running

`pipenv run python droid/droid.py <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes or snapshots
*subcommand* - depends on command
*project* is optional
