# android-CoolEditText

Cool UI for EditText made with :
- TextInputLayout 
- AnimatedEditText

## Overview 
This is the android application with cool Ui for EditText made easy to use .


## Prerequisite(Beginner's Guide)
We need to setup environment to develop the app.

1. Java Development Kit [JDK-Latest Version](http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html) 
   - Download this to setup the java environment on your machine.(Select agree license and then download accordingly to your system)
2. Android SDK [Android SDK](https://developer.android.com/studio/index.html)
   - Download the latest version by following this link and install the packaged and tools. 
   
## Coding 
 Clone the repo and open in android studio .
 (or) Clone repo and copy the code inorder to avoid some errors in importing the package .
 
 Add the dependency to the gradle :
 > compile 'com.alimuzaffar.lib:animated-edit-text:1.0'
 
 Code the following in the xml to add the editText with animated Features.
 ```
 <com.alimuzaffar.lib.widgets.AnimatedEditText
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:hint="Animate pop in"
    android:inputType="textNoSuggestions" //recommended when typing text to avoid autocomplete.
    app:animationType="popIn|fromBottom|fromRight|fromMiddle|none" //Optional, default popIn
    app:animateCursor="true|false" //Optional, default true
    app:animateTextClear="true|false" /> //Optional, default true
```
 
 Credits and Inspired [from here](https://github.com/alphamu/AnimatedEditText)
 
 Happy to go :grey_exclamation: Enjoy Developing :thumbsup:
