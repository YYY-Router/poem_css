###### css实现古诗排版（从右向左）

> + 涉及的css属性

```css
p{
    /*设置文本书写方向属性*/
    writing-mode:horizontal-tb;
    /*
    horizontal-tb，表示水平书写，从上到下；
  	vertical-rl，表示垂直书写，从右到左；
    vertical-lr，表示垂直书写，从左到右。
    */
}
```

```css
P{
    /*设置单个文本朝向*/
   text-orientation:upright;
    /*
    upright，设置文字垂直朝向；
    */
}
```

```css
P{
    /*文字在朝下布局下，要不要组合起来属性*/
    text-combine-upright:all;
    /*
    all，表示全部组合起来
    */
}
```

