# Awesome Android Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of the best libraries, tools, frameworks, and resources for modern Android development with Kotlin and Jetpack Compose in 2026. Covers everything from UI and architecture to testing, CI/CD, and community, with a focus on production-ready, actively maintained projects aligned with current Android Jetpack, Coroutines, Material 3, and Kotlin Multiplatform best practices.

<div align="center">

<a href="https://extensionbooster.net">
  <img src="https://extensionbooster.net/logo.webp" alt="Extension Booster" width="150" />
</a>

<h3>💎 &nbsp;DIAMOND SPONSOR&nbsp; 💎</h3>

<p>
  <b><a href="https://extensionbooster.net">Extension Booster</a></b><br/>
  <sub>The growth platform for extension and app developers</sub>
</p>

<p>
  <sub>⭐ Real reviews &nbsp;·&nbsp; 📊 Cross-marketplace analytics (Chrome · Edge · Android · Workspace) &nbsp;·&nbsp; 🔁 Manifest V2 to V3 converter</sub>
</p>

<a href="https://extensionbooster.net"><b>🚀 Start free at extensionbooster.net →</b></a>

</div>

## Contents

- [Official Resources](#official-resources)
- [Languages](#languages)
- [UI and Jetpack Compose](#ui-and-jetpack-compose)
- [Architecture](#architecture)
- [Dependency Injection](#dependency-injection)
- [Networking](#networking)
- [Asynchronous and Reactive](#asynchronous-and-reactive)
- [Data and Persistence](#data-and-persistence)
- [Image Loading](#image-loading)
- [Navigation](#navigation)
- [Testing](#testing)
- [Build and Tooling](#build-and-tooling)
- [Debugging and Profiling](#debugging-and-profiling)
- [CI/CD and Distribution](#cicd-and-distribution)
- [Analytics and Crash Reporting](#analytics-and-crash-reporting)
- [Sample Open-Source Apps](#sample-open-source-apps)
- [Kotlin Multiplatform and Cross-Platform](#kotlin-multiplatform-and-cross-platform)
- [Communities, Newsletters, and Podcasts](#communities-newsletters-and-podcasts)
- [Serialization](#serialization)
- [Tools and Utilities](#tools-and-utilities)
- [Contributing](#contributing)
- [License](#license)

---

## Official Resources

- [Android Developers](https://developer.android.com) - The official home for Android documentation, API references, guides, and codelabs.
- [Android Developers Blog](https://android-developers.googleblog.com) - Official blog covering new platform releases, library updates, and engineering deep-dives from Google.
- [Android Jetpack](https://developer.android.com/jetpack) - Suite of libraries, tools, and guidance from Google to build high-quality Android apps following best practices.
- [AndroidX Releases](https://developer.android.com/jetpack/androidx/versions) - Canonical changelog for all AndroidX library versions, updated continuously.
- [Android Codelabs](https://developer.android.com/get-started/codelabs) - Hands-on, self-paced coding tutorials covering Compose, architecture, testing, and more.
- [Android Studio](https://developer.android.com/studio) - The official IDE for Android development, now including Gemini AI assistance.
- [Now in Android (series)](https://developer.android.com/series/now-in-android) - Google's official video and article series covering the latest in Android development, released bi-weekly.
- [Kotlin for Android](https://developer.android.com/kotlin) - Official Android documentation for Kotlin, including idiomatic patterns, coroutines, and KTX extensions.

---

## Languages

### Kotlin

- [Kotlin](https://kotlinlang.org) - The official language for Android development: concise, null-safe, and fully interoperable with Java.
- [Kotlin Documentation](https://kotlinlang.org/docs/home.html) - Official language reference covering syntax, standard library, and platform targets.
- [Kotlin GitHub](https://github.com/JetBrains/kotlin) - Open-source repository for the Kotlin compiler and standard library maintained by JetBrains.
- [KTX Extensions](https://developer.android.com/kotlin/ktx) - Android KTX provides Kotlin extensions for core Android libraries, reducing boilerplate throughout the Jetpack suite.

### Kotlin Coroutines

- [Kotlinx Coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Official Kotlin coroutines library providing structured concurrency, async/await, and Flow.
- [Coroutines Guide](https://kotlinlang.org/docs/coroutines-guide.html) - Comprehensive official documentation for coroutines, including channels, flows, and testing utilities.

### Kotlin Multiplatform

- [Kotlin Multiplatform](https://kotlinlang.org/multiplatform/) - JetBrains technology for sharing Kotlin business logic across Android, iOS, desktop, and web.
- [KMP Quickstart](https://kotlinlang.org/docs/multiplatform/quickstart.html) - Official getting-started guide for Kotlin Multiplatform projects.

---

## UI and Jetpack Compose

- [Accompanist](https://github.com/google/accompanist) - Google's extension library collection for Jetpack Compose, filling gaps while upstream Compose catches up (some modules now deprecated in favour of built-in APIs).
- [Coil Compose](https://github.com/coil-kt/coil) - Kotlin-first, coroutine-backed image loading library with first-class Jetpack Compose and KMP support.
- [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) - JetBrains framework for sharing Compose UI across Android, iOS (stable since 1.8), desktop, and web.
- [Compose Samples](https://github.com/android/compose-samples) - Official Google repository of production-quality Compose sample apps covering a broad range of use cases.
- [Jetpack Compose](https://developer.android.com/compose) - Google's modern declarative UI toolkit for Android, built in Kotlin with a reactive programming model.
- [Landscapist](https://github.com/skydoves/landscapist) - Pluggable Compose image loading library with adapters for Coil, Glide, and Fresco, plus transition effects.
- [Lottie Android](https://github.com/airbnb/lottie-android) - Airbnb library that renders Adobe After Effects animations natively on Android with Compose support.
- [Material 3 (Material You)](https://m3.material.io) - Google's third-generation design system with dynamic colour, adaptive layouts, and Compose components.
- [Material 3 Compose](https://developer.android.com/develop/ui/compose/designsystems/material3) - Official Jetpack Compose implementation of Material 3 components and theming.
- [Showkase](https://github.com/airbnb/Showkase) - Annotation-processor library from Airbnb for cataloguing and browsing Compose UI components during development.

---

## Architecture

- [Guide to App Architecture](https://developer.android.com/topic/architecture) - Google's official opinionated guide covering UI, domain, and data layers with unidirectional data flow.
- [Now in Android (architecture reference)](https://github.com/android/nowinandroid) - Fully functional, fully modularised production app from Google demonstrating recommended architecture with Compose, Hilt, and Flow.
- [Architecture Components](https://developer.android.com/topic/libraries/architecture) - Jetpack suite covering ViewModel, LiveData, Room, WorkManager, and more for robust app architecture.
- [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Jetpack component for managing UI-related state that survives configuration changes.
- [Lifecycle](https://developer.android.com/topic/libraries/architecture/lifecycle) - Jetpack library for observing Android lifecycle events in a decoupled, observable way.
- [Paging 3](https://developer.android.com/topic/libraries/architecture/paging/v3-overview) - Jetpack library for loading and displaying large datasets incrementally from network or database sources.
- [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager) - Jetpack library for deferrable, guaranteed background work that respects battery and doze constraints.

---

## Dependency Injection

- [Dagger](https://github.com/google/dagger) - Google's compile-time dependency injection framework for Java and Android, the foundation for Hilt.
- [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) - Google's recommended DI solution for Android, built on Dagger with standardised component hierarchy and reduced boilerplate.
- [Hilt GitHub](https://github.com/google/dagger/tree/master/java/dagger/hilt) - Source for Hilt within the Dagger monorepo.
- [Koin](https://github.com/InsertKoinIO/koin) - Lightweight, annotation-optional Kotlin DI framework that works on Android, KMP, and Ktor without code generation.
- [Koin Annotations](https://github.com/InsertKoinIO/koin-annotations) - Optional KSP-based annotation processing layer for Koin that enables Hilt-like declarative component definition.

---

## Networking

- [Apollo Kotlin](https://github.com/apollographql/apollo-kotlin) - Strongly-typed, caching GraphQL client for Android and Kotlin Multiplatform with code generation.
- [Ktor Client](https://github.com/ktorio/ktor) - JetBrains HTTP client written in Kotlin, supporting coroutines and multiple engines including OkHttp and CIO.
- [OkHttp](https://github.com/square/okhttp) - Square's efficient HTTP client for Android and Java with connection pooling, GZIP, and response caching.
- [Retrofit](https://github.com/square/retrofit) - Square's type-safe HTTP client for Android that turns REST APIs into Kotlin/Java interfaces via annotations.
- [Ktorfit](https://github.com/Foso/Ktorfit) - KSP-based Retrofit-inspired HTTP client for Kotlin Multiplatform built on top of Ktor.

---

## Asynchronous and Reactive

- [Kotlin Flow](https://kotlinlang.org/docs/flow.html) - Kotlin's cold asynchronous stream abstraction built on coroutines, the recommended reactive primitive for Android.
- [Kotlinx Coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Official coroutines library providing structured concurrency, dispatchers, channels, and StateFlow/SharedFlow.
- [RxAndroid](https://github.com/ReactiveX/RxAndroid) - Android-specific bindings for RxJava, including a main-thread scheduler for reactive Android development.
- [RxJava](https://github.com/ReactiveX/RxJava) - Reactive Extensions for the JVM: composing asynchronous event-based sequences with a rich operator library.

---

## Data and Persistence

- [DataStore](https://developer.android.com/topic/libraries/architecture/datastore) - Jetpack library for asynchronous, transactional key-value and typed (Proto) persistent storage using coroutines.
- [ObjectBox](https://github.com/objectbox/objectbox-java) - High-performance NoSQL object database for Android with Kotlin support and a Kotlin Multiplatform edition.
- [Realm Kotlin](https://github.com/realm/realm-kotlin) - Mobile-first object database for Kotlin and KMP with reactive queries and optional Atlas Device Sync.
- [Room](https://developer.android.com/training/data-storage/room) - Jetpack abstraction layer over SQLite providing compile-time SQL verification, coroutine support, and Kotlin Flow integration.
- [SQLDelight](https://github.com/cashapp/sqldelight) - CashApp library that generates type-safe Kotlin APIs from SQL files, with first-class Kotlin Multiplatform support.

---

## Image Loading

- [Coil](https://github.com/coil-kt/coil) - Coroutine Image Loader: Kotlin-first, lightweight image loading for Android and KMP with Compose AsyncImage support.
- [Fresco](https://github.com/facebook/fresco) - Facebook's Android image loading library with a specialised memory architecture for efficient bitmap management.
- [Glide](https://github.com/bumptech/glide) - Fast, battle-tested image loading and caching library for Android focused on smooth scrolling performance.
- [Landscapist](https://github.com/skydoves/landscapist) - Pluggable Compose wrapper for Coil, Glide, and Fresco with built-in animations and placeholder support.

---

## Navigation

- [Compose Destinations](https://github.com/raamcosta/compose-destinations) - KSP annotation-processing library for type-safe Jetpack Compose Navigation with zero boilerplate routing.
- [Jetpack Navigation Compose](https://developer.android.com/guide/navigation/navigation-compose) - Official Jetpack Navigation component adapted for Jetpack Compose with a composable-first API.
- [Voyager](https://github.com/adrielcafe/voyager) - Pragmatic Compose Multiplatform navigation library with screen model support, tab navigation, and nested stacks.

---

## Testing

- [AndroidX Test](https://developer.android.com/training/testing/instrumented-tests) - Official suite of instrumented testing APIs including ActivityScenario, Espresso, and UIAutomator.
- [Espresso](https://developer.android.com/training/testing/espresso) - Google's UI testing framework for Android instrumented tests with a synchronisation model that eliminates manual sleeps.
- [JUnit 5 (Jupiter)](https://github.com/junit-team/junit5) - Modern JUnit platform with parameterised tests, extensions, and improved Kotlin ergonomics for Android unit tests.
- [Maestro](https://github.com/mobile-dev-inc/Maestro) - YAML-based, flakiness-tolerant E2E mobile UI testing tool for Android and iOS without writing code.
- [MockK](https://github.com/mockk/mockk) - Kotlin-first mocking library with coroutine support, relaxed mocks, and a clean DSL.
- [Robolectric](https://github.com/robolectric/robolectric) - Industry-standard framework running Android unit tests on the JVM without an emulator, dramatically reducing feedback time.
- [Turbine](https://github.com/cashapp/turbine) - Small, focused testing library for Kotlin Flow from CashApp, making it easy to assert emitted values.
- [Compose UI Testing](https://developer.android.com/develop/ui/compose/testing) - Official Compose test APIs for finding, interacting with, and asserting state on composables in unit and instrumented tests.

---

## Build and Tooling

- [Android Gradle Plugin](https://developer.android.com/build) - Official Gradle plugin for building, testing, and packaging Android apps and libraries.
- [Gradle Version Catalogs](https://docs.gradle.org/current/userguide/version_catalogs.html) - Gradle's built-in TOML-based dependency management system providing a single source of truth for library versions.
- [KSP (Kotlin Symbol Processing)](https://github.com/google/ksp) - Google's fast Kotlin-first replacement for KAPT, used by Room, Hilt, Compose Destinations, and many modern libraries.
- [Spotless](https://github.com/diffplug/spotless) - Gradle plugin for enforcing code formatting rules across Kotlin, Java, and other languages in a single configuration.
- [Detekt](https://github.com/detekt/detekt) - Static analysis tool for Kotlin with configurable rules, Compose-specific rule sets, and Gradle integration.
- [gradle-doctor](https://github.com/runningcode/gradle-doctor) - Gradle plugin that diagnoses build performance problems and provides actionable recommendations.

---

## Debugging and Profiling

- [Android Studio Profiler](https://developer.android.com/studio/profile) - Built-in IDE tool for profiling CPU, memory, network, and energy usage in real time.
- [Chucker](https://github.com/ChuckerTeam/chucker) - On-device OkHttp network inspector that displays HTTP traffic in a notification and shareable UI.
- [Flipper](https://github.com/facebook/flipper) - Facebook's extensible desktop debugging platform for Android and iOS with plugins for network, layout, databases, and more.
- [Layout Inspector](https://developer.android.com/studio/debug/layout-inspector) - Android Studio tool for inspecting the live view hierarchy and Compose semantics tree on a running device.
- [LeakCanary](https://github.com/square/leakcanary) - Square's automatic memory leak detection library that notifies developers of heap leaks directly on-device.

---

## CI/CD and Distribution

- [Fastlane](https://github.com/fastlane/fastlane) - Open-source automation platform for building, testing, and releasing Android and iOS apps with a rich plugin ecosystem.
- [Firebase App Distribution](https://firebase.google.com/docs/app-distribution) - Google service for distributing pre-release Android and iOS builds to testers with simple setup and Firebase Console integration.
- [GitHub Actions for Android](https://github.com/actions/setup-java) - Community and official GitHub Actions workflows for building, testing, and signing Android apps on CI.
- [Gradle Play Publisher](https://github.com/Triple-T/gradle-play-publisher) - Unofficial Gradle plugin for automating App Bundle and APK uploads plus Play Store listing updates.

---

## Analytics and Crash Reporting

- [Firebase Analytics](https://firebase.google.com/docs/analytics) - Google's free app measurement solution providing event-based analytics with deep Firebase and Google Ads integration.
- [Firebase Crashlytics](https://firebase.google.com/docs/crashlytics) - Lightweight, real-time crash reporter from Google that aggregates issues and integrates with Firebase Analytics.
- [Sentry for Android](https://github.com/getsentry/sentry-java) - Open-source crash reporting and performance monitoring SDK with breadcrumbs, traces, and two-way Jira/GitHub integration.
- [Datadog Android SDK](https://github.com/DataDog/dd-sdk-android) - Datadog's Android SDK for mobile RUM (Real User Monitoring), log collection, and distributed tracing.

---

## Sample Open-Source Apps

- [DroidKaigi Conference App 2025](https://github.com/DroidKaigi/conference-app-2025) - Official app for the DroidKaigi 2025 Android conference, showcasing KMP, Compose, and modular architecture.
- [Now in Android](https://github.com/android/nowinandroid) - Google's flagship reference app: fully modularised, Compose-only, using Hilt, Room, DataStore, and Navigation.
- [Pokedex Compose](https://github.com/skydoves/pokedex-compose) - MVVM sample demonstrating Compose, Hilt, Coroutines, Flow, Room, and Retrofit with offline-first design.
- [Sunflower](https://github.com/android/sunflower) - Google gardening app illustrating migration from Views to Jetpack Compose, using Hilt, Room, and Navigation.
- [Tivi](https://github.com/chrisbanes/tivi) - TV tracking app that reached 1.0 after 9 years; a comprehensive showcase of KMP, Compose Multiplatform, and SQLDelight.

---

## Kotlin Multiplatform and Cross-Platform

- [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) - JetBrains UI framework sharing Compose code across Android, iOS (stable), desktop, and web (beta).
- [KMP Libraries Catalogue](https://kotlinlang.org/docs/multiplatform-introduce-your-team.html) - Official JetBrains guide for introducing KMP to teams, covering shared code strategy and tooling.
- [Kotlin Multiplatform](https://kotlinlang.org/multiplatform/) - Official landing page for KMP with quickstarts, case studies, and library compatibility information.
- [Ktor (KMP)](https://github.com/ktorio/ktor) - JetBrains HTTP framework usable as both a server and client across all KMP targets.
- [SQLDelight (KMP)](https://github.com/cashapp/sqldelight) - SQL-first type-safe database library with drivers for Android, iOS, JVM, and JS.
- [Multiplatform Settings](https://github.com/russhwolf/multiplatform-settings) - KMP library for persisting simple key-value data on Android (SharedPreferences), iOS (NSUserDefaults), and other targets.
- [Koin (KMP)](https://github.com/InsertKoinIO/koin) - DI framework with official KMP support, enabling shared module definitions across Android and iOS.

---

## Communities, Newsletters, and Podcasts

### Newsletters

- [Android Weekly](https://androidweekly.net) - Free weekly newsletter curating articles, tutorials, screencasts, and job listings from the Android community since 2011.
- [Kotlin Weekly](https://kotlinweekly.net) - Weekly digest of Kotlin news, library releases, articles, and community highlights distributed to 20k+ developers.

### Podcasts

- [Android Developers Backstage](https://adbackstage.libsyn.com) - Official Google podcast hosted by Android platform engineers covering deep technical topics and team interviews.
- [Fragmented Podcast](https://fragmentedpodcast.com) - Long-running Android developer podcast now focused on AI-assisted development workflows and practical engineering.
- [Talking Kotlin](https://talkingkotlin.com) - JetBrains-affiliated podcast covering Kotlin language features, libraries, and community projects with expert guests.

### Communities

- [Android Dev Reddit (r/androiddev)](https://www.reddit.com/r/androiddev) - Active developer community for discussing Android libraries, architecture decisions, and career topics.
- [Kotlin Slack](https://kotlinlang.org/community/) - Official Kotlin community Slack workspace with channels for Android, KMP, Compose, and coroutines.
- [Android Study Group](https://androidstudygroup.github.io) - Global community study group with reading lists and conference resources for Android developers.

---

## Serialization

Libraries for JSON, Protocol Buffers, and type-safe data serialization.

- [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - Kotlin's official multiplatform, reflectionless serialization library with compiler-plugin support for JSON, Protobuf, CBOR, and more.
- [Moshi](https://github.com/square/moshi) - Square's modern JSON library for Kotlin and Java with Kotlin codegen and a small, fast core.
- [Gson](https://github.com/google/gson) - Google's long-established Java library for converting Java and Kotlin objects to and from JSON.
- [Wire](https://github.com/square/wire) - Square's lightweight Protocol Buffers and gRPC implementation for Kotlin, Java, and Android.

---

## Tools and Utilities

- [ADB (Android Debug Bridge)](https://developer.android.com/tools/adb) - Official command-line tool for communicating with Android devices: installing APKs, capturing logs, and shell access.
- [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/) - Web-based tool for generating launcher icons, notification icons, and other Android asset variants.
- [Figma (Material 3 Kit)](https://m3.material.io/foundations/design-tokens/overview) - Material 3 design kit and token system, the authoritative design source for Android UI work.
- [scrcpy](https://github.com/Genymobile/scrcpy) - Open-source tool for displaying and controlling Android devices over USB or TCP/IP with very low latency.
- [sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser) - Cross-platform GUI tool for inspecting and editing SQLite databases produced by Android apps.
- [pidcat](https://github.com/JakeWharton/pidcat) - Jake Wharton's coloured logcat filter that shows only log messages for a specific running app process.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding, removing, or updating entries.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Released under the [MIT License](LICENSE). Copyright (c) 2026 Quang Phan.

---

<p align="center">
  <sub>Curated for developers · Powered by <a href="https://extensionbooster.net"><b>Extension Booster</b></a>, grow your apps with real reviews and cross-marketplace analytics.</sub>
</p>
