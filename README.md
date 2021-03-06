# Link-Me-Up

Any technical information which I come across everyday, will be logged here.

- Android
  - [Android Resources](https://github.com/Naveentp/Link-Me-Up/blob/master/android/android_resources.md)
  - [Terminal commands[ADB, Git, Emulator]](https://github.com/Naveentp/Link-Me-Up/blob/master/android/terminal_commands.md)
  - [Online Tools](https://github.com/Naveentp/Link-Me-Up/blob/master/android/online_tools.md)
  - [Libraries/Opensource](https://github.com/Naveentp/Link-Me-Up/blob/master/android/libraries.md)
  - [Kotlin Extensions](https://github.com/Naveentp/Link-Me-Up/blob/master/android/kotlin_extensions.md)

- Flutter
	- [Flutter Resources](https://github.com/Naveentp/Link-Me-Up/blob/master/flutter/flutter_resources.md)

- iOS
  - [Basics](https://github.com/Naveentp/Link-Me-Up/blob/master/iOS/basics.md)
  - [iOS Resources](https://github.com/Naveentp/Link-Me-Up/blob/master/iOS/ios_resources.md)
  
	
### Be Productive
	
+ **Know the power of [`.gitignore`](https://stackoverflow.com/a/17803964/5629056) and push only what is needed. [`git rm --cached <file>`](https://stackoverflow.com/a/1274447/5629056) to your rescue if you want to remove already tracked files**
---
+ **Use `alias` and make terminal work for you. Few of [nisrulz adb aliases](https://gist.github.com/nisrulz/b0e79f2b3e27f99ca8b5dba9db6281ec)**
---
+ **Lint’s [STOPSHIP](https://medium.com/@naveentp/lints-stopship-can-save-you-from-pushing-your-buggy-code-to-production-4fa0db40d9b1) can save you from pushing your buggy code to production**
---
+ **Be aware of the [online tools](https://medium.com/@naveentp/awesome-list-of-online-tools-for-android-developers-f40af8f46299) which will boost your productivity**
---
+ **Use [LeakCanary](https://github.com/square/leakcanary) to find memory leak in app**
---
+ **Learn [MVP, MVVM, MVI](https://github.com/Naveentp/Link-Me-Up/blob/master/android/architecture.md) architectural patterns**
---
+ **Create build time resource/variables in `build.gradle`**
```groovy
android{
  defaultConfig {
    ...
    //Build variable
    buildConfigField "String", "NEWS_API", '"YOUR_NEWS_API"'

    //Resource variable
    resValue 'string', 'APP_NAME', APP_NAME

    //Manifest Placeholder 
    manifestPlaceholders = [crashlyticsApiKey: "514bec26d15bb8f67dc8129f0eda3cabf79fXXXX"]
    ...
  }
}

//Can be accessed as
BuildConfig.NEWS_API

getString(R.string.APP_NAME);

<meta-data
       android:name="io.fabric.Api∏Key"
       android:value="${crashlyticsApiKey}" />
``` 

---
+ **Make use of IntelliJ's Live templates [this](https://github.com/keyboardsurfer/idea-live-templates), [this](https://www.bignerdranch.com/blog/android-studio-live-templates/)**
---
+ **Stay updated and Learn from [youtube programming channels](https://www.lvguowei.me/post/ultimate-list-of-youtube-programming-channels/)** 
---
+ **[Android Gradle DSL ref](http://google.github.io/android-gradle-dsl/) - Be productive by using gradle scripts of building and delevering your app**
---
+ **Take [interviews](https://github.com/kdn251/interviews), test and upgrade your skills time to time**
---
+ **[Recommended programming books](https://github.com/Javagroup123/group/wiki/Recommended-Books)**
---
+ **Kotlin [standard functions](https://github.com/JetBrains/kotlin/blob/master/libraries/stdlib/src/kotlin/util/Standard.kt)(let, apply, with, also, run), [When to use Kotlin's standard functions](https://blog.danlew.net/2019/02/12/when-to-use-kotlins-stdlib-functions/) and [when to use what](https://medium.com/@elye.project/mastering-kotlin-standard-functions-run-with-let-also-and-apply-9cd334b0ef84)?**  

<h1 align="center">
  <img src="https://cdn-images-1.medium.com/max/800/1*pLNnrvgvmG6Mdi0Yw3mdPQ.png">
  <br>
  <br>
</h1>

+ **You can now debug `build.gradle` file using IntelliJ IDE [[Ref link](https://twitter.com/gradle/status/1025066195848810496)]**
---
+ **Learn everything about `ConstraintLayout` [here](https://constraintlayout.com/). This has some cool tips and tricks as well.**
---
+ **Run single kotlin class with main function in android studio**
```kotlin
class Sample {
    companion object {
        @JvmStatic
        fun main(args: Array<String>) {
            print("Hello World!")
        }
    }
}
```
---
+ **Retrofit**
    + [Send JSON Requests and Receive XML Responses (or vice versa)](https://stackoverflow.com/a/46619199/5629056)
    + [Customize Network Timeouts](https://futurestud.io/tutorials/retrofit-2-customize-network-timeouts)
---
