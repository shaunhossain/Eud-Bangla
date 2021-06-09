# MarketDeal

The App for this website using Wordpress rest api and used a set of Android Jetpack libraries and used paging 3 library to pagination 

### About this App

* Educational app for this website using Wordpress rest api 
* Handling Network call using Kotlin Coroutine
* offline caching using Room Database
* Fetch data using State Flow (Coroutine Flow)


## Architecture

The project uses MVVM architecture pattern.

## Libraries 

* [DataBinding](https://developer.android.com/topic/libraries/data-binding) - support library that allows binding of UI components in layouts to data sources,binds character details and search results to UI
* [Navigation Component](https://developer.android.com/guide/navigation/navigation-getting-started) - Android Jetpack's Navigation component helps in implementing
navigation between fragments
* [Retrofit](https://square.github.io/retrofit/) - To access the Rest Api
* [Coroutines](https://developer.android.com/kotlin/coroutines/) - To Handle network call
* [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel/) - Manage UI related data in a lifecycle conscious way and act as a channel between use cases and ui
* [Dagger Hilt](https://developer.android.com/training/dependency-injection/hilt-android/) - Hilt is a dependency injection library for Android that reduces the boilerplate of doing manual dependency injection in this project
* [Room Database](https://developer.android.com/training/data-storage/room/) - To store offline data and save favourite posts
* [ViewPager2](https://developer.android.com/jetpack/androidx/releases/viewpager2) - to manage multiple fragments for categores 
* [State Flow](https://developer.android.com/kotlin/flow/stateflow-and-sharedflow) - to manage server data on the activity 
* [Paging library](https://developer.android.com/topic/libraries/architecture/paging/v3-overview) - to paginate recyclerview data
## App [Link](https://github.com/shaunhossain/Market-Deal/releases/download/V1.0/MarketDeal.apk)


## Screenshots
|<img src="screenshots/home_screen.jpg" width=200/>|<img src="screenshots/details_screen.jpg" width=200/>|
|:----:|:----:|
