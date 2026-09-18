# Three Ways to Add CSS

`1. Inline CSS - CSS is written directly inside the HTML element using the style attribute.`

```
 example - <p style="color: red;">Hello</p> 
 ```

`2. Internal CSS - CSS is written inside a <style> block within the HTML document.`
```
example ;<head>
             <style>
                    p {
                       color: red;
                      }
             </style>
         </head>
```



`3. External CSS - CSS is written in a separate .css file and connected to HTML.`
```
example :
HTML
<link rel="stylesheet" href="style.css">  -- this command is used to link the css file --

style.css
p {
    color: red;
}

```