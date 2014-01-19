file_input_js
===
This small plugin (665 byte) is created to make cross-browser file input styling, easy. It creates a main div with two child divs. The plugin differentiate between the inputs by the "name" attribute, so it won't work before you grant your inputs a name.

***Disclaimer:*** *This isn't a styled option, but rather a "convertion" so you can style your own inputs as it fits you, with cross-browser support. You can of course use the demo-page as a starting point :)*

Demo
---
[Demo-page](http://kallehauge.github.io/file_input_js/)

Initialize
---
Include [the script](https://github.com/kallehauge/file_input_js/tree/master/js) in your project and either use the default class-names and button-text or define your own at init:

    fileInput('fi_container', 'fi_btn', 'fi_filename', 'Browse...');

Semantics
---
Based on the init, shown above, this will be the output you will get:

    <input type="file" name="file1" >

The above will be converted into:

    <div class="fi_container" name="file1">
      <div class="fi_btn">Browse...</div>
      <div class="fi_filename"> </div>
    </div>

License
---
[MIT license](https://github.com/kallehauge/flex-duck-js/blob/master/LICENSE)
