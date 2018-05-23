# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo and uses boto3 to manager AWS EC2 instance snapshots


## Configuring

shotty uses the Configuration file created by the AWS cli e.g .

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <commnad> <subcommand> <--project= PROJECT>`

*command* is instances, volumes, or snapshots
*subcommand* - depends on command
*project* is optional
