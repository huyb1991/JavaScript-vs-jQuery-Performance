# Performance Comparison of JavaScript and jQuery
Performance comparsion of **`native JavaScript`** and **`jQuery (version 2.1.0)`** follow [You might not need jquery](http://youmightnotneedjquery.com/).

The numbers at the right of links are the result of execute time with the same function for **1,000** loops of `Native JavaScript / jQuery`.
## Index
### Ajax
Ajax request only for 10 loops

* <a href="#json-comparsion">JSON</a> (1.039 ms / 11.025 ms)
* <a href="#post-comparsion">Post</a> (5.765 ms / 17.940 ms)
* <a href="#request-comparsion">Request</a> (2.095 ms / 12.439 ms)

### Effects
* <a href="#fade-in-comparsion">Fade In</a> (11 ms / 269 ms)
* <a href="#hide-comparsion">Hide</a> (1.195 ms / 28.484 ms)
* <a href="#show-comparsion">Show</a> (0.765 ms / 5.179 ms)

### Elements
* <a href="#add-class-comparsion">Add Class</a> (0.740 ms / 5.649 ms)
* <a href="#after-comparsion">After</a> (3.569 ms / 45.005 ms)
* <a href="#append-comparsion">Append</a> (0.650 ms / 62.530 ms)
* <a href="#before-comparsion">Before</a> (3.225 ms / 27.440 ms)
* <a href="#children-comparsion">Children</a> (0.279 ms / 7.029 ms)
* <a href="#clone-comparsion">Clone</a> (4.934 ms / 42.889 ms)
* <a href="#contains-comparsion">Contains</a> (0.934 ms / 1.605 ms)
* <a href="#contains-selector-comparsion">Contains Selector</a> (0.604 ms / 5.759 ms)
* <a href="#each-comparsion">Each</a> (4.120 ms / 8.220 ms)
* <a href="#empty-comparsion">Empty</a> (1.969 ms / 3.639 ms)
* <a href="#filter-comparsion">Filter</a> (2.709 ms / 9.860 ms)
* <a href="#find-children-comparsion">Find Children</a> (0.949 ms / 5.404 ms)
* <a href="#find-elements-comparsion">Find Elements</a> (0.970 ms / 12.250 ms)
* <a href="#get-attributes-comparsion">Get Attributes</a> (0.390 ms / 6.164 ms))
* <a href="#get-html-comparsion">Get Html</a> (0.555 ms / 6.339 ms)
* <a href="#get-outer-html-comparsion">Get Outer Html</a> (0.714 ms / 269.639 ms)
* <a href="#get-style-comparsion">Get Style</a> (1.424 ms / 11.745 ms)
* <a href="#get-text-comparsion">Get Text</a> (0.320 ms / 2.470 ms)
* <a href="#has-class-comparsion">Has Class</a> (0.480 ms / 2.689 ms)
* <a href="#matches-comparsion">Matches</a> (0.345 ms / 6.534 ms)
* <a href="#matches-selector-comparsion">Matches Selector</a> (0.460 ms / 8.185 ms)
* <a href="#next-comparsion">Next</a> (0.215 ms / 1.130 ms)
* <a href="#offset-comparsion">Offset</a> (2.470 ms / 7.034 ms)
* <a href="#offset-parent-comparsion">Offset Parent</a> (1.045 ms / 21.250 ms)
* <a href="#outer-height-comparsion">Outer Height</a> (0.714 ms / 19.774 ms)
* <a href="#outer-height-with-margin-comparsion">Outer Height With Margin</a> (5.360 ms / 26.779 ms)
* <a href="#outer-width-comparsion">Outer Width</a> (3.125 ms / 19.805 ms)
* <a href="#outer-width-with-margin-comparsion">Outer Width With Margin</a> (2.490 ms / 27.835 ms)
* <a href="#parent-comparsion">Parent</a> (0.230 ms / 4.860 ms)
* <a href="#position-comparsion">Position</a> (1.019 ms / 77.925 ms)
* <a href="#position-relative-to-viewport-comparsion">Position Relative To Viewport</a> (1.549 ms / 10.710 ms)
* <a href="#prepend-comparsion">Prepend</a> (1.085 ms / 75.240 ms)
* <a href="#prev-comparsion">Prev</a> (0.249 ms / 3.744 ms)
* <a href="#remove-comparsion">Remove</a> (0.404 ms / 2.105 ms)
* <a href="#remove-class-comparsion">Remove Class</a> (0.615 ms / 5.480 ms)
* <a href="#replace-from-html-comparsion">Replace From Html</a> (0.354 ms / 6.789 ms)
* <a href="#set-attributes-comparsion">Set Attributes</a> (1.059 ms / 5.615 ms)
* <a href="#set-html-comparsion">Set Html</a> (2.225 ms / 9.705 ms)
* <a href="#set-style-comparsion">Set Style</a> (2.425 ms / 21.509 ms)
* <a href="#set-text-comparsion">Set Text</a> (0.900 ms / 11.405 ms)
* <a href="#siblings-comparsion">Siblings</a> (11.504 ms / 8.060 ms)
* <a href="#toggle-class-comparsion">Toggle Class</a> (1.169 ms / 29.754 ms)

