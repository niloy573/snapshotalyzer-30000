# snapshotalyzer-30000

Python with AWS practice

##About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

##Configuring

shotty uses the configuration file created by the AWS cli. e.g.

'aws configure --profile shotty'

##Running

'pipenv run python .\shotty\shotty.py <command> <--project=PROJECT>'

*command* is instances, volumes or snapshots 
*subcommand is list, start, stop
*project* is optional