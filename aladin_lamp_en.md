---
layout: post
title: Aladin Lamp Privacy Policy
---

[한국어](aladin_lamp)

**BizDooroo (비즈두루)** (the “Developer,” “we,” or “us”) explains the information processed by **Aladin Lamp (알라딘램프)** (the “app”), its purposes, and your choices below. The app does not require an account. Information stored on your device, communications needed for book services, optional error reporting, and support emails are handled separately.

## 1. Information Processed on Your Device

| Information | Purpose and location |
| --- | --- |
| Search history, watched books and their identifiers, and cached book/used-stock information | Stored on your device to provide search history, watchlists, stock queries, and purchase planning by store. |
| Filters, display preferences, and background-check, notification, autocomplete, and diagnostics preferences | Stored on your device to preserve your selected features and display choices. |
| Notification schedules and background-task state | Used on your device to schedule and manage stock checks and local notifications. |
| Local execution logs | Request addresses and request information that may contain search terms/book identifiers, task times, and errors are recorded on your device to inspect execution status. These are separate from diagnostics sent to Sentry. |

## 2. External Communications for Book Queries

The app connects to Aladin's website and image servers for search, autocomplete, book/used-stock queries, and cover images. Searches send your search terms; autocomplete sends the text you are typing; book/stock queries send book identifiers and store-related query parameters. Image retrieval requests the cover-image address. Receiving servers may process connection information, such as IP addresses, access times, and request addresses.

If you enable background checks, the app may query stock for watched books even when you are not viewing the app. Disabling autocomplete stops automatic requests while typing, but searches you submit and book/stock queries still communicate externally. Disabling background checks stops scheduled stock checks.

