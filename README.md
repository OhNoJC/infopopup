# infopopup
Infowindow: A JavaScript plugin, Google do not provide fancy an Infowindow, an alternative of an Infowindow.

Easy to modified. Put your HTML template and enjoy fancy infopopup on Google map.

Code:

```javascript
var options = {
  'className': 'info-pop-up-content',
  'background': '#FFFFFF',
  'padding': '5px',
  'minWidth': '200', //px
  'content': '<div class="tile"><div class="width-30"><img src="profile-photo.jpg"></div><div class="width-70"><label>Sarthak Dabhi</label><br>WEB DEVELOPER<br>Website: <a href="http://sarthakdabhi.me/">sarthakdabhi.me</a></div></div>'
};
var infoPopup = new InfoPopup(marker, map, options);
```