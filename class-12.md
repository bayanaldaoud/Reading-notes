# **<span style="color:#d85164"> Chart.js, Canvas </span>**


You can download the latest version of Chart.js from the GitHub releases or use a Chart.js CDN. Detailed installation instructions can be found on the installation page.



## Creating a Chart
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.

In this example, we create a bar chart for a single dataset and render that in our page. You can see all the ways to use Chart.js in the usage documentation.

>```<canvas id="buyers" width="600" height="400"></canvas>```
### The `<canvas>` element :
At first sight a `<canvas>` looks like the `<img> `element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.
As a consequence of the way fallback is provided, unlike the `<img>` element, the `<canvas>` element requires the closing tag (`</canvas>`). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.
>`<canvas id="foo" ...></canvas>`

### The grid 
Unlike SVG, `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

![](https://lh3.googleusercontent.com/proxy/iV4PkGirM_glsLm_6CE3D81y9xP44RPTNGDFjwp-1M2OwVti5UnYYYkxr5uU6FV07JPlHMvIbfRuILaPDDrv4XtskXG-YmKJ0WKTu0_1YuZYQtTovJ6qI9BQX_YQz1BavwyYdXtBKXHM277BwxcHWR3N-L-gKMO9S3p5Z6qx6_5Qi7KglbNhyaZlTcZL9uoS933B7nLYrZyl5-4)



**color** is a string representing a CSS `<color>`, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).
```ctx.fillStyle = 'orange';
ctx.fillStyle = '#FFA500';
ctx.fillStyle = 'rgb(255, 165, 0)';
ctx.fillStyle = 'rgba(255, 165, 0, 1)'; 
```

what you can do ;


![](https://download.infragistics.com/users/gmurray/blogs/images/canvas/part2/canvaspart2.png)