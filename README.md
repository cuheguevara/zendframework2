ZendSkeletonApplication
=======================

Introduction
------------
This is a simple, skeleton application using the ZF2 MVC layer and module
systems. This application is meant to be used as a starting place for those
looking to get their feet wet with ZF2.


Installation
------------
Afterwards, set up an alias to point to the public/ directory of the
project and you should be ready to go!

XAMPP : 
file : /xampp/apache/conf/httpd.conf
#add this
Include "conf/extra/zendframework2.conf"

on conf/extra/zendframework2.conf
Alias /zendframework2 "<path>/public"
<Directory "<path>/public">
    AllowOverride All
    Order allow,deny
	Allow from all
</Directory>