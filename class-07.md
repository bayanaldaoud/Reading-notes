# **<span style="color:#d85164">HTML Tables; JS Constructor Functions</span>**

## **<span style="color:#b789">HTML Tables</span>**

he `<table>` tag defines an HTML table.

Each table row is defined with a `<tr>` tag. Each table header is defined with a `<th>` tag. Each table data/cell is defined with a `<td>` tag.

By default, the text in `<th>` elements are bold and centered.

By default, the text in `<td>` elements are regular and left-aligned.

![](https://flaviocopes.com/html-tables/no-styling.png)


Use the CSS :
* `border` property to define a border
* `border-collapse` property to collapse cell borders
* `padding` property to add padding to cells
* `text-align `property to align cell text
* `border-spacing` property to set the spacing between cells
* `colspan` attribute to make a cell span many columns
* `rowspan` attribute to make a cell span many rows
* `id` attribute to uniquely define one table




## **<span style="color:#b789"> functions methods and objects</span>**



- The `this` Keyword :
    In a function definition, `this` refers to the "owner" of the function.

In the example above, `this` is the person object that "owns" the fullName function.

In other words, `this.firstName` means the firstName property of this object.

Read more about the `this` keyword at JS this Keyword.

JavaScript methods are actions that can be performed on objects.

A JavaScript method is a property containing a function definition.

- You access an object method with the following syntax:

- ``objectName.methodName()``
You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().
- ``toUpperCase()`` method of the String object, to convert a text to uppercase:
```
var message = "Hello world!";
var x = message.toUpperCase();

```
### In a simple way : 


![](https://lh3.googleusercontent.com/proxy/cubh4NNQp31FMpQK8fQpNCtR-4upRy_OQoWcrC3FccdPxm_JkZxm4zsmhVrhseaUsPYq5dKn9wRwwPR_VwRkyqmgdEk2kPSmH4a-)


