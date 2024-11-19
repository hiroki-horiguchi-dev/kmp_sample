This is a Kotlin Multiplatform project targeting Android, iOS.

* `/composeApp` is for code that will be shared across your Compose Multiplatform applications.
  It contains several subfolders:
  - `commonMain` is for code that’s common for all targets.
  - Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
    For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
    `iosMain` would be the right folder for such calls.

* `/iosApp` contains iOS applications. Even if you’re sharing your UI with Compose Multiplatform, 
  you need this entry point for your iOS app. This is also where you should add SwiftUI code for your project.


Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)…

# 目的
- [Create your own application﻿](https://www.jetbrains.com/help/kotlin-multiplatform-dev/compose-multiplatform-new-project.html?_gl=1%2A54mcrn%2A_gcl_au%2AMTUwOTU3NzIwNi4xNzI4NTIwNjc2%2A_ga%2AMTc4NjIzNjkwMi4xNjkzOTA1NDE5%2A_ga_9J976DJZ68%2AMTczMTkyMzA2OS42NS4xLjE3MzE5MjMxODAuMzguMC4w)
を Intelli J Fleet を使ってやってみる
  
# 感想
- まだまだよくわかってないので、サンプルプロジェクトを落として読み込んでいく
- [Alkaa 3.0 - マルチプラットフォーム](https://github.com/igorescodro/alkaa) を参考に API 通信、DB を用いた永続化、Tarbin を使った遷移、Koin を使った DI について学ぶ
- Fleet は VSCode と比較して、早いとは感じなかった
- vim をまだ有効にできてなくて色々といじりづらいので入れられる方法を調べる
