# Hacker News Light Style

A customized light style for Hacker News. Somewhat identical to [lobste.rs](https://lobste.rs/).

Steps to install:

1. Install [Stylus](https://github.com/openstyles/stylus), this is the alternative for Stylish but without [the evil stuff](https://news.ycombinator.com/item?id=17447816).
2. Write a new style for `news.ycombinator.com`, paste the following CSS, and that's all:

```css
#hnmain {
    width: 750px;
    background: none;
}

#hnmain td:first-child {
    background: #FFF;
}

a.storylink {
    font-weight: bold;
}

.itemlist {
    margin-top: 10px;
}

.itemlist tr.spacer {
    height: 10px !important;
}

form[action="comment"] textarea {
    border: 1px solid #AAA;
    resize: none;
}

form[action="comment"] input[type="submit"] {
    padding: 5px 10px;
    background: #333; color: #FFF;
    border: none;
}

.topsel a:link, .topsel a:visited {
    background: #333;
    padding: 2px 5px;
}
```
