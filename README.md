# CircularButton
Android Circular button widget for Android.

## Usage
#### Set up the dependency
1. Add the mavenCentral() repository to your root build.gradle at the end of repositories:
```
allprojects {
	repositories {
		...
		mavenCentral()
	}
}
```
2. Add the CircularButton dependency in the build.gradle:
```
implementation group: 'com.apachat', name: 'circularbutton-android', version: '1.0.3'
```

Badge:
-----
[![Maven Central](https://img.shields.io/maven-central/v/com.apachat/circularbutton-android.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22com.apachat%22%20AND%20a:%22circularbutton-android%22)

#### Use `CircularButton` for `Only` Circular button.
```
  <com.apachat.circularbutton.core.CircularButton
    android:id="@+id/button"
    android:layout_width="64dp"
    android:layout_height="64dp"
    app:cb_color="#99cc00"
    app:cb_pressedRingWidth="8dp" />
```

#### Use a `CircularButtonText` to support `Text` in your button.
```
  <com.apachat.circularbutton.core.CircularButtonText
    android:layout_below="@id/buttonText"
    android:layout_width="64dp"
    android:layout_height="64dp"
    android:text="1"
    android:textSize="25sp"
    android:textColor="#000000"
    app:cb_color="#99cc00"
    app:cb_pressedRingWidth="8dp" />
```

### And you're done, easy-peasy. ^_^

## Bugs and Feedback
For bugs, questions and discussions please use the [Github Issues](https://github.com/FarhamHosseini/CircularButton/issues).
