Underliner jQuery Plugin
========================


### Underliner ###
>v1.0.0

###Features:
Creates animated underline for links.

### Usage
First you need to include necessary files
```html
<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="underliner.js"></script>
<link rel="stylesheet" href="underliner.css" />
```

Then simply apply underliner to &lt;a&gt; elements of your choice
```html
<script>
	$('.underliner').underliner();
</script>
```

### Parameters
Animation
```html
<script>
	$('.underliner').underliner({
		direction: 'center' // Default, animation starts from center
	});

	$('.underliner').underliner({
		direction: 'left' // animates from left to right
	});
	
	$('.underliner').underliner({
		direction: 'right' // animates from right to left
	});

	$('.underliner').underliner({
		color: '#f00' /* Underline color, any valid css color.
		                 If omitted underline will be the same color
		                 as the applied element */
	});

	$('.underliner').underliner({
		duration: 400 // animation duration in milliseconds, defaults to 200
	});

	$('.underliner').underliner({
		show: true /* element appears underlined instead of animating on hover
					  defaults to false */
	});

</script>
```

### Important
May only be applied &lt;a&gt; elements which displays inline. Since this plugin mimics the background-color, please only use on solid backgrounds.

[beltslib.net](http://beltslib.net/)

### Dependencies
* [jQuery](http://jquery.com/)

License
------------
CC0 1.0 Universal Licence

Dependecies have their own licence information. Please view them before use.