### Events
* <a href="#off-comparsion">Off</a> (0.855 ms / 4.554 ms)
* <a href="#on-comparsion">On</a> (1.230 ms / 14.205 ms)
* <a href="#ready-comparsion">Ready</a> (0.140 ms / 7.514 ms)
* <a href="#trigger-custom-comparsion">Trigger Custom</a> (4.385 ms / 33.589 ms)
* <a href="#trigger-native-comparsion">Trigger Native</a> (3.375 ms / 24.730 ms)

### Utils
* <a href="#bind-comparsion">Bind</a> (0.730 ms / 2.024 ms)
* <a href="#array-each-comparsion">Array Each</a> (0.575 ms / 1.094 ms)
* <a href="#deep-extend-comparsion">Deep Extend</a> (1.105 ms/ 2.869 ms)
* <a href="#extend-comparsion">Extend</a> (0.674 ms / 2.084 ms)
* <a href="#index-of-comparsion">Index Of</a> (0.174 ms / 0.330 ms)
* <a href="#is-array-comparsion">Is Array</a> (0.299 ms / 0.349 ms)
* <a href="#map-comparsion">Map</a> (3.484 ms / 2.774 ms)
* <a href="#now-comparsion">Now</a> (0.280 ms / 0.150 ms)
* <a href="#parse-html-comparsion">Parse Html</a> (29.465 ms / 51.220 ms)
* <a href="#parse-json-comparsion">Parse Json</a> (0.605 ms / 1.460 ms)
* <a href="#trim-comparsion">Trim</a> (0.200 ms/ 0.279 ms)
* <a href="#type-comparsion">Type</a> (1.610 ms / 0.210 ms)

