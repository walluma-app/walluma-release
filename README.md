# Walluma — releases

Binaries for [Walluma](https://github.com/mysideproject/walluma), a free native
macOS live-wallpaper app. It plays looping video wallpapers under the desktop
icons, on every display at once, and on macOS 26 it can drive the lock screen
too. The wallpapers it offers ship inside the app.

Nothing is committed to this repository's tree: installers live as assets on the
[Releases](../../releases) page, and updates are delivered through the Sparkle
appcast at <https://walluma-landing.pages.dev/appcast.xml>.

- **First install:** `Walluma-<version>-arm64.dmg` (Developer ID signed,
  notarized, stapled).
- **Auto-update archive:** `Walluma-<version>-arm64.zip` — what Sparkle
  downloads; notarized and stapled, signed with Walluma's Ed25519 key.

Apple Silicon only. A build compiled from source carries no update key and never
contacts the feed — see [SECURITY](https://github.com/mysideproject/walluma/blob/main/SECURITY.md#network-access)
for how to tell which kind of build you have.

Walluma is a renamed continuation of [Muro](https://github.com/MrRockySL/Muro)
by MrRockySL, and stays under the MIT license.
