# flex 布局

## 父盒子属性

```
   .container {
            display: -webkit-flex;
            display: flex;
        }
        -----------------------------------------
        1、flex-direction属性

        flex-direction 属性决定主轴的方向（子元素的排列方向）。

        .container { flex-direction:  row;  /* 水平方式: row | row-reverse 垂直方向: column | column-reverse */ }

        2、flex-wrap属性

        默认情况下，项目都排在一条线（又称"轴线"）上。flex-wrap属性定义，如果一条轴线排不下，如何换行。

        .box{ flex-wrap:nowrap;  /* 默认 nowrap | wrap 换行 | wrap-reverse; 换行反序 */ }

        3、flex-flow

        flex-flow属性是flex-direction属性和flex-wrap属性的简写形式，默认值为row nowrap。

        .box { flex-flow: <flex-direction> || <flex-wrap>; }

        4、justify-content属性

        justify-content属性定义了项目在主轴上的对齐方式。

        .box { justify-content:flex-start;}

        /*  flex-start 左对齐 | flex-end 右对齐 | center 居中 | space-between 两端对齐，项目之间的间隔都相等 | space-around; 每个项目两侧的间隔相等。所以，项目之间的间隔比项目与边框的间隔大一倍  */




```

## 子盒子属性
