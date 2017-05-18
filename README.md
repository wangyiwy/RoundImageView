# RoundImageView
圆角/圆形的ImageView 继承的ImageView，所以使用就和普通ImageView一样，可以在xml中指定一些属性
```
    <com.wangyi.roundimageview.RoundImageView
        android:id="@+id/image"
        android:layout_width="150dp"
        android:layout_height="150dp"
        android:layout_alignParentRight="true"
        android:scaleType="centerCrop"
        android:src="@drawable/avatar"
        app:cover_color="@android:color/white"
        app:radius="8dp"
        app:shape="fillet" />
```
**三个属性说明：**
shape：circle 表示圆形 fillet表示圆角；
cover_color:表示遮罩的颜色，不设置就是白色；
radius：圆角的大小。

![](/image/sample.png)
