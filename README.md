# TCard

[![GitHub stars](https://img.shields.io/github/stars/xrr2016/tcard)](https://github.com/xrr2016/tcard/stargazers) [![pub package](https://img.shields.io/pub/v/tcard.svg)](https://pub.dev/packages/tcard) ![Test](https://github.com/xrr2016/tcard/workflows/Test/badge.svg)

![example](./example/example.gif)

## Install

```yml
dependencies:
  tcard: ^0.1.0
```

## Uasge

```dart
TCard(
  cards: [
    Container(color: Colors.blue),
    Container(color: Colors.yellow),
    Container(color: Colors.red),
  ],
)
```

## Property

| property | type | default | description | required |
| :- | :---: | :---: | :---: | :-: |
| cards | `List<Widget>` | `null` | Render cards | `true` |
| size | `Size` | `null` | Card size | `false` |
| controller | `TCardController` | `null` | Card controller | `false` |
| onForward | `ForwardCallback` | `null` | Forward animation callback | `false` |
| onBack | `BackCallback` | `null` | Back animation callback | `false` |
| onEnd | `EndCallback` | `null` | Forward end callback | `false` |

## Contribute

1. Fork it (https://github.com/xrr2016/tcard.git)
2. Create your feature branch (git checkout -b feature/foo)
3. Commit your changes (git commit -am 'Add some foo')
4. Push to the branch (git push origin feature/foo)
5. Create a new Pull Request

## License

[MIT](./LICENSE)