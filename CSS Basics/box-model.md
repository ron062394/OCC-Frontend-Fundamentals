```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Padding, Margin, Border</title>
    <link rel="stylesheet" href="./box-model.css" />
    <style>
      /* Inline Styles */
      .box {
        background-color: #02474d;
        height: 100px;
        width: 150px;
        color: white;
        font-weight: bolder;
        margin-bottom: 10px;
      }
    </style>
  </head>
  <body>
    <h2>Padding</h2>
    <div class="box box1">
      <p>This uses padding.</p>
    </div>

    <div class="box box2">
      <p>This uses the padding shorthand.</p>
    </div>

    <h2>Margin</h2>
    <div class="box box3">
      <p class="parag1">This uses margin.</p>
    </div>

    <div class="box box4">
      <p class="parag2">This uses the margin shorthand.</p>
    </div>

    <h2>Border</h2>
    <div class="mix-borders">
      <p class="my-parag">This is a paragraph.</p>
    </div>

    <div class="circle-container">
      <h2>Hi!</h2>
    </div>
  </body>
</html>
```