# Imellie Android music app

Imellie is a modified GPL-3.0 build based on [InterTune](https://github.com/ItzSkyeYT/InterTune), with credits to InterTune, OuterTune and InnerTune. The application ID and launcher name are Imellie. The interface adds animated liquid glass navigation and button interactions.

The [build workflow](.github/workflows/build-apk.yml) checks out a pinned upstream revision and applies [`imellie-customize.patch`](imellie-customize.patch). Download the `Imellie-debug` artifact from a successful GitHub Actions run and install its APK on Android. This debug build uses a runner-generated signing key, so updates may require reinstalling.

The source and modifications retain the upstream GPL-3.0 license.
