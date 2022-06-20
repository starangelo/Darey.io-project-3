## MERN stack implementation
### Connecting to EC2 instance
A new instance is created and connected to via git bash.
![ec2_instance](./img/1%20connect%20to%20ec2.png)

### Step one (Backend configuration)
The instance is updated to ensure smooth flow of the instance.
![updating_instance](./img/2%20updating%20instance.png)
The instance is upgraded to the latest version.
![upgrade_instance](./img/3%20upgrading%20instance.png)
Nodejs is installed in the ec2-instance.
![nodejs](./img/4%20installing%20nodejs.png)
Viewing the version of installed nodejs.
![nodejs_version](./img/5%20nodejs%20version.png)
A new directory is created.
![new_dir](./img/6%20new%20dir.png)
Enter into the newly created directory.
![inside_dir](./img/7%20inside%20newly%20created%20dir.png)
The project is initialized in the directory.
![project_init](./img/8%20project%20init.png)

### Installing expressjs
Expressjs is installed in the instance.
![expressjs](./img/9%20install%20expressjs.png)
Installing dotenv into the ec2-instance.
![dotenv](./img/10%20install%20dotenv.png)
Port 5000 is configured to give access when accessed via the web.
![port_config](./img/11%20configuring%20port.png)
Accessing expressjs content via the web.
![access_expressjs](./img/12%20expressjs%20web%20access.png)
A new directory is created inside the Todo directory and its named routes.
![new_dir](./img/13%20creating%20a%20new%20dir.png)
This newly created directory is configured to suit its specifications.
![config_dir](./img/14%20config%20for%20dir%20route.png)

### Step two (Models)
Mongodb is used for the website's database. A technology known as mongoose is installed which contains mongodb.
![install_mongoose](./img/15%20install%20mongoose.png)
From the mongodb platform, a connection string is copied and pasted on the backend of the site which will serve as the means to link the website to the database.
![mongodb_connecting_string](./img/16%20mongodb%20connecting%20string.png)
The database connectivity is tested locally and it shows that it is connected.
![mongodb_connection_successfully](./img/17%20mongodb%20connected%20sucessfully.png)
The backend functionality was tested using postman. Some of these functionalities are:
A post request which was successfully posted.
![pot_request](./img/18%20requested%20posted%20on%20postman.png)
A get request which was successful.
![get_request](./img/19%20request%20gotten%20from%20postman.png)

### Step three (Frontend creation)
A react application was created which is the java model that impliments the frontend functionalities.
![creating_react_app](./img/20%20creating%20react%20app.png)
Various deployments were made in this react application. Some of which are:
The first deployment.
![first_dep](./img/21%20first%20recat%20dep.png)
Second deployment.
![second_dep](./img/22%20second%20react%20dep.png)

### Step four (continuation of frontend creation)
A proxy web link was created so as to allow the free access of the site without having to write the entire site link.
![proxy_link](./img/23%20proxy%20config%20sucessful.png)
A directory named "components" was created in the react app so as to house the css and json files of the website frontend.
![dir_components](./img/24%20creating%20a%20comp%20in%20react.png)
Here the frontend is completed and the website is up and running locally in the terminal.
![frontend_completed](./img/25%20frontend%20completed%20and%20webpack%20compiled%20sucessfully.png)
The site is accessed via a web browser using the public IP and indicating the port which is port 3000.
![my_todo_app](./img/26%20my%20todo%20app.png)
