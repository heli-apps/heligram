<div align="center">

<img src="https://heligram.org/icon_aqua.png" width="112" height="112" alt="Heligram">

# Heligram

**Telegram, without the parts you never open.**

A Telegram client for Android and desktop. Pick the features you install,<br>
read unseen, and keep what others delete.

[![Android](https://img.shields.io/badge/Android-APK-3DDC84?logo=android&logoColor=white)](https://api.heligram.org/v1/releases/latest/android/apk)
[![Linux](https://img.shields.io/badge/Linux-AppImage-FCC624?logo=linux&logoColor=black)](https://api.heligram.org/v1/releases/latest/linux/appimage)
[![Channel](https://img.shields.io/badge/Telegram-@heligramorg-26A5E4?logo=telegram&logoColor=white)](https://t.me/heligramorg)
[![License](https://img.shields.io/badge/license-GPL--3.0-blue)](#license)

[Website](https://heligram.org) · [Download](#download) · [Channel](https://t.me/heligramorg) · [Chat](https://t.me/heligramchat) · [Plugins and themes](https://t.me/heligramhub)

</div>

> [!NOTE]
> Heligram is in active development. Features and screens may still change.
> Source code is coming to this repository soon.

---

## Install only what you use

Calls, stories, stars, mini apps and seven more parts of Telegram are separate
modules. Skip any of them on first launch and add it later from Settings.
Whatever you skip never touches your phone, and an installed module can be
removed again from the same screen.

| Chats and calls | Content | Payments | Tools |
|---|---|---|---|
| Calls | Stories | Stars | Mini apps |
| Secret chats | Gifts | Telegram Business | In-app browser |
| Translation | Boosts and giveaways | | Telegram Passport |

## Read without being seen

Ghost mode keeps read receipts, typing and your online status on your phone.
Turn it on for everyone, or set exceptions for single chats.

| | |
|---|---|
| Read receipts | Not sent |
| Story views | Not sent |
| Typing status | Not sent |
| Online status | Hidden |
| Your messages | Go out 12 s later |
| Sponsored messages | Off |

## Video notes that look like video

Heligram records round videos with its own camera engine and squeezes out
everything a video note can carry. Every knob is yours: lens, bitrate,
stabilization, mirroring.

| | Stock app | Heligram |
|---|---|---|
| Resolution | 384-512 px | **640 px**, the largest Telegram accepts |
| Frame rate | | **60 fps**, fixed or auto range |
| Bitrate | | **8 Mbit/s** by default, adjustable |

The **Heligram filter** *(beta)* adds temporal denoise that cleans grain across
frames instead of smearing detail, edge-aware sharpening and a gentle lift for
dark scenes.

## Private by design

To Telegram, a Heligram login is one more official client on one more ordinary
device.

- **A device of its own.** Every install gets a randomized identity, either
  Telegram Desktop or the official Android app, generated once and kept.
- **Your choice of code.** Get the login code by SMS or on another device.
  Telegram has the final say on delivery.
- **Official credentials** *(in development)*. Login through our server as a
  proxy with official Telegram app credentials.

## Find any message, offline

Heligram keeps a local index of your chats. Search without waiting on the network.

- **Text**: plain words across every chat, answered from the device.
- **Regex**: patterns for the things you only half remember: flight numbers, codes, links.
- **Semantic**: finds messages by meaning, photo and file captions included,
  through your own embeddings endpoint.

## And the small things you will use daily

- **Keeper.** Messages other people delete or edit stay with you, dimmed, with
  every earlier version. Last seen and read times are recorded too.
- **Message filters.** Hide incoming messages that match a regex. Your own and
  service messages are never touched.
- **Tweaks.** A long list of fixes for small annoyances in the stock app.
- **Menu extras.** Put the actions you reach for into the chats list menu.
- **Send from other accounts.** Reply from any account you are logged into,
  without switching.
- **Only the popups that matter.** No "Is this still your number?", no call
  permission prompts for features you never asked for.

## Coming next

- **Plugins.** Small tweaks as Lua plugins. Each declares its permissions in a
  manifest, like an Android app, and you approve them when you turn it on.
  Need more power? Build a module: signed native code with the full app at hand.
- **Helithemes.** Themes that change more than colors: bubble shapes,
  wallpapers and patterns, avatars, animations. Ships as its own module.
- **Heli Sync.** Keeper history follows you to every device, sealed end to end.
  Our server stores blobs it cannot read.

## On your computer too

A desktop client for Linux, macOS and Windows. Same chats, same account,
the same Rust core underneath.

## Written in a modern stack

<p>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin">
<img src="https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white" alt="Rust">
</p>

The Android UI is Kotlin, everything native is Rust. Based on Telegram for Android.

## Download

Free and open source. Log in with your Telegram account, nothing else to sign up for.

| Platform | Package | |
|---|---|---|
| Android | APK for arm64 phones | [Download APK](https://api.heligram.org/v1/releases/latest/android/apk) |
| Linux | AppImage / deb | [AppImage](https://api.heligram.org/v1/releases/latest/linux/appimage) · [deb](https://api.heligram.org/v1/releases/latest/linux/deb) |

## Community

| | |
|---|---|
| [@heligramorg](https://t.me/heligramorg) | News and releases |
| [@heligramchat](https://t.me/heligramchat) | Chat and support |
| [@heligramhub](https://t.me/heligramhub) | Verified plugins, modules and themes |
| [@heliapps](https://t.me/heliapps) | The Heli apps family |

## Support us

Support Heligram with any amount and get a **supporter badge** (tier 1):
send a screenshot of the transfer to [@heliapps](https://t.me/heliapps) in direct messages.

| Network | Address |
|---|---|
| USDT (TRC20) | `TYeVSBSwdim74edSTSbgd7cXCVkJjpipmN` |
| TON | `UQDRiSZ8zKLaH7X2DNm6FYnM3_J2KrfI6vu4gvE5X8t52WLk` |
| Bitcoin | `bc1q8da758gkp8pju8rwxuxarst3dm3z26s2tnjw3p` |
| Ethereum / Polygon | `0xb4627E08c62BAd3261547aAEA2eEA503b32dd817` |
| Solana | `62S7aQKZHNvziRXSeYSSUF1J2LMja7eo7GHM1AoGrbdE` |

## License

Heligram is free software under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).

<sub>Not affiliated with Telegram FZ-LLC.</sub>
