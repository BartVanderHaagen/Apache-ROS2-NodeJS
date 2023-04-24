# Apache-ROS2-NodeJS
Web Interface for robot 

This webinterface aims to:
- serve as debug
- publish on topics 
- stream video from robot 


To install a simple web interface with Apache on Ubuntu, you can follow these steps:

Install Apache: Open the terminal and type the following command:

sudo apt-get update
sudo apt-get install apache2
# This will install Apache on your system.

sudo systemctl stop apache2
sudo systemctl start apache2
sudo systemctl enable apache2
# This will start Apache and ensure that it starts automatically on system boot.

Create a simple web interface: To create a simple web interface, paste the file "index.html" in the /var/www/html directory. 

sudo nano /var/www/html/index.html
# In this file, you can add the HTML code in this repo > to display on your web interface.

#Test the web interface: To test the web interface, open a web browser on your system and enter the IP address of your Ubuntu machine in the address bar. You should see the web interface that you created 

# That's it! You now have a simple web interface running on your Ubuntu system using Apache.
 
