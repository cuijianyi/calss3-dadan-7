<?xml version="1.0" encoding="UTF-8"?>

-<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent" android:layout_height="match_parent" android:orientation="vertical" tools:context=".MainActivity">

<Button android:layout_width="match_parent" android:layout_height="wrap_content" android:text="拍摄" android:id="@+id/btn_take_photo"/>

<Button android:layout_width="match_parent" android:layout_height="wrap_content" android:text="从相册中选择" android:id="@+id/btn_choose_from_album"/>

<ImageView android:layout_width="384dp" android:layout_height="417dp" android:id="@+id/img_photo" android:layout_gravity="center_horizontal"/>

</LinearLayout>
