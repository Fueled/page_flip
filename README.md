[![Pub](https://img.shields.io/pub/v/page_flip.svg)](https://pub.dartlang.org/packages/page_flip)

<a href="https://www.buymeacoffee.com/smishra" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

# Page Flip Widget

A flutter package which will help you to add  page flip effect to widgets in your app.

Re-created by Shivam Mishra [@shivbo96](https://github.com/shivbo96)

# Usage

## Use this package as a library

1. Depend on it Add this to your package's pubspec.yaml file:

```
dependencies:
  page_flip: <VERSION>
```

2. Install it You can install packages from the command line:
   with Flutter:

```
$ flutter pub get
```

Alternatively, your editor might support flutter packages get. Check the docs for your editor to
learn more.

3. Import it Now in your Dart code, you can use:

```
import 'package:page_flip/page_flip.dart';
```

## Example

```
   PageFlipWidget(
        key: _controller,
        backgroundColor: Colors.white,
        showDragCutoff: false,
        lastPage: const Center(child: Text('Last Page!')),
        children: <Widget>[
          for (var i = 0; i < 5; i++) DemoPage(page: i),
        ],
      )
      
```
refer to `example/lib/main.dart`


## Screenshots

<img src="https://raw.githubusercontent.com/shivbo96/page_flip/main/screenshots/4.gif" width="250" height="480">
<img src="https://raw.githubusercontent.com/shivbo96/page_flip/main/screenshots/1.png" width="250" height="480">
<img src="https://raw.githubusercontent.com/shivbo96/page_flip/main/screenshots/2.png" width="250" height="480">
<img src="https://raw.githubusercontent.com/shivbo96/page_flip/main/screenshots/3.png" width="250" height="480">
<img src="https://raw.githubusercontent.com/shivbo96/page_flip/main/screenshots/4.png" width="250" height="480">


## More information

[Pub package](https://pub.dartlang.org/packages/page_flip)
[Flutter documentation](https://flutter.io/).
