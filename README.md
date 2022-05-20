# tt_app_log

## Interesting places:

- X.5kW!LIZ
- X.0cN!LIZ
- \*.ttnet.\*!\*
- DefaultTTNetImpl.doPost(url, encryptedData)
- com.bytedance.frameworks.baselib.network.dispatcher.NetThreadPoolManager!executorApiService

## Useful code:

- Injection
``` javascript
    console.log(Java.use("android.util.Log").getStackTraceString(Java.use("java.lang.Exception").$new()))
```

- ADB
```
    adb shell
    adb pull remotePath
```

- frida js

```
    frida-trace -U -n appName -j something.*.class!method
```

## Softwares

- jadx-gui
- LDPlayer
- frida
