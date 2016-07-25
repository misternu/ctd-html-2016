# Media Query Challenge

An increasing number of people are using multiple devices to access the same services and websites. Because of this, CSS has been made adaptable to different screen sizes and resolutions.

### Preparation

Set up an 'index.html' file with the boilerplate, and link it to a 'style.css'. Set the following css rule:

```css
body {
  background: blue;
}
```

### Query

We are going to make it so that the page behaves a certain way when the window is smaller than 600 pixels. Most smartphones are smaller than this, so it should make it so the page has a custom background. Put the following in your css

```css
@media (max-width: 600px) {
  body {
    background: red;
  }
}
```

An `@media` rule specifies a particular set of circumstances in which the inside rules apply. In this case, the rule only applies up to 600px, and then it turns off.

Try changing dragging the bottom right corner of your window. When the window becomes thin enough, it should turn from blue to red, and vice versa. Read more about `@media` on the MDN page.
