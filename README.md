# Formulario 

## Descripción
Este es un formulario de validación desarrollado en HTML y JavaScript con CSS, que permite a los usuarios ingresar información personal y validarla en tiempo real.

## Capturas de Pantalla
![image](https://github.com/KevinMMF23/Practica2Unidad3/assets/105268123/ece6bbc2-5434-4531-a897-7b024a36a15d)

## Código de Ejemplo
A continuación, proporciono el una parte del código de mi página web, sonde se definió el estilo para la pagina.
```bash
/* Estilos generales */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
    
}

.container {
    max-width: 600px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    text-align: center;
    color: #333;
}

/* Estilos para el formulario */
form {
    margin-top: 20px;
}

.form-control {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.btn-primary {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
}

/* Estilos para mensajes de error */
.text-danger {
    color: #ff0000;
    font-size: 14px;
    margin-top: 10px;
}
```
## Preguntas y Respuestas

### 1. ¿Cómo funciona la etiqueta `<input>` en HTML y cuáles son sus diferentes argumentos?

La etiqueta `<input>` en HTML se utiliza para crear campos de entrada en formularios. Puede tener varios argumentos, como `type`, `name`, `id`, `value`, `placeholder`, `required`, entre otros.

### 2. ¿Cómo se puede configurar la etiqueta `<button>`?

La etiqueta `<button>` en HTML se configura mediante el atributo `type`, que puede ser "submit" para enviar un formulario o "button" para acciones personalizadas a través de JavaScript. También puedes configurar el contenido del botón dentro de la etiqueta, como texto o íconos.

### 3. ¿Qué es el método `addEventListener` y cómo se utiliza en este proyecto?

`addEventListener` es un método de JavaScript que se utiliza para escuchar eventos en elementos HTML y ejecutar funciones en respuesta a esos eventos. En este proyecto, `addEventListener` se usa para escuchar eventos de entrada (`input`) en cada campo del formulario. Cuando el usuario escribe en un campo, se activa una función que valida los datos en tiempo real y muestra mensajes de error si es necesario.

### 4. ¿Cómo se validan las entradas en este formulario?

Las entradas en este formulario se validan utilizando JavaScript y expresiones regulares. Cada campo tiene una función de validación que verifica si los datos cumplen con ciertos criterios. Por ejemplo, se comprueba que el ID tenga 5 dígitos exactos y solo números, que los nombres y apellidos contengan solo letras, que el teléfono tenga el formato correcto, que el correo electrónico tenga un formato válido y que la edad sea un número positivo. Los mensajes de error se muestran en tiempo real mientras el usuario escribe y se resaltan cuando se envía el formulario.
