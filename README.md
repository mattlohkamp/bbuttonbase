#bbuttonbase

bbuttonbase allows common ui elements (anchors, inputs, and buttons) to be presented consistently cross-browser.

---

With bbuttonbase, the following markup pattern:
```html
<span class="bbuttonbase"><input type="button" value="this is an input button" /></span>

<span class="bbuttonbase"><input type="submit" value="this is an input submit" /></span>

<span class="bbuttonbase"><input type="reset" value="this is an input reset" /></span>

<span class="bbuttonbase"><input type="image" value="" src="accept.png" /></span>

<button type="button" class="bbuttonbase"><img src="accept.png" /><span>this is a button</span></button>

<a href="" class="bbuttonbase"><img src="accept.png" /><span>this is a link</span></a>
```

renders each interactive element as a plain inline text link. from there, it's easy to extend by adding styles for graphical button elements, like so:

```html
<div class="exampleSkin"><span class="bbuttonbase"><input type="button" value="this is an input button" /></span></div>

<div class="exampleSkin"><span class="bbuttonbase"><input type="submit" value="this is an input submit" /></span></div>

<div class="exampleSkin"><span class="bbuttonbase"><input type="reset" value="this is an input reset" /></span></div>

<div class="exampleSkin"><span class="bbuttonbase"><input type="image" value="" src="accept.png" /></span></div>

<div class="exampleSkin"><button type="button" class="bbuttonbase"><img src="accept.png" /><span>this is a button</span></button></div>

<div class="exampleSkin"><a href="" class="bbuttonbase"><img src="accept.png" /><span>this is a link</span></a></div>
```

allowing you to present common ui elements identically, while choosing your markup according to semantics.

To see these examples in action, check out the exampleImplementations.htm page included in this repo.