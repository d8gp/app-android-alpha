# d8gp Android alpha

Alpha builds of the [d8gp](https://d8gp.com) Android app. The APKs on the
[releases page](https://github.com/d8gp/app-android-alpha/releases) are built
and signed by CI from the app's source repository; this repository only holds
the builds.

## Install with Obtainium

[Obtainium](https://github.com/ImranR98/Obtainium) watches this page and
installs each new build as an in-place update, keeping your data.

1. Install Obtainium: download the latest `app-release.apk` from its
   [releases page](https://github.com/ImranR98/Obtainium/releases) and open it.
2. In Obtainium tap **Add App** and paste
   `https://github.com/d8gp/app-android-alpha`
   (or open [this link](obtainium://add/https://github.com/d8gp/app-android-alpha)
   on your phone to pre-fill it).
3. Turn on **Include prereleases**, then tap **Add**.
4. Tap **Install**. Android asks you to allow Obtainium to install unknown
   apps the first time.

New builds then show up as updates in Obtainium.

## Requirements

- Android 8.0 (API 26) or newer.
- The app asks for SMS and Contacts permissions for the messaging features;
  both are optional for browsing feeds.

## Reporting problems

Open an [issue](https://github.com/d8gp/app-android-alpha/issues) with the
version shown in the app's Settings, your phone model, and what you were
doing. Crashes and "that felt wrong" both count.
