This policy explains how the Replis handles information on your device.

**Effective date:** June 4, 2026\
**Developer:** Empat\
**Contact:** replis.support@gmail.com

## 1. Overview

Replis is designed as an offline-first maintenance management application for iOS, Android, and Windows. In normal use, your project data stays on your device and on devices you explicitly pair with through local sharing features. The app does not transmit your data to any external servers operated by us.

## 2. Information we handle

The app may store or process the following information:

- Maintenance records, equipment data, notes, and attachments that you enter.
- Images and other files you choose to add to a project.
- Diagnostic logs generated on your device to assist with troubleshooting. These logs remain on your device unless you choose to export and share them.
- Sync metadata and local database records needed for offline-first operation.
- Device and connection details (such as local IP addresses) needed for local network pairing, discovery, and project sharing.

## 3. How we use information

We use this information only to:

- provide the app's core maintenance-management features;
- store and restore your local data;
- enable diagnostics, export, and troubleshooting;
- support local network pairing and project transfer between devices;
- request and manage device permissions such as camera and photo-library access.

We do not use your data for advertising, profiling, or any purpose beyond what is described here.

## 4. Data storage and sharing

All app data is stored locally on your device using a SQLite database. We do not operate servers that receive or store your data.

When you use the local network sync or project-sharing feature, some data is transmitted directly between devices on your local network (LAN) using WebSocket and mDNS discovery. This data does not leave your local network and is not sent to our servers. Local network transfers are not additionally encrypted by the app; their security depends on the security of your local network.

You decide which devices and users you pair with and share projects with, and you are responsible for that choice. Once data is transferred to another device, it is under the control of the owner of that device. We have no access to that data and cannot control how it is subsequently viewed, stored, retained, or shared by the recipient. You should only share projects with devices and people you trust.

When you export logs or files, the exported content is saved or shared according to the destination you choose. We have no access to exported content.

## 5. Permissions

The app may request access to:

- **Camera** — for QR code scanning during device pairing and for capturing images to attach to records.
- **Photo library** — for selecting existing images to attach to records.
- **Local network** — for discovering and connecting to other devices running the app on the same network.
- **Local files / storage** — for importing and exporting project data or diagnostic logs.
- **Background activity** — for maintaining data sync operations when the app is not in the foreground (Android only).

You can decline any permission. Some features will not be available if a required permission is denied.

## 6. Retention and control

Your data remains on your device until you delete it through the app or clear app storage. Because all data is stored locally, you are in full control at all times. Uninstalling the app or clearing its storage will remove locally stored app data.

The app does not retain copies of your data anywhere outside your device.

## 7. Security

App data is stored in a local SQLite database protected by your device's operating-system-level security. We recommend protecting your device with a passcode, biometric lock, or other OS-level security feature. No security method is perfect, and we cannot guarantee absolute security.

Data transmitted during local network sync travels over your LAN only and is not sent to external servers.

## 8. Third-party services

The app does not include advertising SDKs or analytics platforms that track you across apps or websites.

The app relies on standard operating system services including the camera API, photo library API, file pickers, and local network communication frameworks provided by iOS, Android, and Windows.

Apple and Google may collect crash reports and standard analytics as part of their platform services. Their data practices are governed by Apple's and Google's own privacy policies.

## 9. Children's privacy

This app is intended for professional use by maintenance engineers and technical personnel. It is not directed at children under the age of 13, and we do not knowingly collect any information from children under 13. If you believe a child has used the app in a way that raises a privacy concern, please contact us at the address below.

## 10. Your rights (GDPR)

We process data described in this policy on the basis of contract performance — specifically, to provide the features of the app that you use.

Because all data is stored locally on your device and we do not operate servers that receive your personal data, most GDPR rights (access, rectification, erasure, portability) are exercised directly through the app or by clearing app storage.

Roles: You are the controller of the project content you create, and of any personal data you choose to include in it or transfer to other devices and users. Empat provides the app solely as a tool and does not act as the controller of content that you share between devices, and has no access to it. When you share data with another user, that user becomes responsible for the data they receive.

If you have questions or requests related to your personal data, you may contact us at replis.support@gmail.com. We will respond within 30 days.

You have the right to:

- **Access** — request a summary of what data the app holds about you.
- **Rectification** — correct inaccurate data directly within the app.
- **Erasure** — delete your data through the app or by clearing app storage.
- **Portability** — export your data using the app's export feature.
- **Objection** — contact us if you believe data is being processed in a way that is not described here.

This app does not sell personal data. California residents have the right to know what personal information is collected and to request its deletion by contacting us at the email below.

## 11. Changes to this policy

We may update this policy when the app or its features change. The current version is always available at the stable URL where you found this document. The effective date at the top of this page will reflect the date of the most recent update. Material changes will be reflected by an updated effective date at the top of this page. We encourage you to review this policy periodically.

## 12. Governing law

This policy is governed by the laws of Ukraine. If you are located in the European Economic Area, you may also have rights under the General Data Protection Regulation (GDPR).

## 13. Contact

If you have questions about this privacy policy, please contact:

Email: replis.support@gmail.com
