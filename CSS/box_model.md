# CSS Box Model

The CSS Box Model describes how an HTML element is structured as a box.

Every element consists of four main parts:

1. Content
2. Padding
3. Border
4. Margin

# 1. Content 

Content is the actual information inside an HTML element.

It can be:[Text , Images , Buttons , Other HTML elements]

-----------------------------------------------------------------------------------------------------------------------------------------

# 2. Padding

Padding is the space between the content and the border.

```
.box {
    padding: 20px;
}

Padding creates space inside the box, around the content.

┌─────────────────────────┐
│         BORDER          │
│                         │
│      ← PADDING →        │
│        CONTENT          │
│                         │
└─────────────────────────┘
```


# Individual Padding

- Each side can be controlled separately:
```
padding-top: 10px;
padding-right: 20px;
padding-bottom: 30px;
padding-left: 40px;
Padding Shorthand
padding: 10px 20px 30px 40px;
```

Order:TOP → RIGHT → BOTTOM → LEFT

`in simple words `
Padding = space inside the box around the content.


-----------------------------------------------------------------------------------------------------------------------------------------


# 3. Border

Border surrounds the content and padding.

```
Example:

.box {
    border: 3px solid black;
}
```

` syntax`
border: width style color;


` in simple words`
Border = boundary around the content and padding.


-----------------------------------------------------------------------------------------------------------------------------------------


# 4. Margin

Margin is the space outside the border.
[Margin creates space between the element and other elements.]

```
.box {
    margin: 20px;
}



        ←── MARGIN ──→
    ┌─────────────────┐
    │     BORDER      │
    │  ┌───────────┐  │
    │  │  CONTENT  │  │
    │  └───────────┘  │
    └─────────────────┘
 ```

# Individual Margin

Each side can be controlled separately:

margin-top: 10px;
margin-right: 20px;
margin-bottom: 30px;
margin-left: 40px;
Margin Shorthand
margin: 10px 20px 30px 40px;

`Order:TOP → RIGHT → BOTTOM → LEFT`

Two Values
margin: 10px 20px;

Means:Top/Bottom = 10px
      Left/Right = 20px
     

Centering a Box For a  block element:
```
.box {

    margin: 0 auto;
}

This gives automatic left and right margins and can center the box horizontally.
```

` in simple terms`
Margin = space outside the box.