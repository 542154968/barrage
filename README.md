# demo图
(!Image)[https://github.com/542154968/barrage/blob/master/showImgs/show.jpg]

# 简介
受剧中人大神和falseLuffy的启发 为我自己工作的的项目增加了这个功能 因为需求比较少 所以是个很简单的文字DOM滚动功能 CSS3实现的滚动

```JavaScript
// 默认参数
var defaults = {
    // 在哪里产生弹幕
    el: '#barrage',
    // 关闭按钮
    closeEl: '.hide-barrage',
    // 数据的数组 [ {text: ''}, {text: ''} ] text必须有
    data: data,
    // 颜色的数组  {Array}  ['#ff', 'red']
    color: colorArr,
    // 多少个data 分一组  Number
    groupSlice: 5,
    // 多少毫秒秒增加一次dom  这个关乎到弹幕的左右间距（ 密集度 ）
    addIntervar: 3000,
    // 动画时间 25 ~ 20s
    rangeTime: [ 25, 20 ]
};
```
