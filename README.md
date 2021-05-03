# angular-patternlab-bootstrap
Patternlab Starter kit with Bootstrap

# install the package
npm install

# run in the browser (it will open one tab for angular app and a second tab for the patternlab styleguide)
npm run pl:serve

# call an icon in a templat exemple:
add a maker.svg icon in source/icons
call it in your template :
```html
<svg viewBox="0 0 512 512" class="svg-marker-dims">
    <use xlink:href="/images/icons.svg#marker"></use>
</svg>
```
custom svg-marker-dims class can be customized for setting the icon dimensions.


