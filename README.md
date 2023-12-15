# <img src="https://github.com/terrakok/kmm-awesome/raw/master/img/icon.svg" width="30"/> Awesome Kotlin Multiplatform

<img src="https://github.com/terrakok/kmm-awesome/raw/master/img/multiplatform-sharing.svg" align="center" width="400"/>

[![Pull request](https://img.shields.io/badge/PRs-welcome-success)](https://github.com/terrakok/kmm-awesome/pulls)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Repo stars](https://img.shields.io/github/stars/terrakok/kmm-awesome)](https://github.com/terrakok/kmm-awesome)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlin/kotlin-maven-plugin.svg)](https://central.sonatype.com/search?q=g%3Aorg.jetbrains.kotlin)

Kotlin Multiplatform technology simplifies the development of cross-platform projects.
It reduces time spent writing and maintaining the same code for different platforms while retaining the flexibility and benefits of native programming.

**This list contains libraries which support iOS and Android targets in first place.**

## Resources
🖼 [Website](https://www.jetbrains.com/kotlin-multiplatform/)
🚀 [KMP Web Wizard](https://kmp.jetbrains.com/)
🍏 [Compose Multiplatform Wizard](https://terrakok.github.io/Compose-Multiplatform-Wizard/)
📋 [Documentation](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)
📜 [Blog](https://blog.jetbrains.com/kotlin/category/multiplatform/)
📺 [YouTube](https://www.youtube.com/playlist?list=PLlFc5cFwUnmy_oVc9YQzjasSNoAk4hk_C)
🤩 [Samples](https://kotlinlang.org/docs/kmm-samples.html)
🗄 [Jetpack Compose Components](https://m3.material.io/components)
🗄 [Compose Material 3 Gallery](https://terrakok.github.io/compose-material-3-gallery/)
📚 [Kotlin Multiplatform by Tutorials](https://www.kodeco.com/books/kotlin-multiplatform-by-tutorials)
📚 [Simplifying Application Development with Kotlin Multiplatform Mobile](https://www.amazon.com/Simplifying-Application-Development-Kotlin-Multiplatform/dp/1801812586)

## Contents
<table>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#tooling">🛠 Tooling</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-log">📋 Log</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-network">🌎 Network</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-storage">📦 Storage</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-device">📱 Device</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-dependency-injection">💉 Dependency Injection</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-architecture">🏗 Architecture</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-analytics">🔍 Analytics</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-test">🩺 Test</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-crypto">🔑 Crypto</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-file">📁 File</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-language-extensions">🚀 Language extensions</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-serializer">🗃 Serializer</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-date-time">⏰ Date-Time</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-asynchronous">➿ Asynchronous</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-compose-ui">🍎 Compose UI</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-graphics">🎨 Graphics</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-service-sdk">🧩 Service SDK</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-arithmetic">🧮 Arithmetic</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-resources">🛢 Resources</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-utils">🔧 Utils</a></td>
  </tr>
</table>

### 🛠 Tooling

[Kotlin Multiplatform Mobile plugin](https://plugins.jetbrains.com/plugin/14936-kotlin-multiplatform-mobile) for Android Studio
> The Kotlin Multiplatform Mobile (KMM) plugin helps you develop applications that work on both Android and iOS.

[CocoaPods](https://kotlinlang.org/docs/native-cocoapods.html) integration
> Kotlin/Native provides integration with the CocoaPods dependency manager. You can add dependencies on Pod libraries as well as use a multiplatform project with native targets as a CocoaPods dependency (Kotlin Pod).

[Amper](https://github.com/JetBrains/amper) new experimental way for project configuration
[![GitHub Repo stars](https://img.shields.io/github/stars/JetBrains/amper)](https://github.com/JetBrains/amper)
> Improving developer experience while configuring project setup. Kotlin multiplatform support is out-of-the-box. Project now has experimental status.

[Swift Package](https://github.com/PaGr0m/kotlin-spm-plugin) integration
[![GitHub Repo stars](https://img.shields.io/github/stars/PaGr0m/kotlin-spm-plugin)](https://github.com/PaGr0m/kotlin-spm-plugin)
> This gradle plugin provides two-way interoperability between Kotlin dependencies and Kotlin-based Swift Package Multiplatform.

[Carthage](https://github.com/wireapp/carthage-gradle-plugin) integration
[![GitHub Repo stars](https://img.shields.io/github/stars/wireapp/carthage-gradle-plugin)](https://github.com/wireapp/carthage-gradle-plugin)
> Adds support for integrating Carthage dependencies into a KMM project.

[Libres](https://github.com/Skeptick/libres) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/Skeptick/libres)](https://github.com/Skeptick/libres)
> String/Image resources generation in Kotlin Multiplatform.

[MOKO KSwift](https://github.com/icerockdev/moko-kswift) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-kswift)](https://github.com/icerockdev/moko-kswift)
> KSwift it's gradle plugin for generation Swift-friendly API for Kotlin/Native framework.

[SKIE](https://github.com/touchlab/SKIE) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/SKIE)](https://github.com/touchlab/SKIE)
> A Swift-friendly API Generator for Kotlin Multiplatform.

[CompleteKotlin](https://github.com/LouisCAD/CompleteKotlin) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/LouisCAD/CompleteKotlin)](https://github.com/LouisCAD/CompleteKotlin)
> Gradle Plugin to enable auto-completion and symbol resolution for all Kotlin/Native platforms.

[gradle-buildconfig-plugin](https://github.com/gmazzo/gradle-buildconfig-plugin) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/gmazzo/gradle-buildconfig-plugin)](https://github.com/gmazzo/gradle-buildconfig-plugin)
> A plugin for generating BuildConstants for any kind of Gradle projects: Java, Kotlin, Groovy, etc. Designed for KTS scripts.

[BuildKonfig](https://github.com/yshrsmz/BuildKonfig) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/yshrsmz/BuildKonfig)](https://github.com/yshrsmz/BuildKonfig)
> BuildConfig for Kotlin Multiplatform Project

[Kotlin Native Xcode Support](https://github.com/touchlab/xcode-kotlin)
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/xcode-kotlin)](https://github.com/touchlab/xcode-kotlin)
> Plugin to facilitate debugging iOS applications using Kotlin Native in Xcode. Defines Kotlin files as source code, with basic highlighting. Allows you to set breakpoints and includes llvm support to view data in the debug window. Xcode does not officially support custom language definitions, but they also don't explicitly block them.

[Dokka](https://github.com/Kotlin/dokka) documentation generation tool
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/dokka)](https://github.com/Kotlin/dokka)
> Dokka is a documentation engine for Kotlin, performing the same function as javadoc for Java. Just like Kotlin itself, Dokka fully supports mixed-language Java/Kotlin projects. It understands standard Javadoc comments in Java files and KDoc comments in Kotlin files, and can generate documentation in multiple formats including standard Javadoc, HTML and Markdown.

[KDoctor](https://github.com/Kotlin/kdoctor) command-line tool
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kdoctor)](https://github.com/Kotlin/kdoctor)
> KDoctor is a command-line tool that helps to set up the environment for Kotlin Multiplatform Mobile app development. It ensures that all required components are properly installed and ready for use. If something is missed or not configured Kdoctor highlights the problem and suggests how to fix the problem.

[Swift Klib](https://github.com/ttypic/swift-klib-plugin) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/ttypic/swift-klib-plugin)](https://github.com/ttypic/swift-klib-plugin)
> Gradle Plugin to build Swift code as part of your Kotlin Multiplatform project. With this plugin, you can access Swift-only iOS libraries, such as CryptoKit and experiment with Swift to Kotlin interoperability.

[parcelize-darwin](https://github.com/arkivanov/parcelize-darwin) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/parcelize-darwin)](https://github.com/arkivanov/parcelize-darwin)
> Kotlin/Native compiler plugin that generates Parcelable implementations for Darwin (Apple) targets. Allows writing Parcelable classes for all Darwin targets, similary to the Android's kotlin-parcelize plugin. Can be also used together with the kotlin-parcelize plugin to write Parcelable classes in the commonMain source set.

[AboutLibraries](https://github.com/mikepenz/AboutLibraries) gradle plugin
[![GitHub Repo stars](https://img.shields.io/github/stars/mikepenz/AboutLibraries)](https://github.com/mikepenz/AboutLibraries)
> Collects all dependencies and licenses of gradle projects (Kotlin Multiplatform) and provides an easy to integrate Attribution / Open Source library UI to integrate in Compose / Android targets.

## Libraries

### 📋 Log
[Napier](https://github.com/AAkira/Napier) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/AAkira/Napier)](https://github.com/AAkira/Napier)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.aakira/napier)](https://central.sonatype.com/artifact/io.github.aakira/napier)
> Napier is a logger library for Kotlin Multiplatform. It supports for the Android, Darwin(iOS, macOS, watchOS, tvOS), JVM, JavaScript. Logs written in common module are displayed on logger viewer of each platform.

[Kermit](https://github.com/touchlab/Kermit) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Kermit)](https://github.com/touchlab/Kermit)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/kermit)](https://central.sonatype.com/artifact/co.touchlab/kermit)
> Kermit is a Kotlin Multiplatform logging utility with composable log outputs. The library provides prebuilt loggers for outputting to platform logging tools such as Logcat and NSLog.

[Kodein-Log](https://github.com/Kodein-Framework/Kodein-Log) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-Log)](https://github.com/Kodein-Framework/Kodein-Log)
[![Maven Central](https://img.shields.io/maven-central/v/org.kodein.log/kodein-log)](https://central.sonatype.com/artifact/org.kodein.log/kodein-log)
> Kodein-Log is a lightweight Kotlin/Multiplatform logging library with a simple API, that works on JVM, Android, JavaScript, iOS, as well as for all Kotlin/Native targets.

[Klogger](https://github.com/korlibs/klogger) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/klogger)](https://github.com/korlibs/klogger)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.klogger/klogger)](https://central.sonatype.com/artifact/com.soywiz.korlibs.klogger/klogger)
> Klogger is a logger library for multiplatform Kotlin. This library provides a simple interface to do logging into suitable outputs like javascript’s console, or stdout/stderr.

[Cabret](https://github.com/Foso/Cabret-Log) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/Foso/Cabret-Log)](https://github.com/Foso/Cabret-Log)
[![Maven Central](https://img.shields.io/maven-central/v/de.jensklingenberg.cabret/cabret-compiler-runtime)](https://central.sonatype.com/artifact/de.jensklingenberg.cabret/cabret-compiler-runtime)
> This is an Kotlin Library that enables Annotation-triggered method call logging for Kotlin Multiplatform.

[KmLogging](https://github.com/LighthouseGames/KmLogging) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/LighthouseGames/KmLogging)](https://github.com/LighthouseGames/KmLogging)
[![Maven Central](https://img.shields.io/maven-central/v/org.lighthousegames/logging)](https://central.sonatype.com/artifact/org.lighthousegames/logging)
> Kotlin multiplatform logging. High performance, composable and simple to use.

[Kydra Log](https://github.com/PocketByte/kotlin-kydra-log) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/PocketByte/kotlin-kydra-log)](https://github.com/PocketByte/kotlin-kydra-log)
[![Maven Central](https://img.shields.io/maven-central/v/ru.pocketbyte.kydra/kydra-log)](https://central.sonatype.com/artifact/ru.pocketbyte.kydra/kydra-log)
> Kotlin Multiplatform Library that allows to write logs in common module.

[kmp-xlog](https://github.com/HackWebRTC/kmp-xlog) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/HackWebRTC/kmp-xlog)](https://github.com/HackWebRTC/kmp-xlog)
[![Maven Central](https://img.shields.io/maven-central/v/com.piasy/kmp-xlog)](https://central.sonatype.com/artifact/com.piasy/kmp-xlog)
> KMP wrapper for [tencent mars xlog](https://github.com/Tencent/mars).

### 🌎 Network
[Ktor](https://github.com/ktorio/ktor) - http client
[![GitHub Repo stars](https://img.shields.io/github/stars/ktorio/ktor)](https://github.com/ktorio/ktor)
[![Maven Central](https://img.shields.io/maven-central/v/io.ktor/ktor)](https://central.sonatype.com/artifact/io.ktor)
> Ktor includes a multiplatform asynchronous HTTP client, which allows you to make requests and handle responses, extend its functionality with plugins (formerly known as features), such as authentication, JSON serialization, and so on.

[Ktorfit](https://github.com/Foso/Ktorfit) - Retrofit for Kotlin Multiplatform on KTS
[![GitHub Repo stars](https://img.shields.io/github/stars/Foso/Ktorfit)](https://github.com/Foso/Ktorfit)
[![Maven Central](https://img.shields.io/maven-central/v/de.jensklingenberg.ktorfit/ktorfit-lib)](https://central.sonatype.com/artifact/de.jensklingenberg.ktorfit/ktorfit-lib)
> HTTP client / Kotlin Symbol Processor for Kotlin Multiplatform (Android,Js, Jvm , Native, iOS) using KSP and Ktor clients inspired by Retrofit https://foso.github.io/Ktorfit

[Apollo GraphQL](https://github.com/apollographql/apollo-android) - GraphQL client
[![GitHub Repo stars](https://img.shields.io/github/stars/apollographql/apollo-android)](https://github.com/apollographql/apollo-android)
[![Maven Central](https://img.shields.io/maven-central/v/com.apollographql.apollo3/apollo-runtime)](https://central.sonatype.com/artifact/com.apollographql.apollo3/apollo-runtime)
> A strongly-typed, caching GraphQL client for the JVM, Android, and Kotlin multiplatform.

[kgql](https://github.com/yshrsmz/kgql) - GraphQL Document wrapper generator
[![GitHub Repo stars](https://img.shields.io/github/stars/yshrsmz/kgql)](https://github.com/yshrsmz/kgql)
[![Maven Central](https://img.shields.io/maven-central/v/com.codingfeline.kgql/core)](https://central.sonatype.com/artifact/com.codingfeline.kgql/core)
> GraphQL Document wrapper generator for Kotlin Multiplatform Project. Currently, available for JVM/Android/iOS

[WebRTC KMP](https://github.com/shepeliev/webrtc-kmp) - WebRTC client
[![GitHub Repo stars](https://img.shields.io/github/stars/shepeliev/webrtc-kmp)](https://github.com/shepeliev/webrtc-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/com.shepeliev/webrtc-kmp)](https://central.sonatype.com/artifact/com.shepeliev/webrtc-kmp)
> WebRTC Kotlin Multiplatform SDK

[Krossbow](https://github.com/joffrey-bion/krossbow) - WebSocket client
[![GitHub Repo stars](https://img.shields.io/github/stars/joffrey-bion/krossbow)](https://github.com/joffrey-bion/krossbow)
[![Maven Central](https://img.shields.io/maven-central/v/org.hildan.krossbow/krossbow-stomp-core)](https://central.sonatype.com/artifact/org.hildan.krossbow/krossbow-stomp-core)
> A coroutine-based Kotlin multi-platform WebSocket client and STOMP 1.2 client over web sockets.

[MOKO SocketIo](https://github.com/icerockdev/moko-socket-io) - Socket.IO implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-socket-io)](https://github.com/icerockdev/moko-socket-io)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/socket-io)](https://central.sonatype.com/artifact/dev.icerock.moko/socket-io)
> This is a Kotlin Multiplatform library that provides real-time, event-based communication for iOS and Android.

[rsocket](https://github.com/rsocket/rsocket-kotlin) - RSocket Kotlin multi-platform implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/rsocket/rsocket-kotlin)](https://github.com/rsocket/rsocket-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.rsocket.kotlin/rsocket-core)](https://central.sonatype.com/artifact/io.rsocket.kotlin/rsocket-core)
> RSocket is a binary protocol for use on byte stream transports such as TCP, WebSockets and Aeron.

### 📦 Storage
[Multiplatform-Settings](https://github.com/russhwolf/multiplatform-settings) - Key-Value preferences
[![GitHub Repo stars](https://img.shields.io/github/stars/russhwolf/multiplatform-settings)](https://github.com/russhwolf/multiplatform-settings)
[![Maven Central](https://img.shields.io/maven-central/v/com.russhwolf/multiplatform-settings)](https://central.sonatype.com/artifact/com.russhwolf/multiplatform-settings)
> This is a Kotlin library for Multiplatform apps, so that common code can persist key-value data

[abc-kmm-shared-storage](https://github.com/line/abc-kmm-shared-storage) - Key-Value storage
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-shared-storage)](https://github.com/line/abc-kmm-shared-storage)
[![Maven Central](https://img.shields.io/maven-central/v/com.linecorp.abc/kmm-shared-storage)](https://central.sonatype.com/artifact/com.linecorp.abc/kmm-shared-storage)
> A local storage management library for Kotlin Multiplatform Mobile iOS and Android

[KVault](https://github.com/Liftric/KVault) - secure key-value storage
[![GitHub Repo stars](https://img.shields.io/github/stars/Liftric/KVault)](https://github.com/Liftric/KVault)
[![Maven Central](https://img.shields.io/maven-central/v/com.liftric/kvault)](https://central.sonatype.com/artifact/com.liftric/kvault)
> It acts as an iOS Keychain wrapper and implements encrypted SharedPreferences for Android.

[SQLDelight](https://github.com/cashapp/sqldelight) - SQLite database
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/sqldelight)](https://github.com/cashapp/sqldelight)
[![Maven Central](https://img.shields.io/maven-central/v/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin)](https://central.sonatype.com/artifact/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin)
> SQLDelight generates typesafe kotlin APIs from your SQL statements. It verifies your schema, statements, and migrations at compile-time and provides IDE features like autocomplete and refactoring which make writing and maintaining SQL simple.

[Realm](https://github.com/realm/realm-kotlin) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/realm/realm-kotlin)](https://github.com/realm/realm-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.realm.kotlin/gradle-plugin)](https://central.sonatype.com/artifact/io.realm.kotlin/gradle-plugin)
> Realm is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Kotlin SDK for Realm, which runs on Kotlin Multiplatform and Android.

[Kotbase](https://github.com/jeffdgr8/kotbase) - NoSQL JSON document database
[![GitHub Repo stars](https://img.shields.io/github/stars/jeffdgr8/kotbase)](https://github.com/jeffdgr8/kotbase)
[![Maven Central](https://img.shields.io/maven-central/v/dev.kotbase/couchbase-lite)](https://central.sonatype.com/namespace/dev.kotbase)
> Kotlin Multiplatform library for Couchbase Lite—a lightweight, embedded, NoSQL JSON document database—supporting SQL++, key/value, and full-text search queries; observability; binary attachments; and data sync.

[Store 5](https://github.com/MobileNativeFoundation/Store) - Kotlin Library for Async Data Loading and Caching
[![GitHub Repo stars](https://img.shields.io/github/stars/MobileNativeFoundation/Store)](https://github.com/MobileNativeFoundation/Store)
[![Maven Central](https://img.shields.io/maven-central/v/org.mobilenativefoundation.store/store5)](https://central.sonatype.com/artifact/org.mobilenativefoundation.store/store5)
> A Store is responsible for managing a particular data request. When you create an implementation of a Store, you provide it with a Fetcher, a function that defines how data will be fetched over network. You can also define how your Store will cache data in-memory and on-disk.

[Flower](https://github.com/hadiyarajesh/flower) - Flower simplifies networking and database caching on Android/Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/hadiyarajesh/flower)](https://github.com/hadiyarajesh/flower)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.hadiyarajesh.flower-core/flower-core)](https://central.sonatype.com/artifact/io.github.hadiyarajesh.flower-core/flower-core)
> Flower is a Kotlin multi-platform library that makes networking and database caching easy. It enables developers to fetch network resources and use them as is OR combine them with local database at single place with fault-tolerant architecture.

[cache4k](https://github.com/ReactiveCircus/cache4k) - In-memory Cache
[![GitHub Repo stars](https://img.shields.io/github/stars/ReactiveCircus/cache4k)](https://github.com/ReactiveCircus/cache4k)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.reactivecircus.cache4k/cache4k)](https://central.sonatype.com/artifact/io.github.reactivecircus.cache4k/cache4k)
> Provides a simple in-memory key-value cache for Kotlin Multiplatform, with support for time-based (expiration) and size-based evictions.

[SQLiter](https://github.com/touchlab/SQLiter) - SQLite driver
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/SQLiter)](https://github.com/touchlab/SQLiter)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/sqliter)](https://central.sonatype.com/artifact/co.touchlab/sqliter)
> SQLiter is a SQLite driver for Kotlin Native, currently Apple and Windows variants. It is designed to serve as a driver to power user-friendly libraries rather than something to use directly. Currently SQLiter powers the SQLDelight library on native clients.

[SQLlin](https://github.com/ctripcorp/SQLlin) - Low-level API for SQLite in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/ctripcorp/SQLlin)](https://github.com/ctripcorp/SQLlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.ctrip.kotlin/sqllin-driver)](https://central.sonatype.com/artifact/com.ctrip.kotlin/sqllin-driver)
> SQLlin is a Kotlin Multiplatform SQLite library that based on DSL and KSP. You can write SQL statements with your Kotlin code and these can be verified by Kotlin compiler.

[Kodein-DB](https://github.com/Kodein-Framework/Kodein-DB) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-DB)](https://github.com/Kodein-Framework/Kodein-DB)
[![Maven Central](https://img.shields.io/maven-central/v/org.kodein.db/kodein-db)](https://central.sonatype.com/artifact/org.kodein.db/kodein-db)
> Kodein-DB is a Kotlin/Multiplatform embedded NoSQL database that works on JVM, Android, Kotlin/Native and iOS. It is suited for client or mobile applications.

[KStore](https://github.com/xxfast/KStore) - File-based object storage
[![GitHub Repo stars](https://img.shields.io/github/stars/xxfast/KStore)](https://github.com/xxfast/KStore)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.xxfast/kstore)](https://central.sonatype.com/artifact/io.github.xxfast/kstore/)
> A Kotlin multiplatform library that assists in saving and restoring objects to and from disk

[Universal-Cache](https://github.com/andrew0000/universal-cache) - Kotlin caching and request sharing
[![GitHub Repo stars](https://img.shields.io/github/stars/andrew0000/universal-cache)](https://github.com/andrew0000/universal-cache)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.andrew0000/universal-cache)](https://central.sonatype.com/artifact/io.github.andrew0000/universal-cache/)
> Kotlin Flow caching and request sharing. Main idea: don't request data more times than it's needed.

[kotlin-cacheable](https://github.com/mori-atsushi/kotlin-cacheable) - Annotation-based caching library
[![GitHub Repo stars](https://img.shields.io/github/stars/mori-atsushi/kotlin-cacheable)](https://github.com/mori-atsushi/kotlin-cacheable)
[![Maven Central](https://img.shields.io/maven-central/v/com.moriatsushi.cacheable/cacheable-core)](https://central.sonatype.com/artifact/com.moriatsushi.cacheable/cacheable-core)
> Kotlin Cacheable is an annotation-based caching library for Kotlin Multiplatform.

### 📱 Device
[MOKO Permissions](https://github.com/icerockdev/moko-permissions) - System permissions manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-permissions)](https://github.com/icerockdev/moko-permissions)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/permissions)](https://central.sonatype.com/artifact/dev.icerock.moko/permissions)
> Kotlin Multiplatform library for providing runtime permissions on iOS & Android

[abc-kmm-notifications](https://github.com/line/abc-kmm-notifications) - Notification Manager
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-notifications)](https://github.com/line/abc-kmm-notifications)
[![Maven Central](https://img.shields.io/maven-central/v/com.linecorp.abc/kmm-notifications)](https://central.sonatype.com/artifact/com.linecorp.abc/kmm-notifications)
> Remote Notification Manager for Kotlin Multiplatform Mobile

[abc-kmm-Location](https://github.com/line/abc-kmm-location) - Location manager
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-location)](https://github.com/line/abc-kmm-location)
[![Maven Central](https://img.shields.io/maven-central/v/com.linecorp.abc/kmm-location)](https://central.sonatype.com/artifact/com.linecorp.abc/kmm-location)
> Location Service Manager for Kotlin Multiplatform Mobile iOS and android

[MOKO Geo](https://github.com/icerockdev/moko-geo) - Location manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-geo)](https://github.com/icerockdev/moko-geo)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/geo)](https://central.sonatype.com/artifact/dev.icerock.moko/geo)
> Geolocation access for mobile (android & ios) Kotlin Multiplatform development

[MOKO Biometry](https://github.com/icerockdev/moko-biometry) - System biometry manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-biometry)](https://github.com/icerockdev/moko-biometry)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/biometry)](https://central.sonatype.com/artifact/dev.icerock.moko/biometry)
> This is a Kotlin Multiplatform library that provides authentication by FaceId and TouchId (Fingerprint)

[MOKO Media](https://github.com/icerockdev/moko-media) - System media manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-media)](https://github.com/icerockdev/moko-media)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/media)](https://central.sonatype.com/artifact/dev.icerock.moko/media)
> This is a Kotlin Multiplatform library that provides media picking in common code (photo/video) and video player controls.

[MOKO Maps](https://github.com/icerockdev/moko-maps) - Google/Mapbox maps manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-maps)](https://github.com/icerockdev/moko-maps)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/maps)](https://central.sonatype.com/artifact/dev.icerock.moko/maps)
> This is a Kotlin Multiplatform library that provides controls of maps to common code.

[Kable](https://github.com/juullabs/kable) - Coroutines-powered API for interacting with Bluetooth Low Energy devices.
[![GitHub Repo stars](https://img.shields.io/github/stars/juullabs/kable)](https://github.com/juullabs/kable)
[![Maven Central](https://img.shields.io/maven-central/v/com.juul.kable/core)](https://central.sonatype.com/artifact/com.juul.kable/core/)
>Kotlin Asynchronous Bluetooth Low Energy provides a simple Coroutines-powered API for interacting with Bluetooth Low Energy devices.

[Blue-Falcon](https://github.com/Reedyuk/blue-falcon) - A Bluetooth kotlin multiplatform library for iOS and Android
[![GitHub Repo stars](https://img.shields.io/github/stars/Reedyuk/blue-falcon)](https://github.com/Reedyuk/blue-falcon)
[![Maven Central](https://img.shields.io/maven-central/v/dev.bluefalcon/blue-falcon-rpi)](https://central.sonatype.com/artifact/dev.bluefalcon/blue-falcon-rpi)
>A Bluetooth "Cross Platform" Kotlin Multiplatform library for iOS, Android, MacOS, Raspberry Pi and Javascript.
Bluetooth in general has the same functionality for all platforms, e.g. connect to device, fetch services, fetch characteristics.

[Connectivity status](https://github.com/ln-12/multiplatform-connectivity-status) - Multiplatform connectivity status
[![GitHub Repo stars](https://img.shields.io/github/stars/ln-12/multiplatform-connectivity-status)](https://github.com/rsocket/rsocket-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.ln-12/multiplatform-connectivity-status)](https://central.sonatype.com/artifact/com.github.ln-12/multiplatform-connectivity-status)
> This Kotlin multiplatform mobile utility library allows monitoring the internet connection status of the device. You can use it from shared code as well as directly from Android or iOS code.

[Kontrol](https://github.com/chopyourbrain/kontrol) - Debug menu
[![GitHub Repo stars](https://img.shields.io/github/stars/chopyourbrain/kontrol)](https://github.com/chopyourbrain/kontrol)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.chopyourbrain/kontrol)](https://central.sonatype.com/artifact/io.github.chopyourbrain/kontrol)
> A Kotlin Multiplatform library for creating debug menu.

[KMPNotifier](https://github.com/mirzemehdi/KMPNotifier) - Firebase Push Notification library for iOS and Android
[![GitHub Repo stars](https://img.shields.io/github/stars/mirzemehdi/KMPNotifier)](https://img.shields.io/github/stars/mirzemehdi/KMPNotifier)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.mirzemehdi/kmpnotifier)](https://central.sonatype.com/artifact/io.github.mirzemehdi/kmpnotifier)
> Kotlin Multiplatform Push Notification Library using Firebase for iOS and Android.

### 💉 Dependency Injection
[Koin](https://github.com/InsertKoinIO/koin) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/InsertKoinIO/koin)](https://github.com/InsertKoinIO/koin)
[![Maven Central](https://img.shields.io/maven-central/v/io.insert-koin/koin-core)](https://central.sonatype.com/artifact/io.insert-koin/koin-core)
> A pragmatic lightweight dependency injection framework for Kotlin developers. Koin is a DSL, a light container and a pragmatic API

[Kodein](https://github.com/Kodein-Framework/Kodein-DI) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-DI)](https://github.com/Kodein-Framework/Kodein-DI)
[![Maven Central](https://img.shields.io/maven-central/v/org.kodein.di/kodein-di)](https://central.sonatype.com/artifact/org.kodein.di/kodein-di)
> Kodein-DI is a very simple and yet very useful dependency retrieval container.

[kotlin-inject](https://github.com/evant/kotlin-inject) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/evant/kotlin-inject)](https://github.com/evant/kotlin-inject)
[![Maven Central](https://img.shields.io/maven-central/v/me.tatarka.inject/kotlin-inject-runtime)](https://central.sonatype.com/artifact/me.tatarka.inject/kotlin-inject-runtime)
> A compile-time dependency injection library for kotlin.

[Koject](https://github.com/mori-atsushi/koject) - KSP DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/mori-atsushi/koject)](https://github.com/mori-atsushi/koject)
[![Maven Central](https://img.shields.io/maven-central/v/com.moriatsushi.koject/koject-core)](https://central.sonatype.com/artifact/com.moriatsushi.koject/koject-core)
> Koject is a DI Container Library for Kolin Multiplatform using KSP.

[DI.kt](https://github.com/sergeshustoff/dikt) - DI for kotlin multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/sergeshustoff/dikt)](https://github.com/sergeshustoff/dikt)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.sergeshustoff.dikt/dikt-compiler-plugin)](https://central.sonatype.com/artifact/io.github.sergeshustoff.dikt/dikt-compiler-plugin)
> Simple DI with compile-time dependency graph validation for kotlin multiplatform. It uses IR to create method's bodies with dependency injection.

[PopKorn](https://github.com/corbella83/PopKorn) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/corbella83/PopKorn)](https://github.com/corbella83/PopKorn)
[![Maven Central](https://img.shields.io/maven-central/v/cc.popkorn/popkorn)](https://central.sonatype.com/artifact/cc.popkorn/popkorn)
> PopKorn is a simple, powerful and lightweight Kotlin Multiplatform Dependency Injector. It doesn't need any modules or components, just use it without writing a single extra file! It supports AND, IOS, JVM, JS and NATIVE.

### 🏗 Architecture
[MVI Kotlin](https://github.com/arkivanov/MVIKotlin) - MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/MVIKotlin)](https://github.com/arkivanov/MVIKotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.mvikotlin/mvikotlin)](https://central.sonatype.com/artifact/com.arkivanov.mvikotlin/mvikotlin)
> MVIKotlin is a Kotlin Multiplatform framework that provides a way of (not only) writing shared code using MVI pattern. It also includes powerful debug tools like logging and time travel.

[Orbit MVI](https://github.com/orbit-mvi/orbit-mvi) - MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/orbit-mvi/orbit-mvi)](https://github.com/orbit-mvi/orbit-mvi)
[![Maven Central](https://img.shields.io/maven-central/v/org.orbit-mvi/orbit-core)](https://central.sonatype.com/artifact/org.orbit-mvi/orbit-core)
> Orbit is a Redux/MVI-like library for KMM, targetting Android and iOS.

[FlowMVI](https://github.com/respawn-app/FlowMVI) - Plugin-based MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/respawn-app/FlowMVI)](https://github.com/respawn-app/FlowMVI)
[![Maven Central](https://img.shields.io/maven-central/v/pro.respawn.flowmvi/core)](https://central.sonatype.com/namespace/pro.respawn.flowmvi)
> FlowMVI is a KMP MVI library based on coroutines with a rich DSL and a powerful plugin system.

[KMM-ViewModel](https://github.com/rickclephas/KMM-ViewModel) - KMM ViewModels
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/KMM-ViewModel)](https://github.com/rickclephas/KMM-ViewModel)
[![Maven Central](https://img.shields.io/maven-central/v/com.rickclephas.kmm/kmm-viewmodel-core)](https://central.sonatype.com/artifact/com.rickclephas.kmm/kmm-viewmodel-core)
> A library that allows you to share ViewModels between Android and iOS.

[VisualFSM](https://github.com/Kontur-Mobile/VisualFSM) - FSM-based MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/Kontur-Mobile/VisualFSM)](https://github.com/Kontur-Mobile/VisualFSM)
[![MavenCentral](https://img.shields.io/maven-central/v/ru.kontur.mobile.visualfsm/visualfsm-core)](https://central.sonatype.com/artifact/ru.kontur.mobile.visualfsm/visualfsm-core)
> VisualFSM is a Kotlin Multiplatform library for implements an FSM-based (Finite-state machine) MVI pattern and a set of tools for visualization and analysis of FSM's diagram of states.

[Redux Kotlin](https://github.com/reduxkotlin/redux-kotlin) - Redux framework
[![GitHub Repo stars](https://img.shields.io/github/stars/reduxkotlin/redux-kotlin)](https://github.com/reduxkotlin/redux-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/org.reduxkotlin/redux-kotlin-threadsafe)](https://central.sonatype.com/artifact/org.reduxkotlin/redux-kotlin-threadsafe)
> Redux implementation for Kotlin (supports multiplatform JVM, native, JS, WASM)

[CoRed](https://github.com/kittinunf/CoRed) - Opinionated Redux-like implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/kittinunf/CoRed)](https://github.com/kittinunf/CoRed)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.kittinunf.cored/cored)](https://central.sonatype.com/artifact/com.github.kittinunf.cored/cored)
> CoRed is Redux-like implementation that maintains the benefits of Redux's core idea without the boilerplate. No more action types, action creators, switch statements or complicated setup. It is Kotlin and it has coroutine supported right out-of-the-box.

[Flywheel](https://github.com/abhimuktheeswarar/Flywheel) - Redux for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/abhimuktheeswarar/Flywheel)](https://github.com/abhimuktheeswarar/Flywheel)
[![Maven Central](https://img.shields.io/maven-central/v/com.msabhi/flywheel)](https://central.sonatype.com/artifact/com.msabhi/flywheel)
> A simple and predictable state management library inspired by Redux for Kotlin Multiplatform using the concepts of actors.

[FlowRedux](https://github.com/freeletics/FlowRedux) - Statemachine library with nice DSL
[![GitHub Repo stars](https://img.shields.io/github/stars/freeletics/FlowRedux)](https://github.com/freeletics/FlowRedux)
[![Maven Central](https://img.shields.io/maven-central/v/com.freeletics.flowredux/flowredux)](https://central.sonatype.com/artifact/com.freeletics.flowredux/flowredux)
> Building async. running Kotlin Multiplatform state machine made easy with a DSL and coroutines.

[Mobius.kt](https://github.com/DrewCarlson/mobius.kt) - Mobius Framework
[![GitHub Repo stars](https://img.shields.io/github/stars/DrewCarlson/mobius.kt)](https://github.com/DrewCarlson/mobius.kt)
[![Maven Central](https://img.shields.io/maven-central/v/org.drewcarlson/mobiuskt-core)](https://central.sonatype.com/artifact/org.drewcarlson/mobiuskt-core)
> Kotlin Multiplatform [Mobius](https://github.com/spotify/mobius) implementation.

[MOKO MVVM](https://github.com/icerockdev/moko-mvvm) - MVVM framework
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-mvvm)](https://github.com/icerockdev/moko-mvvm)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/mvvm)](https://central.sonatype.com/artifact/dev.icerock.moko/mvvm)
> This is a Kotlin Multiplatform library that provides architecture components of Model-View-ViewModel for UI applications. Components are lifecycle-aware on Android.

[Oolong](https://github.com/oolong-kt/oolong) - MVU for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/oolong-kt/oolong)](https://github.com/oolong-kt/oolong)
[![Maven Central](https://img.shields.io/maven-central/v/org.oolong-kt/oolong)](https://central.sonatype.com/artifact/org.oolong-kt/oolong)
> Oolong is an [Elm](https://guide.elm-lang.org/architecture) inspired Model-View-Update (MVU) implementation for Kotlin multiplatform.

[Summer](https://github.com/adevone/summer) - Share ViewModels between iOS, Android and Web apps
[![GitHub Repo stars](https://img.shields.io/github/stars/adevone/summer)](https://github.com/adevone/summer)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.adevone.summer/summer)](https://central.sonatype.com/artifact/com.github.adevone.summer/summer)
> Summer is a presentation level library with kotlin-multiplatform support. It can be used to share viewModels between iOS, Android and Web apps.  Summer does not use code generation and thus have not significant effort on compilation time and odd build-time errors.  Project aims to have out-of-box support of Android Framework, Jetpack Compose, UIKit and SwiftUI without any adapters and platform-specific limitations.

[Premo](https://github.com/dmdevgo/Premo) — Presentation Model (aka View Model) and Navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/dmdevgo/premo)](https://github.com/dmdevgo/Premo)
[![Maven Central](https://img.shields.io/maven-central/v/me.dmdev.premo/premo)](https://central.sonatype.com/artifact/me.dmdev.premo/premo)
> Premo is a Kotlin Multiplatform library that helps to implement the Presentation Layer and share it on iOS, Android, Desktop and Web. Focus on writing logic instead of solving common and boring UI related issues: lifecycle, persistence, navigation, etc.

[Decompose](https://github.com/arkivanov/Decompose) - componentization and navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Decompose)](https://github.com/arkivanov/Decompose)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.decompose/decompose)](https://central.sonatype.com/artifact/com.arkivanov.decompose/decompose)
> Decompose is a Kotlin Multiplatform library for breaking down your code into lifecycle-aware business logic components (aka BLoC), with routing functionality and pluggable UI (Jetpack Compose, Android Views, SwiftUI, JS React, etc.)

[Decompose-Router](https://github.com/xxfast/Decompose-Router) - navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/xxfast/Decompose-Router)](https://github.com/xxfast/Decompose-Router)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.xxfast/decompose-router)](https://central.sonatype.com/artifact/io.github.xxfast/decompose-router/)
> A Compose-multiplatform navigation library that leverage Decompose to create an API inspired by Conductor

[Ballast](https://github.com/copper-leaf/ballast) - State Management framework
[![GitHub Repo stars](https://img.shields.io/github/stars/copper-leaf/ballast)](https://github.com/copper-leaf/ballast)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.copper-leaf/ballast-core)](https://central.sonatype.com/artifact/io.github.copper-leaf/ballast-core)
> Opinionated Application State Management framework for Kotlin Multiplatform

[Essenty/Lifecycle](https://github.com/arkivanov/Essenty#lifecyle) - lifecycle handling in the Kotlin Multiplatform common code
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Essenty)](https://github.com/arkivanov/Essenty)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.essenty/lifecycle)](https://central.sonatype.com/artifact/com.arkivanov.essenty/lifecycle)
> Essenty provides the Lifecycle API to help with lifecycle handling in the common code. It is very similar to Android Activity lifecycle.

[multiplatform-paging](https://github.com/cashapp/multiplatform-paging) - Pagination library for KMM by `Cash App`
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/multiplatform-paging)](https://github.com/cashapp/multiplatform-paging)
[![Maven Central](https://img.shields.io/maven-central/v/app.cash.paging/paging-common)](https://central.sonatype.com/artifact/app.cash.paging/paging-common)
> A Kotlin Multiplatform library for pagination with the same API as AndroidX Paging

[multiplatform-paging](https://github.com/kuuuurt/multiplatform-paging) - Pagination library for KMM
[![GitHub Repo stars](https://img.shields.io/github/stars/kuuuurt/multiplatform-paging)](https://github.com/kuuuurt/multiplatform-paging)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.kuuuurt/multiplatform-paging)](https://central.sonatype.com/artifact/io.github.kuuuurt/multiplatform-paging)
> A Kotlin Multiplatform library for pagination.

[Kotlin Bloc](https://github.com/1gravity/Kotlin-Bloc) - UI framework for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/1gravity/Kotlin-Bloc)](https://github.com/1gravity/Kotlin-Bloc)
[![Maven Central](https://img.shields.io/maven-central/v/com.1gravity/bloc-core)](https://central.sonatype.com/artifact/com.1gravity/bloc-core)
> Kotlin Bloc is a simple, predictable and composable UI framework for Kotlin Multiplatform supporting Android, iOS and JVM.

[kmp-viewmodel](https://github.com/hoc081098/kmp-viewmodel) - Kotlin Multiplatform ViewModel
[![GitHub Repo stars](https://img.shields.io/github/stars/hoc081098/kmp-viewmodel)](https://github.com/hoc081098/kmp-viewmodel)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.hoc081098/kmp-viewmodel)](https://central.sonatype.com/artifact/io.github.hoc081098/kmp-viewmodel/)
> A Kotlin Multiplatform library that provides shared MVVM. Supports Android Parcelable, Kotlin Parcelize, AndroidX SavedStateHandle for restoring state after process death.

[Meteor](https://github.com/getspherelabs/meteor-kmp)  - MVI framework with CommonViewModel, CommonStateFlow, UseCase
[![GitHub Repo stars](https://img.shields.io/github/stars/getspherelabs/meteor-kmp)](https://github.com/getspherelabs/meteor-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.behzodhalil/meteor-mvi)](https://central.sonatype.com/artifact/io.github.behzodhalil/meteor-mvi)
>  MVI/Redux framework for Kotlin Multiplatform

[KStateMachine](https://github.com/nsk90/kstatemachine) - Multiplatform state machine library with coroutines support
[![GitHub Repo stars](https://img.shields.io/github/stars/nsk90/kstatemachine)](https://github.com/nsk90/kstatemachine)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.nsk90/kstatemachine)](https://central.sonatype.com/artifact/io.github.nsk90/kstatemachine)
> KStateMachine is a Kotlin DSL library for creating state machines and statecharts.

### 🔍 Analytics
[MOKO Crash Reporting](https://github.com/icerockdev/moko-crash-reporting) - reporting to Crashlytics
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-crash-reporting)](https://github.com/icerockdev/moko-crash-reporting)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/crash-reporting-crashlytics)](https://central.sonatype.com/artifact/dev.icerock.moko/crash-reporting-crashlytics)
> Fatal and Non-Fatal reporting to Crashlytics for Kotlin Multiplatform Mobile

[CrashKiOS](https://github.com/touchlab/CrashKiOS) - Crash reporting for Kotlin/Native iOS applications
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/CrashKiOS)](https://github.com/touchlab/CrashKiOS)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/crashkios)](https://central.sonatype.com/artifact/co.touchlab/crashkios)
> Thin library that provides symbolicated crash reports for Kotlin code on iOS.

[NSExceptionKt](https://github.com/rickclephas/NSExceptionKt) - Better crash reports on Apple platforms
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/NSExceptionKt)](https://github.com/rickclephas/NSExceptionKt)
[![Maven Central](https://img.shields.io/maven-central/v/com.rickclephas.kmp/nsexception-kt-core)](https://central.sonatype.com/artifact/com.rickclephas.kmp/nsexception-kt-core)
> Unhandled Kotlin exceptions logging for Apple platforms.

[abc-kmm-analytics-tools](https://github.com/line/abc-kmm-analytics-tools) - Analytics Tools
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-analytics-tools)](https://github.com/line/abc-kmm-analytics-tools)
[![Maven Central](https://img.shields.io/maven-central/v/com.linecorp.abc/kmm-analytics-tools)](https://central.sonatype.com/artifact/com.linecorp.abc/kmm-analytics-tools)
> Automatically tracking and sending events of screen view and capture

[Analytics](https://github.com/ppav/analytics) - analytics facade
[![GitHub Repo stars](https://img.shields.io/github/stars/ppav/analytics)](https://github.com/ppav/analytics)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.ppav.analytics/analytics)](https://central.sonatype.com/artifact/io.github.ppav/analytics/analytics)
> Kotlin Multiplatform library as a simple facade or abstraction for analytics.

[trckr](https://github.com/dzmpr/trckr) - KSP processor
[![GitHub Repo stars](https://img.shields.io/github/stars/dzmpr/trckr)](https://github.com/dzmpr/trckr)
[![Maven Central](https://img.shields.io/maven-central/v/ru.cookedapp.trckr/trckr-core)](https://central.sonatype.com/artifact/ru.cookedapp.trckr/trckr-core)
> KSP processer that simplifies the collection of analytics

### 🩺 Test
[Kotest](https://github.com/kotest/kotest) - test framework
[![GitHub Repo stars](https://img.shields.io/github/stars/kotest/kotest)](https://github.com/kotest/kotest)
[![Maven Central](https://img.shields.io/maven-central/v/io.kotest/kotest-mpp)](https://central.sonatype.com/artifact/io.kotest/kotest-mpp)
> Powerful, elegant and flexible test framework for Kotlin with additional assertions, property testing and data driven testing

[Turbine](https://github.com/cashapp/turbine) - test library
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/turbine)](https://github.com/mpetuska/klip)
[![Maven Central](https://img.shields.io/maven-central/v/app.cash.turbine/turbine)](https://central.sonatype.com/artifact/app.cash.turbine/turbine)
> A small testing library for kotlinx.coroutines Flow

[MockingBird](https://github.com/careem/mockingbird) - test framework
[![GitHub Repo stars](https://img.shields.io/github/stars/careem/mockingbird)](https://github.com/careem/mockingbird)
[![Maven Central](https://img.shields.io/maven-central/v/com.careem.mockingbird/mockingbird)](https://central.sonatype.com/artifact/com.careem.mockingbird/mockingbird)
> A Koltin multiplatform library that provides an easier way to mock and write unit tests for a multiplatform project

[Mockative](https://github.com/mockative/mockative) - Mocking with KSP
[![GitHub Repo stars](https://img.shields.io/github/stars/mockative/mockative)](https://github.com/mockative/mockative)
[![Maven Central](https://img.shields.io/maven-central/v/io.mockative/mockative)](https://central.sonatype.com/artifact/io.mockative/mockative)
> Mocking for Kotlin/Native and Kotlin Multiplatform using the Kotlin Symbol Processing API (KSP)

[MocKMP](https://github.com/Kodein-Framework/MocKMP) - Mocking with KSP
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/MocKMP)](https://github.com/Kodein-Framework/MocKMP)
[![Maven Central](https://img.shields.io/maven-central/v/org.kodein.mock.mockmp/org.kodein.mock.mockmp.gradle.plugin)](https://central.sonatype.com/artifact/org.kodein.mock.mockmp/org.kodein.mock.mockmp.gradle.plugin)
> A Kotlin/Multiplatform Kotlin Symbol Processor that generates Mocks & Fakes.

[KLIP](https://github.com/mpetuska/klip) - Snapshot ((c|k)lip) manager for tests.
[![GitHub Repo stars](https://img.shields.io/github/stars/mpetuska/klip)](https://github.com/mpetuska/klip)
[![Maven Central](https://img.shields.io/maven-central/v/dev.petuska/klip)](https://central.sonatype.com/artifact/dev.petuska/klip)
> Kotlin Multiplatform snapshot ((c|k)lip) manager for tests. Automatically generates and asserts against a persistent Any::toString() representation of the object until you explicitly trigger an update. Powered by kotlin compiler plugin to inject relevant keys and paths.

[Assertk](https://github.com/willowtreeapps/assertk) - Fluent assertions library
[![GitHub Repo stars](https://img.shields.io/github/stars/willowtreeapps/assertk)](https://github.com/willowtreeapps/assertk)
[![Maven Central](https://img.shields.io/maven-central/v/com.willowtreeapps.assertk/assertk)](https://central.sonatype.com/artifact/com.willowtreeapps.assertk/assertk)
> Fluent assertions library for Kotlin with full Multiplatform support.

### 🔑 Crypto
[Cryptography-Kotlin](https://github.com/whyoleg/cryptography-kotlin) - Type-safe Multiplatform cryptography library for Kotlin
[![GitHub Repo stars](https://img.shields.io/github/stars/whyoleg/cryptography-kotlin)](https://github.com/whyoleg/cryptography-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/dev.whyoleg.cryptography/cryptography-core)](https://central.sonatype.com/artifact/dev.whyoleg.cryptography/cryptography-core)
> The library doesn’t implement any cryptography algorithm on its own, but wraps well-known future-proof solutions like OpenSSL 3.x, WebCrypto or JCA with type-safe multiplatform API providing uniform experience with aligned default behavior, and same expected results using identical parameters while allowing to use platform-specific capabilities.

[Libsodium](https://github.com/ionspin/kotlin-multiplatform-libsodium) - Libsodium bindings for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/ionspin/kotlin-multiplatform-libsodium)](https://github.com/ionspin/kotlin-multiplatform-libsodium)
[![Maven Central](https://img.shields.io/maven-central/v/com.ionspin.kotlin/multiplatform-crypto-libsodium-bindings)](https://central.sonatype.com/artifact/com.ionspin.kotlin/multiplatform-crypto-libsodium-bindings)
> Libsodium bindings project uses libsodium c sources and libsodium.js to provide a kotlin multiplatform wrapper library for libsodium.

[Krypto](https://github.com/korlibs/krypto) - Pure Kotlin cryptography library
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/krypto)](https://github.com/korlibs/krypto)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.krypto/krypto)](https://central.sonatype.com/artifact/com.soywiz.korlibs.krypto/krypto)
> SecureRandom, Hash (MD5/SHA1/SHA256), AES

[cryptohash](https://github.com/appmattus/crypto/tree/main/cryptohash) - A set of cryptographic (and not so cryptographic) hashing functions
[![GitHub Repo stars](https://img.shields.io/github/stars/appmattus/crypto)](https://github.com/appmattus/crypto)
[![Maven Central](https://img.shields.io/maven-central/v/com.appmattus.crypto/cryptohash)](https://central.sonatype.com/artifact/com.appmattus.crypto/cryptohash)
> xxHash, Blake, HMAC, Keccak, MD5, SHA, etc

[murmurhash](https://github.com/goncalossilva/kotlinx-murmurhash) - library for hashing using MurmurHash
[![GitHub Repo stars](https://img.shields.io/github/stars/goncalossilva/kotlinx-murmurhash)](https://github.com/goncalossilva/kotlinx-murmurhash)
[![Maven Central](https://img.shields.io/maven-central/v/com.goncalossilva/murmurhash)](https://central.sonatype.com/artifact/com.goncalossilva/murmurhash)
> Kotlin Multiplatform (KMP) library for MurmurHash, a non-cryptographic hash function for general hash-based lookup focused on simplicity and performance.

[Diglol Crypto](https://github.com/diglol/crypto) - Diglol Crypto for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/crypto)](https://github.com/diglol/crypto)
[![Maven Central](https://img.shields.io/maven-central/v/com.diglol.crypto/aead)](https://central.sonatype.com/artifact/com.diglol.crypto/aead)
> Lots of crypto algorithms for Kotlin Multiplatform.

[KotlinCrypto/MACs](https://github.com/KotlinCrypto/MACs) - Message Authentication Code algorithms for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/MACs)](https://github.com/KotlinCrypto/MACs)
[![Maven Central](https://img.shields.io/maven-central/v/org.kotlincrypto.macs/hmac)](https://central.sonatype.com/artifact/org.kotlincrypto.macs/hmac)
> Message Authentication Code algorithms for Kotlin Multiplatform: HmacMD5, HmacSHA1, HmacSHA224, HmacSHA256, HmacSHA384, HmacSHA512, HmacSHA512/224, HmacSHA512/256

[KotlinCrypto/hash](https://github.com/KotlinCrypto/hash) - Cryptographic hash functions for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/hash)](https://github.com/KotlinCrypto/hash)
[![Maven Central](https://img.shields.io/maven-central/v/org.kotlincrypto.hash/md5)](https://central.sonatype.com/artifact/org.kotlincrypto.hash/md5)
> Cryptographic hash functions for Kotlin Multiplatform: MD5, SHA-1, SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, SHA-512/256

[KotlinCrypto/secure-random](https://github.com/KotlinCrypto/secure-random) - cryptographically secure random data from system sources
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/secure-random)](https://github.com/KotlinCrypto/secure-random)
[![Maven Central](https://img.shields.io/maven-central/v/org.kotlincrypto/secure-random)](https://central.sonatype.com/artifact/org.kotlincrypto/secure-random)
> Kotlin Multiplatform library for obtaining cryptographically secure random data from the system. Modeled after Java's SecureRandom class, it provides a simple API surface area. Under the hood it utilizes system functions so that SecureRandom is accessible from common code.

### 📁 File
[Okio](https://github.com/square/okio) - access, store, and process your data
[![GitHub Repo stars](https://img.shields.io/github/stars/square/okio)](https://github.com/square/okio)
[![Maven Central](https://img.shields.io/maven-central/v/com.squareup.okio/okio)](https://central.sonatype.com/artifact/com.squareup.okio/okio)
> Okio is a library that complements java.io and java.nio to make it much easier to access, store, and process your data.

[KorIO](https://github.com/korlibs/korio) - access, store, and process your data
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korio)](https://github.com/korlibs/korio)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.korio/korio)](https://central.sonatype.com/artifact/com.soywiz.korlibs.korio/korio)
> KorIO is a library for Charsets, Encodings, Checksums, Compression, I/O, Streams, Virtual File System, Networking, Http, WebSockets, Serialization…

[Suparnatural FS](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs) - file system i/o
[![GitHub Repo stars](https://img.shields.io/github/stars/suparngp/kotlin-multiplatform-projects)](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs)
[![Maven Central](https://img.shields.io/maven-central/v/com.suparnatural.kotlin/fs)](https://central.sonatype.com/artifact/com.suparnatural.kotlin/fs)
> Kotlin multiplatform file system i/o for android, iOS, Java and NodeJS

### 🚀 Language extensions
[Arrow](https://github.com/arrow-kt/arrow) - Functional companion to Kotlin's Standard Library
[![GitHub Repo stars](https://img.shields.io/github/stars/arrow-kt/arrow)](https://github.com/arrow-kt/arrow)
[![Maven Central](https://img.shields.io/maven-central/v/io.arrow-kt/arrow-core)](https://central.sonatype.com/artifact/io.arrow-kt/arrow-core)
> Arrow aims to provide a lingua franca of interfaces and abstractions across Kotlin libraries. For this, it includes the most popular data types such as Option, Either, Validated etc and functional operators such as traverse and computation blocks to empower users to write pure FP apps and libraries built atop higher order abstractions.

[Result](https://github.com/kittinunf/Result) - success/failure result
[![GitHub Repo stars](https://img.shields.io/github/stars/kittinunf/Result)](https://github.com/kittinunf/Result)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.kittinunf.result/result)](https://central.sonatype.com/artifact/com.github.kittinunf.result/result)
> This is a tiny framework for modelling success/failure of operations in Kotlin. In short, it is a model in type of Result<V: Any?, E : Throwable>.

[ApiResult](https://github.com/respawn-app/ApiResult) - Declarative Error Handling
[![GitHub Repo stars](https://img.shields.io/github/stars/respawn-app/ApiResult)](https://github.com/respawn-app/ApiResult)
[![Maven Central](https://img.shields.io/maven-central/v/pro.respawn.apiresult/core)](https://central.sonatype.com/namespace/pro.respawn.apiresult)
> ApiResult is a Kotlin Multiplatform declarative error handling framework that is performant, easy to use and feature-rich.

### 🗃 Serializer
[kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - JSON serialization
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.serialization)](https://github.com/Kotlin/kotlinx.serialization)
[![Maven Central](https://img.shields.io/maven-central/v/net.peanuuutz.tomlkt/tomlkt)](https://central.sonatype.com/artifact/net.peanuuutz.tomlkt/tomlkt)
> Kotlin serialization consists of a compiler plugin, that generates visitor code for serializable classes, runtime library with core serialization API and support libraries with various serialization formats.

[Ksoup](https://github.com/fleeksoft/ksoup) - HTML & XML Parser (Jsoup Alternative)
[![GitHub Repo stars](https://img.shields.io/github/stars/fleeksoft/ksoup)](https://github.com/fleeksoft/ksoup)
[![Maven Central](https://img.shields.io/maven-central/v/com.fleeksoft.ksoup/ksoup)](https://central.sonatype.com/artifact/com.fleeksoft.ksoup/ksoup)
> Ksoup: A Kotlin Multiplatform port of the renowned Java library, jsoup. Designed to scrape, parse, manipulate, and clean HTML and XML documents with ease and efficiency.

[XmlUtil](https://github.com/pdvrieze/xmlutil) - Component of the XMLUtil library
[![GitHub Repo stars](https://img.shields.io/github/stars/pdvrieze/xmlutil)](https://github.com/pdvrieze/xmlutil)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.pdvrieze.xmlutil/core)](https://central.sonatype.com/artifact/io.github.pdvrieze.xmlutil/core)
> XmlUtil is a set of packages that supports multiplatform XML in Kotlin.

[tomlkt](https://github.com/Peanuuutz/tomlkt) - Multiplatform TOML encoder and decoder, powered by kotlinx.serialization
[![GitHub Repo stars](https://img.shields.io/github/stars/Peanuuutz/tomlkt)](https://github.com/Peanuuutz/tomlkt)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.pdvrieze.xmlutil/core)](https://central.sonatype.com/artifact/io.github.pdvrieze.xmlutil/core)
> Lightweight and easy to use kotlinx.serialization plugin for TOML serialization and deserialization.

[Ksoup](https://github.com/MohamedRejeb/ksoup) - Kotlin Multiplatform HTML Parser
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/ksoup)](https://github.com/MohamedRejeb/ksoup)
[![Maven Central](https://img.shields.io/maven-central/v/com.mohamedrejeb.ksoup/ksoup-html)](https://central.sonatype.com/artifact/com.mohamedrejeb.ksoup/ksoup-html)
> Ksoup is a lightweight Kotlin Multiplatform library for parsing HTML, extracting HTML tags, attributes, and text, and encoding and decoding HTML entities.

[Essenty/Parcelable](https://github.com/arkivanov/Essenty#parcelable-and-parcelize) - @Parcelize annotation for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Essenty)](https://github.com/arkivanov/Essenty)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.essenty/parcelable)](https://central.sonatype.com/artifact/com.arkivanov.essenty/parcelable)
> Essenty brings both Android Parcelable interface and the `@Parcelize` annotation from kotlin-parcelize compiler plugin to Kotlin Multiplatform, so they both can be used in common code.

[Kotlin Object Notation](https://github.com/mpetuska/kon) - Lightweight DSL to build fluid JSON trees
[![GitHub Repo stars](https://img.shields.io/github/stars/mpetuska/kon)](https://github.com/mpetuska/kon)
[![Maven Central](https://img.shields.io/maven-central/v/dev.petuska/kon)](https://central.sonatype.com/artifact/dev.petuska/kon)
> Kotlin Object Notation - Lightweight DSL to build fluid JSON trees

[MOKO Parcelize](https://github.com/icerockdev/moko-parcelize) - Parcelize in common code
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-parcelize)](https://github.com/icerockdev/moko-parcelize)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/parcelize)](https://central.sonatype.com/artifact/dev.icerock.moko/parcelize)
> This is a Kotlin Multiplatform library that supports Parcelize in common code.

[Pbandk](https://github.com/streem/pbandk) - Kotlin code generator and runtime for Protocol Buffers.
[![GitHub Repo stars](https://img.shields.io/github/stars/streem/pbandk)](https://github.com/streem/pbandk)
[![Maven Central](https://img.shields.io/maven-central/v/pro.streem.pbandk/protoc-gen-pbandk-jvm)](https://central.sonatype.com/artifact/pro.streem.pbandk/protoc-gen-pbandk-jvm)
>It has the core set of protobuf features implemented and is being used in production.

### ⏰ Date-Time
[Kotlinx DateTime](https://github.com/Kotlin/kotlinx-datetime) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx-datetime)](https://github.com/Kotlin/kotlinx-datetime)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlinx/kotlinx-datetime)](https://central.sonatype.com/artifact/org.jetbrains.kotlinx/kotlinx-datetime)
> A multiplatform Kotlin library for working with date and time.

[Klock](https://github.com/korlibs/klock) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/klock)](https://github.com/korlibs/klock)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz/klock)](https://central.sonatype.com/artifact/com.soywiz/klock)
> Klock is a Date & Time library for Multiplatform Kotlin. It is designed to be as allocation-free as possible using Kotlin inline classes, to be consistent and portable across targets since all the code is written in Common Kotlin, and to provide an API that is powerful, fun and easy to use.

[Island Time](https://github.com/erikc5000/island-time) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/erikc5000/island-time)](https://github.com/erikc5000/island-time)
[![Maven Central](https://img.shields.io/maven-central/v/io.islandtime/core)](https://central.sonatype.com/artifact/io.islandtime/core)
> A Kotlin Multiplatform library for working with dates and times, heavily inspired by the java.time library.

[Kronos Multiplatform](https://github.com/softartdev/Kronos-Multiplatform) - Network Time Protocol (NTP) client
[![GitHub Repo stars](https://img.shields.io/github/stars/softartdev/Kronos-Multiplatform)](https://github.com/softartdev/Kronos-Multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.softartdev/kronos)](https://central.sonatype.com/artifact/io.github.softartdev/kronos)
> Kotlin Multiplatform library for network time synchronization. Extension for [Kotlinx DateTime](https://github.com/Kotlin/kotlinx-datetime) library.

### ➿ Asynchronous
[Kotlinx Coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Kotlin coroutines
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.coroutines)](https://github.com/Kotlin/kotlinx.coroutines)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlinx/kotlinx-coroutines-core)](https://central.sonatype.com/artifact/org.jetbrains.kotlinx/kotlinx-coroutines-core)
> Library support for Kotlin coroutines

[Reaktive](https://github.com/badoo/Reaktive) - Reactive Extensions
[![GitHub Repo stars](https://img.shields.io/github/stars/badoo/Reaktive)](https://github.com/badoo/Reaktive)
[![Maven Central](https://img.shields.io/maven-central/v/com.badoo.reaktive/reaktive)](https://central.sonatype.com/artifact/com.badoo.reaktive/reaktive)
> Kotlin multiplatform implementation of Reactive Extensions.

[Kotlinx Atomicfu](https://github.com/Kotlin/kotlinx.atomicfu) - atomic operations
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.atomicfu)](https://github.com/Kotlin/kotlinx.atomicfu)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlinx/atomicfu)](https://central.sonatype.com/artifact/org.jetbrains.kotlinx/atomicfu)
> The idiomatic way to use atomic operations in Kotlin.

[Stately](https://github.com/touchlab/Stately) - Kotlin Multiplatform State Library
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Stately)](https://github.com/touchlab/Stately)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/stately)](https://central.sonatype.com/artifact/co.touchlab/stately)
> Stately is a state utility library to facilitate state management in Kotlin Multiplatform.

[CoroutineWorker](https://github.com/Autodesk/coroutineworker) - Workers for Kotlin Native
[![GitHub Repo stars](https://img.shields.io/github/stars/Autodesk/coroutineworker)](https://github.com/Autodesk/coroutineworker)
[![Maven Central](https://img.shields.io/maven-central/v/com.autodesk/CoroutineWorker)](https://central.sonatype.com/artifact/com.autodesk/CoroutineWorker)
> Kotlin Coroutine-based workers for native

[Koru](https://github.com/FutureMind/koru) - Coroutine wrappers for Kotlin Native
[![GitHub Repo stars](https://img.shields.io/github/stars/FutureMind/koru)](https://github.com/FutureMind/koru)
[![Maven Central](https://img.shields.io/maven-central/v/com.futuremind/koru)](https://central.sonatype.com/artifact/com.futuremind/koru)
> Automatically generates wrappers for suspend functions and Flow for easy access from Swift code in Kotlin Multiplatform projects.

[KMP-NativeCoroutines](https://github.com/rickclephas/KMP-NativeCoroutines) - Swift wrapper for Kotlin Coroutines
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/KMP-NativeCoroutines)](https://github.com/rickclephas/KMP-NativeCoroutines)
[![Maven Central](https://img.shields.io/maven-central/v/com.rickclephas.kmp/kmp-nativecoroutines-core)](https://central.sonatype.com/artifact/com.rickclephas.kmp/kmp-nativecoroutines-core)
> Library to use Kotlin Coroutines from Swift code in KMP apps

[FlowExt](https://github.com/hoc081098/FlowExt) - Kotlinx Coroutines Flow Extensions
[![GitHub Repo stars](https://img.shields.io/github/stars/hoc081098/FlowExt)](https://github.com/hoc081098/FlowExt)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.hoc081098/FlowExt)](https://central.sonatype.com/artifact/io.github.hoc081098/FlowExt)
> A Kotlin Multiplatform library, that provides many operators and extensions to Kotlin Coroutines Flow.

### 🍎 Compose UI
[Appyx](https://github.com/bumble-tech/appyx) Navigation, transition animations, gestures, UI components.
[![GitHub Repo stars](https://img.shields.io/github/stars/bumble-tech/appyx)](https://github.com/bumble-tech/appyx)
[![Maven Central](https://img.shields.io/maven-central/v/com.bumble.appyx/appyx-interactions)](https://img.shields.io/maven-central/v/com.bumble.appyx/appyx-interactions)
> Model-driven navigation + UI components with gesture control for Compose Multiplatform

[Voyager](https://github.com/adrielcafe/voyager) Compose Multiplatform Navigation.
[![GitHub Repo stars](https://img.shields.io/github/stars/adrielcafe/voyager)](https://github.com/adrielcafe/voyager)
[![Maven Central](https://img.shields.io/maven-central/v/cafe.adriel.voyager/voyager-core)](https://central.sonatype.com/artifact/cafe.adriel.voyager/voyager-core)
> A multiplatform navigation library built for, and seamlessly integrated with, Jetpack Compose.

[Calf](https://github.com/MohamedRejeb/Calf) Compose Adaptive Look & Feel
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/Calf)](https://github.com/MohamedRejeb/Calf)
[![Maven Central](https://img.shields.io/maven-central/v/com.mohamedrejeb.calf/calf-ui)](https://central.sonatype.com/artifact/com.mohamedrejeb.calf/calf-ui)
> Calf is a library that allows you to easily create adaptive UIs for your Compose Multiplatform apps.

[Libres-Compose](https://github.com/Skeptick/libres) Resources generation in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/Skeptick/libres)](https://github.com/Skeptick/libres)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.skeptick.libres/libres-compose)](https://central.sonatype.com/artifact/io.github.skeptick.libres/libres-compose)
> This artifact provides painterResource function that can be used to get Painter from io.github.skeptick.libres.Image in common code.

[InsetsX](https://github.com/mori-atsushi/insetsx) WindowInsets
[![GitHub Repo stars](https://img.shields.io/github/stars/mori-atsushi/insetsx)](https://github.com/mori-atsushi/insetsx)
[![Maven Central](https://img.shields.io/maven-central/v/com.moriatsushi.insetsx/insetsx)](https://central.sonatype.com/artifact/com.moriatsushi.insetsx/insetsx)
> InsetsX provides a WindowInsets utility for Compose Multiplatform.

[Window Size Class](https://github.com/chrisbanes/material3-windowsizeclass-multiplatform) Window Size Class
[![GitHub Repo stars](https://img.shields.io/github/stars/chrisbanes/material3-windowsizeclass-multiplatform)](https://github.com/chrisbanes/material3-windowsizeclass-multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/dev.chrisbanes.material3/material3-window-size-class-multiplatform)](https://central.sonatype.com/artifact/dev.chrisbanes.material3/material3-window-size-class-multiplatform)
> Compose Multiplatform: Material 3 Window Size Class

[Compose-Imageloader](https://github.com/qdsfdhvh/compose-imageloader) Compose Image library for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/qdsfdhvh/compose-imageloader)](https://github.com/qdsfdhvh/compose-imageloader)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.qdsfdhvh/image-loader)](https://central.sonatype.com/artifact/io.github.qdsfdhvh/image-loader)
> Compose Image library for Kotlin Multiplatform.

[Kamel](https://github.com/Kamel-Media/Kamel) Compose Multiplatform image loading.
[![GitHub Repo stars](https://img.shields.io/github/stars/Kamel-Media/Kamel)](https://github.com/Kamel-Media/Kamel)
[![Maven Central](https://img.shields.io/maven-central/v/media.kamel/kamel-core)](https://central.sonatype.com/artifact/media.kamel/kamel-core)
> An asynchronous media loading library for Compose Multiplatform.

[Compose Icons](https://github.com/DevSrSouza/compose-icons) Open Source icon packs for Compose Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/DevSrSouza/compose-icons)](https://github.com/DevSrSouza/compose-icons)
[![Maven Central](https://img.shields.io/maven-central/v/br.com.devsrsouza.compose.icons/simple-icons)](https://central.sonatype.com/artifact/br.com.devsrsouza.compose.icons/simple-icons)
> Compose Multiplatform icons is a pack of libraries that provide well known Icon Packs. The library usage is inspired by Compose Material Icons.

[Compose Rich Editor](https://github.com/MohamedRejeb/Compose-Rich-Editor) Provides Rich Editor component for Compose Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/Compose-Rich-Editor)](https://github.com/MohamedRejeb/Compose-Rich-Editor)
[![Maven Central](https://img.shields.io/maven-central/v/com.mohamedrejeb.richeditor/richeditor-compose)](https://central.sonatype.com/artifact/com.mohamedrejeb.richeditor/richeditor-compose)
> A Rich text editor library for both Jetpack Compose and Compose Multiplatform, fully customizable and supports the common rich text editor features.

[Material Theme Preferences](https://github.com/softartdev/MaterialThemePrefs) Switching Dark/Light Material themes.
[![GitHub Repo stars](https://img.shields.io/github/stars/softartdev/MaterialThemePrefs)](https://github.com/softartdev/MaterialThemePrefs)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.softartdev/material-theme-prefs)](https://central.sonatype.com/artifact/io.github.softartdev/material-theme-prefs)
> Kotlin Multiplatform library for easy switching Dark/Light Material themes on Compose.

[Drag Select Compose](https://github.com/jordond/drag-select-compose) Google Photos style drag-to-select multi-selection.
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/drag-select-compose)](https://github.com/jordond/drag-select-compose)
[![Maven Central](https://img.shields.io/maven-central/v/com.dragselectcompose/dragselect)](https://central.sonatype.com/artifact/com.dragselectcompose/dragselect)
> Compose Multiplatform library that allows you to easily implement a "Google Photos"-style multi-selection in
your Compose apps.

[MaterialKolor](https://github.com/jordond/materialkolor) Generate Material3 color schemes from a seed color.
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/materialkolor)](https://github.com/jordond/materialkolor)
[![Maven Central](https://img.shields.io/maven-central/v/com.materialkolor/material-kolor)](https://central.sonatype.com/artifact/com.materialkolor/material-kolor)
> Compose multiplatform library for generating dynamic Material3 color schemes from a seed color.

[AAY-chart](https://github.com/TheChance101/AAY-chart) Compose Multiplatform chart library.
[![GitHub Repo stars](https://img.shields.io/github/stars/TheChance101/AAY-chart)](https://github.com/TheChance101/AAY-chart)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.thechance101/chart)](https://central.sonatype.com/artifact/io.github.thechance101/chart)
> The library contains several chart composables for usage in Kotlin Multiplatform projects and Android Native. Currently supported platforms are Desktop Android and IOS

[kmPalette](https://github.com/jordond/kmpalette) A port of Androidx Palette, generate palettes from image.
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/kmpalette)](https://github.com/jordond/kmpalette)
[![Maven Central](https://img.shields.io/maven-central/v/com.kmpalette/kmpalette-core)](https://central.sonatype.com/artifact/com.kmpalette/kmpalette-core)
> A Compose Multiplatform library for generating color palettes from images, including the dominant color.

[Reveal](https://github.com/svenjacobs/reveal) Reveal effect for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/svenjacobs/reveal)](https://github.com/svenjacobs/reveal)
[![Maven Central](https://img.shields.io/maven-central/v/com.svenjacobs.reveal/reveal-core)](https://central.sonatype.com/artifact/com.svenjacobs.reveal/reveal-core/badge.svg)
> A reveal effect (coach mark, tutorial, onboarding) for Compose Multiplatform (Android, iOS, desktop, Web)

[KMP-ComposeUIViewController](https://github.com/GuilhE/KMP-ComposeUIViewController) KMP-ComposeUIViewController.
[![GitHub Repo stars](https://img.shields.io/github/stars/GuilhE/KMP-ComposeUIViewController)](https://github.com/GuilhE/KMP-ComposeUIViewController)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.guilhe.kmp/kmp-composeuiviewcontroller-ksp)](https://central.sonatype.com/artifact/com.github.guilhe.kmp/kmp-composeuiviewcontroller-ksp)
> KSP library for generating ComposeUIViewController and UIViewControllerRepresentable files when using Compose Multiplatform for iOS.

[KodeView](https://github.com/SnipMeDev/KodeView) KodeView
[![GitHub Repo stars](https://img.shields.io/github/stars/SnipMeDev/KodeView)](https://github.com/SnipMeDev/KodeView)
[![Maven Central](https://img.shields.io/maven-central/v/dev.snipme/kodeview)](https://central.sonatype.com/artifact/dev.snipme/kodeview/badge.svg)
> Kotlin Multiplatform syntax highlighting views.

[QRose](https://github.com/alexzhirkevich/qrose) - Multiplatform QR code generator
[![GitHub Repo stars](https://img.shields.io/github/stars/alexzhirkevich/qrose)](https://github.com/alexzhirkevich/qrose)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.alexzhirkevich/qrose)](https://central.sonatype.com/artifact/io.github.alexzhirkevich/qrose/badge.svg)
> Styled QR code generation library for Compose Multiplatform.

[ZoomImage](https://github.com/panpf/zoomimage) - Multiplatform Image Zoom Component
[![GitHub Repo stars](https://img.shields.io/github/stars/panpf/zoomimage)](https://github.com/panpf/zoomimage)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.panpf.zoomimage/zoomimage-compose)](https://central.sonatype.com/artifact/io.github.panpf.zoomimage/zoomimage-compose)
> Library for zoom images, supported scale, pan, locate, rotation, and super-large image subsampling

[rebugger](https://github.com/theapache64/rebugger) - A recomposition debugger
[![GitHub Repo stars](https://img.shields.io/github/stars/theapache64/rebugger)](https://github.com/theapache64/rebugger)
[![jitpack.io](https://jitpack.io/v/theapache64/rebugger.svg)](https://jitpack.io/#theapache64/rebugger)
> A simple Compose library to print the reason for recomposition in your `Logcat` window.

[Compose WebView Multiplatform](https://github.com/KevinnZou/compose-webview-multiplatform) WebView for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/KevinnZou/compose-webview-multiplatform)](https://github.com/KevinnZou/compose-webview-multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.kevinnzou/compose-webview-multiplatform.svg)](https://search.maven.org/artifact/io.github.kevinnzou/compose-webview-multiplatform)
> A WebView library that offers essential WebView features for Compose Multiplatform. It supports loading URLs and HTML data, evaluating JavaScript, and managing cookies. Currently, it is available for Android, iOS, and Desktop platforms.

[ZoomImage](https://github.com/panpf/zoomimage) Library for zoom images
[![GitHub Repo stars](https://img.shields.io/github/stars/panpf/zoomimage)](https://github.com/panpf/zoomimage)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.panpf.zoomimage/zoomimage-core)](https://search.maven.org/artifact/io.github.panpf.zoomimage/zoomimage-core)
> Library for zoom images, supported Android View, Compose and Compose Multiplatform; supported double-click zoom, One or two fingers gesture zoom, single-finger drag, inertial sliding, positioning, rotation, super-large image subsampling and other functions.

[peekaboo](https://github.com/TEAM-PREAT/peekaboo) - Image Picker Library for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/TEAM-PREAT/peekaboo)](https://img.shields.io/github/stars/TEAM-PREAT/peekaboo)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.team-preat/peekaboo-image-picker)](https://search.maven.org/search?q=g:io.github.team-preat)
> Kotlin Multiplatform library for Compose Multiplatform, designed for seamless integration of an image picker feature in iOS and Android applications.

### 🎨 Graphics
[MOKO Graphics](https://github.com/icerockdev/moko-graphics) - Graphics primitives
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-graphics)](https://github.com/icerockdev/moko-graphics)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/graphics)](https://central.sonatype.com/artifact/dev.icerock.moko/graphics)
> This is a Kotlin Multiplatform library that provides graphics primitives to common code.

[Korim](https://github.com/korlibs/korim) - Imaging utilities
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korim)](https://github.com/korlibs/korim)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.korim/korim)](https://central.sonatype.com/artifact/com.soywiz.korlibs.korim/korim)
> Kotlin cORoutines IMaging, Bitmap and Vector graphics for Multiplatform Kotlin

### 🧩 Service SDK
[Firebase Kotlin SDK](https://github.com/GitLiveApp/firebase-kotlin-sdk) - A Kotlin-first SDK for Firebase
[![GitHub Repo stars](https://img.shields.io/github/stars/GitLiveApp/firebase-kotlin-sdk)](https://github.com/GitLiveApp/firebase-kotlin-sdk)
[![Maven Central](https://img.shields.io/maven-central/v/dev.gitlive/firebase-auth)](https://central.sonatype.com/artifact/dev.gitlive/firebase-auth)
> The Firebase Kotlin SDK is a Kotlin-first SDK for Firebase. It's API is similar to the Firebase Android SDK Kotlin Extensions but also supports multiplatform projects, enabling you to use Firebase directly from your common source targeting iOS, Android or JS.

[openai-kotlin](https://github.com/Aallam/openai-kotlin) - OpenAI SDK
[![GitHub Repo stars](https://img.shields.io/github/stars/Aallam/openai-kotlin)](https://github.com/Aallam/openai-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.aallam.openai/openai-client)](https://central.sonatype.com/artifact/com.aallam.openai/openai-client)
> Kotlin client for [OpenAI's API](https://beta.openai.com/docs/api-reference) with multiplatform and coroutines capabilities.

[Sentry SDK](https://github.com/getsentry/sentry-kotlin-multiplatform) - Sentry Kotlin Multiplatform SDK
[![GitHub Repo stars](https://img.shields.io/github/stars/getsentry/sentry-kotlin-multiplatform)](https://github.com/getsentry/sentry-kotlin-multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/io.sentry/sentry-kotlin-multiplatform)](https://central.sonatype.com/artifact/io.sentry/sentry-kotlin-multiplatform)
> This project is an experimental SDK for Kotlin Multiplatform. This SDK is a wrapper around different platforms such as JVM, Android, iOS, macOS, watchOS, tvOS that can be used on Kotlin Multiplatform.

[VK SDK Kotlin](https://github.com/vksdk/vk-sdk-kotlin) - Unofficial VK SDK
[![GitHub Repo stars](https://img.shields.io/github/stars/vksdk/vk-sdk-kotlin)](https://github.com/vksdk/vk-sdk-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.petersamokhin.vksdk/core)](https://central.sonatype.com/artifact/com.petersamokhin.vksdk/core)
> Create a chat-bot for VK.com in a few lines of code, use the API and forget about the limitations

[bitcoin-kmp](https://github.com/ACINQ/bitcoin-kmp) - Kotlin Multiplatform Bitcoin Library
[![GitHub Repo stars](https://img.shields.io/github/stars/ACINQ/bitcoin-kmp)](https://github.com/ACINQ/bitcoin-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/fr.acinq.bitcoin/bitcoin-kmp)](https://central.sonatype.com/artifact/fr.acinq.bitcoin/bitcoin-kmp)
> This is a simple Kotlin Multiplatform library which implements most of the bitcoin protocol

[MOKO Tensorflow](https://github.com/icerockdev/moko-tensorflow) - Mobile Kotlin TensorFlow
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-tensorflow)](https://github.com/icerockdev/moko-tensorflow)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/tensorflow)](https://central.sonatype.com/artifact/dev.icerock.moko/tensorflow)
> This is a Kotlin MultiPlatform library that provides access to TensorFlow-Lite functionality from common source set.

[qBittorrent](https://github.com/DrewCarlson/qBittorrent-Kotlin) - wrapper for the qBittorrent Web API
[![GitHub Repo stars](https://img.shields.io/github/stars/DrewCarlson/qBittorrent-Kotlin)](https://github.com/DrewCarlson/qBittorrent-Kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/org.drewcarlson/qbittorrent-client)](https://central.sonatype.com/artifact/org.drewcarlson/qbittorrent-client)
> Multiplatform Kotlin wrapper for the qBittorrent Web API using Ktor.

[Cognito-idp](https://github.com/Liftric/cognito-idp) - AWS Cognito Identity Provider
[![GitHub Repo stars](https://img.shields.io/github/stars/Liftric/cognito-idp)](https://github.com/Liftric/cognito-idp)
[![Maven Central](https://img.shields.io/maven-central/v/com.liftric/cognito-idp)](https://central.sonatype.com/artifact/com.liftric/cognito-idp)
> Lightweight AWS Cognito Identity Provider client for Kotlin Multiplatform and Typescript projects.

[TMDb API](https://github.com/MoviebaseApp/tmdb-api) - access to TMDb API
[![GitHub Repo stars](https://img.shields.io/github/stars/MoviebaseApp/tmdb-api)](https://github.com/MoviebaseApp/tmdb-api)
[![Maven Central](https://img.shields.io/maven-central/v/app.moviebase/tmdb-api)](https://central.sonatype.com/artifact/app.moviebase/tmdb-api)
> This library gives access to TMDb API version 3 and 4 for mobile, desktop, and web applications. It supports Swift, Kotlin, and JavaScript by setting up as a Kotlin Multiplatform project.

[Growth Book SDK](https://github.com/growthbook/growthbook-kotlin) - GrowthBook Kotlin SDK
[![GitHub Repo stars](https://img.shields.io/github/stars/growthbook/growthbook-kotlin)](https://github.com/growthbook/growthbook-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.growthbook.sdk/GrowthBook)](https://central.sonatype.com/artifact/io.growthbook.sdk/GrowthBook)
> GrowthBook is an open-source platform for feature flagging and a/b testing built for data teams, engineers, and product managers. It's great whether you're looking to just analyze experiment results or looking to make it easier to deploy code.

[ConfigCat](https://github.com/configcat/kotlin-sdk) - Kotlin Multiplatform SDK for ConfigCat
[![GitHub Repo stars](https://img.shields.io/github/stars/configcat/kotlin-sdk)](https://github.com/configcat/kotlin-sdk)
[![Maven Central](https://img.shields.io/maven-central/v/com.configcat/configcat-kotlin-client)](https://central.sonatype.com/artifact/com.configcat/configcat-kotlin-client)
> Kotlin Multiplatform SDK for ConfigCat, a feature flag, feature toggle, and configuration management service. That lets you launch new features and change your software configuration remotely without actually (re)deploying code. ConfigCat even helps you do controlled roll-outs like canary releases and blue-green deployments.

[Solana-kmp](https://github.com/metaplex-foundation/solana-kmp) - Kotlin Multiplatform SDK for Kotlin
[![GitHub Repo stars](https://img.shields.io/github/stars/metaplex-foundation/solana-kmp)](https://github.com/metaplex-foundation/solana-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/foundation.metaplex/solana)](https://central.sonatype.com/artifact/foundation.metaplex/solana)
> Solana-KMP leverages the power of Kotlin Multiplatform to enable developers to work with the Solana blockchain across various platforms including Android, iOS, and the JVM.

### 🧮 Arithmetic
[KBigNum](https://github.com/korlibs/kbignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/kbignum)](https://github.com/korlibs/kbignum)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.kbignum/kbignum)](https://central.sonatype.com/artifact/com.soywiz.korlibs.kbignum/kbignum)
> Library for Big Numbers

[BigNum](https://github.com/ionspin/kotlin-multiplatform-bignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/ionspin/kotlin-multiplatform-bignum)](https://github.com/ionspin/kotlin-multiplatform-bignum)
[![Maven Central](https://img.shields.io/maven-central/v/com.ionspin.kotlin/bignum)](https://central.sonatype.com/artifact/com.ionspin.kotlin/bignum)
> Kotlin Multiplatform BigNum library is a pure kotlin implementation of arbitrary precision arithmetic operations. It follows the same approach as Kotlin does on JVM to keep the interface familiar.

### 🛢 Resources
[MOKO Resources](https://github.com/icerockdev/moko-resources) - System resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-resources)](https://github.com/icerockdev/moko-resources)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/resources)](https://central.sonatype.com/artifact/dev.icerock.moko/resources)
> This is a Kotlin Multiplatform library that provides access to the resources on iOS & Android with the support of the default system localization.

[Kotlinx-Resources](https://github.com/goncalossilva/kotlinx-resources) - text resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/goncalossilva/kotlinx-resources)](https://github.com/goncalossilva/kotlinx-resources)
[![Maven Central](https://img.shields.io/maven-central/v/com.goncalossilva/resources)](https://central.sonatype.com/artifact/com.goncalossilva/resources)
> Kotlin Multiplatform (KMP) plugin and library that add support for reading resources in tests.
> The plugin and a library work in tandem to provide a unified API across platforms for reading resources from each source set's resources folder.

### 🔧 Utils
[UUID](https://github.com/benasher44/uuid) - UUID generator
[![GitHub Repo stars](https://img.shields.io/github/stars/benasher44/uuid)](https://github.com/benasher44/uuid)
[![Maven Central](https://img.shields.io/maven-central/v/com.benasher44/uuid)](https://central.sonatype.com/artifact/com.benasher44/uuid)
> Kotlin Multiplatform UUID generator

[Uri KMP](https://github.com/eygraber/uri-kmp) - A library for working with URIs in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/eygraber/uri-kmp)](https://github.com/eygraber/uri-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/com.eygraber/uri-kmp)](https://central.sonatype.com/artifact/com.eygraber/uri-kmp)
> A library for working with URIs in Kotlin Multiplatform

[Diglol Encoding](https://github.com/diglol/encoding) - Common encodings for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/encoding)](https://github.com/diglol/encoding)
[![Maven Central](https://img.shields.io/maven-central/v/com.diglol.encoding/encoding)](https://central.sonatype.com/artifact/com.diglol.encoding/encoding)
> Diglol Encoding provides Hex/Base16, Base32, Base64 encodings for Kotlin Multiplatform.

[Diglol Id](https://github.com/diglol/id) - A global Id generator for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/id)](https://github.com/diglol/id)
[![Maven Central](https://img.shields.io/maven-central/v/com.diglol.id/id)](https://central.sonatype.com/artifact/com.diglol.id/id)
> A global Id generator for Kotlin Multiplatform. It modifies the timestamp to 5 bytes based on Xid.

[ByteBuffer](https://github.com/DitchOoM/buffer) - Kotlin Multiplatform bytebuffer/byte[] wrapper
[![GitHub Repo stars](https://img.shields.io/github/stars/DitchOoM/buffer)](https://github.com/DitchOoM/buffer)
[![Maven Central](https://img.shields.io/maven-central/v/com.ditchoom/buffer)](https://central.sonatype.com/artifact/com.ditchoom/buffer)
> A kotlin multiplatform library that allows you to allocate and modify byte[] natively using an API similar to Java's ByteBuffer API.

[zipline](https://github.com/cashapp/zipline) - Run Kotlin/JS libraries in Kotlin/JVM and Kotlin/Native programs
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/zipline)](https://github.com/cashapp/zipline)
[![Maven Central](https://img.shields.io/maven-central/v/app.cash.zipline/zipline)](https://central.sonatype.com/artifact/app.cash.zipline/zipline)
> Zipline works by embedding the QuickJS JavaScript engine in your Kotlin/JVM or Kotlin/Native program. It's a small and fast JavaScript engine that's well-suited to embedding in applications.

[Kase64](https://github.com/saschpe/kase64) - Base64 encoder/decoder
[![GitHub Repo stars](https://img.shields.io/github/stars/saschpe/kase64)](https://github.com/saschpe/kase64)
[![Maven Central](https://img.shields.io/maven-central/v/de.peilicke.sascha/kase64)](https://central.sonatype.com/artifact/de.peilicke.sascha/kase64)
> Base64 encoder/decoder for Kotlin/Multiplatform. Supports Android, iOS, JavaScript and plain JVM environments.

[Colormath](https://github.com/ajalt/colormath) - Multiplatform Kotlin color conversion and manipulation
[![GitHub Repo stars](https://img.shields.io/github/stars/ajalt/colormath)](https://github.com/ajalt/colormath)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.ajalt/colormath)](https://central.sonatype.com/artifact/com.github.ajalt/colormath)
> Colormath is a Kotlin Multiplatform library for color manipulation and conversion.

[GEOK](https://github.com/piruin/geok) - Kotlin geometry library
[![GitHub Repo stars](https://img.shields.io/github/stars/piruin/geok)](https://github.com/piruin/geok)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.piruin/geok)](https://central.sonatype.com/artifact/io.github.piruin/geok)
> Small geometry library for Java and Kotlin. Contains useful basic utilities that require on most application.

[fluid-currency](https://github.com/fluidsonic/fluid-currency) - currency library
[![GitHub Repo stars](https://img.shields.io/github/stars/fluidsonic/fluid-currency)](https://github.com/fluidsonic/fluid-currency)
[![Maven Central](https://img.shields.io/maven-central/v/io.fluidsonic.currency/fluid-currency)](https://central.sonatype.com/artifact/io.fluidsonic.currency/fluid-currency)
> Kotlin multiplatform currency library.

[fluid-country](https://github.com/fluidsonic/fluid-country) - country library
[![GitHub Repo stars](https://img.shields.io/github/stars/fluidsonic/fluid-country)](https://github.com/fluidsonic/fluid-country)
[![Maven Central](https://img.shields.io/maven-central/v/io.fluidsonic.country/fluid-country)](https://central.sonatype.com/artifact/io.fluidsonic.country/fluid-country)
> Kotlin multiplatform country library.

[Kmem](https://github.com/korlibs/kmem) - Data primitives
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/kmem)](https://github.com/korlibs/kmem)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.kmem/kmem)](https://central.sonatype.com/artifact/com.soywiz.korlibs.kmem/kmem)
> Kmem is bit, array and fast memory utilities library for multiplatform Kotlin

[KaseChange](https://github.com/pearxteam/kasechange) - convert strings between various case formats
[![GitHub Repo stars](https://img.shields.io/github/stars/pearxteam/kasechange)](https://github.com/pearxteam/kasechange)
[![Maven Central](https://img.shields.io/maven-central/v/net.pearx.kasechange/kasechange)](https://central.sonatype.com/artifact/net.pearx.kasechange/kasechange)
> Multiplatform Kotlin library to convert strings between various case formats including Camel Case, Snake Case, Pascal Case and Kebab Case

[FuzzyWuzzy-Kotlin](https://github.com/willowtreeapps/fuzzywuzzy-kotlin) - Fuzzy string matching for Kotlin
[![GitHub Repo stars](https://img.shields.io/github/stars/willowtreeapps/fuzzywuzzy-kotlin)](https://github.com/willowtreeapps/fuzzywuzzy-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.willowtreeapps/fuzzywuzzy-kotlin)](https://central.sonatype.com/artifact/com.willowtreeapps/fuzzywuzzy-kotlin)
> Useful for selecting the closest matching string from a collection of strings. Various algorithms are available.

[kotlin-semver](https://github.com/z4kn4fein/kotlin-semver) - Semantic versioning
[![GitHub Repo stars](https://img.shields.io/github/stars/z4kn4fein/kotlin-semver)](https://github.com/z4kn4fein/kotlin-semver)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.z4kn4fein/semver)](https://central.sonatype.com/artifact/io.github.z4kn4fein/semver)
> Semantic Versioning library for Kotlin Multiplatform.

[Kontrol](https://github.com/chopyourbrain/kontrol) - Debug menu
[![GitHub Repo stars](https://img.shields.io/github/stars/chopyourbrain/kontrol)](https://github.com/chopyourbrain/kontrol)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.chopyourbrain/kontrol)](https://central.sonatype.com/artifact/io.github.chopyourbrain/kontrol/)
> Kotlin Multiplatform library for creating a debugging menu.

[Korau](https://github.com/korlibs/korau) - Kotlin cORoutines AUdio
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korau)](https://github.com/korlibs/korau)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.korau/korau)](https://central.sonatype.com/artifact/com.soywiz.korlibs.korau/korau)
> Pure Kotlin WAV, MP3 and OGG vorbis decoders

[Kim](https://github.com/Ashampoo/kim) - Kotlin Image Metadata
[![GitHub Repo stars](https://img.shields.io/github/stars/Ashampoo/kim)](https://github.com/Ashampoo/kim)
[![Maven Central](https://img.shields.io/maven-central/v/com.ashampoo/kim)](https://central.sonatype.com/artifact/com.ashampoo/kim)
> Kotlin Multiplatform library for reading and writing image metadata

[XMP Core for Kotlin Multiplatform](https://github.com/Ashampoo/xmpcore) - Kotlin Multiplatform port of Adobe's XMP SDK
[![GitHub Repo stars](https://img.shields.io/github/stars/Ashampoo/xmpcore)](https://github.com/Ashampoo/xmpcore)
[![Maven Central](https://img.shields.io/maven-central/v/com.ashampoo/xmpcore)](https://central.sonatype.com/artifact/com.ashampoo/xmpcore)
> Kotlin Multiplatform library for reading and writing XMP (Extensible Metadata Platform) files

[Highlights](https://github.com/SnipMeDev/Highlights) - Kotlin Multiplatform syntax highlighting engine
[![GitHub Repo stars](https://img.shields.io/github/stars/SnipMeDev/Highlights)](https://github.com/SnipMeDev/Highlights)
[![Maven Central](https://img.shields.io/maven-central/v/dev.snipme/highlights)](https://central.sonatype.com/artifact/dev.snipme/highlights)
 > Kotlin Multiplatform library for analyzing and coloring syntax of code string

[BlahBlah](https://github.com/getspherelabs/blahblah)  - Blah-Blah generates fake data for robust testing and development
[![GitHub Repo stars](https://img.shields.io/github/stars/getspherelabs/blahblah)](https://github.com/getspherelabs/blahblah)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.behzodhalil/blahblah-fake)](https://central.sonatype.com/artifact/io.github.behzodhalil/blahblah-fake)
> Blah-Blah generates fake data for robust testing and development

[KMPUtils](https://github.com/respawn-app/KMMUtils) - Kotlin STL Extensions & Utils
[![GitHub Repo stars](https://img.shields.io/github/stars/respawn-app/KMMUtils)](https://github.com/respawn-app/KMMUtils)
[![Maven Central](https://img.shields.io/maven-central/v/pro.respawn.kmmutils/core)](https://central.sonatype.com/namespace/pro.respawn.kmmutils)
> KMPUtils is a collection of everything missing from the Kotlin Multiplatform Standard Library.

[RSSParser](https://github.com/prof18/RSS-Parser) - A Kotlin Multiplatform library to parse a RSS Feed
[![GitHub Repo stars](https://img.shields.io/github/stars/prof18/RSS-Parser)](https://github.com/prof18/RSS-Parser)
[![Maven Central](https://img.shields.io/maven-central/v/com.prof18.rssparser/rssparser)](https://central.sonatype.com/namespace/com.prof18.rssparser)
> RSS Parser is a Kotlin Multiplatform library for parsing RSS and Atom feeds. It supports Android, iOS, and the JVM.

## Suggest your an idea
[What libraries are you missing?](https://github.com/terrakok/kmm-awesome/discussions/7)

## Authors
https://github.com/terrakok/kmm-awesome/graphs/contributors

## Contribution guide
Feel free to contribute. Follow common style and welcome! :)

## License
```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```