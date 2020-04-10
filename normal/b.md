# [bB] Move Back to the Beginning of Words with B in Normal Mode

## Summary

Use `b` to navigate back — to the beginning of words — in normal mode.
Both lowercase `b` and uppercase `B` navigate to the beggining of the current word.
If you're cursor is already at the beginning of sa word, `b` and `B` will move you to the bigenning of the previous word.

Lowercase `b` and uppercase `B` differ only in how they interpret words.
`b` will stop at non-alphaneumeric characters — as if they were words.
`B` will skip over (most) non-alphaneurmeric characters as if they are parts of a word.

## Lesson

Use `b` to move back to the beginning of a word.
If you're at the beginning of a word, hit `b` to move to the beginning of the previous word.

You can do this until you run out of words to move back to.

Lowercase `b` treats special characters as words.

In this sample paragraph, notice how `b` stops at punctuation.

Jumping to this code block,
Notice how `b` also stops at angle curly braces, brackets, and parenthesis.

With common variable naming, `b` wont stop for capitalization or `_`s.
However, it will stop for dashes.

`B` disregards all characters — defining words by whitespace.
Using capital `B` will effectively move you back to the first word character just after the previous whitespace.

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
