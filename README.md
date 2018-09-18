
# XEditText
-清除所有文本内容只需点击右侧。清晰的可绘制是可定制的。
-完全适合密码输入场景。切换绘制也是可定制的。
-您可以自定义**分隔符**或**模式**以分隔文本内容。但是，复制、剪切和粘贴的文本内容将不再受您设置的**分隔符**或**模式**的影响。
-能够禁用表情符号输入。

## Usage
```xml
  <com.zhoujian.dev.XEditText
            android:id="@+id/show_separator_edit_text"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="normal String separate to pattern"/>

        <com.zhoujian.dev.XEditText
            android:id="@+id/enable_emoji_edit_text"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="20dp"
            android:hint="enable emoji inputting"
            app:x_disableEmoji="false"/>

        <com.zhoujian.dev.XEditText
            android:id="@+id/disable_emoji_edit_text"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="disable emoji inputting"
            app:x_disableEmoji="true"/>
