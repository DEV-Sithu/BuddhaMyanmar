# BuddhaMyanmar

//build.gradle တွင်
implementation "io.noties.markwon:core:4.6.2"

// Adapter တွင်
Markwon.create(context).setMarkdown(holder.tvMessage, message.content)

```
bg_bot_bubble.xml
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle">
    <corners android:topLeftRadius="4dp" android:topRightRadius="16dp" android:bottomLeftRadius="16dp" android:bottomRightRadius="16dp"/>
    <solid android:color="@color/white"/>
    <stroke android:width="1dp" android:color="@color/gray_200"/>
</shape>
```

```
<!-- Right-aligned user message -->
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:orientation="vertical"
    android:layout_marginVertical="8dp"
    android:paddingEnd="16dp">

    <TextView
        android:id="@+id/tvUserMessage"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:maxWidth="80%"
        android:layout_gravity="end"
        android:padding="12dp"
        android:textColor="@color/white"
        android:background="@drawable/bg_user_bubble"
        android:textSize="16sp"/>

</LinearLayout>
```
