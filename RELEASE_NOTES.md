### Version 0.5.6 (October 14, 2012)

* Expose convention property for setting the RMI port - [Issue 21](https://github.com/bmuschko/gradle-cargo-plugin/issues/21).

### Version 0.5.5 (August 4, 2012)

* Provides support for configuration files - [Issue 14](https://github.com/bmuschko/gradle-cargo-plugin/issues/14).

### Version 0.5.4 (July 8, 2012)

* The ZIP URL installer convention property wasn't set correctly for the default local container implementation.
* Checking if all properties are set for the ZIP URL installer closure before applying it.
* Refactored duplicated code for setting the convention properties of a local container.

### Version 0.5.3 (July 7, 2012)

* Support for ZIP artifact installer - [Issue 15](https://github.com/bmuschko/gradle-cargo-plugin/issues/15).
* Upgrade to Gradle Wrapper 1.0.
* Use Groovy @Slf4j annotation for logging.

### Version 0.5.2 (December 5, 2011)

* Fixed minor bug in documentation and code about setting local container-specific properties.

### Version 0.5.1 (December 3, 2011)

* Provide convention properties for Cargo and container log files.

### Version 0.5 (November 27, 2011)

* Allow deployment of multiple artifacts - [Issue 9](https://github.com/bmuschko/gradle-cargo-plugin/issues/9). _Note:_ This slightly
changes the structure of the convention properties. Please check the documentation!

### Version 0.4 (November 27, 2011)

* Support for JVM arguments in local containers.
* Support for configuration properties specific to local container product.
* The deployable artifact can either be a WAR or an EAR file. _Note:_ This release requires your project to run with Gradle >= [1.0-m4](http://wiki.gradle.org/display/GRADLE/Gradle+1.0-milestone-4+Release+Notes).
* Upgrade to Gradle Wrapper 1.0-m6.

### Version 0.3 (June 26, 2011)

* Exposed local run task introduced in Cargo 1.1.1. The plugin does not favor the [deprecation](http://cargo.codehaus.org/Ant+support)
of the `wait` convention property. It got removed completely. Please use `cargoRunLocal` or `cargoStartLocal` depending on
your use case.
* _Note:_ This release requires you to use Cargo >= 1.1.1.

### Version 0.2 (May 30, 2011)

* Added property for setting `cargo.protocol` to remote container tasks.

### Version 0.1 (May 27, 2011)

* Initial release.