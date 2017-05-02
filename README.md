# Scroll the page to top

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

```
   var defaults = {
    background : '#000',
    color: '#fff',
    rounded: true,
    width: '45px',
    height: '45px',
    bottom : '25px',
    right : '25px',
    windowScrollShow: 400,
    customHtml: '',
    mobileOnly: false
}
```

### Examples

```
$('#goup').gotop({
  background: '#ee7601',
  customHtml: '<i class="fa fa-angle-up"></i>',
  bottom: '5px',
  right: '5px',
  mobileOnly: true
});
```

Change the default options for background, color, position and to show the botton only on mobile device.
