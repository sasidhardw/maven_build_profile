Maven-Build-Profiles
This repo helps you configure pom.xml and settings.xml, to deploy the artefacts to tomcat based on the build profile i.e, DEV, QA & PROD.

Steps to run the application
Be in the project directory

mvn mvn tomcat7:redeploy -P dev




mvn mvn tomcat7:redeploy -P qa
