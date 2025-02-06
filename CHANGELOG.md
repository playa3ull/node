## 0.1.0-testnet.1 (2025-02-06)


### 🚀 Features

- add node software ([5b8598bec](https://github.com/playa3ull/playa3ull-ecosystem/commit/5b8598bec))

- base integrated repo ([321513ff1](https://github.com/playa3ull/playa3ull-ecosystem/commit/321513ff1))

- make node cli a factory to validate license key on construction ([cf8116837](https://github.com/playa3ull/playa3ull-ecosystem/commit/cf8116837))

- add cli commands and use chalk for better visuals ([3db450c01](https://github.com/playa3ull/playa3ull-ecosystem/commit/3db450c01))

- move core package to shared subfolder as common ([d068c8457](https://github.com/playa3ull/playa3ull-ecosystem/commit/d068c8457))

- update all apps to use  in production executor ([40692944a](https://github.com/playa3ull/playa3ull-ecosystem/commit/40692944a))

- overhaul terminal system to refresh console logs based on state ([a74319316](https://github.com/playa3ull/playa3ull-ecosystem/commit/a74319316))

- better logging and separation of concerns ([8c84cc9a8](https://github.com/playa3ull/playa3ull-ecosystem/commit/8c84cc9a8))

- documentation overhaul and show uptime ([ef503aaf7](https://github.com/playa3ull/playa3ull-ecosystem/commit/ef503aaf7))

- display uptime as a progress bar and total required time ([37c0d319f](https://github.com/playa3ull/playa3ull-ecosystem/commit/37c0d319f))

- notification worker & ecosystem notification handler ([35cf62ed5](https://github.com/playa3ull/playa3ull-ecosystem/commit/35cf62ed5))

- add additional menu items and support for sub menu items ([16b8e304e](https://github.com/playa3ull/playa3ull-ecosystem/commit/16b8e304e))

- rename select prompt to menu builder and clear logs on logout ([f4016076b](https://github.com/playa3ull/playa3ull-ecosystem/commit/f4016076b))

- unsubscribe from websocket when leaving authenticated state ([68dc6bd3a](https://github.com/playa3ull/playa3ull-ecosystem/commit/68dc6bd3a))

- document menu builder class ([14738d6ae](https://github.com/playa3ull/playa3ull-ecosystem/commit/14738d6ae))

- abstract menu logic to states within the node cli itself ([91e63603d](https://github.com/playa3ull/playa3ull-ecosystem/commit/91e63603d))

- abstract menus to specific states ([45160e8b1](https://github.com/playa3ull/playa3ull-ecosystem/commit/45160e8b1))

- show total number connected and handle log outs better ([e7caf46c8](https://github.com/playa3ull/playa3ull-ecosystem/commit/e7caf46c8))

- paginated total connected ([eacd9722a](https://github.com/playa3ull/playa3ull-ecosystem/commit/eacd9722a))

- reconnect to server if websocket disconnect ([ca9ec6723](https://github.com/playa3ull/playa3ull-ecosystem/commit/ca9ec6723))

- prevent connecting on multiple sessions of the same account ([32178e61b](https://github.com/playa3ull/playa3ull-ecosystem/commit/32178e61b))

- dockerise node-cli ([34f3fae12](https://github.com/playa3ull/playa3ull-ecosystem/commit/34f3fae12))

- show network error message on gui and cap network logs to 10 ([4fbd0bba3](https://github.com/playa3ull/playa3ull-ecosystem/commit/4fbd0bba3))

- reconnect on lost connection and remove max retries ([b8ea0c1f8](https://github.com/playa3ull/playa3ull-ecosystem/commit/b8ea0c1f8))

- allow reconnects with a specific token ([cc03f3c09](https://github.com/playa3ull/playa3ull-ecosystem/commit/cc03f3c09))

- count reconnect events in uptime and forward event token ([965d6c0b9](https://github.com/playa3ull/playa3ull-ecosystem/commit/965d6c0b9))

- add deploy-docker job ([45ecc1c62](https://github.com/playa3ull/playa3ull-ecosystem/commit/45ecc1c62))

- useful logging package inspired by winston with transports ([40646e48b](https://github.com/playa3ull/playa3ull-ecosystem/commit/40646e48b))

- add node-cli into workflow ([eb4144402](https://github.com/playa3ull/playa3ull-ecosystem/commit/eb4144402))


### 🩹 Fixes

- build for node cli ([faef0aaac](https://github.com/playa3ull/playa3ull-ecosystem/commit/faef0aaac))

- re-authenticate automatically with refresh token if access token expires ([f33c9448c](https://github.com/playa3ull/playa3ull-ecosystem/commit/f33c9448c))

- omit re-install bundle handles this, removes all unused deps ([8df782449](https://github.com/playa3ull/playa3ull-ecosystem/commit/8df782449))

- node modules not found, set version ([299b1770e](https://github.com/playa3ull/playa3ull-ecosystem/commit/299b1770e))

- if stdin is not available, don't allow menu render ([0301024ab](https://github.com/playa3ull/playa3ull-ecosystem/commit/0301024ab))

- early return from menu builder if no stdin ([178f5ba3e](https://github.com/playa3ull/playa3ull-ecosystem/commit/178f5ba3e))

- data and log files for node cli ([f41af06c7](https://github.com/playa3ull/playa3ull-ecosystem/commit/f41af06c7))

- early return if stdin does not provide input ([30b6e16d1](https://github.com/playa3ull/playa3ull-ecosystem/commit/30b6e16d1))

- if not interactive dont render ([40e4f7427](https://github.com/playa3ull/playa3ull-ecosystem/commit/40e4f7427))


### ❤️  Thank You

- Akram Mohammed @lyncktechsolutions
- Jourdan Haines @jourdanhaines
- Sam
- Sam Thompson-Kennedy