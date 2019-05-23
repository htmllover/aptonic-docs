### How to change image and background image

**Aptonic** download package does not contain images which are there in our online demo. We are using placeholder images instead of real images. You will see the image code as mentioned below. You can replace placeholder image url with your image url like `img/your-image.jpg` or `img/your-image.svg` or `img/your-image.png`

*We only included SVG images from [Undraw](https://undraw.co/illustrations) . it's Open-source illustrations for every project you can imagine and create.
Created by -[ Katerina Limpitsouni](https://twitter.com/ninalimpi)*
#### for image
```html
<img src="your image path" alt="image alt text" class="img-fluid">
```

#### for background image
When you use background image then you should follow bellow structure `.bg-image` need to call on parent `div` and use `data-overlay` with value. This image overlay value mean the background image overlay opacity color. You can use 1 to 9 for different opacity value. For gradient overlay use this `data-overlay-gradient` 
and we have two different overlay `data-overly-top`, `data-overly-bottom`. In child `div` use this `.background-image-wraper` class and inline style for background image location path. 

```html
<section id="download" class="bg-image" data-overlay-gradient="8">
    <div class="background-image-wraper" style="background: url('img/download-bg.jpg'); opacity: 1;"></div>
    <div class="container">
        <div class="row">
            <!--SECTION CONTENTS-->
        </div>
    </div>
</section>
```



