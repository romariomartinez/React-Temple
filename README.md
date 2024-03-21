# Template Básico de React

Este es un proyecto de React básico que proporciona un punto de partida para desarrollar aplicaciones web utilizando React.

## Cómo utilizar este template

Sigue estos pasos para utilizar este template en tu proyecto:

1. **Clonar el repositorio**: Clona este repositorio en tu máquina local utilizando Git.

   ```bash

   pero antes revisa si tienes node.js instalado en tu pc con este comando

   node --version y con el sabras si esta isntalado y su version, luego si seguir con los pasos


   git clone https://github.com/tu-usuario/template-basico-react.git

2. **Instalar dependencias**: Navega al directorio del proyecto y utiliza npm para instalar las dependencias.
    cd template-basico-react
    npm install

3. **Ejecutar la aplicación**: Utiliza npm para ejecutar la aplicación en un entorno de desarrollo local.
   npm start
   la tendras disponible en tu http://localhost:3000

## Ya con esto tendrias el templete en tu pc listo para poder modificarlo y hacer lo que quieras dentro de el.

## Dentro de este template te encontraras un archivo llamado Dockerfiel el cual esta listo para cuando necesites contenerizar tu app, para hacerlo sigue estos pasos.

1. **Construir la imagen Docker**: Asegúrate de tener Docker instalado en tu sistema. Desde el directorio raíz de tu proyecto, ejecuta el siguiente comando     para construir la imagen Docker.
    docker build -t templatebasico:v1.0 .
    Esto creará una imagen Docker con el nombre templatebasico y la etiqueta v1.0, debes reemplazar los mnombres por el nombre que quieras ponerle a la imagen.

2. **Ejecutar el contenedor Docker**: Una vez que la imagen se haya construido correctamente, puedes ejecutar un contenedor basado en esa imagen.
    docker run -d -p 3000:3000 templatebasico:v1.0
    Esto ejecutará tu aplicación de React dentro de un contenedor Docker, y estará disponible en http://localhost:3000 en tu navegador.
    



