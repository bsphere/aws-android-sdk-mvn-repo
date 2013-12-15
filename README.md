aws-android-sdk-mvn-repo
========================

Maven repository for the Amazon AWS Android SDK.

Gradle usage:

```java
repositories {
    maven {
        url 'https://github.com/bsphere/aws-android-sdk-mvn-repo/raw/master/releases'
    }
    mavenCentral()
}

dependencies {
    compile 'com.amazonaws:android-sdk-core:1.7.0'
    compile 'com.amazonaws:android-sdk-s3:1.7.0'
}
```
