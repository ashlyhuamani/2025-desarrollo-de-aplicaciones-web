## PRIMERA SEMANA
los archivos bosicos en un proyecto web deben ser 
- archivo .html
- archivo .css
- archivo .js

>[!TIP]
A medida que e proyecto creesca se pueden ir agregando mas carpetas incluyo organizalos haciendo uso de patrones de arquictectura (`MVC` , `arquictectura` , `hexagonal`)

-  que carpetas extras podemos agregar
-  por convención podemos agregar la carpeta de `assets` o tambien llamada `public`
-  que funcion cumple cada archivo dentro del proyecto web?
-  **html** este archivo es el encargado de darle la estructura al contenido de nuestra pagina web,  osea porganizar la informacion segun el tipo del contenido(texto(titulos, subtitulos,parrafos, listas, referencias,etc). imagenes, video, audio) que deseamos mostrar; `podemos decir que el html es de la pagina web, lo que el esqueleto son para el ser humano`, *lenguaje de marcado de texto*.
-  **.css** este archivo es el encargado de darle la parte visual atractiva al contenido de nuestra pagina web, osea hacer atractiva y posicionar de manera correcta el contenido, `css es la parte visual, como el maquillaje es para las mujeres` *hojas de estilos*.
-  **js** este archivo es el encargado de darle la funcionalidad a nuestra pagina web, osea el usuario puede interactuar con la informacion con el contenido mostrado, `js es de la pagina web, lo que energia electrica es para una pc`, *lenguaje de programacion para la web*.
-  **assets** en esta carpeta es el lugar donde almacenamos recursos(archivo multimedia:pdf,jpg,png,doc, icon,gif,mp3,wav,mpg4) que mostraremos en nuestra web, *carpeta de recursos permanentes*

 >[!TIP]
 la estructura inicial de mi proyecto web , si concidera que es un proyecto que escalara se debera crear una carpeta para los estilos y otra para las funcionalidades

 - que es un entrypoint?
 - es un archivo inicial que se ejucutara por defecto ojo una vez iniciado el servidor este ejecutara primero ese archivo.
 - para el caso del desarrollo web el entrypoint es el archivo `index.html`, 
 - convencion de nombres de archivos para el desarrollo web (opcional)
 - en el caso de tener unn archivo `.css` el nombre sera	`style.css`
 - en caso de tener un archivo	`js` el nombre sera `scripts.js`
