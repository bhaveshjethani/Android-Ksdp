# Android-Ksdp
Utility to print logs to files

===Usage===

For ex use @dimen/_10sdp instead of hard coded 10dp and that it.

 <android.support.v7.widget.AppCompatTextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_marginBottom="@dimen/_10sdp"
                            android:layout_marginTop="@dimen/_10sdp"
                            android:fontFamily="@font/app_font_semi_bold"
                            android:text="@string/login"
                            android:textColor="@color/colorWhite"
                            android:textSize="@dimen/_32ssp" />


===Implementation===

Include following in your project's build.gradle file under both repositories section
```
maven { url  "https://dl.bintray.com/k9428/ksdp" }
```

Include following in your app's build.gradle file
```
implementation 'lib.ksdp:ksdp:1.0.1' 
```

That's it!
