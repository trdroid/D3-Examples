

** The following does not work **

```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="selections" content="Using D3.js selections">
  </head>
  <body>
    <div id="id1">Item 1</div>
    <div id="id2">Item 2</div>
    <div id="id3">Item 3</div>
    <div id="id4">Item 4</div>
    <div id="id5">Item 5</div>
    <script src="https://d3js.org/d3.v4.min.js"></script>
    <script>
      d3.selectAll('body#id3').style('font-style', 'italic');
    </script>
  </body>
</html>
```
