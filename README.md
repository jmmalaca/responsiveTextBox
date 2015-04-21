# responsiveTextBox

Imagine a TextBox in your web page.
The user will write something and that text is used to request something to the server.

Now,
 If you use only the "focusout" event... only when the user press enter or click out of the box that the request is made,
 If you use only the "keyout" event... after every keypress a request is made...
 
 What's the best choice??... 
 We want to use the "focusout" event yes but using the "keyout" event too but with a little BIG detail... 
  this "keyout" event needs to have a delay like you see on search engines. wait a bit... nothing is pressed... make a request.

This is what I have made using javascript and Kendo UI MVVM.
You can find it too here: http://jsfiddle.net/jmmalaca/v9q48hzp/
