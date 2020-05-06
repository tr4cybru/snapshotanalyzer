##snapshotanalyzer

Demo project to manage EC2 instance snapshots

##about

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots

##configuring

snippy uses the configuration file created by the AWS cli. e.g.

`aws configure --profile snippy`

##Running

`pipenv run python snippy/snippy.py <command> <subcommand>
--project=<PROJECT>`

*command* is instances, volumes or snapshots
*subcommand* depends on command
*project* is optional
