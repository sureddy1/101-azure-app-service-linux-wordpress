# 101-azure-app-service-linux-wordpress

# Deploy a WordPress app on Web App for Container

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsureddy1%2F101-azure-app-service-linux-wordpress%2Fmaster%2Fazuredeploy.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fsureddy1%2F101-azure-app-service-linux-wordpress%2Fmaster%2Fazuredeploy.json)

This template allows you to deploy wordpress on Web App for Container which is built on top of oryx php-fpm image. These are the improvements made:

- Built based on oryx php-fpm 7.4 image
- Added Redis Server
- Added Redis PHP Extension
- Configured nginx with fastcgi cache
- Configured fastcgi cache purge
- WordPress base code on disk.
- Custom configuration to link wordpress content/plugins/themes to app service storage

Next Steps:

Please install nginx helper plugin and redis cache plugin and configure it for fully utilizing the features.



