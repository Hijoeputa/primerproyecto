# primerproyecto
tarea de mi primer proyecto en android

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="mx.unam.primerproyecto.MainActivity">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/imageView"
        android:src="@drawable/marciano"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/titulo_app"
        android:id="@+id/textView"
        android:layout_marginTop="27dp"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:textSize="@dimen/abc_text_size_title_material" />
</RelativeLayout>


idiomas

<resources>
    <string name="app_name"></string>
    <string name="titulo_app">Bienvenido</string>
</resources>

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name"></string>
    <string name="titulo_app">Welcome</string>
</resources>

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name"></string>
    <string name="titulo_app">Willkommen</string>
</resources>

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name"></string>
    <string name="titulo_app">Bievenue</string>
</resources>
