# FontAwesomeUtils

<H3><B>How To Use?</B></H3>
<ol>
<li>Add the fontawesome-webfont.ttf file into your assets directory</li>
<li>Add the font_awesome.xml file to your res folder</li>
<li>Add the two classes ButtonAwesome.java and TextAwesome.java to your package path</li>
</ol>

<H4><B>Using XML</B></H4>
```xml
<com.FontAwesomeUtils.TextAwesome
    android:id="@+id/tvThumb"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="@string/fa_thumbs_up"
    android:textSize="30sp" />

<com.FontAwesomeUtils.ButtonAwesome
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:text="@string/fa_check" >
```

<H4><B>Using Programatically</B></H4>
```java
TextAwesome tvFacebook = new TextAwesome(this);
tvFacebook.setText(this.getResources().getString(R.string.fa_facebook_square));
tvFacebook.setTextSize(TypedValue.COMPLEX_UNIT_SP,50);
layoutMain.addView(tvFacebook, new LayoutParams(LayoutParams.WRAP_CONTENT, LayoutParams.WRAP_CONTENT));
```