## AJAX Comparsion
### JSON Comparsion
Live code at [https://jsfiddle.net/dda467b1/69/](https://jsfiddle.net/dda467b1/69/)

`Native JavScript` take about **1.039** milliseconds / `jQuery` take about **11.025** milliseconds.
##### `Native JavScript code`
```js
var request = new XMLHttpRequest();
request.open('GET', '/my/url', true);

request.onload = function() {
  if (request.status >= 200 && request.status < 400) {
    // Success!
    var data = JSON.parse(request.responseText);
  } else {
    // We reached our target server, but it returned an error

  }
};

request.onerror = function() {
  // There was a connection error of some sort
};

request.send();
```
##### `jQuery code`
```
$.getJSON('/my/url', function(data) {
});
```
### Post Comparsion
Live code at [https://jsfiddle.net/dda467b1/70/](https://jsfiddle.net/dda467b1/70/)

`Native JavScript` take about **5.765** milliseconds / `jQuery` take about **17.940** milliseconds.
##### `Native JavScript code`
```js
var request = new XMLHttpRequest();
request.open('POST', '/my/url', true);
request.setRequestHeader('Content-Type', 'application/x-www-form-urlencoded; charset=UTF-8');
request.send(data);
```
##### `jQuery code`
```
$.ajax({
  type: 'POST',
  url: '/my/url',
  data: data
});
```
### Request Comparsion
Live code at [https://jsfiddle.net/dda467b1/71/](https://jsfiddle.net/dda467b1/71/)

`Native JavScript` take about **2.095** milliseconds / `jQuery` take about **12.439** milliseconds.
##### `Native JavScript code`
```js
var request = new XMLHttpRequest();
request.open('GET', '/my/url', true);

request.onload = function() {
  if (request.status >= 200 && request.status < 400) {
    // Success!
    var resp = request.responseText;
  } else {
    // We reached our target server, but it returned an error
  }
};

request.onerror = function() {
  // There was a connection error of some sort
};

request.send();
```
##### `jQuery code`
```
$.ajax({
  type: 'GET',
  url: '/my/url',
  success: function(resp) {
  },
  error: function() {
  }
});
```
## EFFECTS Comparsion
### Fade In Comparsion
Live code at [https://jsfiddle.net/dda467b1/1/](https://jsfiddle.net/dda467b1/1/)

`Native JavScript` take about **11** milliseconds / `jQuery` take about **269** milliseconds.
##### `Native JavScript code`
```js
function fadeIn(el) {
  el.style.opacity = 0;

  var last = +new Date(),
  var tick = function() {
    el.style.opacity = +el.style.opacity + (new Date() - last) / 400;
    last = +new Date();

    if (+el.style.opacity < 1) {
      (window.requestAnimationFrame && requestAnimationFrame(tick)) || setTimeout(tick, 16);
    }
  };

  tick();
}

fadeIn(el);
```
##### `jQuery code`
```
$(el).fadeIn();
```
### Hide Comparsion
Live code at [https://jsfiddle.net/dda467b1/2/](https://jsfiddle.net/dda467b1/2/)

`Native JavScript` take about **1.195** milliseconds / `jQuery` take about **28.484** milliseconds.
##### `Native JavScript code`
```js
el.style.display = 'none';
```
##### `jQuery code`
```
$(el).hide();
```
### Show Comparsion
Live code at [https://jsfiddle.net/dda467b1/3/](https://jsfiddle.net/dda467b1/3/)

`Native JavScript` take about **0.765** milliseconds / `jQuery` take about **25.179** milliseconds.
##### `Native JavScript code`
```js
el.style.display = ''
```
##### `jQuery code`
```
$(el).show();
```
## ELEMENTS Comparsion
### Add Class Comparsion
Live code at [https://jsfiddle.net/dda467b1/4/](https://jsfiddle.net/dda467b1/4/)

`Native JavScript` take about **0.764** milliseconds / `jQuery` take about **5.649** milliseconds.
##### `Native JavScript code`
```js
if (el.classList)
  el.classList.add(className);
else
  el.className += ' ' + className;
```
##### `jQuery code`
```
$(el).addClass(className);
```
### After Comparsion
Live code at [https://jsfiddle.net/dda467b1/5/](https://jsfiddle.net/dda467b1/5/)

`Native JavScript` take about **3.569** milliseconds / `jQuery` take about **45.005** milliseconds.
##### `Native JavScript code`
```js
el.insertAdjacentHTML('afterend', htmlString);
```
##### `jQuery code`
```
$(el).after(htmlString);
```
### Append Comparsion
Live code at [https://jsfiddle.net/dda467b1/6/](https://jsfiddle.net/dda467b1/6/)

`Native JavScript` take about **0.650** milliseconds / `jQuery` take about **62.530** milliseconds.
##### `Native JavScript code`
```js
parent.appendChild(el);
```
##### `jQuery code`
```
$(parent).append(el);
```
### Before Comparsion
Live code at [https://jsfiddle.net/dda467b1/7/](https://jsfiddle.net/dda467b1/7/)

`Native JavScript` take about **3.225** milliseconds / `jQuery` take about **27.440** milliseconds.
##### `Native JavScript code`
```js
el.insertAdjacentHTML('beforebegin', htmlString);
```
##### `jQuery code`
```
$(el).before(htmlString);
```
### Children Comparsion
Live code at [https://jsfiddle.net/dda467b1/8/](https://jsfiddle.net/dda467b1/8/)

`Native JavScript` take about **0.279** milliseconds / `jQuery` take about **7.029** milliseconds.
##### `Native JavScript code`
```js
el.children
```
##### `jQuery code`
```
$(el).children();
```
### Clone Comparsion
Live code at [https://jsfiddle.net/dda467b1/9/](https://jsfiddle.net/dda467b1/9/)

`Native JavScript` take about **4.934** milliseconds / `jQuery` take about **42.889** milliseconds.
##### `Native JavScript code`
```js
el.cloneNode(true);
```
##### `jQuery code`
```
$(el).clone();
```
### Contains Comparsion
Live code at [https://jsfiddle.net/dda467b1/11/](https://jsfiddle.net/dda467b1/11/)

`Native JavScript` take about **0.934** milliseconds / `jQuery` take about **1.605** milliseconds.
##### `Native JavScript code`
```js
el !== child && el.contains(child);
```
##### `jQuery code`
```
$.contains(el, child);
```
### Contains Selector Comparsion
Live code at [https://jsfiddle.net/dda467b1/12/](https://jsfiddle.net/dda467b1/12/)

`Native JavScript` take about **0.604** milliseconds / `jQuery` take about **5.759** milliseconds.
##### `Native JavScript code`
```js
el.querySelector(selector).length;
```
##### `jQuery code`
```
$(el).find(selector).length;
```
### Each Comparsion
Live code at [https://jsfiddle.net/dda467b1/13/](https://jsfiddle.net/dda467b1/13/)

`Native JavScript` take about **4.120** milliseconds / `jQuery` take about **8.220** milliseconds.
##### `Native JavScript code`
```js
var elements = document.querySelectorAll(selector);
Array.prototype.forEach.call(elements, function(el, i){
  // Do something
});
```
##### `jQuery code`
```
$(selector).each(function(i, el){
  // Do something
});
```
### Empty Comparsion
Live code at [https://jsfiddle.net/dda467b1/14/](https://jsfiddle.net/dda467b1/14/)

`Native JavScript` take about **1.969** milliseconds / `jQuery` take about **3.639** milliseconds.
##### `Native JavScript code`
```js
el.innerHTML = '';
```
##### `jQuery code`
```
$(el).empty();
```
### Filter Comparsion
Live code at [https://jsfiddle.net/dda467b1/15/](https://jsfiddle.net/dda467b1/15/)

`Native JavScript` take about **2.709** milliseconds / `jQuery` take about **9.860** milliseconds.
##### `Native JavScript code`
```js
Array.prototype.filter.call(document.querySelectorAll(selector), filterFn);
```
##### `jQuery code`
```
$(selector).filter(filterFn);
```
### Find Children Comparsion
Live code at [https://jsfiddle.net/dda467b1/16/](https://jsfiddle.net/dda467b1/16/)

`Native JavScript` take about **0.949** milliseconds / `jQuery` take about **5.404** milliseconds.
##### `Native JavScript code`
```js
el.querySelectorAll(selector);
```
##### `jQuery code`
```
$(el).find(selector);
```
### Find Elements Comparsion
Live code at [https://jsfiddle.net/dda467b1/17/](https://jsfiddle.net/dda467b1/17/)

`Native JavScript` take about **0.970** milliseconds / `jQuery` take about **12.250** milliseconds.
##### `Native JavScript code`
```js
document.querySelectorAll('.my #awesome selector');
```
##### `jQuery code`
```
$('.my #awesome selector');
```
### Get Attributes Comparsion
Live code at [https://jsfiddle.net/dda467b1/18/](https://jsfiddle.net/dda467b1/18/)

`Native JavScript` take about **0.390** milliseconds / `jQuery` take about **6.164** milliseconds.
##### `Native JavScript code`
```js
$(el).attr('tabindex');
```
##### `jQuery code`
```
el.getAttribute('tabindex');
```
### Get Html Comparsion
Live code at [https://jsfiddle.net/dda467b1/19/](https://jsfiddle.net/dda467b1/19/)

`Native JavScript` take about **0.555** milliseconds / `jQuery` take about **6.339** milliseconds.
##### `Native JavScript code`
```js
el.innerHTML;
```
##### `jQuery code`
```
$(el).html();
```
### Get Outer Html Comparsion
Live code at [https://jsfiddle.net/dda467b1/20/](https://jsfiddle.net/dda467b1/20/)

`Native JavScript` take about **0.714** milliseconds / `jQuery` take about **269.639** milliseconds.
##### `Native JavScript code`
```js
el.outerHTML;
```
##### `jQuery code`
```
$('<div>').append($(el).clone()).html();
```
### Get Style Comparsion
Live code at [https://jsfiddle.net/dda467b1/21/](https://jsfiddle.net/dda467b1/21/)

`Native JavScript` take about **1.424** milliseconds / `jQuery` take about **11.745** milliseconds.
##### `Native JavScript code`
```js
getComputedStyle(el)[ruleName];
```
##### `jQuery code`
```
$(el).css(ruleName);
```
### Get Text Comparsion
Live code at [https://jsfiddle.net/dda467b1/22/](https://jsfiddle.net/dda467b1/22/)

`Native JavScript` take about **0.320** milliseconds / `jQuery` take about **2.470** milliseconds.
##### `Native JavScript code`
```js
el.textContent
```
##### `jQuery code`
```
$(el).text();
```
### Has Class Comparsion
Live code at [https://jsfiddle.net/dda467b1/23/](https://jsfiddle.net/dda467b1/23/)

`Native JavScript` take about **0.480** milliseconds / `jQuery` take about **2.689** milliseconds.
##### `Native JavScript code`
```js
if (el.classList)
  el.classList.contains(className);
else
  new RegExp('(^| )' + className + '( |$)', 'gi').test(el.className);
```
##### `jQuery code`
```
$(el).hasClass(className);
```
### Matches Comparsion
Live code at [https://jsfiddle.net/dda467b1/24/](https://jsfiddle.net/dda467b1/24/)

`Native JavScript` take about **0.345** milliseconds / `jQuery` take about **6.534** milliseconds.
##### `Native JavScript code`
```js
el === otherEl
```
##### `jQuery code`
```
$(el).is($(otherEl));
```
### Matches Selector Comparsion
Live code at [https://jsfiddle.net/dda467b1/25/](https://jsfiddle.net/dda467b1/25/)

`Native JavScript` take about **0.460** milliseconds / `jQuery` take about **8.185** milliseconds.
##### `Native JavScript code`
```js
var matches = function(el, selector) {
  return (el.matches || el.matchesSelector || el.msMatchesSelector || el.mozMatchesSelector || el.webkitMatchesSelector || el.oMatchesSelector).call(el, selector);
};

matches(el, '.my-class');
```
##### `jQuery code`
```
$(el).is('.my-class');
```
### Next Comparsion
Live code at [https://jsfiddle.net/dda467b1/26/](https://jsfiddle.net/dda467b1/26/)

`Native JavScript` take about **0.215** milliseconds / `jQuery` take about **1.130** milliseconds.
##### `Native JavScript code`
```js
el.nextElementSibling
```
##### `jQuery code`
```
$(el).next();
```
### Offset Comparsion
Live code at [https://jsfiddle.net/dda467b1/28/](https://jsfiddle.net/dda467b1/28/)

`Native JavScript` take about **2.470** milliseconds / `jQuery` take about **7.034** milliseconds.
##### `Native JavScript code`
```js
var rect = el.getBoundingClientRect();
```
##### `jQuery code`
```
$(el).offset();
```
### Offset Parent Comparsion
Live code at [https://jsfiddle.net/dda467b1/29/](https://jsfiddle.net/dda467b1/29/)

`Native JavScript` take about **1.045** milliseconds / `jQuery` take about **21.250** milliseconds.
##### `Native JavScript code`
```js
el.offsetParent || el
```
##### `jQuery code`
```
$(el).offsetParent();
```
### Outer Height Comparsion
Live code at [https://jsfiddle.net/dda467b1/30/](https://jsfiddle.net/dda467b1/30/)

`Native JavScript` take about **0.714** milliseconds / `jQuery` take about **19.774** milliseconds.
##### `Native JavScript code`
```js
el.offsetHeight
```
##### `jQuery code`
```
$(el).outerHeight();
```
### Outer Height With Margin Comparsion
Live code at [https://jsfiddle.net/dda467b1/31/](https://jsfiddle.net/dda467b1/31/)

`Native JavScript` take about **5.360** milliseconds / `jQuery` take about **26.779** milliseconds.
##### `Native JavScript code`
```js
function outerHeight(el) {
  var height = el.offsetHeight;
  var style = getComputedStyle(el);

  height += parseInt(style.marginTop) + parseInt(style.marginBottom);
  return height;
}

outerHeight(el);
```
##### `jQuery code`
```
$(el).outerHeight(true);
```
### Outer Width Comparsion
Live code at [https://jsfiddle.net/dda467b1/32/](https://jsfiddle.net/dda467b1/32/)

`Native JavScript` take about **3.125** milliseconds / `jQuery` take about **19.805** milliseconds.
##### `Native JavScript code`
```js
el.offsetWidth
```
##### `jQuery code`
```
$(el).outerWidth();
```
### Outer Width With Margin Comparsion
Live code at [https://jsfiddle.net/dda467b1/34/](https://jsfiddle.net/dda467b1/34/)

`Native JavScript` take about **2.490** milliseconds / `jQuery` take about **27.835** milliseconds.
##### `Native JavScript code`
```js
function outerWidth(el) {
  var width = el.offsetWidth;
  var style = getComputedStyle(el);

  width += parseInt(style.marginLeft) + parseInt(style.marginRight);
  return width;
}

outerWidth(el);
```
##### `jQuery code`
```
$(el).outerWidth(true);
```
### Parent Comparsion
Live code at [https://jsfiddle.net/dda467b1/35/](https://jsfiddle.net/dda467b1/35/)

`Native JavScript` take about **0.230** milliseconds / `jQuery` take about **4.860** milliseconds.
##### `Native JavScript code`
```js
el.parentNode
```
##### `jQuery code`
```
$(el).parent();
```
### Position Comparsion
Live code at [https://jsfiddle.net/dda467b1/36/](https://jsfiddle.net/dda467b1/36/)

`Native JavScript` take about **1.019** milliseconds / `jQuery` take about **77.925** milliseconds.
##### `Native JavScript code`
```js
{left: el.offsetLeft, top: el.offsetTop}
```
##### `jQuery code`
```
$(el).position();
```
### Position Relative To Viewport Comparsion
Live code at [https://jsfiddle.net/dda467b1/37/](https://jsfiddle.net/dda467b1/37/)

`Native JavScript` take about **1.549** milliseconds / `jQuery` take about **10.710** milliseconds.
##### `Native JavScript code`
```js
el.getBoundingClientRect()
```
##### `jQuery code`
```
var offset = el.offset();

{
  top: offset.top - document.body.scrollTop,
  left: offset.left - document.body.scrollLeft
}
```
### Prepend Comparsion
Live code at [https://jsfiddle.net/dda467b1/38/](https://jsfiddle.net/dda467b1/38/)

`Native JavScript` take about **1.085** milliseconds / `jQuery` take about **75.240** milliseconds.
##### `Native JavScript code`
```js
parent.insertBefore(el, parent.firstChild);
```
##### `jQuery code`
```
$(parent).prepend(el);
```
### Prev Comparsion
Live code at [https://jsfiddle.net/dda467b1/39/](https://jsfiddle.net/dda467b1/39/)

`Native JavScript` take about **0.249** milliseconds / `jQuery` take about **3.744** milliseconds.
##### `Native JavScript code`
```js
el.previousElementSibling
```
##### `jQuery code`
```
$(el).prev();
```
### Remove Comparsion
Live code at [https://jsfiddle.net/dda467b1/40/](https://jsfiddle.net/dda467b1/40/)

`Native JavScript` take about **0.404** milliseconds / `jQuery` take about **2.105** milliseconds.
##### `Native JavScript code`
```js
el.parentNode.removeChild(el);
```
##### `jQuery code`
```
$(el).remove();
```
### Remove Class Comparsion
Live code at [https://jsfiddle.net/dda467b1/41/](https://jsfiddle.net/dda467b1/41/)

`Native JavScript` take about **0.615** milliseconds / `jQuery` take about **5.480** milliseconds.
##### `Native JavScript code`
```js
if (el.classList)
  el.classList.remove(className);
else
  el.className = el.className.replace(new RegExp('(^|\\b)' + className.split(' ').join('|') + '(\\b|$)', 'gi'), ' ');
```
##### `jQuery code`
```
$(el).removeClass(className);
```
### Replace From Html Comparsion
Live code at [https://jsfiddle.net/dda467b1/42/](https://jsfiddle.net/dda467b1/42/)

`Native JavScript` take about **0.354** milliseconds / `jQuery` take about **6.789** milliseconds.
##### `Native JavScript code`
```js
el.outerHTML = string;
```
##### `jQuery code`
```
$(el).replaceWith(string);
```
### Set Attributes Comparsion
Live code at [https://jsfiddle.net/dda467b1/43/](https://jsfiddle.net/dda467b1/43/)

`Native JavScript` take about **1.059** milliseconds / `jQuery` take about **5.615** milliseconds.
##### `Native JavScript code`
```js
el.setAttribute('tabindex', 3)
```
##### `jQuery code`
```
$(el).attr('tabindex', 3);
```
### Set Html Comparsion
Live code at [https://jsfiddle.net/dda467b1/44/](https://jsfiddle.net/dda467b1/44/)

`Native JavScript` take about **2.225** milliseconds / `jQuery` take about **9.705** milliseconds.
##### `Native JavScript code`
```js
el.innerHTML = string;
```
##### `jQuery code`
```
$(el).html(string);
```
### Set Style Comparsion
Live code at [https://jsfiddle.net/dda467b1/45/](https://jsfiddle.net/dda467b1/45/)

`Native JavScript` take about **2.425** milliseconds / `jQuery` take about **21.509** milliseconds.
##### `Native JavScript code`
```js
el.style.borderWidth = '20px';
```
##### `jQuery code`
```
$(el).css('border-width', '20px');
```
### Set Text Comparsion
### Set Style Comparsion
Live code at [https://jsfiddle.net/dda467b1/46/](https://jsfiddle.net/dda467b1/46/)

`Native JavScript` take about **0.900** milliseconds / `jQuery` take about **11.405** milliseconds.
##### `Native JavScript code`
```js
el.textContent = string;
```
##### `jQuery code`
```
$(el).text(string);
```
### Siblings Comparsion
Live code at [https://jsfiddle.net/dda467b1/47/](https://jsfiddle.net/dda467b1/47/)

`Native JavScript` take about **11.504** milliseconds / `jQuery` take about **8.060** milliseconds.
##### `Native JavScript code`
```js
Array.prototype.filter.call(el.parentNode.children, function(child){
  return child !== el;
});
```
##### `jQuery code`
```
$(el).siblings();
```
### Toggle Class Comparsion
Live code at [https://jsfiddle.net/dda467b1/48/](https://jsfiddle.net/dda467b1/48/)

`Native JavScript` take about **1.169** milliseconds / `jQuery` take about **29.754** milliseconds.
##### `Native JavScript code`
```js
if (el.classList) {
  el.classList.toggle(className);
} else {
  var classes = el.className.split(' ');
  var existingIndex = classes.indexOf(className);

  if (existingIndex >= 0)
    classes.splice(existingIndex, 1);
  else
    classes.push(className);

  el.className = classes.join(' ');
}
```
##### `jQuery code`
```
$(el).toggleClass(className);
```
## EVENTS Comparsion
### Off Comparsion
Live code at [https://jsfiddle.net/dda467b1/50/](https://jsfiddle.net/dda467b1/50/)

`Native JavScript` take about **0.855** milliseconds / `jQuery` take about **4.554** milliseconds.
##### `Native JavScript code`
```js
el.removeEventListener(eventName, eventHandler);
```
##### `jQuery code`
```
$(el).off(eventName, eventHandler);
```
### On Comparsion
Live code at [https://jsfiddle.net/dda467b1/51/](https://jsfiddle.net/dda467b1/51/)

`Native JavScript` take about **1.230** milliseconds / `jQuery` take about **14.205** milliseconds.
##### `Native JavScript code`
```js
el.addEventListener(eventName, eventHandler);
```
##### `jQuery code`
```
$(el).on(eventName, eventHandler);
```
### Ready Comparsion
Live code at [https://jsfiddle.net/dda467b1/52/](https://jsfiddle.net/dda467b1/52/)

`Native JavScript` take about **0.140** milliseconds / `jQuery` take about **7.514** milliseconds.
##### `Native JavScript code`
```js
function ready(fn) {
  if (document.readyState != 'loading'){
    fn();
  } else {
    document.addEventListener('DOMContentLoaded', fn);
  }
}
```
##### `jQuery code`
```
$(document).ready(function(){
});
```
### Trigger Custom Comparsion
Live code at [https://jsfiddle.net/dda467b1/53/](https://jsfiddle.net/dda467b1/53/)

`Native JavScript` take about **4.385** milliseconds / `jQuery` take about **33.589** milliseconds.
##### `Native JavScript code`
```js
if (window.CustomEvent) {
  var event = new CustomEvent('my-event', {detail: {some: 'data'}});
} else {
  var event = document.createEvent('CustomEvent');
  event.initCustomEvent('my-event', true, true, {some: 'data'});
}

el.dispatchEvent(event);
```
##### `jQuery code`
```
$(el).trigger('my-event', {some: 'data'});
```
### Trigger Native Comparsion
Live code at [https://jsfiddle.net/dda467b1/54/](https://jsfiddle.net/dda467b1/54/)

`Native JavScript` take about **3.375** milliseconds / `jQuery` take about **24.730** milliseconds.
##### `Native JavScript code`
```js
var event = document.createEvent('HTMLEvents');
event.initEvent('change', true, false);
el.dispatchEvent(event);
```
##### `jQuery code`
```
$(el).trigger('change');
```
## UTILS Comparsion
### Bind Comparsion
Live code at [https://jsfiddle.net/dda467b1/72/](https://jsfiddle.net/dda467b1/72/)

`Native JavScript` take about **0.730** milliseconds / `jQuery` take about **2.024** milliseconds.
##### `Native JavScript code`
```js
fn.bind(context);
```
##### `jQuery code`
```
$.proxy(fn, context);
```
### Array Each Comparsion
Live code at [https://jsfiddle.net/dda467b1/56/](https://jsfiddle.net/dda467b1/56/)

`Native JavScript` take about **0.575** milliseconds / `jQuery` take about **1.094** milliseconds.
##### `Native JavScript code`
```js
array.forEach(function(item, i){
});
```
##### `jQuery code`
```
$.each(array, function(i, item){
});
```
### Deep Extend Comparsion
Live code at [https://jsfiddle.net/dda467b1/55/](https://jsfiddle.net/dda467b1/55/)

`Native JavScript` take about **1.105** milliseconds / `jQuery` take about **2.869** milliseconds.
##### `Native JavScript code`
```js
var deepExtend = function(out) {
  out = out || {};

  for (var i = 1; i < arguments.length; i++) {
    var obj = arguments[i];

    if (!obj)
      continue;

    for (var key in obj) {
      if (obj.hasOwnProperty(key)) {
        if (typeof obj[key] === 'object')
          out[key] = deepExtend(out[key], obj[key]);
        else
          out[key] = obj[key];
      }
    }
  }

  return out;
};

deepExtend({}, objA, objB);
```
##### `jQuery code`
```
$.extend(true, {}, objA, objB);
```
### Extend Comparsion
Live code at [https://jsfiddle.net/dda467b1/57/](https://jsfiddle.net/dda467b1/57/)

`Native JavScript` take about **0.674** milliseconds / `jQuery` take about **2.084** milliseconds.
##### `Native JavScript code`
```js
var extend = function(out) {
  out = out || {};

  for (var i = 1; i < arguments.length; i++) {
    if (!arguments[i])
      continue;

    for (var key in arguments[i]) {
      if (arguments[i].hasOwnProperty(key))
        out[key] = arguments[i][key];
    }
  }

  return out;
};

extend({}, objA, objB);
```
##### `jQuery code`
```
$.extend({}, objA, objB);
```
### Index Of Comparsion
Live code at [https://jsfiddle.net/dda467b1/58/](https://jsfiddle.net/dda467b1/58/)

`Native JavScript` take about **0.174** milliseconds / `jQuery` take about **0.330** milliseconds.
##### `Native JavScript code`
```js
array.indexOf(item);
```
##### `jQuery code`
```
$.inArray(item, array);
```
### Is Array Comparsion
Live code at [https://jsfiddle.net/dda467b1/59/](https://jsfiddle.net/dda467b1/59/)

`Native JavScript` take about **0.299** milliseconds / `jQuery` take about **0.349** milliseconds.
##### `Native JavScript code`
```js
Array.isArray(arr);
```
##### `jQuery code`
```
$.isArray(arr);
```
### Map Comparsion
Live code at [https://jsfiddle.net/dda467b1/60/](https://jsfiddle.net/dda467b1/60/)

`Native JavScript` take about **3.484** milliseconds / `jQuery` take about **2.774** milliseconds.
##### `Native JavScript code`
```js
array.map(function(value, index){
});
```
##### `jQuery code`
```
$.map(array, function(value, index){
});
```
### Now Comparsion
Live code at [https://jsfiddle.net/dda467b1/61/](https://jsfiddle.net/dda467b1/61/)

`Native JavScript` take about **0.280** milliseconds / `jQuery` take about **0.150** milliseconds.
##### `Native JavScript code`
```js
Date.now();
```
##### `jQuery code`
```
$.now();
```
### Parse Html Comparsion
Live code at [https://jsfiddle.net/dda467b1/65/](https://jsfiddle.net/dda467b1/65/)

`Native JavScript` take about **29.465** milliseconds / `jQuery` take about **51.220** milliseconds.
##### `Native JavScript code`
```js
var parseHTML = function(str) {
  var tmp = document.implementation.createHTMLDocument();
  tmp.body.innerHTML = str;
  return tmp.body.children;
};

parseHTML(htmlString);
```
##### `jQuery code`
```
$.parseHTML(htmlString
```
### Parse Json Comparsion
Live code at [https://jsfiddle.net/dda467b1/64/](https://jsfiddle.net/dda467b1/64/)

`Native JavScript` take about **0.605** milliseconds / `jQuery` take about **1.460** milliseconds.
##### `Native JavScript code`
```js
JSON.parse(string);
```
##### `jQuery code`
```
$.parseJSON(string);
```
### Trim Comparsion
Live code at [https://jsfiddle.net/dda467b1/67/](https://jsfiddle.net/dda467b1/67/)

`Native JavScript` take about **0.200** milliseconds / `jQuery` take about **0.279** milliseconds.
##### `Native JavScript code`
```js
string.trim();
```
##### `jQuery code`
```
$.trim(string);
```
### Type Comparsion
Live code at [https://jsfiddle.net/dda467b1/68/](https://jsfiddle.net/dda468b1/67/)

`Native JavScript` take about **1.610** milliseconds / `jQuery` take about **0.210** milliseconds.
##### `Native JavScript code`
```js
Object.prototype.toString.call(obj).replace(/^\[object (.+)\]$/, '$1').toLowerCase();
```
##### `jQuery code`
```
$.type(obj);
```