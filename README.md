# Johanna-Slider-JavaScript-Plugin
Create banners in seconds with Johanna Slider.
Just download, link and create banners.

## How to use:
1. In the `<div>` tag where you will create the slider, put the "johanna" class.
2. Inside the `<div>` tag with the "johanna" class, insert a `<ul>` tag and inside it place the "transition-delay" attribute, assign a numerical value to this attribute to indicate the time the slider will take to show all images
3. Inside the `<ul>` tag insert as many `<li> tags as images you need to display.
4. Within each `<li>` tag insert the <img> tag with its respective source.

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