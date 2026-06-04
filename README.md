# android-webview-lab

Intentionally vulnerable Android app for demonstrating WebView JavaScript interface exploitation.

Built to accompany the SilentGrid blog post: [Exploiting Android JavaScript Interfaces](https://blog.silentgrid.com/p/c5b06103-c870-43e9-995c-013ca26a3fa6/)

## What's Inside
- `addJavascriptInterface` exposed to untrusted URLs
- `setAllowUniversalAccessFromFileURLs` enabled
- Unvalidated Intent URL loaded into WebView
- Bridge methods exposing file read and auth token access

## Usage
Install via adb:
```
adb install vulnapp.apk
```
Then follow the walkthrough in the blog post.
https://blog.silentgrid.com/exploiting-android-javascript-interfaces/

<img width="483" height="1034" alt="image" src="https://github.com/user-attachments/assets/3a99ea93-095f-4000-9550-00206a6f6192" />


