---
layout: post
title: Flight Chat Privacy Policy
---

[한국어](bluechat)

**BizDooroo** (the “Developer”) explains below what information **Flight Chat** (the “App”) handles, why, and what choices you have. The App requires no sign-up, and the Developer runs no server that relays or stores your chats. Information stored on your device, information exchanged directly with nearby devices over Bluetooth, data sent by the QR scanning feature, optional error reports you turn on, and inquiry emails are handled separately.

## 1. Information stored on your device

| Item | Purpose and location |
| --- | --- |
| Your trip name (the name others see) and a random device identifier created by the App | Stored on the device to show and distinguish you to people in the same room. No phone number, email or hardware identifier is used. |
| Names, expiry dates and member lists of rooms you joined, nicknames you gave to rooms or people | Shows rooms and members. |
| Presence signals from nearby Flight Chat devices (device identifier, identifiers of the rooms that device is in, time last heard) | Shows members' online status and decides how to route messages. Signals from devices outside your rooms are received too, and kept for up to 35 days. |
| Messages, photos (reduced to a JPEG of 100 KB or less with EXIF, including location, removed before sending), sync records | Shows conversations and fills in missing messages with nearby devices. |
| Temporary relay storage for other people's messages (text messages and room records such as member names from rooms you have not joined) | Kept until that room's expiry date (7 days if unknown) to deliver messages without internet. Never shown in the App, search, notifications or exports. Photos are not relayed. |
| Language and theme, nearby connection on/off, error-report consent | Keeps your settings. |

## 2. Information exchanged with nearby devices

1. When nearby connection is on, the App finds nearby Flight Chat devices with Bluetooth Low Energy and connects to them directly, without the internet or any Developer server. Nearby connection is off on first install and can be turned off in settings or at the top of the chat list. While it is on, the App keeps running in the background after you close it; on Android an ongoing notification is shown.
2. Connected devices exchange the random device identifier, room information, trip names, messages and sync information. Photos are exchanged only between members of that room.
3. To deliver messages without internet, **nearby Flight Chat devices that are not in the same room may also temporarily store text messages and room records such as member names and pass them on to other devices**. In addition, every nearby Flight Chat device receives your device identifier, the identifiers of the rooms you are in and the time it last heard from you, and keeps them for up to 35 days. The App does not show this data on those devices, but the current version does not provide end-to-end encryption. The App is meant for trip companions who trust each other; do not send sensitive information.
4. Invite QR codes and copied invite codes contain the room identifier, name and expiry date, the device identifiers of the room admin and the inviter, and an invite check value. Anyone who sees or receives the code can read this and join the room.

## 3. Permissions

| Permission | Purpose |
| --- | --- |
| Nearby devices (Bluetooth scan, connect, advertise) | Finds nearby devices and exchanges messages. On Android 12 and later it is declared as not used to derive location. |
| Location (requested only on Android 11 and earlier) | Required by those Android versions for Bluetooth device scanning. The App never reads, stores or sends location. |
| Camera | Scans invite QR codes. Captured images are not stored or sent (feature data sent under Section 4 is separate). |
| Photo selection | Sends the one photo you pick to a room. The App does not access your whole photo library. |
| Notifications | Shows new messages on the device while you are not looking at the App. Notifications are created on the device and show the sender's trip name and the message text, so they can appear on the lock screen or connected wearables. You can hide notification content on the lock screen in the operating system's notification settings. |

You can revoke permissions in the operating system settings at any time. Without Bluetooth you cannot chat with nearby devices; without camera, photo or notification access only that feature is unavailable.

## 4. Data sent by QR scanning (Android)

On Android, QR scanning uses Google's ML Kit barcode scanning. Camera frames are processed on the device only, but ML Kit may send device and app information, a per-installation identifier, feature configuration, error codes and performance metrics to Google when the device is online, to maintain the feature's reliability and performance. The Developer does not receive or see this data; Google's [ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure) and [Privacy Policy](https://policies.google.com/privacy) apply. The iOS version uses Apple's on-device features.

## 5. Optional error and crash reports

“Send error and crash reports” is off by default. Only if you turn it on in settings and agree to the notice does the App send the following to Sentry when an error occurs, so the Developer can fix it:

- The type of error (exception name), where in the code it happened (stack trace), when, and whether it was handled
- App name, version and build number, operating system type, runtime (Dart/Flutter) version, and the operating system version and device maker and model (when available)
- Categories of App activity just before the error (for example connection or sync) with numeric counts (number of connected devices, items processed, data size, task durations), whether the App was in the foreground or background, and nearby connection status

The App does **not** send the following. Before sending, it keeps only fields on an allowlist, and drops a report entirely if anything shaped like an identifier (device identifier, Bluetooth address and the like) or any Korean text remains.

