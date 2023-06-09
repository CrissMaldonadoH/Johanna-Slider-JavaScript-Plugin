# Johanna-Slider-JavaScript-Plugin

Create banners in seconds with Johanna Slider.
Just download, link and create banners.

## How to use:
1. In the `<div>` tag where you will create the slider, put the "johanna" class.
2. Inside the `<div>` tag with the "johanna" class, insert an `<ul>` tag and inside it put the "transition-delay" attribute, assign a numeric value to this attribute to indicate the number of seconds it will take each image to be exposed.
3. Inside the `<ul>` tag insert as many `<li>` tags as images you need to display.
4. Within each `<li>` tag insert the `<img>` tag with its respective source.

### Example:
```html
<div class="my-slider-container">
  <div class="johanna my-other-class">
    <ul transition-delay="3">
      <li><img src="./img/img1.jpg"></li>
      <li><img src="./img/img2.jpg"></li>
      <li><img src="./img/img3.jpg"></li>
      <li><img src="./img/img4.jpg"></li>
    </ul>
  </div>
</div>
```