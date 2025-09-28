# Flutter Riverpod Snippets

Flutter Riverpod snippets is a way to enhance the way you use Riverpod. It contains a collection of different
snippets such as `provider`.

![greetingProviderGif](gifs/greetingProvider.gif)

## Snippets

| Shortcut                             | Description                                                                 |
| ------------------------------------ | --------------------------------------------------------------------------- |
| `consumer`                           | Creates the Consumer widget                                                 |
| `statelessConsumerWidget`            | Creates a ConsumerWidget                                                    |
| `statefulConsumerWidget`             | Creates a ConsumerStatefulWidget                                            |
| `statelessHookConsumerWidget`        | Creates a HookConsumerWidget                                                |
| `statefulHookConsumerWidget`         | Creates a StatefulHookConsumerWidget                                        |
| `provider`                           | Creates an autodispose Provider                                             |
| `providerKeepAlive`                  | Creates a non-autodispose Provider                                          |
| `providerFamily`                     | Creates an autodispose family provider                                      |
| `futureProvider`                     | Creates an autodispose FutureProvider                                       |
| `futureProviderKeepAlive`            | Creates a non-autodispose FutureProvider                                    |
| `futureProviderFamily`               | Creates an autodispose family FutureProvider                                |
| `streamProvider`                     | Creates an autodispose StreamProvider                                       |
| `streamProviderKeepAlive`            | Creates a non-autodispose StreamProvider                                    |
| `streamProviderFamily`               | Creates an autodispose family StreamProvider                                |
| `changeNotifier`                     | Creates a ChangeNotifierProvider                                            |
| `changeNotifierProvider`             | Creates an autodispose ChangeNotifierProvider                               |
| `changeNotifierProviderKeepAlive`    | Creates a non-autodispose ChangeNotifierProvider                            |
| `changeNotifierProviderFamily`       | Creates an autodispose family ChangeNotifierProvider                        |
| `stateProvider`                      | Creates an autodispose StateProvider (legacy)                               |
| `stateProviderKeepAlive`             | Creates a non-autodispose StateProvider (legacy)                            |
| `stateProviderFamily`                | Creates an autodispose family StateProvider (legacy)                        |
| `stateNotifierProvider`              | Creates an autodispose StateNotifierProvider (legacy)                       |
| `stateNotifierProviderKeepAlive`     | Creates a non-autodispose StateNotifierProvider (legacy)                    |
| `stateNotifierProviderFamily`        | Creates an autodispose family StateNotifierProvider (legacy)                |
| `stateNotifier`                      | Creates a StateNotifier (legacy)                                            |
| `stateNotifierFamily`                | Creates a parametrized StateNotifier (legacy)                               |
| `asyncNotifierProvider`              | Creates an autodispose AsyncNotifierProvider                                |
| `asyncNotifierProviderFamily`        | Creates an autodispose family AsyncNotifierProvider                         |
| `asyncNotifier`                      | Creates an AsyncNotifier                                                    |
| `asyncNotifierFamily`                | Creates a parametrized AsyncNotifier                                        |
| `notifierProvider`                   | Creates an autodispose NotifierProvider                                     |
| `notifierProviderKeepAlive`          | Creates a non-autodispose NotifierProvider                                  |
| `notifierProviderFamily`             | Creates an autodispose family NotifierProvider                              |
| `notifier`                           | Creates a Notifier                                                          |
| `notifierFamily`                     | Creates a parametrized Notifier                                             |
| `streamNotifierProvider`             | Creates an autodispose StreamNotifierProvider                               |
| `streamNotifierProviderKeepAlive`    | Creates a non-autodispose StreamNotifierProvider                            |
| `streamNotifierProviderFamily`       | Creates an autodispose family StreamNotifierProvider                        |
| `streamNotifier`                     | Creates a StreamNotifier                                                    |
| `streamNotifierFamily`               | Creates a parametrized StreamNotifier                                       |
| `listen`                             | Listens to a provider                                                       |
| `riverpod`                           | Creates an autodispose Provider (codegen)                                   |
| `riverpodKeepAlive`                  | Creates a non-autodipose Provider (codegen)                                 |
| `riverpodFuture`                     | Creates an autodispose FutureProvider (codegen)                             |
| `riverpodFutureKeepAlive`            | Creates a non-autodispose FutureProvider (codegen)                          |
| `riverpodStream`                     | Creates an autodispose StreamProvider (codegen)                             |
| `riverpodStreamKeepAlive`            | Creates a non-autodispose StreamProvider (codegen)                          |
| `riverpodClass`                      | Creates an autodispose Notifier/NotifierProvider (codegen)                  |
| `riverpodClassKeepAlive`             | Creates a non-autodispose Notifier/NotifierProvider (codegen)               |
| `riverpodAsyncClass`                 | Creates an autodispose AsyncNotifier/AsyncNotifierProvider (codegen)        |
| `riverpodAsyncClassKeepAlive`        | Creates a non-autodispose AsyncNotifier/AsyncNotifierProvide (codegen)      |
| `riverpodStreamClass`                | Creates an autodispose StreamNotifier/StreamNotifierProvider (codegen)      |
| `riverpodStreamClassKeepAlive`       | Creates a non-autodispose StreamNotifier/StreamNotifierProvider (codegen)   |
| `riverpodPart`                       | Creates a part statement for Riverpod (codegen)                             |

## Contributing
Feel free to open PRs for small issues such as typos. For large issues or features, please open an issue first.

### How to do it
First fork the repo on [GitHub](https://github.com/RobertBrunhage/flutter-riverpod-snippets).
```
git clone <your-forked-repo>

git switch -c my-fix
# fix some code...

git commit -m "Fix typo in readme"
git push origin my-fix
```

Add the changes done to `CHANGELOG.md` and update the version in `package.json`

## Release Notes

Please check [Changelog](CHANGELOG.md)
