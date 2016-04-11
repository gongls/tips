```
/* edit plus begin
@author gongWB
@d      2015-05-13
*/

/* 编辑器颜色：不要背景色 */
.note-palette-title {
    display: none;
}

ul.dropdown-menu[data-name="color"] {
    width: 180px;
    width: 200px;
    padding-left: 10px;
}

/*编辑器颜色里的 重置 按钮 */
.note-color-reset {
    width: 20px;
    height: 20px;
    padding: 0;
    margin: 0 0px 0px 5px;
    border: 1px solid #f00;
    border-radius: 50%;
    background: #fff;
    cursor: pointer;
    overflow: hidden;
    line-height: 1000px;
    display: block;
}

.note-color-reset:before {
    content: "X";
    display: block;
    background: #fff;
    line-height: 20px;
    text-align: center;
    color: #f00;
}

.note-color-palette {
    margin: -20px 0px 0px 25px;
}

/* 编辑器图说 字体变灰色 */
.note-editable .imgdesc {
    font-size: 13px;
    color: #909090;
    margin: 2px 0px 2px 0px;
    text-align: left;
}

/* 编辑器里的img最大宽度不可以超过父元素 */
.note-editable img {
    max-width: 100%;
}

/* edit plus end */
```

```
colors: [
    ['#000', '#2f2f2f', '#2d2d2d', '#909090', '#fff','#f00']
],
```


```
input#title {
  font-family: -webkit-pictograph;
}

this.insertNode = function ($editable, node) {
    beforeCommand($editable);
    var rng = this.createRange($editable);
    console.dir(rng.ec.parentElement)
    //rng.insertNode(node);
    range.createFromNode(node).collapse().select();
    afterCommand($editable);
};
```

```
http://127.0.0.1:5001/lottery/thailand/come_on_join/

http://127.0.0.1:5001/lottery/thailand/come_on_share/1/

http://127.0.0.1:5001/lottery/thailand/come_on_description/

http://127.0.0.1:5001/lottery/thailand/come_on_index/

http://127.0.0.1:5001/lottery/thailand/come_on_share/2976064377/
```

```
api
wx6a0490655d008b70
70369747a6d0cbec973c86a47116ed7e
```
