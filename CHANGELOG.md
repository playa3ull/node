## 0.4.22 (2025-05-26)

### Improvements

- Added support for improved logging tools to aid in troubleshooting issues.

### Fixes

- Fixed an issue that would cause the application to crash if an invalid response was received from the Master Node
  Network whilst getting the uptime.
    - Developer note: This would happen from time to time if the network was down for a short period of time, or if the
      network was under heavy load and the request timed out.
- Fixed an issue that would cause the application to make progressively more and more requests to the Master Node
  Network the longer the application was running, which would eventually lead to a crash.

## 0.4.21 (2025-05-23)

### Fixes

- Fixed an issue that would cause the application to reconnect multiple times if the connection was lost and the last
  event was a disconnect event.

## 0.4.20 (2025-05-22)

### Fixes

- Fixed an issue where a node could become stuck in a disconnected state and not reconnect to the network.

## 0.4.19 (2025-05-22)

### Fixes

- Fixed an issue that would cause the application to crash if the node tried reconnecting to the network after a sudden
  disconnect, after it had been online for a long time.

## 0.4.18 (2025-05-22)

### Fixes

- Fixed an issue where an instance of the software would not reconnect to the same session on restart from a crash.

## 0.4.17 (2025-05-12)

This was a version bump only, there were no code changes.

## 0.4.16 (2025-05-12)

### Improvements

- Report additional metrics when making network requests to better support debugging

### ❤️ Thank You

- Jourdan Haines @jourdanhaines

## 0.4.14 (2025-05-12)

### Improvements

- Report version number of application for debugging purposes when making network requests

## 0.4.13 (2025-05-07)

This was a version bump only, there were no code changes.

## 0.4.12-0 (2025-05-07)

### Fixes

- Fixed an issue that would cause newly refreshed tokens to not be saved
- Fixed an auto-refresh session issue that would cause the application to hang

### ❤️ Thank You

- Jourdan Haines @jourdanhaines

## 0.4.11 (2025-05-05)

### Fixes

- Fixed an issue that would cause the application to exit if it failed to refresh an authentication token

### ❤️ Thank You

- Jourdan Haines @jourdanhaines

## 0.4.9 (2025-05-02)

### Improvements

- Application will continue to attempt a reconnect to the Master Node Network, even if it is down for long stretches of
  time

### Fixes

- Fixed an issue where the uptime calculate was taking into account the time since the client session was created,
  instead of the time since the last uptime request was made

### ❤️ Thank You

- Jourdan Haines @jourdanhaines

## 0.4.7 (2025-03-19)

Initial public release of the PLAYA3ULL GAMES Master Node Software.

This version includes the following features:

- Authentication and connection to the PLAYA3ULL GAMES Master Node Network
- Monitor uptime and performance of your Master Node
- View and monitor network activity

This initial release only requires you to run a single Master Node for your account.

### ❤️ Thank You

- Jourdan Haines @jourdanhaines
- Sam Thompson-Kennedy @samthompsonkennedy
