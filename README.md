# datapower-generic
A sample generic datapower set of files for deployment

The request file will look like this:

Example Request File
---------------------
Filename = GENERIC.req
Requester = rlange@ibm.com
TargetDomain = DEV
TemplateName = GenericMPG

##
## Parameters for the Template
## The parameters must match to the template you provide
##
GIT_REPOSITORY = https://github.com/rslangehennig/datapower-generic.git
SERVICE_NAME = AWSConsumerMPG
FROM_DIRECTORY = datapower-generic/AWSConsumerMPG/DEV/ALERTS
TO_DIRECTORY = local:///AWSConsumerMPG/DEV/ALERTS
