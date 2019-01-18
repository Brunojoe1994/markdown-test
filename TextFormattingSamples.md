# Text Formatting

This is a paragraph with out any formatting.

You can use star for *italic*

You can also use underscore for _italic_

You can use double asterisks for **bold**

You can also use doubel underscore for __bold__

You can use double tilde for ~~striksthrough~~

For horizontal line you can use three dashes as shown below:

---

You can also use triple underscore for horizontal line as show below:
___

The escape character is back slash. For example you can skip italic and have asterisk character by using a back slash as shown here \*not in bold\*

>This is a quote and you get blue line right next to this line of sentence.

For a hyperlink you will have the text in square bracket and the URL in parentheses. For example: 
[Microsoft Learning](https://www.microsoft.com)

If you need a title, include that too as shown below:
[Microsoft Learning](https://www.microsoft.com, "Microsoft Learning")

For bullets you can use asterisks
* SQL Server
* Visual Studio
* Office
* SharePoint

If you need a next level list of bullet, use tab for spaceing and use asterisks
* Included in Office Package
    * Word
    * Excel
    * PowerPoint
    * Skype for Business
    * Outlook

For ordered list use 1 and a dot

1. SQL Server
1. Visual Studio
1. Office
1. SharePoint

For inline code block use the HTML tags.
<p>This is a paragraph</p>
<ul>
    <li>Redmond</li>
    <li>Bellevue</li>
    <li>Kirkland</li>
</ul>



For Images use the exclamation symbol then the title in square bracket and the image URL in parentheses.


For comments use the less than symbol the exclamation symbol and two dashes and to close two dashes and the greater than symbol (Same as there in HTML and XML).

![Sample Image](https://markdown-here.com/img/icon256.png)


<!-- This is a comment-->

## GitHub Markdown

For code block you can use triple backtick character

```
cd c:
mkdir myfolder
cd myfolder

```

You can also have syntax specific code block 
``` javascript
function fnAdd(int x, inty){
    var y;
    y = x + y;
    return y; 
}
```

```python
def fnAdd(x, y) : 
    return x + y
```

### Tables

| Make  | Model  |
|-------|--------|
| Honda | Civic  |
| Toyota| Corolla|

### Task List
* [x] Seattle
* [x] Redmond
* [x] Bellevue
* [ ] California
* [ ] San Francisco
* [x] Texas

