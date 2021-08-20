The [words](https://pub.dev/packages/words) package comprises two sets of [lints][rules] which help in development of consistent, predictable applications.

Two sets of linter rules are used:

* **Core lints**: Lints applicable to *all* Dart code across every platform, expected to be enforced in every code library published by [WordCollector][wordcollector], as well as in private repositories.

* **Flutter lints**: **Core** lints + additional lints only applicable to the Flutter framework.

To learn more about lints, visit the official Dart [lints](https://pub.dev/packages/lints) package repository.

## How to enable these lints

1. Add the `words` package as a developer dependency using the terminal:
  
    ```terminal
    dart pub add --dev words
    ```

2. Create an `analysis_options.yaml` file at the root of the repository (next to `pubspec.yaml`).

3. In a Flutter project you should add: 
  
    ```yaml
    include: package:words/flutter.yaml
    ```

    Otherwise:
  
    ```yaml
    include: package:words/core.yaml
    ```

[wordcollector]: https://github.com/wordcollector
[rules]: https://dart.dev/tools/linter-rules
