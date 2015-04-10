# Awection Theme
Simple Liferay Portal container theme to create the correct look and feel for a corresponding Portlet project. This project
is available under [Awection Portlets](https://github.com/divid3byzero/awection).

**Note:** The theme is to be used in conjunction with Liferay 6.2 GA 3 bundled with a Apache Tomcat server. It will **probably** also work using the Glassfish or JBoss bundle, but this has **not** been tested and is therefore not advised. The correct version can be downloaded from [here](http://sourceforge.net/projects/lportal/files/?source=navbar). If you've never used Liferay before, I suggest you read the according documentation [here](http://www.liferay.com/documentation/liferay-portal/6.2/user-guide).

## Usage
1. Check out master branch
2. Compile and package using Maven with **mvn clean package**
3. Copy the resulting WAR file in the **target/** folder to **/path/to/liferay**/deploy

If Apache Tomcat is already running the WAR will be immediately deployed by the Liferay deployment mechanism. Otherwise Liferay
will add the theme WAR to its deployment queue after starting Tomcat and deploy the application after finishing the start-up routine.

