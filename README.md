# MarkJax
Markdown with LaTeX parser in Javascript

# Usage

Load MarkJax into a web page by including its main JavaScript file into the page.
Place the following line in the `<head>` section of your document:
```html
<script type="text/javascript" src="https://codeassign.github.io/markjax/dist/markjax.min.js"></script>
```

Now you can write simple HTML which users `markjax`:
```html
<html>
  <head>
    <script type="text/javascript" src="https://codeassign.github.io/markjax/dist/markjax.min.js"></script>
  </head>

  <body>
    <div id="output"></div>

    <script>
      document.getElementById("output").innerHTML = markjax("# Hello\n$\LaTeX$");
    </script>
  </body>
</html>
```

Same HTML is available [here](http://codepen.io/anon/pen/XNqRLV?editors=1000).
