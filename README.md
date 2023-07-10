# devops-exam-expressjs-mongodb-statsd 

This is an example NodeJS application that works with MongoDB

The application is a very simple list where you can add or delete values.

To install it, simply fork this repository and create an application from your GitHub repo.

That's it, the application will use the environnement variables to connect to MongoDB.

### Docker image
1. Fork github repo: https://github.com/kawinpromsopa/devops-exam-expressjs-mongodb-statsd.git
2. Create Dockerfile to build your own image.

### Provision
3. Write script any tools to provision 2 servers

#### Application server
4. Setup server to be able to run docker container
5. Setup environment as follows
	- MONGODB_ADDON_URI=mongodb://<database_server>:27017/test
	- PORT=3000
6. Run application using command "npm start"

#### Database server
7. Setup MongoDB using docker
8. Setup security to allow only application server to access database

### **Bonus** DevOps pipelines / GitOps
9. Setup Jenkins server and create 2 pipelines
	- Build docker image
	- Deploy to server
