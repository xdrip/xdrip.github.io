# Welcome to the xDrip Developers documentation

This page is intented for developers only.

## Install development environment

1. Install Android Studio at least v3.5 but the newest version should be fine, too
1. Install [Lombok IntelliJ plugin](https://projectlombok.org/setup/android)
1. Fork the xDrip repository and clone it localy from your fork
1. Add the upstream repository as remote using `git remote add upstream https://github.com/NightscoutFoundation/xDrip.git`
1. Start Android Studio and load the xDrip project
1. Do not update the Android Studio Gradle plugin for the xDrip project. You can update Gradle itself, but not the Gradle plugin.

## Updating PRs

If you need to change or cleanup you PR, please rebase it afterwards to the current master. Then push it with `git push --force-with-lease ...`.
