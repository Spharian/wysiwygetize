# wysiwygetize

wysiwygetize is a simple and lightweight plugin adding wysiwyg editor to textareas. After selecting some text, a menu appears and let you apply styles to your content.

## Configuration
``` javascript
$('textarea').wysiwygetize({
    buttons: {
        // values = the menu buttons labels. You can also specify which buttons you want by calling only some of them
        bold: 'B',
        italic: 'I',
        underline: 'U',
        link: 'Link',
        h1: 'H1',
        h2: 'H2',
        h3: 'H3'
    },
    viewsource: {
        display: true, // allow the viewsource feature?
        label: 'View source', // viewsource button label
        class: 'viewsource-style', // viewsource button class
        activeClass: 'active-btn' // viewsource active button class
    },
    fullscreen: {
        display: true, // allow the fullscreen feature?
        label: 'Fullscreen', // fullscreen button label
        exitLabel: 'Quit fullscreen', // quit fullscreen button label
        class: 'fullscreen-style' // fullscreen button class
    },
    style: 'dark' // change the menu appearance (dark or light)
});
```