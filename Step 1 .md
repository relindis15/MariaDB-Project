# Create a MariaDB DB instance

## The basic building block of Amazon RDS is the DB instance. This environment is where you run your MariaDB databases

In this example, you use Standard create to create a DB instance running the MariaDB database engine with a db.t3.micro DB instance class.

Sign in to the AWS Management Console and open the Amazon RDS console at <https://console.aws.amazon.com/rds/>.

In the upper-right corner of the Amazon RDS console, choose the AWS Region in which you want to create the DB instance. In the navigation pane, choose Databases.

<img width="945" alt="ENGINE 2023-03-14 072757" src="https://user-images.githubusercontent.com/114790551/228089103-a04641f5-e99e-4476-b254-ed5bd2b2590a.png">

In Configuration, choose MariaDB.

For DB instance size, choose Free tier.

For DB instance identifier, enter database-1

For Master username, enter a name for the master user, or keep the default name.

The Create database page should look similar to the following image.

<img width="934" alt="Screenshot 2023-03-14 072938" src="https://user-images.githubusercontent.com/114790551/228090629-df58afb8-bf36-447b-8280-cd03f14e4c69.png">

To use an automatically generated master password for the DB instance, select Auto generate a password.

To enter your master password, make sure Auto generate a password is cleared, and then enter the same password in Master password and Confirm password.

<img width="949" alt="Screenshot 2023-03-14 073135" src="https://user-images.githubusercontent.com/114790551/228090715-d1bc5c60-c8b8-41cd-828d-f0f8b666daf6.png">

<img width="941" alt="Screenshot 2023-03-14 073215" src="https://user-images.githubusercontent.com/114790551/228090786-9790235b-6855-4931-b07c-92c7ae173f63.png">

In the Databases list, choose the name of the new MariaDB DB instance to show its details.

The DB instance has a status of Creating until it is ready to use.

Wait for the Region & AZ value to appear. When it appears, make a note of the value because you need it later. In the following image, the Region & AZ value is us-east-1f.

<img width="932" alt="CREATE DB 2023-03-14 072511" src="https://user-images.githubusercontent.com/114790551/228091433-b2357163-af63-4785-ac97-569c450abf2c.png">

<img width="925" alt="db creating2023-03-14 074135" src="https://user-images.githubusercontent.com/114790551/228091530-01882c7e-16dd-421b-961f-d6ab7e6877f2.png">

<img width="928" alt="db available 2023-03-14 075040" src="https://user-images.githubusercontent.com/114790551/228091655-f556ec81-fcbb-4794-a93f-86cd5671d259.png">
