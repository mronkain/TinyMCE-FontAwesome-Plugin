# TinyMCE FontAwesome Plugin

###### v2.9.10

A plugin that lets you insert FontAwesome icons via TinyMCE. Currently uses FontAwesome v5 Pro and is tested on TinyMCE v4.4.2.


### Instructions
1. Make sure you have FontAwesome loaded on the page that contains TinyMCE.
2. Copy the `fontawesome` folder from this repository into your TinyMCE plugins folder.
3. Add this to your TinyMCE script:
```js
tinymce.init({
    ...
    noneditable_noneditable_class: 'fa fal',
    plugins: 'fontawesome noneditable',
    toolbar: 'fontawesome',
    extended_valid_elements: 'span[*]'
});
```

### Issues
This project is currently for my own specific use case and the current status is
a quick-and-dirty hack...
