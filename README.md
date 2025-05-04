# BuddhaMyanmar

// build.gradle တွင်
implementation "io.noties.markwon:core:4.6.2"

// Adapter တွင်
Markwon.create(context).setMarkdown(holder.tvMessage, message.content)

~~~
bg_bot_bubble.xml
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle">
    <corners android:topLeftRadius="4dp" android:topRightRadius="16dp" android:bottomLeftRadius="16dp" android:bottomRightRadius="16dp"/>
    <solid android:color="@color/white"/>
    <stroke android:width="1dp" android:color="@color/gray_200"/>
</shape>
~~~
