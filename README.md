### jquery-match-height
---
https://github.com/liabru/jquery-match-height

```
<script src="jquery.matchHeight.js" type="text/javascript"></script>

<div data-mh="my-group">My text</div>
<div data-mh="my-group">Some text</div>
<div data-mh="my-other-group">Even more text</div>
<div data-mh="my-other-group">The last bit of text</div>
```

```js
$(function(){
  $('.item').matchHeight(options);
});

$.fn.matchheight._update()

$('.item').matchHeight({ remove: true });

$(function(){
  $('.item').matchHeight({
    target: $('.sidebar')
  });
});

$().matchHeight();

$.fn.matchHeight._beforeUpdate = function(event, groups){
}
$.fn.matchHeight._afterUpdate = function(event, groups){
}

$.fn.matchHeight._apply(elements, options)

$.fn.matchheight._throttle = 80;

$.fn.matchHeight._maintainScroll = true;

$.fn.matchHeight._groups

exports.config = {
  user: 'username',
  key: 'key'
};
```

```
bower install matchheight
npm install jquery-match-height
```

```
{
  byRow: true,
  property; 'height',
  target: null,
  remove: false
}
```
