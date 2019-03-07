
# Android is Easy

### Użyte aplikacje / biblioteki do osiągnecia celu:
- [ApkStudio](https://github.com/vaibhavpandeyvpz/apkstudio) - zestaw gotowych narzędzi do dekompilacji, edycji,  
kompilacji, podpisania i instalacji zmodyfikowanej aplikacji.

- [jarsigner](https://docs.oracle.com/javase/7/docs/technotes/tools/windows/jarsigner.html) - podpisanie aplikacji

---
- [Uber Apk Signer](https://github.com/patrickfav/uber-apk-signer) - kolejne narzedzie do podpisywania, ale z ulepszonymi możliościami:
    - zipalign, (re)signing and verifying of multiple APKs in one step
    - verify signature (with hash check) and zipalign of multiple APKs in one step
    - built-in zipalign & debug keystore for convenient usage
    - supports v1 and v2 android apk singing scheme
    - support for multiple signatures for one APK
    - crypto/signing code relied upon official implementation
    
---
- [apktool](https://ibotpeaches.github.io/Apktool/) - kombajn do kompletnej dekompilacji apk:
    - A tool for reverse engineering 3rd party, closed, binary Android apps. 
    - It can decode resources to nearly original form and rebuild them after making some modifications.
    - It also makes working with an app easier because of the project like file structure and automation of some repetitive tasks like building apk, etc.
- [javac](https://docs.oracle.com/javase/7/docs/technotes/tools/windows/javac.html) - kompilator plikow java do bytecode

---
- [dx](https://mvnrepository.com/artifact/com.google.android.tools/dx) - konwenter plików z bytecodem javy do dex file. Można go znaleźć w każdym katalogu z build-toolsami:

    - <ANDROID-SDK-ROOT>/build-tools/28.0.0/
    - konkretne [wytłumaczenie StackOverflow FTW](https://stackoverflow.com/questions/8487268/android-dx-tool)
- [smalidea](https://github.com/JesusFreke/smali/wiki/smalidea) - plugin do android studio supportujący pliki smali.
- ddms - na macu działa z javą wersja < 152

---
### Instalacja
- Windows i linux bez problemu bo jest gotowy release, pobierasz, odpalasz, działa.

---
+++
- ##### mac: 
- pobierasz środowisko [QT - wersja opensource](https://www.qt.io/download)
- instalujesz|
- modlisz się zeby się uruchomiło ( i tak sie nie uruchomi za pierwszym razem, trzeba doinstalowywać biblioteki o jakie prosi)|
- jak już uruchomisz QT - idziesz po piwo|
- pobierasz repo ApkStudio|
- odpalsz plik ApkStudio.pro w QTCreator|
- Build|
- Wypijasz piwo, bo masz dużo czasu.|
    
    
