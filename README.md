# Docker Compose for Public Cloud

クラウドが提供するdockerを試した時のdocker composeファイルです。AWSとAzureでは、多少文法が異なるため、それぞれ別のファイルとして定義しています。

| ファイル名 | 対象クラウド |
| --------- | --------- |
| docker-compose-aws.yml | AWS |
| docker-compose-azure.yml | Azure |

### 関連サイト

* [AWC ECSでdocker composeを設置する方法](https://www.haneca.net/how-to-deploy-docker-compose-on-awc-ecs/)
