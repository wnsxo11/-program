# -program
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/activity_main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    tools:context="com.example.a403.myapplication.MainActivity"
    android:weightSum="1">

    <TextView
        android:text="TextView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/textView5" />

    <TextView
        android:text="어른(15000원)"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/textView8" />

    <TextView
        android:text="청소년(12000원)"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/textView7" />

    <TextView
        android:text="어린이(8000원)"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/textView6" />

    <RadioButton
        android:text="기본할인(5% 할인)"
        android:layout_width="264dp"
        android:layout_height="wrap_content"
        android:id="@+id/radioButton" />

    <RadioButton
        android:text="현금할인(10%할인)"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/radioButton2" />

    <RadioButton
        android:text="MemberShip있음(20% 할인)"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/radioButton3" />

    <Button
        android:text="예약완료"
        android:layout_width="137dp"
        android:layout_height="wrap_content"
        android:id="@+id/button3" />

    <Button
        android:text="시간예약GO"
        android:layout_width="126dp"
        android:layout_height="wrap_content"
        android:id="@+id/button5" />

    <ImageView
        android:layout_width="159dp"
        android:layout_height="wrap_content"
        app:srcCompat="@mipmap/ic_launcher"
        android:id="@+id/imageView"
        android:layout_weight="1.78" />

    <TextView
        android:text="총 명수:"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/textView9" />

    <TextView
        android:text="할인금액:"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/textView10" />

    <TextView
        android:text="TextView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/textView11" />

    <Button
        android:text="시간예약GO"
        android:layout_width="113dp"
        android:layout_height="0dp"
        android:id="@+id/button4" />

    <Button
        android:text="Button"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:id="@+id/button2" />

</LinearLayout>
