
# **<span style="color:#d85164">JS Object Literals; The DOM</span>**

## **<span style="color:#b789">Object Literals</span>**

You have already learned that JavaScript variables are containers for data values.
This code assigns a simple value (Fiat) to a variable named mobile:

> `var mobile = "Fiat";`

Objects are variables too. But objects can contain many values.

This code assigns many values (Fiat, 500, white) to a variable named mobile:
> `var mobile = {type:"Fiat", model:"500", color:"white"};`


The values are written as name:value pairs (name and value separated by a colon).Spaces and line breaks are not important. An object definition can span multiple lines.


## **<span style="color:#b789">Document Object Model</span>**
When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects:



With the object model, JavaScript gets all the power it needs to create dynamic HTML:

- JavaScript can change all 
   - the HTML elements in the page
   - the HTML attributes in the page
   - the CSS styles in the page


- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page


**HTML DOM** methods are actions you can perform (on HTML Elements).

**HTML DOM** properties are values (of HTML Elements) that you can set or change.


### **The DOM Programming Interface**
The HTML DOM can be accessed with JavaScript (and with other programming languages).

In the DOM, all HTML elements are defined as objects.

The programming interface is the properties and methods of each object.

A property is a value that you can get or set (like changing the content of an HTML element).

A method is an action you can do (like add or deleting an HTML element).

Example :
The following example changes the content (the innerHTML) of the` <p> element with id="demo"` :

```
<html>
<body>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello World!";
</script>

</body>
</html>
```


In the example above, getElementById is a method, while innerHTML is a property.

**The getElementById Method**

The most common way to access an HTML element is to use the id of the element.

In the example above the getElementById method used id="demo" to find the element.

**The innerHTML Property**

The easiest way to get the content of an element is by using the innerHTML property.

The innerHTML property is useful for getting or replacing the content of HTML elements.
