# numberAnimate

numberAnimate 是一款数据滚动组件，我是站在巨人的肩膀上进行制作，提高页面美观性 ，使页面更加绚丽。

## About

### 创建时间 2016-09-18 16:58

#### 作者 [@zoeblow](https://github.com/zoeblow)

#### Demo [在线 Demo](http://ifuyuan.wang/gitdemo/numberAnimate/index.html)

## 效果

![numberAnimate-preview](https://raw.githubusercontent.com/zoeblow/numberAnimate/master/numberAnimate.gif)

## 版本

> - V 1.0
> - 修改时间 ：2016-09-18 16:58
> - 描述：V 1.0 首次提交，之前已经对页面，井进行过若干次修改。
> - 本次就不做具体说明

---

> - V 1.1
> - 修改时间 ：2019-04-09 16:23
> - 描述：V 1.1 修复 bug
> - 修复显示错位[bug](https://github.com/zoeblow/numberAnimate/issues/1)

---

## 调用方式

在 html 中引入 jquery 之后引入 numberAnimate.js
完成之后即可直接使用

```html
<div class="number_run_box"></div>
<br /><br />

<script type="text/javascript" src="../dest/script/jquery.min.js"></script>
<script type="text/javascript" src="../dest/script/numberAnimate.js"></script>
<script>
  $(".number_run_box").numberAnimate({
    num: "15342.10",
    pst: "%",
    dot: 2,
    speed: 2000,
    symbol: ",",
  });
</script>
```

---

## 参数

```js
numberAnimate({ num: "15342.10", pst: "%", dot: 2, speed: 2000, symbol: "," });
```

|  参数  |   取值类型    | 默认值 | 描述                                      |
| :----: | :-----------: | :----: | :---------------------------------------- |
|  num   | String/Number | 必填项 | 需要滚动的数字                            |
| speed  |    Number     |  1000  | 滚动的时间默认为一秒                      |
| symbol |    String     |   -    | 是否存在千位分隔符，可输入任意字符        |
|  dot   |    Number     |   0    | 是否保留小数默认为 0 位小数(也就是分没有) |
|  pst   |    String     |   -    | 是否有百分号默认为空                      |

---
