# Scroll to top of web page

jQuery plugin to display a button for scrolling the page to the top.

### Options

- background: (string) Button background color. Use hexadecimal or rgb colors.
- color: (string) Icon color. Use hexadecimal or rgb colors.
- rounded: (bool) Make the button rounded
- width: (string) Button width. Use px, em or rem mesure unit.
- height: (string) Button height. Use px, em or rem mesure unit.
- bottom: (string) Bottom position. Use px, em or rem mesure unit.
- right: (string) Right position. Use px, em or rem mesure unit.
- windowScrollShow: (integer) Window height after which show the button.
- speed: (integer) Scrolling speed
- customHtml: (string) Set custom html for icon
- mobileOnly: (bool) Show button only on mobile device

#### Default option

```javascript
   var defaults = {
    background : '#000',
    color: '#fff',
    rounded: true,
    width: '45px',
    height: '45px',
    bottom : '25px',
    right : '25px',
    windowScrollShow: 400,
    speed: 800,
    customHtml: '',
    mobileOnly: false
}
```

### How to use

1. Include necessary JS files

   ```html
   <script src="js/jquery.js"></script>
   <script src="js/jquery.gotop.js"></script>
   ```

2. Create a link element in your body

   ```html
   <div id="gotop"></div>
   ```

3. Fire plugin using jQuery selector

   ```javascript
   (function ($) {
     $('#gotop').gotop();
   }(jQuery));
   ```

4. Change default options

   ```javascript
   $('#gotop').gotop({
     customHtml: '<i class="fa fa-angle-up"></i>',
     bottom: '5px',
     right: '5px'
   });
   ```
