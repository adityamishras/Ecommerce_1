# E-commerce Website

An e-commerce website built with HTML, CSS, and JavaScript. This project is designed to provide a simple and effective online shopping experience.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## links

- [Visit here](https://adityamishras.github.io/Ecommerce_1)

## Screenshots

![screenshots_1](https://github.com/adityamishras/Ecommerce_1/assets/136791974/f2519b5c-d7bb-4778-b2c7-b8378200b235)

## HTML

```html
<div class="single_product_container container text-center">
  <div class="row">
    <div class="col">
      <img src="images/gallery-1.jpg" alt="" height="800px" id="mainimage" />
      <div class="small_image_container">
        <ul>
          <li>
            <img src="images/gallery-1.jpg" alt="" class="smallimg" />
          </li>
          <li>
            <img src="images/gallery-2.jpg" alt="" class="smallimg" />
          </li>
          <li>
            <img src="images/gallery-3.jpg" alt="" class="smallimg" />
          </li>
          <li>
            <img src="images/gallery-4.jpg" alt="" class="smallimg" />
          </li>
        </ul>
      </div>
    </div>
    <div class="col">
      <h1>Red Printed T-Shirts</h1>
      <h2>Rs- 2000</h2>
      <select name="" id="select">
        <option value="">Select Size</option>
        <option value="">Small</option>
        <option value="">Medium</option>
        <option value="">Large</option>
        <option value="">Xl</option>
        <option value="">XXl</option>
      </select>
      <input id="smallcontainer_input" type="number" value="1" />
      <div class="product_details">
        <h2>Description</h2>
        <p>
          Elevate your casual wardrobe with our Red Printed Cotton T-Shirt.
          Designed for comfort and style, this t-shirt features a vibrant red
          color with a striking printed design that sets you apart from the
          crowd. Perfect for everyday wear, it combines a modern aesthetic with
          a soft, breathable fabric to keep you comfortable all day long.
        </p>
        <ul>
          <h2><b>Features:</b></h2>
          <li><b>Color:</b> Red</li>
          <li><b>Design: </b>Unique printed graphic on the front</li>
          <li><b>Neckline:</b> Crew neck</li>
          <li><b>Fit:</b> Regular fit</li>
          <li><b>Hemline:</b> Straight hem</li>
          <li><b>Material:</b> 100% Cotton Care Instructions: Machine</li>
          <li>wash cold,</li>
          <li>tumble dry low</li>
        </ul>
      </div>
    </div>
  </div>
</div>
```

##JavaScript

```javascript
<script>
      let mainimage = document.getElementById("mainimage");
      let smallimg = document.getElementsByClassName("smallimg");
      smallimg[0].onclick = function () {
        mainimage.src = smallimg[0].src;
      };
      smallimg[1].onclick = function () {
        mainimage.src = smallimg[1].src;
      };

      smallimg[2].onclick = function () {
        mainimage.src = smallimg[2].src;
      };
      smallimg[3].onclick = function () {
        mainimage.src = smallimg[3].src;
      };
    </script>
```
