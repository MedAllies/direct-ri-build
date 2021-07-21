# direct-ri-build

 Build pom for full Java RI componentry including stock assembly. 

This contains instructions for cloing the DirectProject Java RI projects and building all components including the Stock Assembly.

## Tools

The following tools are needed to perform the full build

* Maven
* Git
* JDK 8
* Ant
* Unzip
* Tar
* JQ (optional: for automated clone of all repositories)


## Clone repositories
Each module of the Java RI is contained within its own repository.  You can either manually clone each repository, or you could create an automated script to clone all repositories.  

## Build Components
All project using maven pom.xml files for the build lifecyle.  After cloning all repositories, switch to the `direct-ri-build` directory and run the following command to build all components.

`mvn clean install`
