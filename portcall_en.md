---
layout: post
title: Duru — Voice & Video Calls Privacy Policy
---

**Bizdooroo** (the "Developer," "we," "us," or "our") provides **Duru — Voice & Video Calls** (두런두런, the "Service"). This Privacy Policy explains what information the Service processes, why it is processed, and how to contact us about it. If this translation differs from the Korean version, the Korean version prevails.

## 1. The Service and the Information We Process

The Service is an Android app for voice and video calls between people who sign in with Google and become friends by scanning each other's QR code. We do not collect phone numbers, contacts, or location, and the app does not request those permissions. Call audio and video are never recorded, either in the app or on the server.

| Information | Where and why it is processed |
| --- | --- |
| Google account identifier (sub) and Google account name | Processed at sign-in to verify the Google ID token and link it to an internal account ID on our server. The server does not store your Google email address or profile photo. The Google account name is used only as your initial display name. |
| Display name | Stored on the server so friends see it in their friend list and on the incoming-call screen. You can change it in the app. |
| Internal account ID and sign-in sessions (stored hashed, up to 30 days) | Stored on the server to identify your account and sign-in state. |
| Friend relationships and friend-invite QR codes (stored hashed, valid 10 minutes, single use) | Stored on the server to create friendships and check who may call whom. |
| Push token (FCM) and app installation ID | Stored on the server to deliver call notifications when the app is not open. |
| Call records (call ID, caller and callee internal IDs, start/connect/end times, result) | Written to a server log to manage call state and investigate failures. They contain no names, IP addresses, or call content. |
| Call connection data (SDP and ICE candidates, which include device IP addresses) | Passed through the server to the other device only during a call so the two devices can connect. Not stored on the server. |
| On-device call history (last 100 calls, including call-quality figures), sign-in session, and settings | Kept on your device. |
| Error and crash information (optional) | Processed only if you turn it on, as described in Section 3. |
| Support email address and message | Processed to answer you if you contact us by email. |

## 2. Permissions and Third-Party Features

| Permission | Purpose |
| --- | --- |
| Microphone | Sends your voice to the other person during a call. |
| Camera | Used for video calls and for scanning friend QR codes. It is not turned on for audio-only calls. |
| Notifications, full-screen notifications, vibration | Shows the incoming-call notification and screen, and rings or vibrates. The caller's display name may be visible on the lock screen. |
| Battery optimization exemption, foreground service | Keeps calls running and lets calls arrive while the screen is off. |

You can revoke permissions at any time in your device settings; the related features will then stop working.

- **Google Sign-In**: Google account verification is governed by the [Google Privacy Policy](https://policies.google.com/privacy).
- **Firebase Cloud Messaging (Google)**: Used to deliver call notifications. A notification contains the call ID, the caller's and recipient's internal IDs, the caller's display name, whether it is a video call, and an expiry time, and is valid for at most 30 seconds. The app does not use Firebase Analytics.
- **QR scanning (Google ML Kit)**: QR codes are recognized on the device, and camera images are not uploaded to our server. According to Google, ML Kit may send technical information such as device and app details and performance and error statistics to Google. See the [ML Kit terms and privacy notice](https://developers.google.com/ml-kit/terms).

## 3. Sending Error and Crash Information (Optional)

The "오류 및 크래시 정보 서버 전송" (send error and crash information) switch on the account screen is **off by default**. Only when you turn it on after reading the notice does the app start the Sentry error-analysis service. While it is off, Sentry is not started at all.

| Item | Details |
| --- | --- |
| Sent | Error and crash type and code location (stack trace); call stage and connection method (for example connecting or failed, relayed or not, video or not, server error code); app performance measurements (such as app start time); app version; device manufacturer and model; OS name and version; technical device details such as memory; a random number generated per app installation |
| Not sent | Names or display names, email, Google account information, friend list, call partner, call ID, call audio or video, phone number, contacts, location, device name, app activity logs |
| Purpose | Finding the causes of app freezes and failed call connections, and improving stability |
| How to stop | Turn the switch off on the same screen to stop sending immediately. Uninstalling the app also stops it. |

Before sending, the app filters out everything listed as "Not sent." For errors in the app's Flutter code, the error message text is removed as well, and only the error type and code location are sent. Crashes at the Android system level may include a technical error description generated by the operating system. The random installation number is not linked to any name or account and is used only to group errors from the same device. The app does not put IP addresses into error reports, and our Sentry project is configured not to store IP addresses. Because of how internet communication works, Sentry's servers may still process the connecting IP address at the moment they receive data; Sentry's policies apply to that processing.

| Item | Details |
| --- | --- |
| Processor / recipient | Functional Software, Inc. d/b/a Sentry |
| Contact | [compliance@sentry.io](mailto:compliance@sentry.io), [Sentry Privacy Policy](https://sentry.io/privacy/) |
| Country and method of transfer | United States. When an error occurs while the switch is on, data is sent over encrypted communication (HTTPS). |
| Retention | Kept for the period set by Sentry's data retention policy, then deleted. We use it only for error analysis. |
| How to refuse and its effect | Leave the switch off (the default) or turn it off at any time. All app features keep working when it is off. |

## 4. Retention and Deletion

1. Your account, display name, and friend relationships are kept until you ask us to delete your account. The app does not yet have an in-app account deletion feature, so please send a request to the contact in Section 6. After verification we delete your account, friend relationships, and push tokens.
2. When you sign out, the server deletes that sign-in session and the push tokens tied to it. Removing a friend deletes the friendship in both directions.
3. Server call records are kept for about 7 days and then deleted. Server operation logs are handled according to the server system's retention settings.
4. On-device information (call history, settings) can be removed by clearing the app's data or uninstalling the app. The app does not use Android backup.
5. Support emails are kept for one year to handle your inquiry and then deleted. Where the law requires longer retention, we follow that requirement.

## 5. Service Providers and Safeguards

The server runs on Amazon Web Services (Seoul region) and processes account, friend, and push information and call records. On networks where devices cannot connect directly, a relay (TURN) server operated by the Developer forwards the encrypted call data; the relay may keep connection records containing the connecting IP address and an internal identifier. The relay server does not decrypt call content.

- Communication between the app and the server is encrypted with HTTPS and WSS.
- Call audio and video are encrypted with WebRTC DTLS-SRTP.
- Sign-in sessions and friend-invite codes are stored hashed on the server.

We do not use your information for advertising or tracking, and the app has no ads or in-app purchases.

## 6. Your Requests and Contact

To access, correct, or delete your information, delete your account, stop processing, or ask about privacy, contact us below. Tell us the name shown in the app and the Google account you signed in with. After verifying your identity we will tell you the result, or why we cannot fulfill the request. You can change your display name and remove friends directly in the app.

- Privacy Officer: Jiyeon Jang (장지연), Representative (Developer)
- Operator: Bizdooroo (비즈두루)
- Email: bizdooroo@gmail.com
- Support website: <https://hoppipolla.me>

## 7. Changes

We will announce important changes, such as changes to the information processed or its purposes, in advance on this page or a linked screen.

- First published and effective: October 27, 2026
