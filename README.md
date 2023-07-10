# devops-exam-expressjs-mongodb-statsd 

This is an example NodeJS application that works with MongoDB

The application is a very simple list where you can add or delete values.

To install it, simply fork this repository and create an application from your GitHub repo.

That's it, the application will use the environnement variables to connect to MongoDB.

### Containerize
1. Create Dockerfile to build your own image.

### Provisioning
2. Write Infrastructure as a Code (IaC) any tools to provision 2 servers

#### Application server
3. Setup server to be able to run container
4. Setup environment as follows
	- MONGODB_ADDON_URI=mongodb://<database_server>:27017/test
	- PORT=3000
5. Run application using command "npm start"

#### Database server
6. Setup MongoDB using container
7. Setup security to allow only application server to access database

### **Bonus** DevOps pipelines
8. Setup any tools and create 2 pipelines
	- Build containerize
	- Deployment
