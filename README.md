# CSS-sprites-demo
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS sprites</title>
    <style>
        .position{
            width: 100px;
            height: 100px;
            display: inline-block;
            background: url(css_sprite.png) no-repeat;
            background-position: -5px 0;
        }
        .love{
            width: 100px;
            height: 100px;
            display: inline-block;
            background: url(css_sprite.png) no-repeat;
            background-position: -115px 0;
        }
    </style>
</head>
<body>
    <div class="position"></div>
    <div class="love"></div>
</body>
</html>
```
