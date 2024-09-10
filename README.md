# delivery

sed -i "s/latest/$(Build.BuildId)/g" $(System.DefaultWorkingDirectory)/_Delivery-CI/drop/azure/deploy.yaml
