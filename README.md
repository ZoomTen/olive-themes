# Olive-Editor Themes

This is a repo for Qt CSS themes made for [Olive Video Editor](https://github.com/olive-editor/olive).

## Installation
* Clone or Download -> Download ZIP
* Extract the ZIP file into a directory of your choosing. A folder named `olive-themes-master` should be there after the extraction.

## Applying the Themes
* Open Olive Video Editor, then go to Preferences.
* Go to the Appearance tab, then click `Browse` next to `Custom CSS`.
* Navigate to the directory where you put the repo's folder.
* Go to the `stylesheets` folder in `olive-themes-master`.
* Pick a `qss` file, click Open.
* Click OK. Olive should warn about a restart.
* Click Yes, and save your work.
* The theme should be applied to Olive at this point. How it looks may be different, depending on your operating system and Qt 5 settings.

## Contributing
Fork the repo, write your QSS file in the `stylesheets` directory, and create a [pull request](https://github.com/zoomten/olive-themes/pulls). It may take time for it to be merged.

If possible, please create a screenshot for your theme! This will help users to see what Olive will look like after applying your theme. You should place the screenshot in the `preview` directory.

You may also create an issue instead, and attach your QSS (and screenshot) in the description.

## Additional Resources
### Docs
* [Qt Style Sheets](https://doc.qt.io/qt-5/stylesheet.html)
    * [Syntax](https://doc.qt.io/qt-5/stylesheet-syntax.html) - if you're familiar to CSS, this should be easy to pick up.
    * [Reference](https://doc.qt.io/qt-5/stylesheet-reference.html) - master document of all Qt styleable widgets.
    * [Examples](https://doc.qt.io/qt-5/stylesheet-examples.html#customizing-a-qpushbutton-using-the-box-model) - *lots* of examples of styling applications using QSS
* [Specifics of Widget Rendering](https://doc.qt.io/qt-5/stylesheet-customizing.html)
### Testing
* [Testing styles in Qt Designer](https://doc.qt.io/qt-5/stylesheet-designer.html)
* [Qt Inspector](https://github.com/robertknight/Qt-Inspector) - Like "inspect element", but for Qt applications
