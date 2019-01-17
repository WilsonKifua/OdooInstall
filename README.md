# OdooInstall
 Odoo install script

# Inventory_odoo [Odoo](https://www.odoo.com "Odoo's Official website")


If it is your first time to use odoo, below guide you how to install ODOO in your linux machine
## Installation procedure

##### 1. Download the script:
```
sudo wget https://raw.githubusercontent.com/WilsonKifua/OdooInstall/master/odoo_install.sh
```
##### 2. Modify the parameters as you wish.
There are a few things you can configure, this is the most used list:<br/>
```OE_USER``` will be the username for the system user.<br/>
```INSTALL_WKHTMLTOPDF``` set to ```False``` if you do not want to install Wkhtmltopdf, if you want to install it you should set it to ```True```.<br/>
```OE_PORT``` is the port where Odoo should run on, for example 8069.<br/>
```OE_VERSION``` is the Odoo version to install, for example ```12.0``` for Odoo V12.<br/>
```IS_ENTERPRISE``` will install the Enterprise version on top of ```12.0``` if you set it to ```True```, set it to ```False``` if you want the community version of Odoo 12.<br/>
```OE_SUPERADMIN``` is the master password for this Odoo installation.<br/>

#### 3. Make the script executable
```
sudo chmod +x odoo_install.sh
```
##### 4. Execute the script:
```
sudo ./odoo_install.sh
```
