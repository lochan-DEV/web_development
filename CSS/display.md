## What is `display`?

The CSS display property controls `how an HTML element behaves in the page layout.`

In simple words:

- `display` tells the browser how an element should occupy space and interact with other elements.


# 1. `display: block`

A block element:

- Starts on a new line.
- Usually takes the full available width by default.
- Allows `width` and `height`.
- Other block elements normally appear below it.

# 2. `display: inline`

we can display more no of separate elements into same line :

```
example :

`hello
world 
i m 
learning 
css`

into 

`hello world im learning css`
```

# 3. `display: inline-block`

inline-block combines important properties of inline and block.

It behaves: Like inline → it can sit beside other elements.
            Like block → you can set width and height.
```            
Example
<div class="box">One</div>
<div class="box">Two</div>
<div class="box">Three</div>
.box {
    display: inline-block;
    width: 100px;
    height: 100px;
}
```

# 4. display: none

display: none makes an element completely disappear from the page layout.
it does not delete the element it just hides the element .which can be brought back using commnds like javascript...
```
Example
<p>Hello</p>
<p class="hidden">World</p>
.hidden {
    display: none;
}
Output
Hello

World is not displayed.


``` 

More importantly, it does not occupy any space.

# summary 
- BLOCK → new line + size 
- INLINE → same line + content size 
- INLINE-BLOCK → same line + custom size 
- NONE → hidden + no space