Aladin is an external book-search and stock-information service, distinct from an error-analysis processor such as Sentry. Retention and rights relating to connection information processed by Aladin are governed by the [Aladin Privacy Policy](https://www.aladin.co.kr/account/wprivacy.aspx). The relevant service's policy also applies when you open a book page in an external browser or use another app.

## 3. Optional Error and Diagnostic Reporting

“Send diagnostic logs” (“진단 로그 보내기”) is off by default. If you enable it, the app initializes Sentry to analyze errors, crashes, app health, and performance issues. The following information may be transmitted during app use and background tasks:

- App version, operating system/device model, language/time zone, and device state such as memory and storage
- Error types/messages, stack traces, event times, active screens/features, task activity, and network state
- SDK-generated installation, event, and session identifiers, and stability information such as session start/end and crash status
- Aggregate diagnostics such as watched-book counts, store counts, stock-candidate counts, calculation time, and whether calculation limits were exceeded
- IP addresses processed by the receiving server during transmission and approximate location that may be derived from them

We do not separately set names, email addresses, or similar direct identifiers as Sentry user information. The app's diagnostic helpers are configured to use lengths, counts, and success indicators in place of search terms, book titles, book identifiers, and store names. However, automatic error reporting includes execution context such as error messages and stack traces. This does not mean all data is anonymized or that personal information can never be included. The app has no feature that collects precise location or contacts for diagnostics.

Turning diagnostics off is intended to stop subsequent diagnostic collection and transmission. Information already received by the server is not automatically deleted; you can request deletion using the contact in Section 7. Declining diagnostics does not prevent use of core features such as book search and stock checks.

## 4. Processing Providers and International Transfers

Optional diagnostics are processed by the following provider on our behalf for error analysis. They are not provided for advertising sales or tracking you across other apps or websites.

| Item | Details |
| --- | --- |
| Processor and recipient | Functional Software, Inc. d/b/a Sentry |
| Contact | [compliance@sentry.io](mailto:compliance@sentry.io), [Sentry Privacy Policy](https://sentry.io/privacy/) |
| Purpose | Analysis of errors, crashes, app stability, and performance |
| Information transferred | Error, diagnostic, session, and connection information described in Section 3 |
| Timing and method | HTTPS transmission over the internet when error, diagnostic, or session events occur while diagnostics are enabled |
| Transfer location | The Sentry ingestion address currently configured in the app is a US-region address. See the official materials below for Sentry's storage locations and subprocessors. |
| Retention | See the Sentry retention explanation in Section 5. |
| How to decline and consequences | Leave “Send diagnostic logs” off or turn it off. Core features remain available, but our ability to analyze the relevant errors is limited. For requests about existing information, see Section 7. |

Sentry states that it stores events in the United States or Germany depending on the selected region, and processes certain administrative information in the United States regardless of region. It provides [storage-location information](https://docs.sentry.io/organization/data-storage-location/) and a [subprocessor list](https://sentry.io/legal/subprocessors/). The ingestion address alone does not establish every retention and transfer setting of the actual project. For questions about the project's specific retention and processing locations, contact us under Section 7.

## 5. Retention and Deletion

1. You can delete search history, watched books, and cached book information using **Reset data** (“데이터 초기화”) in settings. This does not erase all app preferences or local execution logs. **Resync book information** (“책 정보 다시 동기화”) refreshes cached information while retaining watched books.
2. To remove all app data, including device preferences and local logs, clear app data where the operating system supports it or delete the app. Offloading an app on iOS may retain data and is different from deleting it. The app does not set a separate, uniform automatic deletion deadline for local logs.
3. Operating-system backup and restore copies must be managed separately in the relevant backup settings. Deleting the app does not by itself delete backups, information received by external services, or emails you have already sent to support.
4. Sentry error and diagnostic information is deleted according to its retention policy and the settings applicable to the project. Sentry's published default retention for error events is **30 days on the Developer plan and 90 days on Team, Business, and Enterprise plans**, with possible Enterprise retention options. This is [Sentry's general retention guidance](https://docs.sentry.io/security-legal-pii/security/data-retention-periods/), not a guarantee that every type of diagnostic/session information or backup has the same retention period. See Section 7 for individual deletion requests.
5. Inquiry emails are retained for one year to respond and resolve issues, and are then deleted. Where retention is legally required, information is retained on the applicable legal basis for the required period. Information under the Developer's control is deleted when retention is no longer necessary.

## 6. Notifications, Choices, and Safeguards

Notification permission is used to display stock-check results and similar notices on your device. You can revoke it in operating-system settings and still use book search. Turning off “Show book titles in notifications” (“알림에 책 제목 표시”) prevents book titles from being displayed in notifications. Disabling notification permission is separate from disabling background stock checks or diagnostics.

App information is processed in the device's app storage, and Sentry diagnostic transmissions use HTTPS. Diagnostic data explicitly prepared by the app is processed to reduce unnecessary identifying information. External communications for book queries and local logging may continue separately even when diagnostics are disabled.

The app is not directed to children under 14 and does not knowingly collect their personal information. If we learn that such information has been processed, we take necessary action, including deletion, in accordance with applicable law. Legal guardians may also contact us or exercise rights through the contact below.

## 7. Support Information and Your Rights

We use sender email addresses, inquiry contents, and attachments only to respond and resolve issues. Contacting support is optional and is not required to use the app. Email providers are used to transmit and store correspondence. Please do not send unnecessary personal information or information about other people.

You can contact us below to request access to, correction or deletion of, or restriction of processing of personal information, withdraw consent, or make a request concerning international transfers. A legal guardian or authorized representative may also make a request. Provide only the minimum information needed to identify the information concerned, such as the inquiry date, app version, or error time. We verify authority only to the extent necessary and explain the outcome or any limitations in accordance with applicable law. Because there are no accounts and diagnostics are not managed by linking them to real names, we may be unable to identify a particular user's events. In that case, we explain available actions and limitations. We cannot remotely delete information stored only on your device.

- Operator: BizDooroo (비즈두루)
- Privacy Officer: Jiyeon Jang (장지연), Representative (Developer)
- Email: [BizDooroo@gmail.com](mailto:BizDooroo@gmail.com)

For external advice or dispute resolution in Korea, you may contact the [Personal Information Infringement Report Center](https://privacy.kisa.or.kr/) or the [Personal Information Dispute Mediation Committee](https://www.kopico.go.kr/).

## 8. Changes to This Policy

We publish material changes in the app or on this page at least seven days before they take effect. We provide separate notice or obtain consent when required by law. Earlier versions are available in the [document history](https://github.com/BizDooroo/privacy-policy/commits/main/aladin_lamp.md) or through our contact address.

- First effective: June 29, 2026
- Clarification published and effective: October 22, 2026
- This clarification explains external book queries, optional diagnostics, local logs, and the scope of deletion. It does not introduce new collection features.
