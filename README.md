### graphicsjs
---
https://github.com/AnyChart/GraphicsJS

http://www.graphicsjs.org/?lang=ja

```js
var stage = acgraph.create('stage-container');
stage.rect(5, 5, 350, 300);
stage.circle(177.5, 205, 100);
stage.path()
  .moveTo(5, 305)
  .lineTo(175, 5)
  .lineTo(355, 305);
stage.path()
  .moveTo(175, 5)
  .lineTo(175, 305);
```

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <script src="https://cdn.anychart.com/release/v8/js/graphics.min.js"></script>
</head>
<body>
  <div id="stage-container" style="width: 400px; height: 375px;"></div>
  <script>
var stage = acgraph.create('stage-container');
stage.rect(5, 5, 350, 300);
stage.circle(177.5, 205, 100);
stage.path()
  .moveTo(5, 305)
  .lineTo(175, 5)
  .lineTo(355, 305);
stage.path()
  .moveTo(175, 5)
  .lineTo(175, 305);  
  </script>
</body>
</html>
```

```
```


