
Primero que nada, chequeamos nuestra versión del cli

 => ng version 

Si queremos actualizar debemos primero desinstalar la actual versión de angular-cli
*  npm uninstall -g angular-cli

hay que verificar el cache 
* npm cache verify

es muy importante limpiar el cache
*  npm cache clean
 
 es momento de instalar la Version nueva de angular

* npm install -g @angular/cli@latest

# 

si queremos instalar una versión tenemos que específicar (ejemplo: 11.0.1)
*  npm install -g @angular/cli@11.0.1
