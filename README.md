A repository that contains two `List<String>` objects:
1. `legalWords`, which contains all of the legal words in Wordle (as of early 2025)
2. `legalGuesses`, which contains all of the additional words that are legal guesses in Wordle (as of early 2025)

Use them in your Dart implementation of Wordle-like games, add the following to your `pubspec.yaml`

```yaml
dependencies:
  legal_wordle_words:
    git: https://github.com/ericwindmill/legal_wordle_words
```

If you're following the [Flutter Getting Started tutorial](https://docs.flutter.dev/tutorial), you can use these lists with the following steps:


1. Add the above to your `pubspec.yaml`, and then run `pub get` in your terminal at the project root.
2. open your `game.dart` file and make these changes:
   REMOVE **ony** the `legalWords` and `legalGuesses` variables.
   ADD the import: `import 'package:legal_wordle_words/legal_wordle_words.dart';`

You're all set.

