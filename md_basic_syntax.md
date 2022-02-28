<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


<!-- Bold -->
**This text is made bold using double asterisk**

__This text is made bold using double  underscores__
<!-- Italics -->
*This text is made italic using asterisk*

_This text is made italic using single underscores_
<!-- Italics and bold at the same time -->
***For both italics and bold We use tripple asterisks or tripple underscores***

<!-- NB -->
**To use the asterisk or underscore as part of text we use an escape character \*text or \_text**
<!-- Strikethrough -->
~~To strikethrough text~~ we use double tilde
<!-- Horizontal Rule -->
---
We use tripple hyphens or tripple underscores to create an horizontal rule 
___
<!-- Blockquotes -->
> Blockquote we use a greter than symbol
>
>> We are nesting another blocquote by using two greater than signs.
<!-- Links -->
[Link to Hasgotech](https://www.hasgotech.com)

[Link to Hasgotech with title on hover](https://www.hasgotech.com "Hasgotech")
<!-- Unordered Lists -->
> For Unordered Lists We use  a single hyephen(-) or asterisk(*) or plus(+) before the item. To nest an item we indent.
- Item 1
- Item 2
- Item 3
  - Nested Item 1
  - Nested Item 2
- Item 4
   - Nested Item 3
     - Twice Nested Item 
- Item 5
  
  <!-- Ordered Lists -->
> For Ordered lists we use (1) before every item or normal numbering.To nest an item we indent.
 1. Item 1
 1. Item 2
 1. Item 3
     1. Indeted Item 3.1
     2. Indented Item 3.2
1.  Item 4

<!-- Inline Code Block -->
`<p>This is a paragraph</p>`

<!-- Images -->
To add an image, use an exclamation mark followed by alt text in brackets, then link to the image in parentheses.To add a title o hover we put it in quotes after the link but still within the parentheses.
![Laptop Image](https://cdn.pixabay.com/photo/2020/10/21/18/07/laptop-5673901_960_720.jpg "Laptop Image Pixabay")

To link an Image, enclose the markdown for the image in brackets, followed by the link to the image.
[![code on pc](https://cdn.pixabay.com/photo/2021/08/05/12/36/software-development-6523979_960_720.jpg "coding man")](https://pixabay.com/photos/software-development-developer-6523979/)

<!-- Code -->
    <!DOCTYPE html>
    <html>
        <head>
        </head>
        <body>
         `<p>This is a paragraph<p>`
        </body>
    </html>

<!-- Github Markdown -->
<!-- Code Blocks -->
We enclose code in 3-backticks on two lines.The language can be specified after the first backticks

```bash
$ git add .

$ git commit -M "Adding project files"

$ git push origin main

```

```css
   h1 {
     color: blue;
     fontsize: 120%;
   }
   a:hover {
     background-color: red;
   }
```
```javascript
   numbers = {1,2,3,4,5,6,7,8,9,}
   const filteredArray = numbers.filter(value => value < 5)

   const square = value => {
     return value * value;
   }
   square(3);
```

```json
{
  "firstName": "Hassan",
  "lastName": "Bulega",
  "age": 27,
  "Occupation": "Full Stack Web Developer"
}
```
<!-- Tables -->
|City|Country|Continent|
|:-----|:-----:|-----:|
|Kampala|Uganda|Africa|
|Moscow|Russia|Asia|
|Leeds|England|Europe|

<!-- Task List -->
* [x] Task list 1 checked
* [ ] Task list 2 unchecked
* [ ] Task list 3 unchecked