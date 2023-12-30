
# TextField Widget

Fancy container package lets you add a beautiful gradient container to your Flutter app.

## Installation

1. Add the latest version of package to your pubspec.yaml (and run`dart pub get`):

```yaml
dependencies:
  alneamah: ^2.0.0
```

2. Import the package and use it in your Flutter App.

```dart
import 'package:alneamah/alneamah.dart';
```

## Example

There are a number of properties that you can modify:

- height
- width
- title
- subtitle
- gradient (color1 and color2)

<hr>

<table>
<tr>
<td>

```dart
class Home extends StatelessWidget {
  const Home({super.key});

  @override
  Widget build(BuildContext context) {
    return const Scaffold(body: TextFieldWidget(hintText: 'hint',labelText: 'label'),);
  }
}
```

</td>
<td>
<img  src="https://user-images.githubusercontent.com/53579386/126896556-911d4778-04cd-49bf-b32a-01a6eb3b0155.jpeg"  alt="">
</td>
</tr>
</table>

## Next Goals

- [x] Add onTap for functions.
 Now, you can specify the onTap and specify a function.

- [x] Change font and color style for text.
 Change color by specifying `textcolor` and `subtitlecolor` properties.

- [ ] Add more containers to the package.
