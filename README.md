# DropShadow
[![](https://jitpack.io/v/LordSahandii/DropShadow.svg)](https://jitpack.io/#LordSahandii/DropShadow)

## What is it?

DropShadow is a Library that let developers to add shadows beneath their texts or icons and design them as what they desired.

## Installation

- First you need to add maven url inside the settings.gradle file.
```
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
- Then inside the project gradle.build add the maven url.
```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```
- Finally, add the dependency inside the module gradle file.
```
dependencies {
  implementation 'com.github.LordSahandii:DropShadow:Tag'
}
```
For more information about installations visit the [jitpack website](https://jitpack.io/#LordSahandii/DropShadow/1.0.1)

## How To Use

=> To use this addon, just import it in the header of your file.

=> If you want a shadow on text just make a DropShadowText() and you can edit it as a Text component
```
DropShadowText(
    text = "Put your text",
    color = Color.Green,
    fontSize = 34.sp
   )
```

=> If you want a shadow on text just make a DropShadowIcon() and you can edit it as a Icon component
```
 DropShadowIcon(Icon = R.drawable.yourIcon)
```

## Jitpack Link

https://jitpack.io/#LordSahandii/DropShadow/1.0.1

## License

MIT

Free Open Source Library

