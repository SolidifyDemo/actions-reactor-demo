# actions-reactor-sample

## create app 

`dotnet new mvc --name actions-demo`


## Create environments

* test
* prod

## Variables and secrets
### SECRETS
* Repository secrets
  * AZURE_PUBLISH_PROFILE - PROD PUBLISH PROFILe
* TEST
  * AZURE_PUBLISH_PROFILE - Test slot publish profile

### Variables

* Repository leve:
  * APP_NAME = actions-demo

* Environment level:
  * TEST
    * SLOT_NAME = test
  * PROD
    * SLOT_NAME = production