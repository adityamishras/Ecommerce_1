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
## output

https://github.com/adityamishras/Ecommerce_1/assets/136791974/60b329b6-1c2e-4f1f-a270-27a9606916a4