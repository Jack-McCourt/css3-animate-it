# CSS3-animate-it
*Just-add-water CSS animation*

`CSS3-animate-it` is a bunch of cool, fun, and cross-browser animations for you to use in your projects.

## Usage
To use CSS3-animate-it in your website, simply drop `css3-animated.js` at the end of your file and `animations.css` in the head.

```html
<head>
  <link rel="stylesheet" href="animations.css">
</head>
<body>
<script type="text/javascript" src="/js/css3-animate-it.js"></script>
</body>
```


Once you have done that you can just define `animatedParent` as the parent class which is what will trigger the child class `animated`` to animate whichever animation is defined, here we are using `bounceInDown`. 

You can do a whole bunch of other stuff with CSS3-animate-it.

## Sequencing

If you want to have a set of animations start one after the other then you can set a sequence time in ms using `data-sequence` then define the order with `data-id`. 



```html
<div class="animatedParent" data-sequence="500">
  <h2 class="animated bounceInDown" data-id="1">It Works!</h2>
  <h2 class="animated bounceInDown" data-id="2">This animation will start 500ms after</h2>
  <h2 class="animated bounceInDown" data-id="3">This animation will start 500ms after</h2>
</div>
```

And some more other stuff with CSS3-animate-it. for more go through these link <a href="http://jackonthe.net/css3animateit/" target="_Blank">http://jackonthe.net/css3animateit/</a>


## License
animations.css is licensed under the MIT license. (http://opensource.org/licenses/MIT)

## Contributing
Pull requests are the way to go here. I apologize in advance for the slow action on pull requests and issues.

CSS3-Animate-it by <a href="http://jackonthe.net/" target="_Blank">Jack Mccourt</a>

