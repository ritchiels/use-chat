# @chatscope/use-chat changelog

## [3.1.1](https://github.com/chatscope/use-chat/compare/v3.1.0...v3.1.1) (2023-01-18)


### Bug Fixes

* [#15](https://github.com/chatscope/use-chat/issues/15) lazy service init ([834634e](https://github.com/chatscope/use-chat/commit/834634ed978ebfea8928758d7e54686d62db1ee3))

# [3.1.0](https://github.com/chatscope/use-chat/compare/v3.0.0...v3.1.0) (2022-12-18)


### Features

* added removeMessagesFromConversation method to ChatProvider ([c957453](https://github.com/chatscope/use-chat/commit/c957453880a55438c1063490e2d9e81b60a50047))

# [3.0.0](https://github.com/chatscope/use-chat/compare/v2.0.3...v3.0.0) (2022-12-18)


* feat!: added removeMessagesFromConversation ([639588b](https://github.com/chatscope/use-chat/commit/639588b5e52745c4b708db11917a11ba31935dd9))


### BREAKING CHANGES

* due to the addition of a new method to the IStorage interface.
However, this is only relevant if you are using a custom storage implementation.
Otherwise, the library is backward compatible and the upgrade is safe.

## [2.0.3](https://github.com/chatscope/use-chat/compare/v2.0.2...v2.0.3) (2022-12-18)


### Bug Fixes

* react peerDependency ([7827756](https://github.com/chatscope/use-chat/commit/782775640ba08672dfbf75b8641bc69cfed72003))
* yarn lockfile ([f02148f](https://github.com/chatscope/use-chat/commit/f02148f3001b32fe814488f66806987fa4b03c1e))

## [2.0.2](https://github.com/chatscope/use-chat/compare/v2.0.1...v2.0.2) (2022-09-13)


### Bug Fixes

* [#13](https://github.com/chatscope/use-chat/issues/13) replace and update message methods in MessageGroup ([ae0006d](https://github.com/chatscope/use-chat/commit/ae0006df1cd1035785ae524887a1d0b88fdeccf6))

## [2.0.1](https://github.com/chatscope/use-chat/compare/v2.0.0...v2.0.1) (2022-08-06)


### Bug Fixes

* added sources to the npm package ([63d9992](https://github.com/chatscope/use-chat/commit/63d99924811ed29f65da2a1d5e44affda0b2f4c8))

# [2.0.0](https://github.com/chatscope/use-chat/compare/v1.5.0...v2.0.0) (2022-07-27)


### Documentation

* readme update ([2752aeb](https://github.com/chatscope/use-chat/commit/2752aeb75ccceb8f94bbdc7d165aaac4eb341f2f))


### BREAKING CHANGES

* changed names of properties createdDate and updatedDate

# [1.5.0](https://github.com/chatscope/use-chat/compare/v1.4.1...v1.5.0) (2022-07-27)


### Features

* added createdDate and updatedDate properties to the ChatMessage ([f9febc4](https://github.com/chatscope/use-chat/commit/f9febc49d9091d7300c74fbbd33abf0f2af5a6f5))

## [1.4.1](https://github.com/chatscope/use-chat/compare/v1.4.0...v1.4.1) (2022-07-12)


### Bug Fixes

* children type of chat provider ([0e74498](https://github.com/chatscope/use-chat/commit/0e744989afef22e99edd6e4b1d9efe123fc829a6))

# [1.4.0](https://github.com/chatscope/use-chat/compare/v1.3.1...v1.4.0) (2022-04-16)


### Features

* added generic user data and conversation data ([2a3447e](https://github.com/chatscope/use-chat/commit/2a3447e72d350a4440586c50d23e039c1780d314))

## [1.3.1](https://github.com/chatscope/use-chat/compare/v1.3.0...v1.3.1) (2022-02-20)


### Bug Fixes

* force build ([d6667d3](https://github.com/chatscope/use-chat/commit/d6667d39fd6020e739769c2207321aae70b637d0))

# [1.3.0](https://github.com/chatscope/use-chat/compare/v1.2.2...v1.3.0) (2022-02-17)


### Features

* added removeConversation method ([44f58d6](https://github.com/chatscope/use-chat/commit/44f58d668b8a8e78895efab8f9bce57a18ffd21f))

## [1.2.2](https://github.com/chatscope/use-chat/compare/v1.2.1...v1.2.2) (2022-02-17)

## [1.2.1](https://github.com/chatscope/use-chat/compare/v1.2.0...v1.2.1) (2021-12-18)


### Bug Fixes

* description in replaceconversation ([387e75e](https://github.com/chatscope/use-chat/commit/387e75ea9e883d21875548faeaf1ff73c1d54c29))

# [1.2.0](https://github.com/chatscope/use-chat/compare/v1.1.1...v1.2.0) (2021-12-18)


### Features

* added description property to the conversation ([8a565ad](https://github.com/chatscope/use-chat/commit/8a565adb734eb09cfc465bb3749aab69a4838b5d))

## [1.1.1](https://github.com/chatscope/use-chat/compare/v1.1.0...v1.1.1) (2021-10-30)


### Bug Fixes

* added missing param to replace conversation ([ed2bab4](https://github.com/chatscope/use-chat/commit/ed2bab4561be9da6b9140208d019900b96c332e0))

# [1.1.0](https://github.com/chatscope/use-chat/compare/v1.0.7...v1.1.0) (2021-10-30)


### Features

* added readonly parameter to the conversation ([3861353](https://github.com/chatscope/use-chat/commit/3861353e7dcbde49b77793705b87d129c8e7090d))

## [1.0.7](https://github.com/chatscope/use-chat/compare/v1.0.6...v1.0.7) (2021-10-30)


### Bug Fixes

* allow empty props in the conversation and participant constructor ([bd25d51](https://github.com/chatscope/use-chat/commit/bd25d517d24338052f29f4b26c12b60c92a356af))

## [1.0.6](https://github.com/chatscope/use-chat/compare/v1.0.5...v1.0.6) (2021-10-30)


### Bug Fixes

* allow empty props in the user constructor ([bc2949a](https://github.com/chatscope/use-chat/commit/bc2949ad399e3355f1084099391c329ef6e74918))

## [1.0.5](https://github.com/chatscope/use-chat/compare/v1.0.4...v1.0.5) (2021-09-20)


### Bug Fixes

* **provider:** [#2](https://github.com/chatscope/use-chat/issues/2) added missing callbacks dependencies ([5b4042d](https://github.com/chatscope/use-chat/commit/5b4042dec938767582edf6742eea487a92a16dfe))

## [1.0.4](https://github.com/chatscope/use-chat/compare/v1.0.3...v1.0.4) (2021-05-17)


### Bug Fixes

* **provider:** allow empty children ([9b1a97e](https://github.com/chatscope/use-chat/commit/9b1a97edd70115a29a942ebf8d4a5b3239e5f5cf))

## [1.0.3](https://github.com/chatscope/use-chat/compare/v1.0.2...v1.0.3) (2021-05-17)


### Bug Fixes

* **provider:** error message ([09b7e05](https://github.com/chatscope/use-chat/commit/09b7e05170d062af65bb427563d806fbe1da718f))

## [1.0.2](https://github.com/chatscope/use-chat/compare/v1.0.1...v1.0.2) (2021-05-10)


### Bug Fixes

* **provider:** wrapped api methods in useCallback for referential equality ([9f7b7b9](https://github.com/chatscope/use-chat/commit/9f7b7b93f67fb1674202894589cce84027380d34))

## [1.0.1](https://github.com/chatscope/use-chat/compare/v1.0.0...v1.0.1) (2021-05-10)


### Bug Fixes

* **fake:** don't want to fight with npm ([4b072f7](https://github.com/chatscope/use-chat/commit/4b072f72f60c622cd2edc06e604a44d9e7f1a96d))

# 1.0.0 (2021-05-10)


### chore

* **release:** first release ([5cbf1fd](https://github.com/chatscope/use-chat/commit/5cbf1fd15b082b816d52ecbec837da2b972d7a3e))


### BREAKING CHANGES

* **release:** First stable release
