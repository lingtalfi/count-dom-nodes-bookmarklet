Count DOM nodes bookmarklet
==============================
2016-09-23



A bookmarklet that alerts how many DOM nodes you have on your page.




How to use
---------------

### In Firefox

Paste the following code into a web page and open it in a browser,
then put add the link to your favorites (drag the link in your tool bar).


```html
<!DOCTYPE html>
<html>
<head>
	<title>Count DOM nodes on a page</title>
</head>
<body>
<a href="javascript: (function () {alert(document.getElementsByTagName('*').length); }());">Count DOM nodes of a page: put me in your favorites</a>
</body>
</html>
```



### In Chrome

In Chrome, click Bookmarks->Bookmark Manager.<br>
You should see a new tab with the bookmarks and folders listed.<br>
Select the "Bookmarks Tab" folder on the left.<br>
Click the "Organize" link, then "Add Page" in the drop down.<br>
You should see two input fields. ...<br>
Paste the javascript code below into the second field.<br>


```js
javascript: (function () {alert(document.getElementsByTagName('*').length); }());
```





