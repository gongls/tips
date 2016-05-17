###https://github.com/mattbryson/TouchSwipe-Jquery-Plugin


NPM
```
npm install jquery-touchswipe --save
```
Bower
```
bower install jquery-touchswipe --save

```
code:
```
$(function() {
  $("#test").swipe( {
    //Generic swipe handler for all directions
    swipe:function(event, direction, distance, duration, fingerCount, fingerData) {
      $(this).text("You swiped " + direction );  
    }
  });

  //Set some options later
  $("#test").swipe( {fingers:2} );
});
```
