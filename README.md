<html><h2> git clone below project. </h2>
https://github.com/plusforum/docker-compose-nodejs-mysql.git

> check the docker-compose.yml file. There are two services configured to launch in container.
> We want to get these services to be deployed in Kube Cluster.
> We also to mainta the dependency of services by defining the configuration in Manifest for both services.

App Service
> Make use of configMaps and Secrets to save variable data. Use configMaps and Secrets as volumes in POD template and deploy in Cluster.
> Image is not prebuild.

mysqldb service:
> Use Dynamic storage volume (localpath) for accessing and Storing mysql data files.
> Make use of configMaps and Secrets to save variable data. 

</html>
