# PythonApp

# How to deploy a simple Python application in AWS EC2 server.

### To package and host a simple Python application,we would need to follow these simple steps

##### 1. Spin up an ec2 instance server with tag name : ApplicationsDeploy as shown below. Select an existing key pair and Launch an instance

![Alt text](1.png)

![Alt text](2.png)

![Alt text](3.png)

![Alt text](4.png)

![Alt text](18.png)

Instance launched successfully

![Alt text](19.png)

![Alt text](20.png)

##### 2. Click on connect button to get the SSH key and connect using the termius terminal

![Alt text](21.png)

##### 3. Put an hostname on the ubuntu server (ApplicationDeploy) and install an update and upgrade as shown below

![Alt text](23.png)

![Alt text](22.png)

##### 4.Proceed to install Python ,check its version and install the npm dependencies

![Alt text](5.png)

![Alt text](6.png)

##### 5. Install the Flask

![Alt text](7.png)

##### 6.  Create a file using the vim editor and paste the Python code inside it making a slight modification to reflect "Python Application successfully deployed".Please take note of the port number : 3000 which we would be adding to the security group sooner

![Alt text](8.png)

![Alt text](9.png)

##### 7. Using the nohup function

![Alt text](15.png)

##### 8. Navigate back to your AWS instance server and click to modify the security group

![Alt text](10.png)

![Alt text](11.png)

##### 9. Click on Edit inbound rules to "Add and Save" new rule of port :3000 to allow us to connect with the application server

![Alt text](12.png)

![Alt text](13.png)

##### 10. Security group added successfully

![Alt text](14.png)

##### 11. Launch your ip address on the browser at port:3000 .You would see that the application was successfully deployed

![Alt text](image-24.png)

Congratulations !!!
