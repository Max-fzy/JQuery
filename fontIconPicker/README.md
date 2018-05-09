jQuery fontIconPicker v1.0 is out
==============

![fontIconPickers](/fontIconPicker/demo/image.jpg)

## How it works
 Just include a copy of jQuery, the fontIconPickers script, the fontIconPickers theme and your Font Icons. Now you can trigger it on aINPUT[type="text"]` element.

### Include the JavaScript
 ```html
 <!-- jQuery -->
<script type="text/javascript" src="js/jquery-1.9.1.min.js"></script>

 <!-- fontIconPicker JS -->
<script type="text/javascript" src="js/jquery.fonticonpicker.min.js"></script>

Include core DATA JS
<!-- fontIconPickerData JS -->
<script type="text/javascript" src="js/fonticonpicker.js"></script>

### Include the CSS
```html
<!-- required default theme -->
<link rel="stylesheet" type="text/css" href="css/jquery.fonticonpicker.grey.min.css" />

Include core CSS 
<!-- fontIconPicker core CSS -->
<link rel="stylesheet" type="text/css" href="css/jquery.fonticonpicker.min.css" />

Include Font Icons core CSS
<!-- fontAwesome core CSS -->
<link rel="stylesheet" type="text/css" href="css/font-awesome.min.css">


### Initialize with jQuery
Finally call the fontIconPicker on a `INPUT[type="text"]` element.


```html
<!-- INPUT element -->
<input type="text" name="mytext" id="mytext" />
<script>
    $(function(){
        $('#mytext').fontIconPicker({
            source:    resourceInfoIconDatas,//ICON DATA
            emptyIcon: true,
            hasSearch: true,
            emptyIconValue: 'none',
        });
    });
</script>
```

## Browser Compatibility

jQuery iconPicker has been successfully tested on: Firefox (edge), Safari (edge), Chrome (edge),  Opera (edge).
No support for the time being IE8+ (edge).

## Credits

jQuery fontIconPicker has been made by [me](http://www.fzycoco.com) & (https://github.com/Max-fzy). You can contact me at zhangyu8333@126.com for any issue or feauture request.
