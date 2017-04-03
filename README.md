# making-css-smaller

I think the reason CSS is so confusing for me is that it gives the same treatment to a lot of unrelated concepts.

```css
.thing {
  color: green;
  display: inline-flex;
  background-image: url(img/cat.gif);
  height: 400%;
  transition: opacity 1.2s ease-in-out;
}
```

## Separation of Concerns

Three or four hundred of these properties fall under the same umbrella of presentation. I like to imagine an alternate reality where SoC relates to categories like typography, placement, size, shape, and motion. It's conceivable that they'd all have there own design tools, and maybe there are different job roles associated with each one. No wonder CSS is hard for me - I'm doing the work of 5 people :).

## Grouping Properties

In our current reality we may be able to make CSS conceptually smaller by sorting its properties into categories.
