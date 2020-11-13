# ProgressFloatingActionButton

# Requirements
The library requires Android **API Level 14+**.

# Screenshots
![Main screen](/screenshots/pfab.gif)

# Usage
Add it in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Add a dependency to your `build.gradle`:
```
dependencies {
    compile 'com.github.pejman-74:ProgressFloatingActionButton:1.0'
}
```

Add the `register.progressfloatingactionbutton.ProgressFloatingActionButton` to your layout XML file.
```XML
  <register.progressfloatingactionbutton.ProgressFloatingActionButton
        android:id="@+id/pfab"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:backgroundTint="@android:color/holo_blue_light"
        app:elevation="5dp"
        app:fabCustomSize="70dp"
        app:maxImageSize="30dp"
        app:pfab_showEditModePreview="true"
        app:pfab_arcProportion="0.5"
        app:pfab_startAngel="180"
        app:pfab_animationDuration="2000"
        app:pfab_color="@color/white"
        app:pfab_margin="2dp"
        app:pfab_width="2dp"
        app:srcCompat="@drawable/arrow"
        app:tint="@android:color/white" />
```

