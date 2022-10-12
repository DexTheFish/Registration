# Registration Form

HTML registration form, with user data control and some CSS styling. Useful as a template for adding a registration feature to other apps. Built with guidance from FreeCodeCamp. 

## Lessons Learned

get rid of redundant scroll-bars by setting the body default margin (added by some browsers) to 0:
```html
body {
  margin: 0;
}
```
inline elements can be separated onto their own lines by adding `<br>` tags to our html *or* by adding `display: block` to the parent element's CSS. Use context to determine whether the separation is *structural* or *stylistic*. Poems are a good example of where `<br>` is appropriate. For the registration form, `display: block` is appropriate.  
<br>
html offers some form validation features such as `required` and `minlength` that can be added to inputs, for example: 
```html
<input type="password" required minlength="8">
```
Another example is the `pattern` attribute that can specify charsets and lengths of input elements.
