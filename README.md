# AtomNAV
An Atom keymap snippet that enables you to navigate through, select, and delete (both with backspace and delete) subwords (works with camelCase, snake_case, kebab-case and PascalCase)

### Add the following snippet to your Atom's keymap.cson file:
```
'.editor':
  'ctrl-backspace': 'editor:delete-to-beginning-of-subword'
  'ctrl-delete': 'editor:delete-to-end-of-subword'
  'ctrl-right': 'editor:move-to-next-subword-boundary'
  'ctrl-left': 'editor:move-to-previous-subword-boundary'
  'ctrl-shift-right': 'editor:select-to-next-subword-boundary'
  'ctrl-shift-left': 'editor:select-to-previous-subword-boundary'
```
### That's it! Enjoy your subword ctrl navigations and deletions!
