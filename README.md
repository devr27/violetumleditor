How to compile
===================================

This is developped in Java and is packaged with Maven.
So, prerequisites are :
+ Java Development Kit 8 or greater (http://www.oracle.com/technetwork/java/javase/downloads/index.html)
+ Maven 3 or greater (http://maven.apache.org/)
 
Once you grabbed the source code (git pull), just run 'mvn clean package' from the root directory. This command will compile and package everything. 

As project is composed of several sub-projects (plugins, products, etc...), it is organized as a main maven project (parent) with modules (children). 
