![Json-Java logo](/JsonAndroid.png)



JSON in Android [package android.org.json]
===============================
A port of the JSON-Java library specifically refactored for Android development.


## Overview

The original JSON-Java library is widely used for JSON parsing and manipulation in Java applications. However, it has compatibility issues when used in Android environments due to package conflicts and platform differences.

This repository provides a forked and refactored version of the JSON-Java library with a changed package name to avoid conflicts on Android. This allows Android developers to seamlessly integrate JSON handling capabilities without worrying about clashes with other libraries or the Android runtime.

## Features

* Fully compatible with Android development environments.
* Refactored package namespace to prevent conflicts.
* Maintains the original functionality and API of JSON-Java.
* Easy to integrate into Android projects.

## Installation

Add the library to your Android project as a dependency. You can include it as a local library or build it into your project.

## Usage

Use the library as you would the original JSON-Java library, but with the updated package name to avoid conflicts.

```java
// Example usage
import com.yournewpackage.json.JSONObject;

JSONObject obj = new JSONObject();
obj.put("key", "value");
System.out.println(obj.toString());
```

## Why This Fork?
The original JSON-Java library uses a package name that can conflict with other libraries or Android system classes, causing build or runtime issues. By changing the package name, this fork ensures smooth integration and usage within Android apps.

## Contributing / Building / Updating
#### To build or update this library, follow these simple steps:

- Clone the repository (it is a Gradle project).

- Update or replace the relevant classes in the src directory with the latest versions from the new JSON-Java release.

- Rebuild the project using Gradle.

**In a nutshell: all you have to do is copy, paste, and replace the classes in the src folder to update the library.

