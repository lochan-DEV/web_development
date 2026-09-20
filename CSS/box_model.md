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

