Count DOM nodes bookmarklet
==============================
2016-09-23



A bookmarklet that alerts how many DOM nodes you have on your page.




How to use
---------------

Paste the following code into a web page and open it in a browser,
then put add the link to your favorites (in firefox, drag the link in your tool bar).


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



