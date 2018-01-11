# Atom tips and tricks

## Tips
#### Multiple Cursors
Just hold cmd (Mac) or ctrl (Windows/Linux) and click in every place you want to type.

#### Duplicate line
To create a duplicate line use following key combinations.

`Cmd + Shift + D (Mac)`
`Ctrl + Shift + D (Windows/Linux)`

#### Toggle comments (on and off)
To toggle comments use following key combinations.

`Cmd + / (Mac)`
`Ctrl + / (Windows/Linux)`

#### Changing scrollbar width and color
Add following code snippet in styles.less [File->Stylesheet...]

```css
::-webkit-scrollbar {
  width: 12px !important;
  border: 0!important;

  &-track {
    background-color: #2c3e50 !important;
  }

  &-thumb {
    background-color: #3498db !important;
  }
}
```
