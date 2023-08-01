<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

## Installation

1. Add the latest version of package to your pubspec.yaml (and run dart pub get)
dependencies:
    simple_container: ^0.0.1

2. Import the package and use it in your Flutter App

Import 'package:very_simple_container/simple_container';

## Example
There are a number of properties that you can modify:

- width
- height
- title
- subtitle
- gradient (color1 and color2)

<hr>
<table>
<tr>
<td>

class SimpleScreen extends StatelessWidget {
  const SimpleScreen({key? key}) : super(Key: key);
  
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: const SimpleContainer(
            title: 'Hello World',
            color1: Colors.lightGreenAccent,
            color2: Colors.lightBlue,
            subtitle: 'This is a new package,
        ),
      )
    );
  }
}
