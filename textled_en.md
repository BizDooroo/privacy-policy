---
layout: post
title: Bitmal Privacy Policy
---

[한국어](textled)

**Bizdooroo** (the “Developer,” “we,” or “us”) explains how **Bitmal - LED Scrolling Sign (빛말)** (the “Service”) handles information below.

## 1. The Service and Information Handling

The Service shows a message you type in large type on your screen, like an LED sign, without requiring an account. It is offered as a phone and tablet app; where a desktop app (Windows, macOS, Linux) or a web version is offered, this policy applies to it as well. The messages you enter, their styles, your favorites and recent items, and your app settings are stored on your device (in the browser for the web version) and are not sent to the Developer's servers. You do not need to provide your name, contact details, or account information. Emails you voluntarily send to support are handled as described in Section 5.

## 2. Information Stored on Your Device and Its Purposes

| Information | Purpose |
| --- | --- |
| Messages you enter and their font, size, color, LED, motion, blink, and effect settings | Reopen the sign you are editing and the sign you used last. |
| Favorites (including the names and order you give them) and up to 50 recently shown or edited signs, with the time each was last used | Let you show or edit them again from the library. |
| Playlists (the names you give them, when they were made, their display orientation, the favorites they hold and their order, and how long each one shows) | Show several signs one after another. |
| Packs you download (font, phrase, background, and style files, license documents, and install information) | Use those fonts, phrases, backgrounds, and styles without an internet connection. |
| Language and theme, display defaults such as keeping the screen on, maximum brightness, auto-off, and the default orientation, the unlock method, list preview autoplay, and the safety notices you have already confirmed | Keep your chosen display preferences and avoid repeating safety notices. |

The phone and tablet app stores this in the storage the operating system provides to the app; the desktop app in your user account's app-data folder (`%APPDATA%\BizDooroo\Bitmal` on Windows; `~/Library/Application Support/com.bizdooroo.textled`, or the same folder inside the app's container, on macOS; `~/.local/share/com.bizdooroo.textled` on Linux); and the web version in that browser's site storage (localStorage, and IndexedDB for packs). Packs are kept in a `packs` folder in the same storage location. If a saved file is damaged and cannot be read, the app does not delete it but keeps a copy (`.bak`) in the same storage location.

## 3. Permissions and External Services

The app does not request microphone, location, or contacts access. It uses the camera only to scan a shared QR code and asks for camera permission when you tap "Scan QR". The camera image is used on your device only to read the QR code and is never stored or sent. When reading a QR code from an image, only the one image you choose in the operating system's photo or file picker is given to the app; the app does not request access to your whole photo library. It does not use advertising, user tracking, or external analytics or crash-reporting SDKs, and does not provide your messages or settings to the developer or third parties, outsource their processing, or transfer them overseas (sharing that you start yourself works as described below). Keeping the screen on and raising the brightness while a sign is shown work only on your device and are restored when you stop showing it or the app leaves the screen. If the app ends abnormally, the brightness may not return at once; you can adjust it in your device settings.

So you can open them from the home screen, the Android app hands the names of your favorites and playlists (a favorite without a name is numbered, such as "Favorite 1") to your device's launcher for app shortcuts and the home-screen widget. A name you gave may contain words of its message; the app hands these names only to the device's shortcut and widget lists and never sends them off the device (a backup made by the operating system is covered in Section 4). The message itself is not handed over. Shortcuts and widgets placed on the home screen may keep showing the last name after you delete that favorite or playlist, until you remove them from the home screen.

When you tap "Share", the app creates, on your device, a link, a QR image, or a `.textled` file holding the sign's message and style settings, and hands it to the operating system's share sheet or the clipboard. You decide what to send and to whom; the developer does not receive or keep shared content. In a share link (`https://hoppipolla.me/textled/s#…`) the sign data sits after the `#` in the address, so the browser that opens the link does not send it to the server. The preview page that opens stores nothing and uses no cookies or analytics. It is delivered from storage and a content delivery network (CloudFront) of Amazon Web Services (AWS), which the developer uses; in the process, AWS servers, including servers abroad near you, may process connection information such as your IP address, the time, and the address requested. The developer keeps no access logs, and the sign data after the `#` is not part of this. When you open a shared link, QR code, or file in the app, it shows a preview first and fetches nothing from addresses written inside it. The app reads the clipboard only when you tap "Paste".

When the web version shows a character that the fonts included in the app do not cover (some emoji, symbols, or scripts), it may download the font file that draws that character from Google's font server. Your browser connects to Google's server directly, so connection information may be transferred overseas as follows. The message you typed is not sent.

