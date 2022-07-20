# Cliente-Servidor

- Un servidor web y un navegador web se comunican entre si mediante el protocolo HTTP.
- El protocolo HTTP incluye mensajes de respuesta, los cuales especifican el contenido de la peticion realizada.

## Modelo basico de comunicacion

1. El navegador realiza una peticion HTTP GET al servidor.
2. El navegador obtiene el codigo del documento HTML solicitado, el cual contiene la estructura de la pagina web.

## DOM

El contenido de una pagina web se estructura de forma jerarquica mediante el modelo padre-hijo

    html
        head
            link
            script
        head
        body
            div
                h1
                p
            div
        body
    html

DOM (Document Object Model es una interfaz de programacion de aplicaciones (API)), la cual permite modificar el contenido de una pagina mediante un lenguaje de programacion (JavaScript).

## CSS

Los estilos son añadidos de forma habitual a un documento HTML mediante una etiqueta <link>.

    <link rel="stylesheet" href="style.css"></link>

El codigo de un archivo .css se estrutura mediante reglas de estilo.

    .container {
        padding: 5px;
    }

    .notes {
        color: blue;
    }