FROM tomcat
#Descarga la libreria de internet y la copia en la ruta lib de tomcat
ADD https://jdbc.postgresql.org/download/postgresql-42.2.16.jar /usr/local/tomcat/lib/
#Copia el proyecto demoHa.war en webapps
COPY demoHa.war /usr/local/tomcat/webapps/