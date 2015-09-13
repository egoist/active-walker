# active-walker

for some header element, like:

`<a href="#" class="nav active-walker" data-active-when=".section-1"></a>`

ActiveWalker.watch('.active-walker')

---

And then if you scroll to the element specified in `data-active-when`
it shall trigger .addClass function on `.active-walker`
