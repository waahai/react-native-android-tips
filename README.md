# react-native-android-tips

## Sock Proxy
Default Sock port is 1080
For Linux/Mac
``` sh
export _JAVA_OPTIONS="-DsocksProxyHost=<YourProxyHost> -DsocksProxyPort=<YourProxyPort>"
```
For Windows
``` sh
set _JAVA_OPTIONS="-DsocksProxyHost=<YourProxyHost> -DsocksProxyPort=<YourProxyPort>"
```
