![cover](https://img10.360buyimg.com/n1/jfs/t5137/97/1685769989/174379/f9198124/59133f09Ne066edff.jpg)

# CSS图标制作
## 边框
```
<style>
.box{
  width: 100px;
  height: 100px;
  border-top: 10px solid red;
  border-right: 10px solid green;
  border-bottom: 10px solid orange;
  border-left: 10px solid pink;
}
</style>
<div class="box"></div>
```

![border](https://github.com/swordrain/css-core-notes/blob/master/screenshot/border.png)

修改大小，显示三角形效果

```
<style>
.box{
  width: 0;
  height: 0;
  border-top: 20px solid red;
  border-right: 20px solid green;
  border-bottom: 20px solid orange;
  border-left: 20px solid pink;
}
</style>
<div class="box"></div>
```

![triangle](https://github.com/swordrain/css-core-notes/blob/master/screenshot/triangle.png)

选择性将边框设成透明，并调整大小可以生成想要的三角形