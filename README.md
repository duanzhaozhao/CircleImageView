# CircleImageView
里面有一个三方现成的CircleImageView  还有一个自己定义的MyView 都可以用
dependencies {
    ...
    compile 'de.hdodenhof:circleimageview:2.1.0'
}

<de.hdodenhof.circleimageview.CircleImageView
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:id="@+id/profile_image"
    android:layout_width="96dp"
    android:layout_height="96dp"
    android:src="@drawable/profile"
    app:civ_border_width="2dp"
    app:civ_border_color="#FF000000"/>
