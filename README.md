# codestyle

* Last updated on March 31, 2017

## AutoGravity Java Code Style

This is to provide the better code readability for Java projects using both
Eclipse and IntelliJ IDEA. Each IDE should produce the same formatted code,
or at least should not complain each other.

Let's make the code clean!

### Eclipse (JEE Neon.2 or above)

1. Import code style: **autogravity-style-eclipse.xml** and **autogravity-style-eclipse.importorder**
2. Format code using **Shift+Command+F**.
3. Organize imports using **Shift+Command+O**.

### IntelliJ IDEA (2016.3 or above)

1. Import code style: **autogravity-style-intellij.xml**
2. Format code using **Option+Command+L**.
3. Use auto import options (imports on the fly).

## Changes from Google Style

Using the [Google Style](https://github.com/google/styleguide) with the latest
version of Eclipse and IntelliJ IDEA will reformat the code slightly different
from each other. Two spaces for indentation is not readable on a big wide monitor.
Here are some fixes:

* Indentation/Tab size: 4
* Maximum line width: 120
* Maximum line width for comments: 120
* Never join already wrapped lines
* Insert new line in empty block (Eclipse)
* Disable block comment formatting (Eclipse)
* Line comment at first column (Eclipse)
* Blank lines fixes (Eclipse)
* Line wrapping fixes (IntelliJ IDEA)
* Import layout/order fixes (Eclipse, IntelliJ IDEA)
* Removed other language settings (IntelliJ IDEA)
* Wrap always on class, method and field annotations (IntelliJ IDEA)
