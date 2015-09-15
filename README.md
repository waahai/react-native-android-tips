# react-native-android-tips

## Sock Proxy

For Linux/Mac
``` sh
export _JAVA_OPTIONS="-DsocksProxyHost=<YourProxyHost> -DsocksProxyPort=<YourProxyPort>"
```
For Windows
``` sh
set _JAVA_OPTIONS="-DsocksProxyHost=<YourProxyHost> -DsocksProxyPort=<YourProxyPort>"
```
>Default Sock port is 1080
<You will see something like this at the start:
>Picked up _JAVA_OPTIONS: -DsocksProxyHost=<YourProxyHost>
