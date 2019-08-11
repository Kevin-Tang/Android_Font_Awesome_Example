# Android Font Awesome Example Project
Example using Font Awesome icons for Android. 

Included in this project is a strings.xml of all free font awesome icons on the latest version (5.10.1).

## References
`@string/fa_lightbulb` - Regular lightbulb icon

`@string/fa_cat_solid` - Solid cat icon

`@string/fa_google_brand` - Brand google icon

## Introduction
Since API level 26, Android introduced a new feature, Fonts in XML, which lets you use fonts as resources. This project shows you how to add fontawesome icons as a font file in your res directory. To use Fonts in XML on devices running Android 4.1 (API level 16) and higher, using at least Support Library 26.0 is required. Make sure to add support for appcompat-v7 to your app-level gradle.

```xml
implementation "com.android.support:appcompat-v7:28.0.0"
```

## Useful Resources
* Android Developers - [Fonts in XML](https://developer.android.com/guide/topics/ui/look-and-feel/fonts-in-xml)

* Font Awesome - [Website](https://fontawesome.com/)

* Font Awesome Github - [Repo](https://github.com/FortAwesome/Font-Awesome)


## Usage
Referencing Font Icons within a `TextView`
```xml
<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="@font/fa_regular_400"
        android:text="@string/fa_lightbulb"
        android:textColor="@color/colorPrimary"
        app:fontFamily="@font/fa_regular_400" />
```
## Demo
<img src = "https://user-images.githubusercontent.com/6528777/62830223-fb95c900-bbd0-11e9-9749-ccdbbd2e3a4f.jpg" alt="Font Awesome Demo Screenshot" title="Font Awesome Demo" width="300">
