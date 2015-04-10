# Awection Theme
Simple Liferay Portal container theme to create the correct look and feel for a corresponding Portlet project. This project
is available under [Awection Portlets](https://github.com/divid3byzero/awection).

## Usage
**Note:** The theme is to be used in conjunction with Liferay bundled with a Apache Tomcat server. It will **probably** also work
using the Glassfish or JBoss bundle, but this has **not** been tested and is therefore not advised.

Basic knowledge of Liferay is helpful but not necessarily required.

1. Check out master branch
2. Compile and package using Maven with **mvn clean package**
3. Copy the resulting WAR file in the **target/** folder to </path/to/liferay>/deploy

If Apache Tomcat is already running the WAR will be immediately deployed by the Liferay deployment mechanism. Otherwise Liferay
will add the theme WAR to its deployment queue after starting Tomcat and deploy the application after starting up.

