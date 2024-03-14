# TFG-GLPi-Proyect    
   
[![GLPI-Logo-color.png](https://i.postimg.cc/bwvyVwLL/GLPI-Logo-color.png)](https://postimg.cc/fJ6QJZG0)  

GLPI is a System developed in Free Software belonging to the category of "Software for Computer Service Management (ISMS)", mostly known by its English name "IT Service Management" (ITSM). An "ITSM" software, therefore Generally, it works as a ticketing system that encompasses the activities that are carried out by an organization to deliver services and resolve IT problems with the greatest possible added value for greater effectiveness and efficiency of the resources managed.

It is a web system that allows the administration (inventory) of the IT park (Equipment: servers, computers, peripherals, printers, multifunction devices, among others), and even the software used on the servers and computers.

GLPI is a computer solution used to monitor technological incidents in IT departments. This software is created with PHP, uses MySQL/MariaDB for the managed database, HTML in web pages, CSS in style sheets and XML to generate reports, and is distributed under the GNU/GPL version 2 license.
Among the most notable thing about it is that since it is created as Free Software and/or Open Source, the code can be executed, modified or developed and redistributed or shared freely. In this way, its creators, contributors and users can participate and benefit from its progressive development, and from additional free and open source modules on sites like GitHub.

The main purpose of using GLPI is to facilitate the work in the administration of support and ticketing, however in our case we are going to modify it to implement plugins and configurations to add new functions to be able to manage and report teams remotely where through a Own script will allow us to see the location of the device in real time, computer name and installed applications. This will provide us with personalized support for clients, we will be able to anticipate many errors.
It will allow us to create and send reports on the equipment, both components and their failures remotely. Additionally, in case the company may lose one of the equipment due to a move, this tool allows us to geo-locate it and tell you which of its branches it was sent to.
Just by running the script we can create a map of all the devices on the network and we can classify them in a previously configured database that will report all the data to our website.

# logos references tools
[![GLPI-Logo-color.png](https://i.postimg.cc/prDyfVRx/GLPI-Logo-color.png)](https://postimg.cc/Lg8HRpJ0)
[![Php-My-Admin-logo.png](https://i.postimg.cc/BnXW1YqQ/Php-My-Admin-logo.png)](https://postimg.cc/5XdKhmYZ) 
      [![feather.png](https://i.postimg.cc/3Jqm3NNf/feather.png)](https://postimg.cc/LnznTHzj)   
      [![Maria-DB-Logo-d8a208f0a889a8f0f0551b8391a065ea79c54f3a.png](https://i.postimg.cc/Wb0qc8Rz/Maria-DB-Logo-d8a208f0a889a8f0f0551b8391a065ea79c54f3a.png)](https://postimg.cc/w7TjhhjY) 
      [![fusininventory-logo.png](https://i.postimg.cc/W4MKcQNz/fusininventory-logo.png)](https://postimg.cc/Mcpty3jJ) 
      [![77b3f85d-13be-45da-ab78-67918ec7a0d0-profile-image-300x300.png](https://i.postimg.cc/4dbpZRF8/77b3f85d-13be-45da-ab78-67918ec7a0d0-profile-image-300x300.png)](https://postimg.cc/sQxM9qzS)
# 👀 References pages 👀

- https://fusioninventory.org/
- https://github.com/fusioninventory/documentation
- https://github.com/fusioninventory/fusioninventory-for-glpi/releases

# Fusion-Inventory page for download version lists and configuration
- https://github.com/fusioninventory/fusioninventory-for-glpi/releases
- https://github.com/fusioninventory/documentation


# Installation
Get the archive for your GLPI
  First, download archive:

- Recent versions (>= 0.90) : https://github.com/fusioninventory/fusioninventory-for-glpi/releases
- FusionInventory for GLPI tarball name follow this convention:

# Fusioninventory-for-GLPi

- GLPI major release (0.80, 0.83, 0.84, 0.85, etc)
- a '+' symbol
  
# FusionInventory release 


# Examples versions

- 9.5+4.0

- 10.0.0+1.0

# Installation

#  ⚠️ Warning ⚠️

- If a previous FusionInventory version is already installed, you must read the Update page.

# Important

Please, do a backup of your database before install 

Uncompress the archive into the plugin folder of GLPI. File list looks like:
```
   |- glpi    
      |- plugins  
         |- fusioninventory
            | - index.php  
            | - hook.php  
            | - inc  
            | - ...  
```         
# Installation procedure

# CLI installation (recommanded)

Run these commands from console / terminal:
```console
php bin/console glpi:plugin:install --username=glpi fusioninventory
php bin/console glpi:plugin:activate --username=glpi fusioninventory
```
# Web interface installation

- Connect to GLPI
- Go in the menu Setup > Plugins
- Install the plugin FusionInventory
- Activate FusionInventory

