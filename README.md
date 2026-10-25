# Smart House releases

Public download page for the Smart House home-lighting system. This repository
holds only the built files; the source code lives in private repositories.

Each release is published automatically from a version tag:

| Tag prefix | Contents | Asset |
|------------|----------|-------|
| `app-vX.Y.Z` | Android app | `SmartHouse-X.Y.Z.apk` |
| `firmware-vX.Y.Z` | ESP32 controller firmware | `SmartHomeESP32-X.Y.Z.bin` |

The app checks these releases for updates. Neither file contains secrets: each
controller keeps its own remote-access key in its flash memory.
