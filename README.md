# CompositeBuild
Example project that causes problems in Android Studio import

Reproduction steps:
1) Clone repo
2) Open project in Android Studio

Expected result:
Gradle sync succeeds

Actual result:
IDE error with java.lang.AssertionError: Already disposed: Module: 'app'
