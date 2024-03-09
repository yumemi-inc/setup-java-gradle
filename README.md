[![CI](https://github.com/yumemi-inc/setup-java/actions/workflows/ci.yml/badge.svg)](https://github.com/yumemi-inc/setup-java/actions/workflows/ci.yml)

# Setup Java - Gradle

A GitHub Action that sets up a Java JDK and Gradle environment.
It is a composite action that combines the following actions.

- [actions/setup-java](https://github.com/actions/setup-java)
- [gradle/gradle-build-action](https://github.com/gradle/gradle-build-action)
- [yumemi-inc/problem-matchers/kotlin-gradle](https://github.com/yumemi-inc/problem-matchers/tree/main/kotlin-gradle)

Simplify the setup description each time you run a Gradle command, and do not create Gradle caches by default.
