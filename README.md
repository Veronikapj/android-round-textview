# android-round-textview
Sometime, to do round textview is hard.

````
allprojects {
	repositories {
	...
	maven { url 'https://jitpack.io' }
	}
}
  
dependencies {
	compile 'com.github.apg-mobile:android-round-textview:v1.0.0'
}
````


### Available components

1. RoundTextView
2. RoundLayout
3. BadgeView

### Example Preview
![alt text](https://github.com/apg-mobile/android-round-textview/blob/master/preview.png)

### Example Usage
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="wrap_content"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp"
    tools:context="com.apg.mobile.roundtextviewsample.MainActivity">

    <com.apg.mobile.roundtextview.RoundTextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:paddingBottom="8dp"
        android:paddingLeft="16dp"
        android:paddingRight="16dp"
        android:paddingTop="8dp"
        android:text="Round me up !"
        android:textColor="#fff"
        app:allCorner="16dp"
        app:bgColor="#456432" />

    <com.apg.mobile.roundtextview.RoundLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:paddingBottom="8dp"
        android:paddingLeft="16dp"
        android:paddingRight="16dp"
        android:paddingTop="8dp"
        app:allCorner="16dp"
        app:bgColor="#EA3238">

        <RelativeLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Round Any View Group"
                android:textColor="#fff" />

        </RelativeLayout>

    </com.apg.mobile.roundtextview.RoundLayout>

    <com.apg.mobile.roundtextview.BadgeView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        app:mainAllCorner="30dp"
        app:mainText="Wait for transfer"
        app:subAllCorner="30dp" />

    <com.apg.mobile.roundtextview.BadgeView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        app:mainAllCorner="30dp"
        app:mainBgColor="#598dd0"
        app:mainText="Ask for address"
        app:subAllCorner="30dp"
        app:subText="+ 2" />

    <com.apg.mobile.roundtextview.BadgeView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        app:mainAllCorner="30dp"
        app:mainBgColor="#6407c1"
        app:mainText="A very very long long tag g g g g"
        app:subAllCorner="30dp" />


    <com.apg.mobile.roundtextview.BadgeView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        app:mainAllCorner="30dp"
        app:mainBgColor="#bab8bc"
        app:mainText="A very very long long tag g g g g"
        app:subAllCorner="30dp"
        app:subText="+ 2" />

</LinearLayout>
```
