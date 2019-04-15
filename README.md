[![pub package](https://img.shields.io/pub/v/underline_indicator.svg)](https://pub.dartlang.org/packages/underline_indicator)
[ ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](https://github.com/crazycodeboy/underline_indicator/pulls)
[ ![underline_indicator release](https://img.shields.io/github/release/crazycodeboy/underline_indicator.svg?maxAge=2592000?style=flat-square)](https://github.com/crazycodeboy/underline_indicator/releases)


A underline indicator.

## Getting Started

```dart
TabBar(
...
  indicator: UnderlineIndicator(
    strokeCap: StrokeCap.round,// Set your line endings.
      borderSide: BorderSide(
        color: Color(0xff2fcfbb),
        width: 3,
      ),
      insets: EdgeInsets.only(bottom: 10)),
...
  )
```
