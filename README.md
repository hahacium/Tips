
**Changing the formatting**
```javascript
$.tips({ 
  text : "Let's test some HTML stuff... <a href='#'>github</a>", 
  showHideTransition : 'slide',  // It can be plain, fade or slide
  bgColor : 'blue',              // Background color for toast
  textColor : '#eee',            // text color
  allowTipsClose : false,       // Show the close button or not
  hideAfter : 5000,              // `false` to make it sticky or time in miliseconds to hide after
  stack : 5,                     // `fakse` to show one stack at a time count showing the number of toasts that can be shown at once
  textAlign : 'left',            // Alignment of text i.e. left, right, center
  position : 'bottom-left'       // bottom-left or bottom-right or bottom-center or top-left or top-right or top-center or mid-center or an object representing the left, right, top, bottom values to position the toast on page
})
```
