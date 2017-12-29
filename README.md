<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.android.helloandroid.MainActivity">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/obrazok" />

    <TextView
        android:id="@+id/Name"
        android:layout_centerHorizontal="true"
        android:layout_width="wrap_content"
        android:fontFamily="casual"
        android:padding="10dp"
        android:layout_height="wrap_content"
        android:text="Udacity"  />

    <TextView
        android:layout_centerHorizontal="true"
        android:id="@+id/Adresa"
        android:padding="5dp"
        android:fontFamily="casual"
        android:layout_below="@id/Name"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="2465 Latham St" />

    <TextView
        android:layout_centerHorizontal="true"
        android:id="@+id/Ulica"
        android:padding="5dp"
        android:fontFamily="casual"
        android:layout_below="@id/Adresa"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Mountain View, CA 94043" />
    <TextView
        android:layout_centerHorizontal="true"
        android:id="@+id/Cislo"
        android:padding="5dp"
        android:fontFamily="casual"
        android:layout_below="@id/Ulica"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="650-555-5555" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Cislo"
        android:text="www.Udacity.com"
        android:fontFamily="casual"
        android:layout_centerHorizontal="true"/>



</RelativeLayout>
