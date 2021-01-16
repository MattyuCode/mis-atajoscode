#mis Atajos de angular;
<!-- -------------------------------------->
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


( cambiar puerto )
ng serve -o --port 4300   

              [ ` ]


(---------TERMINARL VST CODE-----------)

"terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe"

<!-----------------------SUBIR ARCHIVOS DE ANGULAR EN RIFEBASE------------------------------------>
//SUBIR UN ARCHIVO EN (FIREBASE-DE-ANGULAR)

npm install -g firebase-tools

firebase login

ng build --prod

firebase init

{
    "public": "./dist/{nombre-del-proyecto}",
}

firebase deploy

//tutorial para ver el video
https://www.youtube.com/watch?v=Ek3LyBWtJbY

<!---------------INSTALAR FIREBASE Y SUBIR ARCHIVOS DE HTML-------------------------->

Link del video para install firebase https://www.youtube.com/watch?v=drvXMz75k5s

dentro del proyecto abrir cmd

>$ npm install -g firebase-tools

>$ firebase login

>$ firebase init

>$ firebase deploy



<!--------------SUBIR ARCHIVO EN GITHUB-------------->
PRIMERO
============si te pide resgistrar/ digitar esto=================

(((((((((((((((((DENTRO DEL PRYECTO))))))))))))))))))))))))))
C:>$ git config --global user.name "Mateo"

C:>$ git config --global user.email "ememattyu12@gmail.com"

===============================================================
> git clone --------link del repository---------
para clonar la carpeta por donde esta el proyecto.
con el nombre del repository/ y dentro de la carpeta clonada se habre GitBash



c:>$ ls -la

c:>$ git init

c:>$ git add . (o se puede -A)

c:>$ git commit -m "TypeScript "

c:>$ git status

c:>$ git push
