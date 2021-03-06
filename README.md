[![Build status](https://travis-ci.org/arodic/io-object.svg?branch=master)](https://travis-ci.org/arodic/io-object)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/arodic/io-object)


## &lt;io-object&gt;

`io-object` is a simple editor for javascript objects.
By default, it uses `io-value` element for string, number and boolean editors.
It can be configured to use any other element as property editor.

Example:

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="io-object.html">
    <link rel="import" href="demo/io-object-demo.html">
    <style>
    io-object {
      display: block;
      margin: 1px;
      border: 1px solid #eee;
    }
    </style>
    <div id="container">
      <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<io-object expanded></io-object>
```

Preview:

![io-object preview]( https://raw.githubusercontent.com/arodic/io-object/master/preview.png "io-object preview")
