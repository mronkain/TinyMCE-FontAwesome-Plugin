# TinyMCE FontAwesome Plugin

###### v5.12.0

A plugin that lets you insert FontAwesome icons via TinyMCE. Currently uses FontAwesome v5.12.0 Pro and is tested on TinyMCE v4.6.7.


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
This project is a quick-and-dirty hack forked from josh18 and modified to run on FA 5 Pro.
It's mainly to suit my own specific needs but I can clean it up a bit if someone else has a need for this as well...
