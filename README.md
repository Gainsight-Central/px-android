[![Gainsight PX](https://app-dev.aptrinsic.com/home/gainsight-px-logo.svg)](https://app.aptrinsic.com)

# Gainsight PX Android SDK

![version](https://img.shields.io/badge/version-1.13.6-green.svg)

## Installation

The Gainsight PX Android SDK is available through Maven.

### 1. Add the repository into `build.gradle` file

* App level — the root-level `repositories` block, not `buildscript`

  ```groovy
  repositories {
      ...
      maven {
          url "https://github.com/Gainsight-Central/px-android/raw/main/"
      }
  }
  ```

* **Or** project level — inside the `allprojects` block

  ```groovy
  allprojects {
      repositories {
          ...
          maven {
              url "https://github.com/Gainsight-Central/px-android/raw/main/"
          }
      }
  }
  ```

### 2. Add the dependency to `build.gradle` file (App level)

```groovy
dependencies {
    ...
    implementation 'com.gainsight.px:mobile-sdk:1.13.6'
}
```

## Documentation

More detailed documentation is available at: <https://support.gainsight.com/PX/Mobile/01Getting_Started/Install_Gainsight_PX/02_Install_Gainsight_PX_SDK_for_Android>

## Release Notes

See [CHANGELOG.md](CHANGELOG.md) for the full release history.

## License

MIT — see [LICENSE](LICENSE).


temp change