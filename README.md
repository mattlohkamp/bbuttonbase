#bbuttonbase

bbuttonbase allows common ui elements (anchors, inputs, and buttons) to be presented consistently cross-browser.

---

The following markup pattern:
```html
<span class="bbuttonbase"><input type="button" value="this is an input button" /></span>
<span class="bbuttonbase"><input type="submit" value="this is an input submit" /></span>
<span class="bbuttonbase"><input type="reset" value="this is an input reset" /></span>
<span class="bbuttonbase"><input type="image" value="" src="" /></span>
<button type="button" class="bbuttonbase"><span>this is a button</span></button>
<a href="" class="bbuttonbase">this is a link</a>
```

renders inline plain text links. from there, it's easy to extend by adding styles for graphical button elements, like so:

```html
<div class="exampleSkin"><span class="bbuttonbase"><input type="button" value="this is an input button" /></span></div>
<div class="exampleSkin"><span class="bbuttonbase"><input type="submit" value="this is an input submit" /></span></div>
<div class="exampleSkin"><span class="bbuttonbase"><input type="reset" value="this is an input reset" /></span></div>
<div class="exampleSkin"><span class="bbuttonbase"><input type="image" value="" src="accept.png" /></span></div>
<div class="exampleSkin"><button type="button" class="bbuttonbase"><span><img src="accept.png" />this is a button</span></button></div>
<div class="exampleSkin"><a href="" class="bbuttonbase"><img src="accept.png" />this is a link</a></div>
```

allowing you to present common ui elements identically, while choosing your markup according to semantics.