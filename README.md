# Minimal Todo

[![CircleCI](https://circleci.com/gh/cuongpm/android-minimal-todo.svg?style=svg)](https://circleci.com/gh/cuongpm/android-minimal-todo) [![codecov](https://codecov.io/gh/cuongpm/android-minimal-todo/branch/master/graph/badge.svg)](https://codecov.io/gh/cuongpm/android-minimal-todo)

A to-do app with minimal features. It's simple and just enough for you to keep everything on track.

## Roadmap

- [x] Solid Architecture: MVVM, ViewModel, LiveData, Room, Dagger2
- [x] Network module: Retrofit, RxJava, Moshi and Kotshi
- [x] Continuous integration with Circle CI
- [x] Test report and test coverage with: Jacoco and Codecov
- [x] Design offline-first data layer
- [x] Google sign in with Firebase authentication
- [ ] Restful api with Firebase cloud functions
- [ ] Complete all features
- [ ] 100% test coverage
- [ ] Deploy to Google Play
- [ ] Write a series of blog on Medium

## Major technologies

- Language: Kotlin
- Architecture: MVVM
- Android architecture components: ViewModel, LiveData, Room
- Dependency injection: Dagger2
- Network: Retrofit, RxJava, Moshi and Kotshi
- Testing: JUnit, Espresso, Mockito
- Material design

## Design data layer
Apply repository pattern to manage 3 data sources: memory cache, local data source and remote data source


![image](https://user-images.githubusercontent.com/2792438/47374632-a5769880-d718-11e8-9c02-8cb41df68eba.png)

## License

This package is licensed under the MIT license. See [LICENSE](./LICENSE) for details.
