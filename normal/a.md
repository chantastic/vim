# [aA] Append Text with A from Normal Mode

## Summary

Use `a` to append text from normal mode.
From normal mode, both lowercase `a` and uppercase `A` will put you into insert mode.
`a` enters insert mode after the cursor.
`A` enters insert mode at the end of the current line.

## Lesson

Use `a` to append text from normal mode.
Both lowercase `a` and uppercase `A` will put you into insert mode.

Hit `a` to enter insert mode after the cursor.
Hit `esc` to leave insert mode for normal mode.

Hit `A` to enter insert mode at the end of the current line.
This will whereever your cursor is.

Linebreaks determine the end of a line.
For example, this paragraph is only one line but wrapping over multiple lines on screen.
Hitting `A` takes us to the end of the paragraph.

We can run the command `:set nowrap` to turn wrapping off and see where the line ends.
Then `:set wrap` to get back to the default view.

## Samples

### Paragraph

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam at lectus eu sem convallis blandit. Fusce fringilla congue leo. Nam condimentum augue in vehicula hendrerit. Nam dignissim sollicitudin ante, at consequat urna posuere et. Donec tincidunt est sed maximus semper. Donec non arcu vitae nunc efficitur congue. Quisque venenatis ullamcorper est, nec gravida risus sagittis at. Pellentesque dapibus libero et auctor pellentesque.

### Varibles

this-is a_test ofSpecialCases

### Code

```jsx
function MyComponent(props) {
  return <div {...props} />;
}
```
