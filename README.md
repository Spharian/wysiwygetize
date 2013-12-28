# wysiwygetize

wysiwygetize is a simple and lightweight adding wysiwyg editor to textareas. After selecting some text, a menu appears and let you apply styles to your content.

``` javascript
    $('textarea').wysiwygetize({
        buttons: {
            bold: 'B',
            italic: 'I',
            underline: 'U',
            link: 'Link',
            h1: 'H1',
            h2: 'H2',
            h3: 'H3'
        },
        viewsource: {
            display: true,
            label: 'View source',
            class: 'viewsource-style',
            activeClass: 'active-btn'
        },
        fullscreen: {
            display: true,
            label: 'Fullscreen',
            exitLabel: 'Quit fullscreen',
            class: 'fullscreen-style'
        },
        style: 'dark'
    });
```