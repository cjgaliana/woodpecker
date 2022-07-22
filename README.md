<div id="top"></div>

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/cjgaliana/woodpecker">
    <img src="images/woodpecker_logo.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Woodpecker</h3>

  <p align="center">
    A simple and extensible logger for Flutter. Based on 
    <a href="https://github.com/JakeWharton/timber">Timber</a>
    <br />
    <br />
    ·
    <a href="https://github.com/cjgaliana/woodpecker/issues">Report Bug</a>
    ·
    <a href="https://github.com/cjgaliana/woodpecker/issues">Request Feature</a>
  </p>
</div>

## About The Project

Intro

## Getting Started

### Installation

Run this command:

With Dart:

```
$ dart pub add woodpecker
```

With Flutter:

```
$ flutter pub add woodpecker
```

This will add a line like this to your package's pubspec.yaml (and run an implicit dart pub get):

```yaml
dependencies:
  ansicolor: ^2.0.1
```

<!-- USAGE EXAMPLES -->

## Usage

Configure the logger clients in your app.

```dart
import 'package:woodpecker/woodpecker.dart';

Logger.setupLogger(DebugLogger());
```

### DebugLogger

The library includes a `Debug Logger` that prints the information in the console.

The logs are colourized, and it supports 2 modes

```dart
DebugLogger(style = DebugLoggerStyle.colorText)
```

```dart
DebugLogger(style = DebugLoggerStyle.backgroundColor)
```

<!-- ROADMAP -->

## Roadmap

- [ ] Improve documentation
- [ ] Add clients
  - [x] Debug Console
  - [ ] Firebase Events
  - [ ] Sentry

See the [open issues](https://github.com/cjgaliana/woodpecker/issues) for a full list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Library dependencies

Woodpecker relies on [AnsioColor](https://pub.dev/packages/ansicolor) for the colouring of the Debug client.

## Acknowledgments

Logo by: https://freesvg.org/red-woodpecker

## Contact

Camilo Galiana - [@cjgaliana](https://twitter.com/cjgaliana)

Project Link: [https://github.com/cjgaliana/woodpecker](https://github.com/cjgaliana/woodpecker)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/cjgaliana/woodpecker.svg?style=for-the-badge
[contributors-url]: https://github.com/cjgaliana/woodpecker/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/cjgaliana/woodpecker.svg?style=for-the-badge
[forks-url]: https://github.com/cjgaliana/woodpecker/network/members
[stars-shield]: https://img.shields.io/github/stars/cjgaliana/woodpecker.svg?style=for-the-badge
[stars-url]: https://github.com/cjgaliana/woodpecker/stargazers
[issues-shield]: https://img.shields.io/github/issues/cjgaliana/woodpecker.svg?style=for-the-badge
[issues-url]: https://github.com/cjgaliana/woodpecker/issues
[license-shield]: https://img.shields.io/github/license/cjgaliana/woodpecker.svg?style=for-the-badge
[license-url]: https://github.com/cjgaliana/woodpecker/blob/master/LICENSE.txt
