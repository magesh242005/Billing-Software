Counter - build the APK
1. Install Node.js and Android Studio.
2. In this folder run:  npm install
3. Then run:            npx cap sync android
4. Then run:            npx cap open android
5. In Android Studio wait for Gradle sync to finish.
6. Menu: Build > Build Bundle(s) / APK(s) > Build APK(s)
7. Click "locate" in the popup. File: app/build/outputs/apk/debug/app-debug.apk
8. Send the APK to your phone and install it (allow "install unknown apps").
