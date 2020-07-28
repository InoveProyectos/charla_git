![Inove banner](/inove.jpg)
Inove Escuela de Código - Trabajamos en pos de que nuestros alumnos logren sus metras personales y profesionales\
info@inove.com.ar\
Web: [Inove](http://inove.com.ar)
# Charla Git/Github! 💻
Este es un proyecto realizado que forma parte de una charla brindada a cualquiera que quiera introducirse en el mundo del uso de Git y en el control de versión de sus proyectos. Está enfocada tanto para aquellos que no tienen experiencia previa con Git como para aquellos que utilizan el sistema con alguna interfaz gráfica y desean aprender el idioma nativo de Git para su manejo por consola para poder utilizarlo en cualquier plataforma o sistema.

# Pre-requisitos 📋
Para poder poner a prueba los comandos y comenzar a utilizar Git deben previamente instalar Git en sus sistemas. Para ello recomendamos leer el siguiente instructivo:
Git: [Instructivo de instalación](https://drive.google.com/uc?id=1IhpPuwUUyzkZhi2q86S1nqp6E8F339aO&export=download)

# Enlace del video a la charla Git en un nuestro canal ⚙️
Enlace: [Charla git](https://www.youtube.com/channel/UCwMey2qq3SDpS2Sl3CnjLEA/featured?view_as=subscriber)

Enlace: [Canal de Inove](https://www.youtube.com/channel/UCwMey2qq3SDpS2Sl3CnjLEA/featured?view_as=subscriber)

# Comenzando 🚀
En este documento dejamos a diposición los comandos más utilizados a la hora de comenzar a utilizar Git, estos comandos serán los que se utilizarán duranche la charla:\

Configurar nuestras credenciales
```
git config --global user.name [mi_nombre]
git config --global user.email [mi_mail]
```
Descargar un repositorio en la nube existente
```
git clone [url_link]
```
Ver el estado actual del repositorio local
```
git status
```
Ver los cambios realizados en cada archivo
```
git diff
```
Para agregar todos los archivos de la carpeta a “staging” para hacer posteriormente un commit en git (agregar el punto al final)
```
git add .
```
Para generar un commit con los archivos en staging
```
git commit -m [mensaje]
```
Para deshacer todos los cambios actuales no commitiados (se debe agregar el punto al final)
```
git checkout .
```
Para volver descargar los cambios de un archivo en específico
```
git checkout [nombre_archivo]
```
Para poder ver el historial de cambios y commits realizados
```
git log
```
Para poder ver el historial de cambios y que archivos se modificó
```
git log -p
```
Para subir los cambios de nuestro repositorio local al repositorio remoto
```
git push
```
Para bajar los cambios del repositorio remoto a nuestro repositorio local
```
git pull
```
Para sincronizar el repositorio local con el remoto y poder ver el historial de cambios (sin descargarlos)
```
git fetch
```
Para bajar los cambios de repositorio remoto distinto al definido por defecto a nuestro repositorio local
```
git merge [nombre_del_repo_remoto]/master
```
Para sacar un archivo agregado a staging
```
git reset [nombre_archivo]
```
Para deshacer un commit local que no se haya pusheado
```
git reset HEAD~1
```

# Lista completa de comandos [para avanzados] 🔧
Enlace: [Lista completa de comandos](https://drive.google.com/file/d/1IW5lK8g3fdd7GU1zUOXWeLouFa2XmZ2z/view?usp=sharing)

# Autores ✒️
### Miembros de Inove (coding school)
:octocat: Hernán Contigiani 

:octocat: Hector Vergara

# Licencia 📄 :balance_scale:
Este proyecto está bajo la Licencia de Inove (coding school) para libre descarga y uso. Este proyecto tiene un propósito educativo y de muestra, por ello, no nos responsabilizaremos por su uso indebido. Así mismo, no existe garantía en su implementación debido a que se trata de una demostración de uso gratuito con propósitos educativos. 
### :copyright: Inove (coding school) 2020.


# Muchas gracias!
Espero hayan disfrutado de esta charla, cualquier duda o sugerencia pueden contartarse con Inove al mail info@inove.com.ar
o ingresar a nuestra página [Inove](http://inove.com.ar).

Seguinos en las redes

[![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]
[![alt text][4.1]][4]
[![alt text][5.1]][5]

[1.1]: https://github.com/InoveProyectos/Buscador-Alquileres-Python/blob/master/assets/facebook.png
[2.1]: https://github.com/InoveProyectos/Buscador-Alquileres-Python/blob/master/assets/instagram.png
[3.1]: https://github.com/InoveProyectos/Buscador-Alquileres-Python/blob/master/assets/twitter.png
[4.1]: https://github.com/InoveProyectos/Buscador-Alquileres-Python/blob/master/assets/linkedin.png
[5.1]: https://github.com/InoveProyectos/Buscador-Alquileres-Python/blob/master/assets/youtube.png

[1]: https://web.facebook.com/inovecode/
[2]: https://www.instagram.com/inovecode/
[3]: https://twitter.com/inovecode
[4]: https://www.linkedin.com/company/inovecode/
[5]: https://www.youtube.com/channel/UCwMey2qq3SDpS2Sl3CnjLEA/featured

