
```java
taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ flutter doctor
Doctor summary (to see all details, run flutter doctor -v):
[✓] Flutter (Channel beta, 2.10.0-0.3.pre, on Linux Mint 20.2 5.4.0-96-generic, locale en_US.UTF-8)
[✓] Android toolchain - develop for Android devices (Android SDK version 31.0.0)
[✓] Chrome - develop for the web
[✓] Android Studio (version 2020.3)
[✓] VS Code (version 1.63.2)
[✓] Connected device (1 available)
[✓] HTTP Host Availability

• No issues found!
taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ 




```
2.  sudo apt-get install clang cmake ninja-build pkg-config libgtk-3-dev
3. flutter config --enable-linux-desktop
```java


taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ flutter config --enable-linux-desktop
Setting "enable-linux-desktop" value to "true".

You may need to restart any open editors for them to read new settings.
taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ sudo apt-get install clang cmake ninja-build pkg-config libgtk-3-dev
```


## flutter upgrade

```js

taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ flutter upgrade
Flutter is already up to date on channel beta
Flutter 2.10.0-0.3.pre • channel beta • https://github.com/flutter/flutter.git
Framework • revision fdd0af78bb (31 hours ago) • 2022-01-25 22:01:33 -0600
Engine • revision 5ac30ef0c7
Tools • Dart 2.16.0 (build 2.16.0-134.5.beta) • DevTools 2.9.2
taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ 

```
```java

taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ flutter doctor
Doctor summary (to see all details, run flutter doctor -v):
[✓] Flutter (Channel beta, 2.10.0-0.3.pre, on Linux Mint 20.2 5.4.0-96-generic, locale en_US.UTF-8)
[✓] Android toolchain - develop for Android devices (Android SDK version 31.0.0)
[✓] Chrome - develop for the web
[✓] Linux toolchain - develop for Linux desktop
[✓] Android Studio (version 2020.3)
[✓] VS Code (version 1.63.2)
[✓] Connected device (2 available)
[✓] HTTP Host Availability

• No issues found!
taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ flutter devices
2 connected devices:

Linux (desktop) • linux  • linux-x64      • Linux Mint 20.2 5.4.0-96-generic
Chrome (web)    • chrome • web-javascript • Google Chrome 97.0.4692.99
taxi@taxi-HP-ProBook-4540s:~/Programs_2022$ 
```
4. flutter doctor
4. flutter devices




flutter desktop application support is beta.
for platform specific built we will need visual stuiod 2022 for windows. [same may be true for other platforms]


electron have some drawbacks too.[https://youtu.be/3yqDxhR2XxE]
2. larger app size.
3. larger resouce usage. [probably not true as of 2022]


