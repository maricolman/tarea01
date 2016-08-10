Taller Aplicaciones Web.

Carmen Mariela Colman


```html

1. Que es el servidor?
	Es un programa a que es capaz  de atender a requisiciones y enviar una respuesta

2.Que es un protocolo dentro de la informática?
	Es un conjunto de reglas a cumplirse.	

3. Que es un servidor WEB?
	Es un programa aque es capaz de atender a requisiciones y enviar una respuesta, utilizando el protocolo HTML

4. Que es un cliente?
	Se puede definir como cualquier maquina(manipudalo por una persona) que se conecta a un servidor

5. Cual es el cliente WEB cor exelencia?

	
6. Que es HTML?
Es un lenguaje  que se utiliza para crear toda las paginas web de Internet. 


7. Que son las etiquetas?
Son Fragmentos  de texto rodeados por corchetes angulares <> que tienen funciones y usos especificos y se utilizan para escribir codigo HTLM.

8. Cuales las diferencias entre las etiquetas h1, h2, h3, h4, h5, h6?
<h1> texto muy grande ,
 el <h2> texto grande , 
 <h3> texto algo más grande de lo normal,
  <h4>texto normal ,
  <h5> texto pequeño ,
  <h6> texto muy pequeño.


9. Con que etiqueta se agrega una imagen a un documento HTML?
 <img> 

10. Con que etiqueta se agrega un video en un documento HTML?
 <video>

11. Con que etiqueta se agrega un sonido a un documento HTML?
<audio>

12. Con que atributo se indica a la imagen que se utiliza dentro de una etiqueta de imagen?

Una de las primeras ventajas que nos ofrecen estas etiquetas es la de utilizar formatos diferentes, dependiendo del soporte del navegador. Así pues, podríamos hacer algo como esto:
<picture>
  <source srcset="imagen.webp"> <!-- Formato WebP -->
  <source srcset="imagen.jxr"> <!-- Formato JPEG XR -->
  <img src="imagen.jpg" alt="Descripción de la imagen"> <!-- Fallback -->
</picture>
13. Como se indica al navegador que el documento esta escrito en ingles?
Idioma en el que está escrita la página. Se usan las iniciales como: es_ES: español España, en_US: ingles americano

14. Que es una lista ordenada?
elementos relacionados se muestran siguiendo un orden determinado.
En todos estos casos, la lista más adecuada es la lista ordenada, que se define mediante la etiqueta <ol>. Los elementos de la lista se definen mediante la etiqueta <li>, la misma que se utiliza en las listas no ordenadas.
<ol>
  <li>Enchufar correctamente</li>
  <li>Comprobar conexiones</li>
  <li>Encender el aparato</li>
</ol>


15. Que es un alista no ordenad?
Las listas desordenadas funcionan de manera similar a las ordenadas. La diferencia básica es que en el caso de las listas desordenadas no existen relaciones jerárquicas entre los elementos del elenco, por lo cual no se prevén ordenaciones progresivas como las obtenidas mediante números o letras.

Las listas desordenadas constan de una sola marca de apertura y cierre <UL></UL> y tantas marcas de lista como voces hay que ordenar <LI>. La sintaxis correcta para definir una lista desordenada es:

<UL>
<LI> Primera voz del menú
<LI> Segunda voz del menú
<LI> Tercera voz del menú
</UL>

16. Como se indica un parrafo?
<p>	Define una parte que debe mostrarse como un párrafo.


17. Como se indica la negrita, la cursiva, el subrayado, el tachado, el subindice y el superindice?

NEGRITA
*Existen dos etiquetas que hacen que nuestro texto se convierta en negrita. La utilización de cualquiera de ellas es en principio indiferente (aunque pueda atribuírseles un significado diferente a cada una de ellas no vamos a prestarle atención a esto ahora). La primera es la etiqueta <b> y la otra es la etiqueta <strong>.
CURSIVA
*Para escribir un texto en cursiva se ha utilizado mucho en el pasado la etiqueta <i> (que por supuesto debes cerrarla con la etiqueta </i>). También se ha utilizado la etiqueta <em>. Como en el caso de la negrita, aunque podrían atribuírseles distintos significados no vamos a prestarle atención a esta cuestión ahora. Aquí presentamos un ejemplo:

+SUBRAYADO U (DEPRECATED)
*Para que la palabra o el texto quedara subrayado se usó en el pasado el rodearlo con la etiqueta <u> y cerrarlo con su correspondiente etiqueta </u>. Así se subrayaría una frase:

*SUPERÍNDICES Y SUBÍNDICES

Mediante HTML también podemos escribir expresiones con símbolos matemáticos. Gracias a las etiquetas siguientes podrás escribir subíndices y superíndices fácilmente. La etiqueta <sub> te servirá para escribir un subíndice y <sup> será la etiqueta para un superíndice. Así nos queda un ejemplo como el siguiente:

18. Que es Git?
es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente.


19. Que es GitHub?
es una plataforma de desarrollo colaborativo de software para alojar proyectos utilizando el sistema de control de versiones Git. El código se almacena de forma pública, aunque también se puede hacer de forma privada, creando una cuenta de pago.


21. Que es clonar un repocitorio, cual comando se utiliza?
Si deseas obtener una copia de un repositorio Git existente —por ejemplo, un proyecto en el que te gustaría contribuir— el comando que necesitas es git clone. Si estás familizarizado con otros sistemas de control de versiones como Subversion, verás que el comando es clone y no checkout. Es una distinción importante, ya que Git recibe una copia de casi todos los datos que tiene el servidor. Cada versión de cada archivo de la historia del proyecto es descargado cuando ejecutas git clone.
$ git clone git://github.com/schacon/grit.git


22. Que es un commit?
 Realiza el commit de los archivos que han sido registrados (con git-add)
      -a : Automáticamente registra todos los archivos modificados
$ git commit



23. Que es un push?
Guarda los cambios en un repositorio remoto

24. Que es la rama master?
La rama por defecto de Git es la rama master . Con la primera confirmación de cambios que realicemos, se creará esta rama principal master apuntando a dicha confirmación.


```