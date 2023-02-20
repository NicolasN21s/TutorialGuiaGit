# TutorialGuiaGit

Paso a paso para comenzar con GIT/GITHUB

Ir a un navegador, luego ir a la page de Git (https://git-scm.com/),



![image](https://user-images.githubusercontent.com/125577159/220125061-fafd1503-ec49-426e-a5cf-cd708c1ee579.png)



ahi enncontraremos las configuraciones para descarga ya sea para Windows/Mac/Linux para asi realizar esas configuraciones en la descarga.

![image](https://user-images.githubusercontent.com/125577159/220125402-316026b3-a5eb-4328-be03-b36c5f22d9ab.png)



![image](https://user-images.githubusercontent.com/125577159/220125466-9def643e-adc6-4178-97a9-c2c135676918.png)


En mi caso es Windows.

Una vez ya descargado Git se procede hacer las configuraciones que la misma aplicacion te pide para la instalacion, en general es muy sencilla.

Luego se procede a la pagina de github  (https://github.com/), para crear tu perfil y asi tener ya un usuario para que a la hora de hacer proyectos en git podamos subirlos y se vean reflejados en Github.pueden alojar sus proyectos de software en repositorios públicos o privados. Los repositorios contienen los archivos de código fuente y la historia de los cambios realizados en el proyecto a lo largo del tiempo


Con GitHub puedes publicar tus proyectos y crear un portafolio u hoja de vida que demostrará lo que sabes. Fundamental a la hora de hacer cualquier entrevista si quieres dedicarte al desarrollo del software.

Todo esto con la ayuda de Git un sistema de control de versiones, que ayuda a gestionar los archivos guardando el proyecto, los cambios y cada una de sus versiones.

Ya teniendo Git vamos a crear un respositorio nuevo y hacer un breve resumen de comandos git.

✅ GIT INIT --> Este comando te permite inicializar un repositorio a partir de una carpeta donde tengas almacenados los archivos que quieres gestionar.

✅ GIT REMOTE ADD ORIGIN --> El comando git remote te permite crear, ver y eliminar conexiones con otros repositorios. Las conexiones remotas se asemejan más a marcadores que a enlaces directos con otros repositorios.

✅ GIT STATUS --> Te permite conocer la rama en que te encuentras, el estado de tus archivos y si es necesario actualizar el servidor remoto. Es un comando tan simple como útil.

✅ GIT ORIGIN FETCH MAIN --> Es un comando de que descarga los últimos cambios de la rama main del repositorio remoto llamado origin a tu repositorio local.
Cuando vamos a ejecutar git fetch origin main, Git descarga cualquier commit, archivo o cambio que haya ocurrido en la rama main del repositorio remoto desde la última vez que hiciste una actualización en tu repositorio local.

En resumen, git fetch es una forma útil de mantener tu repositorio local actualizado con los cambios que se han realizado en el repositorio remoto.

✅ GIT PULL ORIGIN MAIN --> Es un comando que descarga los últimos cambios de la rama main del repositorio remoto llamado origin a tu repositorio local y fusiona automáticamente los cambios descargados con la rama local correspondiente.
Cuando ejecutamos |git pull origin main|  Git primero descarga los cambios más recientes de la rama main en el repositorio remoto origin a tu repositorio local. Luego, Git intentará fusionar automáticamente los cambios descargados en tu rama local main.

Es importante tener en cuenta que debes estar en la rama que deseas actualizar y fusionar antes de ejecutar el comando git pull. En este caso, deberías estar en la rama main antes de ejecutar el comando git pull.

En resumen, |git pull| es una forma útil de mantener tu repositorio local actualizado con los cambios que se han realizado en el repositorio remoto y fusionarlos automáticamente con tu rama local correspondiente.

✅ GIT ADD (ESPACIO) (. punto) -->  Es una forma de decirle a Git que incluya todos los cambios realizados en el directorio de trabajo en el próximo commit.

Al ejecutar git add . , Git agrega los cambios realizados en todos los archivos y carpetas dentro del directorio actual y sus subdirectorios.

En resumen, git add . es un comando útil cuando deseas incluir todos los cambios realizados en el directorio actual y sus subdirectorios en el próximo commit.

✅ GIT COMMIT --> Es un comando de Git que toma los cambios realizados en la zona de preparación (staging area) y los guarda permanentemente en el repositorio Git como un nuevo commit.
Cuando ejecutas el comando git commit, se abre un editor de texto donde puedes escribir un mensaje para describir los cambios realizados en el commit. Este mensaje es una breve descripción del conjunto de cambios realizados y se utiliza para documentar la razón del commit, los cambios realizados y cualquier información relevante sobre el mismo.

⬇

GTI COMMIT -M Es una forma abreviada de usar el comando git commit para crear un nuevo commit con un mensaje de confirmación (commit message) sin tener que abrir un editor de texto. La opción -m (abreviatura de "message") le permite especificar el mensaje del commit directamente en la línea de comandos.


![image](https://user-images.githubusercontent.com/125577159/220134625-b4a199d5-67bb-46f7-8252-25598c7546dd.png)

Donde vemos ´mensaje de confirmacion´, es donde brevemente es el mensaje que describe los cambios realizados en el commit. Es importante que el mensaje sea claro, preciso y descriptivo, ya que puede ser utilizado por otros desarrolladores para entender los cambios realizados en el proyecto.


✅ GIT PUSH -U ORIGIN MAIN --> es un comando de Git que envía los cambios realizados en tu repositorio local al repositorio remoto en GitHub (u otro servidor Git). La opción -u (abreviatura de "upstream") establece una relación de seguimiento entre la rama local y la rama remota, lo que significa que en futuros push o pull, Git sabe a qué rama remota debe enviar o recibir cambios.

![image](https://user-images.githubusercontent.com/125577159/220134872-c0a91732-558e-4ef1-8c63-3876a8b5c722.png)

Es importante tener en cuenta que para utilizar git push, debes tener permisos de escritura en el repositorio remoto. Además, es posible que debas autenticarte con tus credenciales de GitHub u otro servidor Git antes de poder enviar cambios al repositorio remoto.


¡De no olvidarse! que estos comandos siempre deben de escribirse en minuscula!


Ojo, que esto es solo el primer paso, si quieres aprender a colaborar en grandes proyectos o convertirte en un experto en Git y GitHub, queda un largo recorrido aún.🧍🏻‍♂️🚲🏍🚗🏎✈🚀
