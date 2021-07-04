#mis Atajos de angular;
>------------------------------------------------------
>------------------------------------------------------

 npm install bootstrap --save
 npm install jquery --save
 npm install popper.js --save
 npm install mdbootstrap --save

"styles": [
              "src/styles.css",
              "node_modules/bootstrap/dist/css/bootstrap.min.css",
              "node_modules/mdbootstrap/css/mdb.min.css"
            ],
            "scripts": [
              "node_modules/jquery/dist/jquery.slim.min.js",
              "node_modules/popper.js/dist/umd/popper.min.js",
              "node_modules/bootstrap/dist/js/bootstrap.min.js",
              "node_modules/mdbootstrap/js/mdb.min.js"
            ]


* ( cambiar puerto )
>     ng serve -o --port 4300   

* ( no generar sped  )
>     --skip-tests

* ( cambiar css a scss )
>     ng new " " --style=scss

* Error: More than one module matches. Use skip-import option to skip importing the component into the closest module

Especifique el módulo con el parámetro --module. Por ejemplo, si el módulo principal es app.module.ts, ejecute esto:

>      ng g c new-component --module app 

O si se encuentra en otro directorio
>      ng g c component-name --module ../


              [ `  \]


(---------TERMINARL VST CODE-----------)

"terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe"

>------------------------------------------------------

>     ------------------SUBIR ARCHIVOS DE ANGULAR EN RIFEBASE-------------

> npm install -g firebase-tools

> firebase login

> ng build --prod

> firebase init

{
    "public": "./dist/{nombre-del-proyecto}",
}

> firebase deploy

//tutorial para ver el video
https://www.youtube.com/watch?v=Ek3LyBWtJbY

>------------------------------------------------------

>      ---------------INSTALAR FIREBASE Y SUBIR ARCHIVOS DE HTML--------------

Link del video para install firebase https://www.youtube.com/watch?v=drvXMz75k5s

dentro del proyecto abrir cmd

>$ npm install -g firebase-tools

>$ firebase logout

>$ firebase login

>$ firebase init

>$ firebase deploy


>------------------------------------------------------

>       -----------------------SUBIR ARCHIVO EN GITHUB-----------------------

*Primero

Si nos pide registar para poder hacer el uso de GitHub/ solo se tiene que escribir esto 

>$ git config --global user.name "Mateo"

>$ git config --global user.email "ememattyu12@gmail.com"

>------------------------------------------------------

> git clone (link de la carpeta en Github)

para clonar la carpeta por donde esta el proyecto.
con el nombre del repository/ y dentro de la carpeta clonada se mete el proyect y  se habre GitBash ahi


>$ ls -la

>$ git init

>$ git add . (o se puede -A)

>$ git commit -m "TypeScript "

>$ git status

>$ git push

>------------------------------------------------------

>       -------------------SUBIR UN PROYECTO DE ANGULAR EN GITHUB|----------

abrir un terminal por donde esta el proyecto y empezamos escribir estos codigos


>  git status                    -------------------Ver cambios

>  git add .                     ------Agregar archivos al Stage

>  git commit -m "mensaje"        ---------------Guardar cambios    

*  git remote add origin https://github.com/"pegar aqui el link del  repositorio de git"

* git commit -m "con el mismo nombre" 

>  git push                       -----Subir cambios al repositorio

* git push --set-upstream origin master

>  git log                         -------ver historial de commits
 



















