# triangles.js
A library for Delaunay triangulation and Lambertian reflectance. Want to get familiar with the library? [Check out the playground!](https://opensourceskier.github.io/triangles.js)

*Documentation and more examples will come soon!* 

## Examples
### **Basic Usage**
**HTML** - *index.html*
```html
<head>
    <link rel='stylesheet' href='index.css'/>
    <script type='text/javascript' src='triangles.js'></script>
</head>
<body>
    <div id='container'></div>
</body>
```
**CSS** - *index.css*
```css
body,html {
    width: 100%;
    height: 100%;
    margin: 0;
}

#container {
    width: 100%;
    height: 100%;
}
```

**Javascript** - *index.js*
```javascript
const element = Triangles.add({
  id: 'container'
});
```
## Attribution
Based upon the demo originally created by [**Maksim Surguy**](https://github.com/msurguy/triangles).<br>
Special thanks to him for the inspiration for this library!

## License
Licensed under the [MIT License (MIT)](https://opensource.org/licenses/MIT).
