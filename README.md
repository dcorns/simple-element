#simple-element
##An example of making a custom element using Polymer

It is assumed that node and bower are installed

make a project directory matching the name of your custom element (simple-element)
`bower init`
`bower install Polymer/polymer --save`
install polyserve `npm install -g polyserve`
create an html file matching the name of your custom element (simple-element)

Instead of the usual html start the file out with the import of polymer `<link rel="import" href="../polymer/polymer.html">`

Create your dom module tag for wrapping your elements dom. Be sure to use your element's name as the id.
`<dom-module id="simple-element">    
 </dom-module>`
 
 Outline the rest of the html inside the dom-module tag
 `<dom-module id="simple-element">
    <style>
    </style>
    <template>
        <content>
        </content>
    </template>
  </dom-module>`
  
  Finally add some JavaScript to construct our polymer object
  
  `<script>
    Polymer({
    });
  </script>`
 

