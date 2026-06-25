<div align="center">

<img src="assets/images/logo.svg" width="96" />

# IRC

**A fast, secure, multi-platform proxy client.**

[фارсی](README_fa.md) · [Русский](README_ru.md) · [简体中文](README_cn.md) · [日本語](README_ja.md) · [Português-BR](README_br.md)

</div>

---

## What is IRC?

IRC is a multi-platform proxy client built on the [Sing-box](https://github.com/SagerNet/sing-box) universal proxy tool-chain. It offers automatic node selection, TUN mode, remote profiles, and a clean, modern interface. IRC is ad-free and open-source, with support for a wide range of protocols for a secure and private connection.

## 🚀 Main features

- ✈️ **Multi-platform** — Android, iOS, Windows, macOS and Linux
- ⭐ **Modern, intuitive UI** — refreshed dark & light themes
- 🔍 **Delay-based node selection**
- 🛡 **Wide protocol support** — VLESS, VMess, Reality, TUIC, Hysteria, WireGuard, SSH, and more
- 🔗 **Subscription & config formats** — Sing-box, V2Ray, Clash, Clash Meta
- 🔄 **Automatic subscription updates**
- 🔎 **Profile info** — remaining days and traffic usage
- 🌙 **Dark and light modes**
- ⚙ **Compatible with all proxy management panels**

## 🛠 Building from source

This is a Flutter application.

```bash
flutter pub get
dart run build_runner build --delete-conflicting-outputs   # generates translations, assets, etc.
flutter run            # or: flutter build <apk|ipa|windows|macos|linux|web>
```

## 🌎 Translations

You can improve existing languages or add new ones by editing the JSON files in [`/assets/translations`](./assets/translations). Run the code generator afterwards so the changes are compiled in.

## ✏️ Acknowledgements

This project stands on the shoulders of these excellent open-source projects:

- [Sing-box](https://github.com/SagerNet/sing-box)
- [Sing-box for Android](https://github.com/SagerNet/sing-box-for-android)
- [Sing-box for Apple](https://github.com/SagerNet/sing-box-for-apple)
- [Clash](https://github.com/Dreamacro/clash)
- [Clash Meta](https://github.com/MetaCubeX/Clash.Meta)
- [Vazirmatn Font by Saber Rastikerdar](https://github.com/rastikerdar/vazirmatn)
- [Others](./pubspec.yaml)

## 🙏 Attribution & upstream

**IRC is an open-source fork of [Hiddify](https://github.com/hiddify/hiddify-app).**
We gratefully acknowledge the Hiddify project and its contributors, whose work forms the foundation of this application.

- Original project: https://github.com/hiddify/hiddify-app
- Original license: https://github.com/hiddify/hiddify-app?tab=License-1-ov-file#readme

### Changes made in this fork

In accordance with the upstream license (GPL v3, Section 7 — *Attribution* condition), the changes introduced in this fork are documented here:

- **Rebranding** — the user-facing application name and display identity were changed from "Hiddify" to "IRC" (app titles, window titles, localized in-app strings, store/installer display metadata, and documentation). Internal package identifiers, bundle IDs and the deep-link URL scheme were intentionally left unchanged.
- **Visual redesign** — a refreshed Material 3 theme with an indigo brand accent (`#455FE9`, matching the app logo), rounded cards, refined typography and spacing, and a cohesive light/dark palette.
- The robot-head logo and the core proxy functionality are unchanged from upstream.
- Community/support links were repointed to this fork and its operator.

## 📄 License

IRC is licensed under the **Extended GNU General Public License v3**, the same license as the upstream Hiddify project. See [LICENSE.md](./LICENSE.md) for the full text, including the additional GPL v3 Section 7 conditions that apply.
