# CSS
>毛玻璃效果
```css
#xxx {
    backdrop-filter: saturate(180%) blur(1px);
    background-color: rgba(255, 255, 255, 0.1);
}
```

>好看按钮
```css
.button {
    outline: none;
    line-height: 1.499;
    position: relative;
    display: inline-block;
    font-weight: 400;
    white-space: nowrap;
    text-align: center;
    background-image: none;
    border: 1px solid transparent;
    -webkit-box-shadow: 0 2px 0 rgba(0, 0, 0, 0.015);
    box-shadow: 0 2px 0 rgba(0, 0, 0, 0.015);
    cursor: pointer;
    -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
    transition: all .3s cubic-bezier(.645, .045, .355, 1);
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    -ms-touch-action: manipulation;
    touch-action: manipulation;
    height: 32px;
    padding: 0 15px;
    font-size: 14px;
    border-radius: 4px;
    color: rgba(0, 0, 0, 0.65);
    background-color: #fff;
    border-color: #d9d9d9;
}

.red-color {
    color: #fff;
    background-color: #FFBCBC;
    border-color: #FFBCBC;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.12);
    -webkit-box-shadow: 0 2px 0 rgba(0, 0, 0, 0.045);
    box-shadow: 0 2px 0 rgba(0, 0, 0, 0.045);
}

.red-color:hover {
    background-color: #FF5A44;
    border-color: #FF5A44;
}
```

>渐变
```css
#xxx {
    background-image: linear-gradient(111deg, #155799, #fff);
}
```
