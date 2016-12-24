This is my travel website

## Jekyll

The website must be rebuilt after any change,

    jekyll build

To publish the website

    git add .
    git commit -a
    git gh _site

## Responsive Image

The jekyll has response-image plugin installed. To use responsive image, 
add image to the markdown like this,

    {% responsive_image path: images/d11/honolulu_pano.jpg %}

Wechat doesn't understand responsive image, you have to add your thumbnail as 
normal image like this,

     ![photo]({{site.url}}/images/d11/route_honolulu2.jpg)