| Item | Details |
| --- | --- |
| Recipient | Google LLC (`fonts.gstatic.com`), [Google Privacy Policy](https://policies.google.com/privacy) |
| Information | Connection information such as your IP address and browser details, and the requested font file |
| Country and timing | The United States and other countries where Google's servers are located; sent over an encrypted connection (HTTPS) when the web version first shows such a character |
| Retention | Under Google's policy. The Developer does not receive or keep this information. |
| How to refuse and effect | Use only characters the app's own fonts cover, or use the phone, tablet, or desktop app; nothing is sent then. Some characters may not appear. |

Only when you tap "Get" on the Packs screen or in a font or background notice does the app download additional font, phrase, background, or style pack files from jsDelivr, a public content delivery network (CDN). If a file cannot be downloaded from jsDelivr, some fonts are downloaded once more from their original distributor on GitHub. The requests carry no account, device identifier, or cookie and do not include your messages, and the list of downloadable packs is built into the app, so it is not requested from a server. Your device connects to these servers directly, so connection information may be transferred overseas as follows.

| Item | Details |
| --- | --- |
| Recipient | The jsDelivr public CDN (`cdn.jsdelivr.net`), [jsDelivr Privacy Policy](https://www.jsdelivr.com/terms/privacy-policy-jsdelivr-net); when some fonts are downloaded again, GitHub, Inc. (GitHub-operated hosts such as `github.com`, `raw.githubusercontent.com`, and `release-assets.githubusercontent.com`), [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) |
| Information | Connection information such as your IP address, and the address of the requested pack file (browser details for the web version) |
| Country and timing | The countries where the jsDelivr servers nearest to you are located, and the United States and other countries for GitHub; sent over an encrypted connection (HTTPS) when you tap "Get" |
| Retention | Under each company's policy. The Developer does not receive or keep this information. |
| How to refuse and effect | Nothing is sent unless you tap "Get". The fonts included in the app remain available. |

The web server that delivers the web version may also process connection information while serving its pages. Unless you tap "Get", the phone, tablet, and desktop apps download no files.

If you separately use an external website or email app, such as the privacy policy link in the app or an email inquiry, that service's policy applies.

## 4. Retention and Deletion

Signs, favorites, playlists, recent items, and settings are kept on your device until you delete them. In the library you can delete favorites or recent items one by one or clear the recent list, and playlists can be deleted on the Playlists screen; the recent list also drops its oldest items automatically so that it never holds more than 50. Downloaded packs can be deleted one by one on the Packs screen or all at once with "Delete all".

You can remove all on-device information by clearing app data where the operating system supports it or by deleting the app. For the desktop app, delete the app-data folder in Section 2 (this also removes any `.bak` copies); for the web version, delete the site's data (site storage) in your browser settings. Offloading an app on iOS may retain its data and is different from deleting it. Copies created by operating-system backup and restore features must be managed separately in the relevant backup settings; deleting the app does not by itself delete those copies.

## 5. Support Information and Your Rights

If you submit a look for the official look packs as a GitHub issue, that issue (your GitHub username, the look link you paste, and what you write) is public on GitHub and GitHub's policies apply. The developer reviews submitted looks and, if one is included, credits it in the pack only with the credit name you gave (or "a Bitmal user"). The credit name stays public while that pack is distributed; on request to the contact below, it is removed from packs released afterwards. Paste a "Look only" link and do not write personal data in the issue.

If you contact us by email, we process your sender email address, message, and attachments only to respond and resolve your inquiry. We retain this information for one year and then delete it. Contacting support is optional and is not required to use the app. Please do not send unnecessary personal information or information about other people. Email providers are used to transmit and store correspondence.

You may contact us below to request access to, correction or deletion of, or restriction of processing of your inquiry information, or to withdraw consent. A legal guardian or authorized representative may also make a request; we verify their authority only to the extent necessary. Provide only the minimum information needed to locate the inquiry, such as the sender email address and approximate date. We explain the outcome or any applicable limitations in accordance with applicable law. Uninstalling the app does not automatically delete emails you have already sent.

We cannot remotely access, correct, or delete information stored only on your device. Please manage it through the app and operating-system controls. We delete inquiry information when it is no longer needed; if retention is legally required, we retain it on the applicable legal basis for the required period.

- Operator: Bizdooroo (비즈두루)
- Privacy Officer: Jiyeon Jang (장지연), Representative (Developer)
- Email: [bizdooroo@gmail.com](mailto:bizdooroo@gmail.com)

## 6. Things to Keep in Mind

People around you can see the messages you show, so take care when displaying personal information such as your or others' phone numbers or addresses. Do not use the app while driving or mount it in a vehicle as a sign. The text of a shared sign is written by the person who shares it, who is responsible for it. Do not share content that infringes other people's privacy or rights.

## 7. Changes to This Policy

We announce material changes, such as changes to the information processed or its purposes, on this page or a linked screen in the app at least seven days before they take effect. We provide separate notice or obtain consent when required by law. If a new feature changes how information is handled, we will add it to this policy before offering the feature.

- First published and effective: November 1, 2026
- Amendment announced: November 1, 2026 (font pack downloads added); effective: November 8, 2026
- Amendment announced: November 2, 2026 (sharing by QR code, link, and file; the camera for QR scanning; phrase, background, and style packs; playlists and home-screen shortcuts and widget added); effective: November 9, 2026
