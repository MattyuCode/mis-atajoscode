
Primero que nada, chequeamos nuestra versión del ANGULAR-CLI

 > # ng v 

Si queremos actualizar debemos primero desinstalar la version actual de ANGULAR-CLI
> #  npm uninstall -g angular-cli

hay que verificar el cache 
> # npm cache verify

es muy importante limpiar el cache
> #  npm cache clean
 
 Es momento de instalar la Version nueva de ANGULAR

> # npm install -g @angular/cli@latest

# 

si queremos instalar una versión tenemos que específicar (ejemplo: v11.0.1)
> #  npm install -g @angular/cli@11.0.1

 
>------------------------------------------------------
>                      En caso que de que te tira error de REPOSITORY IN NOT CLEAN. PLEASE COMMIT OR STASH ANY CHANGES BEFORE UPDATING.
>                *  ng update @angular/core@12 @angular/cli@12 --allow-dirty
