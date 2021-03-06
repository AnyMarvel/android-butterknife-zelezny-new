#ButterKnifeZeleznyNew

中文: 兼容AndroidStudio 4.1.0+版本(最新版本兼容)

English: Compatible with AndroidStudio 4.1.0+ version (compatible with the latest version)

以下官方使用介绍

The following official introduction

download by Tag https://github.com/AnyMarvel/android-butterknife-zelezny-new/releases/tag/2.0.0

# ButterKnifeZelezny

Simple plug-in for Android Studio/IDEA that allows one-click creation of [Butterknife](https://github.com/JakeWharton/butterknife) view injections.

## How to install

- in Android Studio: go to `Preferences → Plugins → Browse repositories` and search for `ButterKnife Zelezny`

_or_

- [download it](http://plugins.jetbrains.com/plugin/7369) and install via `Preferences → Plugins → Install plugin from disk`


## How to use it

 ![](img/zelezny_animated.gif)

 1. Make sure you have latest [Butterknife](https://github.com/JakeWharton/butterknife) lib on your classpath
 2. Right click on usage of desired layout reference (e.g. R.layout.main in your Activity or Fragment), then `Generate` and `Generate ButterKnife Injections`
 3. Pick injections you want, you also have an option to create ViewHolder for adapters.
 4. Click `Confirm` and enjoy injections in your code with no work!


## Contributing

Pull requests are welcomed!

- make sure you stick to [our coding style](/code-formatting-config.xml).
- follow [Getting Started with Plugin Development](http://confluence.jetbrains.com/display/IDEADEV/Getting+Started+with+Plugin+Development)
- make sure you have Java 6 installed if you want to publish it in the plugin repository

## Common issue: The plugin is not working after I updated to new Android Studio
- AS promts you to update plugins after update, you need to update them before using
- Make sure you have Butterknife on your classpath
- Make sure that your cursor is placed on a layout ID in a class having one of these types: Activity, Fragment, custom View or Adapter
