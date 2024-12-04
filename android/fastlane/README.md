fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android increment_version_code

```sh
[bundle exec] fastlane android increment_version_code
```

Increment version code in local.properties

### android deploy_to_firebase

```sh
[bundle exec] fastlane android deploy_to_firebase
```



### android deploy_internal

```sh
[bundle exec] fastlane android deploy_internal
```

Submit a new version to the internal track in Google Play

### android build_and_deploy

```sh
[bundle exec] fastlane android build_and_deploy
```



----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
