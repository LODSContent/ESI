## Preparar Cloud Shell para su uso posterior
1. Inicie sesión en Azure Portal (+++https://portal.azure.com/?l=es.es-es+++) con las siguientes credenciales:

    |||
    |--|--|
    |Nombre de usuario|+++@lab.CloudPortalCredential(LabUser).Username+++|
    |Contraseña|+++@lab.CloudPortalCredential(LabUser).Password+++|

1. En la barra de herramientas de la parte superior de Azure Portal, seleccione el icono **Cloud Shell**.

1. En el cuadro de diálogo de Bienvenido a Azure Cloud Shell, seleccione **Bash**.

1. En la pantalla No tiene ningún almacenamiento montado seleccione **Mostrar la configuración avanzada**.

1. En la pantalla Configuración avanzada, rellene los siguientes campos y después haga clic en **Crear almacenamiento**:

    |||
    |--|--|
    |Grupo de recursos|Un grupo de recursos que **no** es NetworkWatcherRG|
    |Cuenta de almacenamiento (crear nueva)|+++cloudshell@lab.LabInstance.Id+++|
    |Recurso compartido de archivos (crear uno)|+++shellstorage+++|
    
    >[!KNOWLEDGE] Si recibe el error que indica que el usuario inquilino ha superado la cuota, cambie la opción **Región de Cloud Shell** a otra región.

1. Cuando Cloud Shell se inicialice y abra una solicitud de texto, salga de Shell.
