# angular-patternlab-bootstrap
Patternlab Starter kit with Bootstrap

# install the package
npm install

# run in the browser (it will open one tab for angular app and a second tab for the patternlab styleguide)
npm run pl:serve

# call an icon in a template,  exemple:
add a maker.svg icon in source/icons
call it in your template :
```html
<svg viewBox="0 0 512 512" class="svg-marker-dims">
    <use xlink:href="/images/icons.svg#marker"></use>
</svg>
```
custom svg-marker-dims class can be customized for setting the icon dimensions.

#Bootstrap classes and themes
Bootstrap is included in the syleguide so you can call the bootstrap classes in your templates and override variables to custom the bootstrap theme colors.

#custom patternlab styles
Add CSS for patternlab ONLY: source/css/pattern-scaffolding.css

#Official Patternlab Documentation
https://patternlab.io/

#use your styleguide as an external library that could be imported in any project
in your web project: npm link [path/to/patternlab-stater-kit]
then your project should import public/css.style.css, icons.svg, fonts, images

or deposit yout patternlab-starter-kit in a npm repo then install it in your project via npm install 


