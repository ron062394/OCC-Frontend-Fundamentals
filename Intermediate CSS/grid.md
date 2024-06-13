```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Grid</title>
    <style>
      html {
        font-size: 16px;
      }

      body {
        background-color: #e3d9c1;
      }

      .gridContainer {
        padding: 20px;
      }

      .gridItem {
        background-color: #fff;
        border: 1px solid #ccc;
        border-radius: 8px;
        padding: 20px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease;
      }

      .gridItem:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
      }
    </style>
    <link rel="stylesheet" href="./grid.css" />
  </head>
  <body>
    <div class="gridContainer">
      <div class="gridItem gridItem1">Home</div>
      <div class="gridItem gridItem2">About Us</div>
      <div class="gridItem gridItem4">Contact Us</div>
      <div class="gridItem gridItem4">Mission</div>
      <div class="gridItem gridItem5">Vision</div>
      <div class="gridItem gridItem6">Cart</div>
      <div class="gridItem gridItem7">Events</div>
      <div class="gridItem gridItem8">Testimonials</div>
      <div class="gridItem gridItem9">Support</div>
      <div class="gridItem gridItem10">Careers</div>
      <div class="gridItem gridItem11">Product 1</div>
      <div class="gridItem gridItem12">Product 2</div>
      <div class="gridItem gridItem13">Product 3</div>
      <div class="gridItem gridItem14">Product 4</div>
      <div class="gridItem gridItem15">Product 5</div>
      <div class="gridItem gridItem16">Product 6</div>
      <div class="gridItem gridItem17">Product 7</div>
      <div class="gridItem gridItem18">Product 8</div>
      <div class="gridItem gridItem19">Product 9</div>
      <div class="gridItem gridItem20">Product 10</div>
      <div class="gridItem gridItem21">Product 11</div>
      <div class="gridItem gridItem22">Product 12</div>
      <div class="gridItem gridItem23">Product 13</div>
      <div class="gridItem gridItem24">Product 14</div>
      <div class="gridItem gridItem25">Product 15</div>
    </div>
  </body>
</html>
```