- Trip names, message or photo content, room names or identifiers, member information
- Device identifiers, Bluetooth addresses, installation or session identifiers, advertising identifiers, device names
- Location, contacts, screenshots, or the original text of error messages

Reports are sent only when an error occurs in the App's (Dart) code; no activity records, usage statistics or screen performance traces are sent when there is no error. Reports for errors that happen with no internet connection are discarded, not sent later. Because reports travel over the internet, the receiving server processes your IP address during transmission. The App does not put your IP address in reports, and the Developer has configured the Sentry project not to store IP addresses.

Turning the setting off stops further sending immediately. Reports already sent are not deleted automatically; you can request deletion at the contact in Section 10. You can use every feature of the App without turning this on.

## 6. Processing by a service provider and transfer abroad

The error information in Section 5 is entrusted to and transferred abroad to the following provider only with your consent. It is not used for advertising or tracking.

| Item | Details |
| --- | --- |
| Recipient | Functional Software, Inc. d/b/a Sentry |
| Contact | [compliance@sentry.io](mailto:compliance@sentry.io), [Sentry Privacy Policy](https://sentry.io/privacy/) |
| Purpose | Analyzing the causes of App errors and crashes |
| Items | Error information in Section 5 and the IP address seen during transmission (configured not to be stored) |
| Country, timing, method | United States. Sent over HTTPS when an error occurs while error reports are on. |
| Retention | Up to 90 days (Section 7.4) |
| How to refuse | Leave error reports off or turn them off. App features are unaffected, but the Developer will have more difficulty analyzing errors. |

See Sentry's [data storage location](https://docs.sentry.io/organization/data-storage-location/) and [subprocessors](https://sentry.io/legal/subprocessors/). The ML Kit transmission in Section 4 is processed by Google for its own purposes and is not processing entrusted by the Developer.

## 7. Retention and deletion

1. After a room's expiry date passes, the room and its messages, photos and relay storage are deleted from the device the next time the App runs. Rooms expire after 7 days by default; each extension can push the expiry up to 30 days from the time of extension. When a room is deleted its data is deleted with it; a record needed to tell other devices about the deletion (the room identifier and the identifier of the device that deleted it) is kept for up to 35 days. A per-room sequence counter keyed by the room identifier is kept so that message ordering does not collide if you rejoin the same room.
2. All on-device data can be removed by clearing the App's data in the operating system or by uninstalling the App. If operating system backup (such as Android Auto Backup) is on, App data may be included in backup copies, which must be managed in those backup settings. Offloading an app on iOS may keep its data.
3. The Developer cannot remotely delete messages and photos already delivered to other people's devices; they are deleted on those devices according to the same expiry and deletion rules.
4. Error information in Sentry is deleted after at most 90 days according to Sentry's retention policy and the project settings. Sentry's published default retention for error events is 30 or 90 days depending on the plan ([retention periods](https://docs.sentry.io/security-legal-pii/security/data-retention-periods/)).
5. Inquiry emails are kept for one year to answer and resolve issues and then deleted, unless the law requires longer retention.

## 8. Security measures

- There is no server that collects conversations; conversation data is stored only on your device and nearby devices.
- Error reports are sent only with your consent, scrubbed by an allowlist and sent over HTTPS. Only the Developer can access the Sentry project, which has IP address storage prevention and automatic sensitive-data scrubbing turned on.
- The current version does not provide end-to-end encryption between nearby devices. This limitation is explained in Section 2.

## 9. Children

The App is not directed at children under 14 and does not knowingly collect their personal information. If we learn such information has been processed, we will take the steps the law requires.

## 10. Contact and your rights

The sender address, content and attachments of inquiry emails are used only to answer and resolve the inquiry. Please do not send personal information that the inquiry does not need, or information about other people.

You may request access, correction, deletion or suspension of processing of your personal information, withdraw consent, or ask about the transfer abroad at the contact below. A legal guardian or authorized agent may also make requests. Error reports are not linked to any account or real name, so please give only what is needed to locate them, such as the App version and approximate time of the error. If we cannot identify a particular user's information, we will explain what we can and cannot do. The Developer cannot remotely access or delete information stored only on your device.

- Operator: BizDooroo (비즈두루)
- Privacy Officer: Jiyeon Jang (장지연), Representative (Developer)
- Email: [BizDooroo@gmail.com](mailto:BizDooroo@gmail.com)

## 11. Changes

Material changes will be posted on this page and in the store listing at least 7 days before they take effect, and reflected in the App from the corresponding update. Where the law requires separate notice or consent, we will follow that procedure.

- Published and effective: October 27, 2026
