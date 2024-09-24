# Conexión a BigQuery 
<u>Requisitos</u>:
1. Proyecto en Google Cloud
2. Instancia activa de Big Query
3. Cuenta de servicio con los permisos necesarios para acceder a google BigQuery (Descargar JSON de autentificación)

Acceder en el panel de servicios en el lado izquierdo:

    Data >> Platform connections >> New Connection + >> Google BigQuery

Ingresar en Formulario

Nombre: Conexion Big Query

Descripción (opcional): Conexión a Big Query para uso en analítica

Project ID: oval-plate-431019-e6

Authentication method >> Account key (full JSON snippet): Pegar el Json descargado desde Google Cloud

Test connection (botón en esquina superior derecha): una vez validada la conexión hacer click en Create (botón en esquina inferior derecha)

# Conexión a Azure SQL Server
<u>Requisitos</u>:
1. Grupo de recursos en Azure
2. Instancia activa de SQL Server
3. Base de datos SQL en instancia de SQL Server
4. Agregar Rango de IPs publicas para acceder a base de datos (solo para próposito del workshop)

Acceder en el panel de servicios en el lado izquierdo:

    Data >> Platform connections >> New Connection + >> Microsoft Azure SQL Database
    
Ingresar en Formulario

Nombre: Conexion Azure SQL Server

Descripción (opcional): Conexión a SQL Server para uso en analítica

Hostname or IP address : wkc-workshop-server.database.windows.net

Port : 1433

Database : wkc-sqlserver

User : wkc

pass : Demoaccount#01

<center>
<video width="320" height="240" controls>
  <source src="recursos/videos/conexión-BigQuery-Azure.mp4" type="video/mp4">
</video>
</center>

# Conexión a Base de Datos Oracle on-premise
<u>Requisitos</u>:

Instalación de base de datos Oracle en windows http://www.oracle.com/technetwork/database/database-technologies/express-edition/overview/index.html

1. Creación de Conexión Satelite en IBM Cloud
<center>
<video width="320" height="240" controls>
  <source src="recursos/videos/crea-conexión-satelite.mp4" type="video/mp4">
</video>
</center>


2. Instalación de Agente en sistema operativo (Guía de referencia acá: https://cloud.ibm.com/docs/satellite?topic=satellite-run-agent-locally&interface=ui)

para más información revisar acá (https://cloud.ibm.com/docs/satellite?topic=satellite-understand-connectors&interface=ui)

3. Creación de endpoint y conexión a base de datos Oracle
<center>
<video width="320" height="240" controls>
  <source src="recursos/videos/conexion-oracle-onprem.mp4" type="video/mp4" class="center">
</video>
</center>