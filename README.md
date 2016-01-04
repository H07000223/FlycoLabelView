#FlycoLabelView

####[中文版](https://github.com/H07000223/FlycoLabelView/blob/master/README_CN.md)
A Simple Android LabelView.

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


##Examples

###Triangle View (inside CardView)

```
<android.support.v7.widget.CardView
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:card_view="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_margin="8dp"
    card_view:cardCornerRadius="4dp">
    
    <com.flyco.labelview.LabelView
        xmlns:lv="http://schemas.android.com/apk/res-auto"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="end"
        lv:lv_fill_triangle="true"
        lv:lv_gravity="TOP_RIGHT"
        lv:lv_text="15%"
        lv:lv_text_size="12sp"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:padding="16dp">

        <TextView
            android:id="@id/name"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="@dimen/single_spacing"
            tools:text="Promotion #1"/>

        <TextView
            android:id="@id/description"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="@dimen/single_spacing"/>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="@dimen/single_spacing"/>

    </LinearLayout

</android.support.v7.widget.CardView>

```

###Line View (inside CardView)
```
<android.support.v7.widget.CardView
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:card_view="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_margin="8dp"
    card_view:cardCornerRadius="4dp">
    
    <com.flyco.labelview.LabelView
        xmlns:lv="http://schemas.android.com/apk/res-auto"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="end"
        lv:lv_gravity="TOP_RIGHT"
        lv:lv_text="15%"
        lv:lv_text_size="12sp"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:padding="16dp">

        <TextView
            android:id="@+id/name"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="8dp"
            tools:text="Name 1"/>

        <TextView
            android:id="@+id/description"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="8dp"
            tools:text="Description 1"/>

        <TextView
            android:id="@+id/date"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="8dp"
            tools:text="Date 1"/>

    </LinearLayout

</android.support.v7.widget.CardView>

```
