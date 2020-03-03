# snapshot-droid
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo and used boto3 to manage AWS instance snapshots

##Configuring

The script uses the Configuration file created by AWS cli, e.g

`aws configure --profile snapshotter`

##Running

`pipenv run python droid/droid.py <command> <--project=PROJECT>`

*command* is list, start or stop
*project* is optional
