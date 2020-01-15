# UIButton
自定义Button 省去频繁创建shape文件

## UIButton
- 无需再写shape
- 支持指定圆角大小和方向
- 支持指定文字颜色、边框颜色、边框大小、背景颜色以及点击状态
- 支持背景渐变以及渐变方向
- 支持设置点击状态

### 展示
<img src="https://github.com/ltym2016/UIButton/blob/master/image/WX20200115-145353%402x.png" width="350"/>

### 使用方式
```
<com.qianfanyun.uilib.widget.button.QFUIButton
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="40dp"
        android:layout_margin="10dp"
        android:paddingLeft="20dp"
        android:paddingRight="20dp"
        android:background="@color/colorPrimary"
        android:text="边框大小和颜色"
        android:textColor="@android:color/holo_red_dark"
        app:ui_solidColor="@android:color/holo_orange_light"
        app:ui_cornerRadius="8dp"
        app:ui_strokeColor="@color/colorPrimary"
        app:ui_strokeWidth="4dp"
        app:ui_activeEnable="true"
        app:ui_pressedColor="#e5e5e5"/>
```

### 属性说明
| 属性名  | 描述  |
| ------------ | ------------ |
|  ui_shapeMode |  Shape的模式 |
| ui_solidColor  |  填充颜色 |
| ui_strokeColor  |  边框颜色 |
| ui_strokeWidth  |  边框宽度 |
| ui_cornerRadius  |  圆角的大小 |
| ui_pressedColor  |  按下的颜色 |
| ui_cornerPosition  |  圆角的位置 |
| ui_activeEnable  |  是否开启点击效果 |
| ui_startColor  |  渐变起始颜色 |
| ui_endColor  |  渐变终了颜色 |
|ui_centerColor| 渐变中间颜色|
| ui_orientation  |  渐变方向 |
