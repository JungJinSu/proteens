###

~~~
$ aws configure

$ vi ~/.aws/credentials
[proteens]
aws_access_key_id = AKIA2OMX2RPDH3VH35BW
aws_secret_access_key = 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

$  vi ~/.aws/config
[profile proteens]
region = ap-northeast-2
$ aws sts get-caller-identity --profile proteens

~~~
