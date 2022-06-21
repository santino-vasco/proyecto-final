//como empezar a compilar sass//

1. abrir la consola en esta carpeta con ctrl+ñ
a.npm install nodemon node-sass
b.npm init

2.abrir el archivo package.json y editarlo
a. a continuacion de && exit 1 "colocar una , presionar enter y pegar el siguiente texto:

"build-css": "node-sass --include-path scss scss/main.scss css/style.css"
"wacth-css": "nodemon -e scss -x \"nom run build-css\""

3crear las carpetas con sus repectivos archivos
a. scss/main.scss
b css/style.css

4 en la consola corre el comando 
a nmp rin build-css //por unica vez
b nmp run watch-css

5 cada vez que se quiera seguir copilando  en SASS 
a. abrir la consola con ctrl+ñ
b. npm run watch-css

//FIN