
<h1 align="center">DisneyCompose</h1>
<p align="center">  
A demo Disney app using compose and Hilt based on modern Android tech-stacks and MVVM architecture. Fetching data from the network and integrating persisted data in the database via repository pattern.<br> Declarative UI version of the <a href="https://github.com/skydoves/DisneyMotions" target="_blank"> DisneyMotions </a> using compose.
</p>

## Task
<p align="center">
Add rating bar to each details screen. Rating bar should be 1-5 stars.
Default value is 0, and whenever user selects something it should fall into the range of 1-5.
Rating bar should be located below description and have margins:
Top: 18dp
Horizontal: 25dp
Bottom: 18dp
View should be centered horizontally.
When user selects rating it should be saved to the database.
Icons for task are: 
Selected: ic_star_full.xml
Not selected: ic_star_empty.xml
</p>

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
  <a href="https://android-arsenal.com/api?level=21"><img alt="API" src="https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat"/></a>
  <a href="https://github.com/skydoves/DisneyCompose/actions"><img alt="Build Status" src="https://github.com/skydoves/DisneyCompose/workflows/Android%20CI/badge.svg"/></a>
  <a href="https://proandroiddev.com/exploring-jetpack-compose-with-dagger-hilt-and-viewmodels-3e0ca939daa7"><img alt="Medium" src="https://skydoves.github.io/badges/Story-Medium.svg"/></a>
  <a href="https://github.com/skydoves"><img alt="Profile" src="https://skydoves.github.io/badges/skydoves.svg"/></a> 
</p>

## Tech stack & Open-source libraries
- Minimum SDK level 21
- 100% [Kotlin](https://kotlinlang.org/) based + [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) + [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/) for asynchronous.
- Hilt for dependency injection.
- JetPack
  - Compose - A modern toolkit for building native Android UI.
  - Lifecycle - dispose observing data when lifecycle state changes.
  - ViewModel - UI related data holder, lifecycle aware.
  - Room Persistence - construct database.
  - App Startup - Provides a straightforward, performant way to initialize components at application startup.
- Architecture
  - MVVM Architecture (Declarative View - ViewModel - Model)
  - Repository pattern
- Material Design & Animations
- [Accompanist](https://github.com/google/accompanist) - A collection of extension libraries for Jetpack Compose.
- [Landscapist](https://github.com/skydoves/landscapist) - Jetpack Compose image loading library with shimmer & circular reveal animations.
- [Orchestra-Balloon](https://github.com/skydoves/orchestra) - Jetpack Compose tooltips library.
- [Retrofit2 & OkHttp3](https://github.com/square/retrofit) - construct the REST APIs and paging network data.
- [Sandwich](https://github.com/skydoves/Sandwich) - construct lightweight http API response and handling error responses.
- [WhatIf](https://github.com/skydoves/whatif) - checking nullable object and empty collections more fluently.
- [Balloon](https://github.com/skydoves/balloon) -  A lightweight popup like tooltips, fully customizable with arrow and animations.
- [Timber](https://github.com/JakeWharton/timber) - logging.
