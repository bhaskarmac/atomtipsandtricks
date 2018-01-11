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

`::-webkit-scrollbar {
  width: 15px !important;
  border: 0px;

  &-track {
    border: 0px!important;
    background-color: #2c3e50 !important;
  }

  &-thumb {
    background-color: #3498db !important;
    border: 0px!important;
  }
}`
