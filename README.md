# radial_button

A new Radial Button 


## Start

A Flutter plugin for iOS and Android for generating radial buttons for floating action buttons and other parts.

> Feedback and Pull Requests are most welcome!

## Installation

Add to pubspec.yaml.

```yaml
dependencies:
  ...
  radial_button: ^0.0.1
```

<img src="assets/1562709801.png" width="300">

<img src="assets/1562709828.png" width="300">


## Usage Example

import flutter_signin_button.dart

```dart
import 'package:radial_button/widget/circle_floating_button.dart';
```

## Samples

```dart
    var itemsActionBar = [
        FloatingActionButton(
        backgroundColor: Colors.greenAccent,
        onPressed: () {},
        child: Icon(Icons.add),
        ),
        FloatingActionButton(
        backgroundColor: Colors.indigoAccent,
        onPressed: () {},
        child: Icon(Icons.camera),
        ),
        FloatingActionButton(
        backgroundColor: Colors.orangeAccent,
        onPressed: () {},
        child: Icon(Icons.card_giftcard),
        ),
    ];
    
    //....

    CircleFloatingButton.floatingActionButton(
    items: itemsActionBar,
    color: Colors.redAccent,
    icon: Icons.ac_unit,
    duration: Duration(milliseconds: 1000),
    curveAnim: Curves.ease)

    //......

    CircleFloatingButton.completeCircle(
        items: itemsToBody,
        color: Colors.red,
        duration: Duration(milliseconds: 1000),
    curveAnim: Curves.elasticOut)

    //........

    CircleFloatingButton.semiCircle(
        items: itemsToBody,
        color: Colors.red,
        duration: Duration(milliseconds: 1000),
    curveAnim: Curves.elasticOut)
```