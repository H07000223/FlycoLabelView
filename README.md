#FlycoLabelView

####[中文版](https://github.com/H07000223/FlycoLabelView/blob/master/README_CN.md)
A Simple Android LabelView.

##Demo
<img src="https://github.com/H07000223/FlycoLabelView/blob/master/preview.png" width="640">

##Gradle

```groovy
dependencies{
    compile 'com.flyco.labelview:FlycoLabelView_Lib:1.0.0@aar'
}
```

##Attributes

|name|format|description|
|:---:|:---:|:---:|
| lv_text | string | set text 
| lv_text_color | color | set text color default #ffffff
| lv_text_size | dimension | set text size default 11sp
| lv_text_bold | boolean | set text bold default true
| lv_text_all_caps | boolean | set text all caps default true
| lv_background_color | color | set LabelView background color default #FF4081
| lv_min_size | dimension | min size of rect of LabelView default mFillTriangle?35dp:50dp
| lv_padding | dimension |set paddingTop and paddingBottom of text default 3.5dp, invalid when mFillTriangle true
| lv_gravity | enum |set LabelView gravity TOP_LEFT or TOP_RIGHT or BOTTOM_LEFT or BOTTOM_RIGHT default TOP_LEFT
| lv_fill_triangle | boolean | set fill triangle area, default false

