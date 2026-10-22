---
layout: post
title: Secret Vote Privacy Policy
---

**Bizdooroo** (the "Developer," "we," "us," or "our") provides **Secret Vote** (the "Service"). This Privacy Policy explains what information the Service processes, why it is processed, and how to contact us about it.

## 1. The Service and the Information We Process

The Service is an online polling service that lets you create questions and share them through QR codes or links without creating an account. Creating polls, participating in polls, and calculating results require communication with our servers. We do not require names, email addresses, or telephone numbers to create or participate in a poll, and the Service does not provide a feature that collects participants' real names and links them to their choices. However, any personal information you enter in a poll question or answer option will also be sent to our servers. Please do not enter personal or sensitive information about yourself or anyone else.

| Information processed | Where and why it is processed |
| --- | --- |
| Poll title, optional description, answer options, whether multiple selections are allowed, and creation time | Sent to and stored on our servers to provide the poll. |
| Randomly generated poll identifiers and organizer management identifiers | Processed on your device and our servers to distinguish polls and validate management requests from organizers. |
| Submitted answer-option identifiers, totals for each option, and participation counts | Processed on our servers to accept votes and calculate results. We do not create a participant register that requires names. |
| Organizer poll history, results, on-device participation indicators, and language and display preferences | Stored in your device's local database and settings storage. Local poll history may include the organizer management identifier. |
| Operational logs, such as request identifiers, request times, API paths, response statuses, and processing times | Recorded on our servers to troubleshoot problems and operate the Service. Network providers may process connection information, such as IP addresses, when handling communications. |
| Your email address and the content of your inquiry | Processed to respond to you and resolve issues if you contact us by email. |

## 2. Camera Access and External Features

Camera permission is used when you choose to scan a QR code. The app does not include a feature that uploads images from the scanning screen to our servers. If you do not grant camera permission, you can still use features that do not require the camera, such as creating polls.

QR code recognition takes place on your device, using Apple Vision on iOS and Google ML Kit on Android. According to Google, ML Kit does not send input images or recognition results to Google's servers. However, on Android, ML Kit sends technical information to Google for diagnostics and usage analytics, including device and app version information, installation-specific identifiers, and performance, error, and API usage statistics. This information is subject to the [Google Privacy Policy](https://policies.google.com/privacy) and [ML Kit privacy information](https://developers.google.com/ml-kit/terms). For details, see [ML Kit's Android data disclosure](https://developers.google.com/ml-kit/android-data-disclosure). This ML Kit disclosure applies to the Android version, not the iOS version.

You can revoke camera access at any time in your device settings. This disables QR code scanning, but features that do not require the camera remain available. Revoking camera permission does not delete poll information already sent to our servers.

The sharing feature passes a poll link and accompanying text to the external app you select. If you choose to open a web page, it opens in an external browser. Information processed by other apps or websites is governed by their respective policies.

## 3. Retention and Deletion

1. Active polls are processed in a server-side Redis store. The default expiration is seven days after creation, but handling may vary depending on whether a poll has ended and the state of result recovery. Seven days is not a final deletion deadline for all poll data.
2. The content and aggregated results of ended or expired polls are retained in separate server-side storage for result recovery and backup. There is currently no automatic deletion period that applies to all stored results of ended polls. You may request deletion using the contact details below. We will review the data concerned and verify your authority to make the request before processing it.
3. Deleting poll history in the app deletes the history on that device. Ending a poll or deleting local history does not mean that results retained on our servers are immediately deleted. You can remove on-device information by clearing the app's data or uninstalling the app. Copies created through operating-system backup and restore features are subject to the relevant operating-system settings.
4. Inquiry emails are retained for one year to handle inquiries and are then deleted. Operational logs and technical information processed by service providers are handled according to the operating and retention settings of the relevant systems. Where retention is required by law, we comply with those requirements.

## 4. Service Providers and Safeguards

We use Amazon Web Services for API processing, result-file storage, and logs, and Upstash for Redis data storage. Amazon Web Services processes poll information and identifiers transmitted through the API, archived results, and operational logs. Upstash processes active poll information, identifiers, and aggregate counts. These providers process information on our behalf to provide online polls and result recovery. The app uses HTTPS for API communications. Anyone who receives a poll's QR code or link can access that poll, so please choose carefully whom you share it with. Do not disclose organizer management identifiers to others.

The Developer does not provide features that use poll information for advertising sales or user tracking, and the app does not include advertising or in-app purchases. Service providers process information on our behalf under their respective policies and applicable agreements. For questions about processing locations or international transfers, please contact us using the details below.

## 5. Your Requests and Contact Information

To request access to, correction of, or deletion of information processed by the Service, withdraw consent to personal information processing, or ask a privacy-related question, please contact us below. Include the relevant poll link or identifier and the action you are requesting. We may verify the poll and your authority to make the request to the extent necessary to process it. We will explain the outcome or why we cannot fulfill the request. Do not post another person's information or confidential organizer management identifiers publicly.

To stop sending additional poll information, stop using features that require server communications, such as creating polls or submitting votes. Stopping use or uninstalling the app does not delete information already retained on our servers; please request deletion separately. Because votes are not managed using participants' real names or accounts, we may be unable to identify an individual participant's vote or delete that vote separately. In such cases, we will explain what action is possible and the reasons for any limitations.

- Privacy Officer: Jiyeon Jang (장지연), Representative (Developer)
- Operator: Bizdooroo (비즈두루)
- Email: bizdooroo@gmail.com
- Support website: <https://hoppipolla.me>

## 6. Changes to This Policy

We will provide advance notice of material changes, such as changes to the information processed or the purposes of processing, on this page or a linked screen. The October 15, 2026 correction clarifies the server-side processing and retention currently used for online polls, corrects the earlier inaccurate statement that the Service operates only on the device without sending information to servers, and corrects the inquiry email address.

- First published: January 30, 2026
- Correction published and effective: October 15, 2026
- Clarification of permission withdrawal and request procedures: October 22, 2026 (no new data collection or purposes of use)
