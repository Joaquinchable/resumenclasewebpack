1. Nota : 
   
   Se Ordenado, una carpeta por proyecto y solo esa carpeta en Vscode, sigue paso a paso el video para poder escribir el codigo correcto en cada archivo , deten el video para poder ir a tu ritmo y componer posibles errores , lee bien los pasos a seguir en este README.md y siguelos junto al video, recuerda que estos pasos son generales y tienen que ser estrictamente complementados con las intrucciones del video.

   Al final vendran unas pequeñas pruebas de conocimiento que sin problema podras responder si seguiste paso a paso las instrucciones.

   Crea un README.md en tu proyecto , copia y pega este README.md para que puedas contestar en tu proyecto las pruebas y para que puedas seguir los pasos desde tu proyecto.
     

     recuerda intalar las dependencias con      npm install

---------------------------------------
Pasos del desarrollo.

1. Crea una carpeta para tu proyecto 

2. Incia tu proyecto en un ambiente Node con los siguientes comandos :   

 npm init 

 ó

 npm init -y 

3. Intalamos dependencias : 

npm install @babel/core @babel/node @babel/preset-env babel-loader clean-webpack-plugin css-loader file-loader --save-dev

npm install html-webpack-plugin node-sass sass-loader style-loader webpack webpack-cli webpack-dev-server --save-dev 

4. Creamos los Archivos y los configuramos (Seguir el Codigo paso a paso en el video)

 webpack.config.js
 .babelrc


5. Creamos la carpeta src.

6. creamos 4 archivos dentro de src un :

 index.html 
 index.js  
 styles.scss
 imagen.jpg

( Nota: Sigue el video para ver el desarrollo del codigo en lso archivos)
 

7. Instalamos React :

npm install react react-dom

(Nota: estas seran dependencias globales)

8. Instalamos react para la configuracion del preset en babel .

npm install @babel/preset-react  --save-dev

(Nota: esta dependencias sera para el desarrollador )


9. Creamos un Carpeta que llamaremos components dentro de src y dentro de components creamos un archivo llamado test.js quedaria asi :

|src
| |-components 
|       |-Test.js 


(Nota: Sigue el video para ver el desarrollo del codigo en lso archivos)


10. Modificamos nuestros scripts de nuestro package.json con:

"build": "webpack"
"start": "webpack-dev-server --mode development --open"

11. Corremos los siguientes comandos:

npm run build   

 (Para la construcción interna de nuestro proyecto )

npm start       

 (Para visulizar nuestro proyecto en nuestro navegador )



12. Recomendaciones 

Crea una README.md con los pasos a seguir de igual manera que este repo.

Crea un .gitignore para no subir archivos y carpetas no recomendadas para un repo remoto. 



Nota : Al final tendremos una estructura de carpetas asi :

|-node-modules
|-src
|   |-components
|   |     |-Test.js
|   |-bck.jpg
|   |-index.html
|   |-index.js
|   |-styles.scss
|
|-.babelrc
|-.gitignore
|-package-lock.json
|-package.json
|-README.md
|-webpack.config.js



¡¡Listo tienes ya configurado tu proyecto en Webpack para hacer tu desarrollo en React !!

Recuerda practicar mucho para superar la curva de aprendizaje de Webpack. ¡¡Exito!!





1. Pruebas.

--------------------------------------------------------------------------

 Con tus propias palabras describe las siguientes Herramientas :

1. NODE :
2. NPM :
3. Webpack :
4. Babel :
5. node_modules :

------------------------------------------------------------------------------

Contesta la siguientes preguntas:

1.  ¿ Que son las dependencias y cuales son los dos tipos que existen ? 
2.  ¿ Que son los loaders? 
3.  ¿ Que definimos en el Entry Point ?
4.  ¿ Que definimos en el output?
5.  ¿ En que nos ayudan los pluguins ?
6.  ¿ Que es el package.json?
7.  ¿ Que es la carpeta dist?
8.  ¿ Que Archivo va en la carpta dist y cual es el fin del Archivo?
9.  ¿ como se llamara la carperta donde desarrollaremos nuestro proyecto?
10. ¿ Para que Usamos el comando npm run build?
11. ¿ Para que Usamos el comando npm start?

--------------------------------------------------------------------------------------



1. Describir linea por linea el webpack.config.js. 
2. Describir linea por linea el .babelrc
3. Describir linea por linea el src
