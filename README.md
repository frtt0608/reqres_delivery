# delivery

sed -i "s/latest/$(Build.BuildId)/g" $(System.DefaultWorkingDirectory)/_Delivery-CI/drop/azure/deploy.yaml

VM기반으로 aks, acr 이용하여 jenkins pipeline 구축 /
Git webhook으로 pipeline 동작 /
