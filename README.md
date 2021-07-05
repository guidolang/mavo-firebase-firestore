# Extended Firebase Backend Plugin for Mavo

Minor extension of [Firebase backend plugin](https://github.com/DmitrySharabin/mavo-firebase-firestore) for [Mavo](https://mavo.io/). This enables the option of saving data in user-specific collections. In other words, it gives the option of restricting users' ability to read/write only their own data. Note that this isn't secured by Firebase security rules, so use with caution. 

## Instructions

1. Load this script after loading Mavo:
```html
<script src="https://cdn.jsdelivr.net/gh/guidolang/mavo-firebase-firestore/mavo-firebase-firestore.js"></script>
```
2. Add `notshared` as a feature in `mv-storage-options`, like `mv-storage-options="auth storage notshared"`

 ---

 Based on [Firebase backend plugin v0.3.9](https://github.com/DmitrySharabin/mavo-firebase-firestore/releases/tag/v0.3.9). Tested with [Mavo v0.2.4](https://github.com/mavoweb/mavo/releases/tag/v0.2.4).