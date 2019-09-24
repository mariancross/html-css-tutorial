Adding CSS rules in HTML file

```
<style type="text/css"> 
  body {
    background-color: black;
    color: white;
  }
  h1 {
    color: red; 
    font-size: xx-large;
    text-align: center;
  }  
  .fancy {
    background-color: orange;
    color: black;
    font-weight: bold;
  }
</style>
```

[Link to result](https://github.com/mariancross/html-css-tutorial/blob/a747f9569a0c94b5a5e4fd6e9e47635ccb3b21ad/page_with_css.html)

--

Adding CSS rules in a .css file

```
body {
  background-color: black;
  color: white;
}
h1 {
  color: red; 
  font-size: xx-large;
  text-align: center;
}
.fancy {
  background-color: orange;
  color: black;
  font-weight: bold;
}
```

and import that file in HTML file

```
<link rel="stylesheet" href="layout.css">
```

[Link to result](https://github.com/mariancross/html-css-tutorial/blob/ca352ab6b1731b7af435a1324175c539dfec5e58/page_with_css.html)
