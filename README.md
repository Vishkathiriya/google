# google


this Error come To Run Time

0 10:36:42.410 20209-20209/com.example.vihmayu.google E/AndroidRuntime: FATAL EXCEPTION: main
    Process: com.example.vihmayu.google, PID: 20209
    java.lang.VerifyError: Verifier rejected class com.google.android.gms.auth.api.signin.GoogleSignInClient due to bad method int com.google.android.gms.auth.api.signin.GoogleSignInClient.zzach() (declaration of 'com.google.android.gms.auth.api.signin.GoogleSignInClient' appears in /data/app/com.example.vihmayu.google-1/base.apk)
        at com.google.android.gms.auth.api.signin.GoogleSignIn.getClient(Unknown Source)
        at com.example.vihmayu.google.MainActivity.onCreate(MainActivity.java:55)
        at android.app.Activity.performCreate(Activity.java:6358)
        at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1108)
        at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2440)
        at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2547)
        at android.app.ActivityThread.access$1100(ActivityThread.java:151)
        at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1398)
        at android.os.Handler.dispatchMessage(Handler.java:102)
        at android.os.Looper.loop(Looper.java:157)
        at android.app.ActivityThread.main(ActivityThread.java:5604)
        at java.lang.reflect.Method.invoke(Native Method)
        at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:774)
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:652)
