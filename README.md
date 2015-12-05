# Endless Tunnel (Work-in-progress)

endlesstunnel-melvincabatuan created by Classroom for GitHub

## Issue

https://github.com/googlesamples/android-ndk/issues/102

```shell
12-06 04:04:17.963 10606-10606/ph.edu.dlsu.endlesstunnel E/AndroidRuntime: FATAL EXCEPTION: main
                                                                           Process: ph.edu.dlsu.endlesstunnel, PID: 10606
                                                                           java.lang.RuntimeException: Unable to start activity ComponentInfo{ph.edu.dlsu.endlesstunnel/android.app.NativeActivity}: java.lang.IllegalArgumentException: Unable to load native library: /data/app-lib/ph.edu.dlsu.endlesstunnel-1/libgame.so
                                                                               at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2377)
                                                                               at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2429)
                                                                               at android.app.ActivityThread.access$800(ActivityThread.java:151)
                                                                               at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1342)
                                                                               at android.os.Handler.dispatchMessage(Handler.java:110)
                                                                               at android.os.Looper.loop(Looper.java:193)
                                                                               at android.app.ActivityThread.main(ActivityThread.java:5333)
                                                                               at java.lang.reflect.Method.invokeNative(Native Method)
                                                                               at java.lang.reflect.Method.invoke(Method.java:515)
                                                                               at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:828)
                                                                               at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:644)
                                                                               at dalvik.system.NativeStart.main(Native Method)
                                                                            Caused by: java.lang.IllegalArgumentException: Unable to load native library: /data/app-lib/ph.edu.dlsu.endlesstunnel-1/libgame.so
                                                                               at android.app.NativeActivity.onCreate(NativeActivity.java:183)
                                                                               at android.app.Activity.performCreate(Activity.java:5343)
                                                                               at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1088)
                                                                               at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2331)
                                                                               at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2429) 
                                                                               at android.app.ActivityThread.access$800(ActivityThread.java:151) 
                                                                               at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1342) 
                                                                               at android.os.Handler.dispatchMessage(Handler.java:110) 
                                                                               at android.os.Looper.loop(Looper.java:193) 
                                                                               at android.app.ActivityThread.main(ActivityThread.java:5333) 
                                                                               at java.lang.reflect.Method.invokeNative(Native Method) 
                                                                               at java.lang.reflect.Method.invoke(Method.java:515) 
                                                                               at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:828) 
                                                                               at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:644) 
                                                                               at dalvik.system.NativeStart.main(Native Method) 

```
