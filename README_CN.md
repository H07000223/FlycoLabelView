#FlycoLabelView

一个简单的Android标签控件.

##Demo
<img src="https://github.com/H07000223/FlycoLabelView/blob/master/preview.png" width="640">

##Gradle

```groovy
dependencies{
    compile 'com.flyco.labelview:FlycoLabelView_Lib:1.0.2@aar'
}
```

##Attributes

|name|format|description|
|:---:|:---:|:---:|
| lv_text | string | 设置文字内容 
| lv_text_color | color | 设置文字颜色,默认#ffffff
| lv_text_size | dimension | 设置文字大小,默认11sp
| lv_text_bold | boolean | 设置文字是否支持加粗,默认true
| lv_text_all_caps | boolean | 设置文字是否支持全部大写,默认true
| lv_background_color | color | 设置背景颜色,默认"#FF4081"
| lv_min_size | dimension | 设置LabelView所在矩形最小宽高,默认mFillTriangle?35dp:50dp
| lv_padding | dimension | 设置文字上下padding,默认3.5dp,mFillTriangle为true时无效
| lv_gravity | enum | 设置LabelView方向,支持左上或右上或左下或右下,默认左上
| lv_fill_triangle | boolean | 设置是否填充三角区域,默认false

