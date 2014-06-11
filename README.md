# text-loader

A text loader plugin for webpack. Use it to load the contents of a file as a string.

e.g.

```
var template = require("text!./template.html");
```

The plugin is trivial, but is useful for supporting the use of the require.js text! plugin in existing projects.