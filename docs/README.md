# HTML PDF COMPONENT

Este es un componente personalizado que permite mostrar un archivo PDF en la página.

En este componente se trabajó con las siguientes tecnologías:

- Vtex.
- React.
- Typescript.

## imágenes del componente

![pdf](https://user-images.githubusercontent.com/87024446/219835027-b7d3939f-2973-49eb-ae8f-2b85f39021a3.png)

## Configuration 

### Paso 1 - Clonar

Realizar la clonación del siguiente repositorio:
- [Repositorio](https://github.com/Yesiblato/itgloberspartnercl-html-pdf)

### Paso 2 - Editar el Manifest.json 

Ingresar al archivo manifest.json y realizar las siguentes modificaciones en: `vendor`, `name`, `version`, `title` y `description`
como se muestra en el siguiente ejemplo: 

```js
{
  "vendor": "itgloberspartnercl",
  "name": "pdf-reader",
  "version": "0.0.1",
  "title": "Lector de PDF",
  "description": "Lector de PDF",
}
```
Además, verifique que el archivo cuente con los siguientes builders: 

```js
  "builders": {
    "react": "3.x",
    "messages": "1.x",
    "docs": "0.x",
    "store": "0.x"
  }
```
### Paso 3 - Instalar node-modules

Para realizar esta instalación de node-modules, debe estar ubicado en la carpeta de `react` de la aplicación y ejecutar el comando `yarn`, y tendrá instaladas todas las dependencias necesarias para usar esta plantilla.

### Paso 4 - Ejecutar el preview

Despues de realizar los pasos anteriores puede verificar si su componente está funcionando ejecutando el comando `vtex link` si todo funciona correctamente deberá ver en consola `Sending locale change event`.

Si la consola muestra algún error, por favor verificar los pasos anteriores y vuelva a ejecutar `vtex link`.

### Paso 5 - Implementar el componente

Por último, para utilizar el componente debe agregarlo a las `dependencies` en el `manifest.json` de su tienda (store-theme) de la siguiente manera:

- vendor.name : version. 

Por ejemplo: 
```js
  "dependencies": {
    "itgloberspartnercl.pdf-reader": "0.x",
  }
```

## Contributors ✨

Yesica Johana Blanco Torregrosa
