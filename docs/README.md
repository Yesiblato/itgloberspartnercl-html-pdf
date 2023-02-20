# HTML PDF COMPONENT

This is a custom component that allows you to display a PDF file on the page.

In this component we worked with the following technologies:

- Vtex.
- React.
- Typescript.
## Component's image.

![pdf](https://user-images.githubusercontent.com/87024446/219835027-b7d3939f-2973-49eb-ae8f-2b85f39021a3.png)

## Configuration 

### Step 1 - Clone

Clone the following repository:
- [Repository](https://github.com/Yesiblato/itgloberspartnercl-html-pdf)

### Step 2 - Edit the Manifest.json 

Enter the manifest.json file and make the following changes to: `vendor`, `name`, `version`, `title` and `description`
as shown in the following example:

```js
{
  "vendor": "itgloberspartnercl",
  "name": "pdf-reader",
  "version": "0.0.1",
  "title": "Lector de PDF",
  "description": "Lector de PDF",
}
```
Also, check that the file has the following builders and the dependencies:

```js
  "builders": {
    "react": "3.x",
    "messages": "1.x",
    "docs": "0.x",
    "store": "0.x"
  }
```
### Step 3 - Install node-modules.

To carry out this installation of Node-Modules, it must be located in the `react` folder of the application and execute the `yarn` command, and will have all the necessary units to use this template installed.

### Step 4 - Execute the preview.

After performing the previous steps you can verify if its component is running by running the `Vtex Link` command if everything works correctly should see in` Sending locale change event`.

If the console shows any error, please verify the previous steps and re -execute `vtex link`.

### Step 5 - Deploy the component

Finally, to use the component you must add it to the `dependencies` in the `manifest.json` of your store (store-theme) as follows:

- vendor.name : version. 

For example:
```js
  "dependencies": {
    "itgloberspartnercl.pdf-reader": "0.x",
  }
```

## Contributors ✨

Yesica Johana Blanco Torregrosa
