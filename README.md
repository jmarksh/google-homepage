Some interesting things I noticed throughout this process that I'll use later or need to look up.

- `border-radius: 50%` is not the same as `border-radius: <50% of the height in pixels>`. I believe that declaring pixels bends just the radius around the height but declaring a percentage bends both the width and the height at that percentage. Need more research.

- Google sets `outline` to `none` on the textbox `input`, but when I looked this up to detemrine how to do it, I was met with a lot of opposition, stating that this makes the page less accessible. This makes sense, but I don't know how Google "gets around" that, so to speak.

- Google keeps the `box-shadow` property set for the search box when the textbox is focused, but I couldn't figure out how to do that since the method I used to generate these items made the element with the shadow the parent of the `input`. As far as I'm aware, parent selectors are not a thing yet.

- Empty `<div>` elements are pretty useful. I wonder if they are frowned upon? But that's how you draw CSS images, so I'm guessing not.