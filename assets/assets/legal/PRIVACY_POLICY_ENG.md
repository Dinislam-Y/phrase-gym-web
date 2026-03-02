# PRIVACY POLICY

**EnglishFit — AI-Powered Language Practice Application**

*Last Updated: February 2026*

---

## 1. INTRODUCTION

This Privacy Policy (hereinafter "Policy") describes how EnglishFit (hereinafter "Application", "App", "we", "us", or "our") handles information when You (hereinafter "User", "You", or "Your") download, install, access, or use the Application.

We are committed to protecting Your privacy. EnglishFit is designed as an **offline-first application with optional cloud synchronization** — Your data is stored primarily on Your device, and if You choose to create an account, it may also be synchronized to secure cloud storage. This Policy explains what information the Application accesses, how it is used, and Your rights regarding that information.

By using the Application, You acknowledge that You have read and understood this Privacy Policy.

---

## 2. INFORMATION WE COLLECT

### 2.1. Locally Stored User Data

EnglishFit stores the following information **exclusively on Your device** using local storage mechanisms (SharedPreferences, encrypted secure storage, and local file storage):

   (a) **Profile Information**: display name, bio text, and avatar photo, as provided voluntarily by You;

   (b) **Learning Progress**: lesson completion status, scores, vocabulary progress, streak data, and practice history;

   (c) **Application Preferences**: language settings, notification preferences, theme selections, and other user-configurable options;

   (d) **Subscription Status**: your current subscription plan type and expiration date, cached locally in encrypted secure storage for offline entitlement verification. This data is protected by platform-level encryption (AES-256 on Android, Keychain on iOS) and integrity verification. No payment credentials are stored.

### 2.2. Information We Do NOT Collect

Regardless of whether You use a guest or registered account, EnglishFit does **NOT** collect, transmit, or store:

   (a) Location data or geolocation information;

   (b) Device identifiers, advertising IDs, or hardware fingerprints;

   (c) Usage analytics, behavioral tracking data, or telemetry;

   (d) Contacts, calendar, or other personal data from Your device;

   (e) Any data for the purpose of advertising, profiling, or sale to third parties.

### 2.3. Optional Account Registration

EnglishFit offers optional account creation using email/password or Google Sign-In. You may also use the Application as a guest without any registration.

If You choose to create an account:

   (a) **Email Registration**: Your email address and encrypted password are stored securely via Firebase Authentication;

   (b) **Google Sign-In**: Authentication is handled by Google. We receive only basic profile information (name, email) necessary for account identification;

   (c) **Cloud Sync**: Your learning progress may be synchronized to cloud storage to enable cross-device access;

   (d) **Guest Mode**: All functionality remains available without providing any personal information. Guest data is stored locally only.

---

## 3. HOW WE USE INFORMATION

All locally stored information is used **solely** for the following purposes:

   (a) **Personalizing Your Experience**: displaying Your chosen profile name, bio, and avatar within the Application;

   (b) **Tracking Learning Progress**: recording lesson scores, vocabulary mastery, streaks, and practice history so You can monitor Your improvement over time;

   (c) **Preserving Preferences**: retaining Your selected settings (language, theme, notifications) between sessions;

   (d) **Delivering Lesson Content**: loading bundled lesson content (stored as local JSON assets) for offline use.

No information is used for advertising, marketing, profiling, or any purpose beyond the direct functionality of the Application.

---

## 4. DATA STORAGE AND SECURITY

4.1. **Local Storage.** All user data is stored on Your device using Android/iOS standard local storage mechanisms, including SharedPreferences, encrypted secure storage (AES-256 on Android, Keychain on iOS), and application-sandboxed file storage. Sensitive data such as subscription status is stored in encrypted secure storage with cryptographic integrity verification. Guest users' data is stored exclusively on the device.

4.2. **Cloud Storage for Registered Users.** If You create an account, the following data is synchronized to Google Cloud Firestore to enable cross-device access and data backup:

   (a) Account information: email address, display name, and profile photo URL;

   (b) Learning progress: completed lessons, scores, and total stars;

   (c) User profile data;

   (d) Unlocked achievements and their unlock dates;

   (e) Theory progress: which lesson theories were opened and which theory quizzes were passed;

   (f) Vocabulary progress: per-word learning status, correct answer counts, and last practice dates;

   (g) Binary Choice exercise progress: iteration counts per exercise;

   (h) Last synchronization timestamp;

   (i) Subscription status: plan type and expiration date (if applicable).

Cloud data is stored on Google's infrastructure (Firebase / Google Cloud Platform) and is subject to [Google Cloud's security practices](https://cloud.google.com/security).

4.3. Data stored locally is protected by Your device's operating system security model, including application sandboxing. Access to Application data is restricted to the Application itself and is not shared with other applications.

4.4. Authentication data (email and encrypted password or Google credentials) is managed by Firebase Authentication, a secure identity management service provided by Google. Passwords are never stored in plain text.

4.5. We recommend that Users maintain standard device security practices, including screen lock, device encryption, and keeping the operating system up to date, to protect locally stored data.

4.6. The Developer has access to cloud-stored data of registered users for the purpose of service maintenance and technical support. The Developer does not have access to data stored locally on Your device.

---

## 5. CAMERA AND PHOTO ACCESS

5.1. The Application requests access to Your device camera and/or photo gallery **only** for the purpose of allowing You to set a profile avatar photo.

5.2. Camera and gallery access is:

   (a) **Optional** — the Application functions fully without granting this permission;

   (b) **User-initiated** — access is requested only when You choose to set or change Your avatar photo;

   (c) **Local-only** — the selected or captured photo is stored exclusively on Your device within the Application's local storage and is never uploaded, transmitted, or shared with any external service or server.

5.3. You may revoke camera or gallery permissions at any time through Your device's system settings without affecting other Application functionality.

---

## 6. TEXT-TO-SPEECH

6.1. The Application uses the device's built-in text-to-speech (TTS) engine to provide audio pronunciation of phrases and vocabulary.

6.2. Text-to-speech processing is performed **entirely on Your device** using the system's native TTS service. No text or audio data is transmitted to external servers by the Application for this purpose.

6.3. The availability and quality of TTS functionality depends on the TTS engines and language packs installed on Your device.

---

## 7. THIRD-PARTY SERVICES

7.1. EnglishFit integrates the following third-party services provided by Google:

   (a) **Firebase Authentication** (Google) — for secure user account management, login via email/password, and Google Sign-In;

   (b) **Cloud Firestore** (Google) — for cloud storage and synchronization of registered users' learning progress and profile data;

   (c) **In-App Purchase Services** — for processing in-app purchases and subscriptions. Depending on the distribution platform, the Application uses one of the following billing providers:
      - **RuStore Billing** (VK / RuStore) — for the RuStore distribution;
      - **Apple StoreKit** (Apple) — for the App Store distribution;
      - **Google Play Billing** (Google) — for the Google Play distribution.

   When you make a purchase, the respective platform processes payment information and transaction data. EnglishFit does not directly collect or store your payment credentials (credit card numbers, bank account details). Purchase history and subscription status are stored locally on your device for entitlement verification.

Firebase services are subject to [Google's Privacy Policy](https://policies.google.com/privacy) and [Firebase Terms of Service](https://firebase.google.com/terms). RuStore Billing is subject to [RuStore's Privacy Policy](https://www.rustore.ru/legal/privacy) and [RuStore Terms of Service](https://www.rustore.ru/legal/terms). Apple StoreKit is subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). Google Play Billing is subject to [Google's Privacy Policy](https://policies.google.com/privacy).

7.2. All lesson content is bundled locally within the Application as JSON assets and does not require network access to function. Firebase services are used exclusively for user account management and data synchronization. In-app purchase services are used exclusively for subscription and purchase management.

7.3. EnglishFit does **not** use any advertising networks, behavioral analytics platforms, or crash reporting services. No user data is shared with third parties for advertising or profiling purposes.

7.4. Should future versions of the Application introduce additional third-party service integrations (such as AI-powered features), this Privacy Policy will be updated accordingly prior to or concurrent with the release of such features. Users will be notified of material changes as described in Section 14.

---

## 8. LEGAL BASIS FOR PROCESSING (GDPR ARTICLE 6)

If You are located in the European Economic Area (EEA) or the United Kingdom, we process Your personal data only when we have a valid legal basis to do so. The legal bases we rely on are:

8.1. **Consent (Article 6(1)(a))** — Where You have given explicit consent to the processing of Your personal data for one or more specific purposes. This applies to:

   (a) Optional account registration (email/password or Google Sign-In);

   (b) Cloud synchronization of Your learning progress;

   (c) Profile photo capture and storage via camera/gallery access.

   You may withdraw Your consent at any time by deleting Your account, revoking device permissions, or contacting us at d6apps.dev@gmail.com. Withdrawal of consent does not affect the lawfulness of processing carried out before withdrawal.

8.2. **Performance of a Contract (Article 6(1)(b))** — Processing that is necessary for the performance of the service You have requested. This applies to:

   (a) Providing the core Application functionality (lesson delivery, progress tracking);

   (b) Managing Your subscription and verifying entitlements;

   (c) Processing in-app purchases through the applicable platform billing service.

8.3. **Legitimate Interests (Article 6(1)(f))** — Processing that is necessary for our legitimate interests, provided those interests are not overridden by Your fundamental rights. This applies to:

   (a) Maintaining and improving the Application's functionality and security;

   (b) Preventing fraud and ensuring the integrity of subscription entitlements.

---

## 9. INTERNATIONAL DATA TRANSFERS

9.1. If You create a registered account, Your personal data (as described in Section 4.2) is transferred to and stored on servers operated by Google Cloud Platform (Firebase) located in the **United States**.

9.2. The United States may not provide the same level of data protection as Your country of residence, particularly if You are located in the EEA or the United Kingdom. To safeguard Your data, these transfers rely on the following mechanisms:

   (a) **Standard Contractual Clauses (SCCs)** adopted by the European Commission, as incorporated into Google's Data Processing Terms for Firebase;

   (b) Google's compliance with its [Data Processing and Security Terms](https://firebase.google.com/terms/data-processing-terms), which include commitments to appropriate technical and organizational security measures;

   (c) Any additional transfer mechanisms recognized under applicable data protection law.

9.3. For guest users, no international data transfer occurs — all data remains on Your device.

9.4. For more information about how Google handles data transfers, please refer to [Google Cloud's data transfer framework](https://cloud.google.com/privacy/gdpr).

---

## 10. DATA RETENTION AND DELETION

10.1. The following data retention periods apply:

   (a) **Local data** (all users): retained on Your device for as long as the Application is installed;

   (b) **Cloud data** (registered users): retained on Firebase servers for as long as Your user account exists;

   (c) **Account deletion requests**: upon receiving a valid account deletion request (via in-app deletion or email), all associated cloud data (Firestore documents and Firebase Authentication records) is permanently deleted within **30 days**;

   (d) **Firebase Authentication records**: retained for the lifetime of the account and deleted as part of the account deletion process described above;

   (e) **Subscription and purchase records**: subscription status is cached locally and deleted upon app uninstall or data clear. Platform-side transaction records (Apple App Store, Google Play, RuStore) are retained by the respective platform in accordance with their own retention policies;

   (f) **Backup and residual copies**: after deletion from active systems, data may persist in encrypted backup systems for up to an additional **30 days** before automatic purge.

10.2. You may delete Your local data at any time by:

   (a) **Clearing Application data** through Your device's system settings (Settings → Apps → EnglishFit → Clear Data / Clear Storage);

   (b) **Uninstalling the Application**, which removes all locally stored Application data from Your device;

   (c) Using any **in-app data management features**, if available, to reset progress or delete profile information.

10.3. **For registered users**, You may delete Your cloud-stored data by:

   (a) **Deleting Your account** via Settings → Delete Account in the Application. This process includes a two-step confirmation (confirmation dialog followed by typing a confirmation word). Upon deletion, the following data is permanently removed within 30 days: all cloud data from Firebase servers (Firestore documents), all locally stored data, and the Firebase Authentication account. For Google Sign-In users, the Google account is also disconnected from the Application. If the authentication session has expired, re-authentication (password entry or Google re-sign-in) will be required before deletion can proceed;

   (b) **Contacting the Developer** at d6apps.dev@gmail.com to request data deletion. We will process Your request within 30 days.

10.4. Once deleted, locally stored data cannot be recovered. Cloud data deletion is permanent and irreversible upon completion of the deletion process.

---

## 11. DATA SUBJECT RIGHTS (GDPR ARTICLES 15–22)

If You are located in the European Economic Area (EEA), the United Kingdom, or another jurisdiction that grants similar rights, You have the following rights regarding Your personal data:

11.1. **Right of Access (Article 15)** — You have the right to obtain confirmation as to whether personal data concerning You is being processed, and if so, to request a copy of that data.

11.2. **Right to Rectification (Article 16)** — You have the right to request correction of inaccurate personal data or completion of incomplete data. You may also update Your profile information directly within the Application at any time.

11.3. **Right to Erasure ("Right to Be Forgotten") (Article 17)** — You have the right to request deletion of Your personal data. You may exercise this right by deleting Your account via Settings within the Application or by contacting us (see Section 16). Upon receiving a valid request, we will delete Your data within 30 days.

11.4. **Right to Restriction of Processing (Article 18)** — You have the right to request that we restrict the processing of Your personal data under certain circumstances, such as when You contest the accuracy of the data or have objected to processing pending verification.

11.5. **Right to Data Portability (Article 20)** — You have the right to receive Your personal data in a structured, commonly used, and machine-readable format, and to request that such data be transmitted to another controller where technically feasible. To exercise this right, contact us at the address provided in Section 16.

11.6. **Right to Object (Article 21)** — You have the right to object to the processing of Your personal data at any time, on grounds relating to Your particular situation, where processing is based on legitimate interests.

11.7. **Right Not to Be Subject to Automated Decision-Making (Article 22)** — EnglishFit does not engage in automated decision-making or profiling that produces legal effects concerning You or similarly significantly affects You.

11.8. To exercise any of the above rights, please contact us using the information provided in Section 16. We will respond to Your request within 30 days of receipt. If we need additional time, we will inform You of the reason and the expected timeframe. There is no fee for exercising Your rights, unless requests are manifestly unfounded or excessive.

11.9. If You believe that Your data protection rights have been violated, You have the right to lodge a complaint with a supervisory authority in the EU Member State of Your habitual residence, place of work, or place of the alleged infringement.

---

## 12. DATA BREACH NOTIFICATION

12.1. In the event of a personal data breach that is likely to result in a risk to the rights and freedoms of natural persons, we will notify the competent supervisory authority without undue delay and, where feasible, no later than 72 hours after becoming aware of the breach, in accordance with Article 33 of the GDPR.

12.2. Where the breach is likely to result in a high risk to the rights and freedoms of affected individuals, we will communicate the breach to the affected Users without undue delay, in accordance with Article 34 of the GDPR, describing the nature of the breach, its likely consequences, and the measures taken or proposed to address the breach.

12.3. We maintain internal procedures for detecting, reporting, and investigating personal data breaches.

---

## 13. AUTOMATED DECISION-MAKING AND PROFILING

13.1. EnglishFit does **not** use automated decision-making or profiling as defined by Article 22 of the GDPR. No decisions that produce legal or similarly significant effects are made about You based on automated processing.

13.2. The Application does not use cookies or tracking technologies beyond the basic operational metrics provided by Firebase Analytics (such as app opens and session duration). No behavioral profiles are constructed from this data.

---

## 14. CHANGES TO THIS POLICY

14.1. We reserve the right to update or modify this Privacy Policy at any time. Changes will be reflected by an updated "Last Updated" date at the top of this document.

14.2. Material changes to this Policy — particularly those involving the introduction of data collection, network transmission, third-party service integration, or any change to the local-only data model — will be communicated to Users through:

   (a) A prominent notice within the Application;

   (b) An updated Privacy Policy accessible within the Application and/or its distribution listing (e.g., App Store, Google Play Store).

14.3. Your continued use of the Application following the posting of changes constitutes Your acceptance of such changes.

---

## 15. CHILDREN'S PRIVACY

15.1. EnglishFit is a general-audience language practice application. We do not knowingly collect personal information from children under the age of 13 (or the applicable age of digital consent in Your jurisdiction, including 16 years in certain EU Member States).

15.2. Account registration is optional and not required to use the Application. Guest mode does not collect or transmit any personal information. For registered users under the applicable age of digital consent, parental or guardian consent is required. The Application's data practices are designed to be consistent with children's privacy protections, including the Children's Online Privacy Protection Act (COPPA) in the United States and similar regulations in other jurisdictions.

15.3. If You are a parent or guardian and believe that Your child has provided personal information through the Application beyond what is described in this Policy, please contact us using the information provided in Section 16.

---

## 16. DATA CONTROLLER AND CONTACT INFORMATION

16.1. The data controller responsible for the processing of Your personal data under this Policy is:

   **D6 Apps**
   Email: d6apps.dev@gmail.com

16.2. For any questions, concerns, or requests regarding this Privacy Policy, Your personal data, or the exercise of Your data subject rights, You may contact us at: **d6apps.dev@gmail.com**

16.3. We will make reasonable efforts to respond to all privacy-related inquiries within 30 days.

---

**BY USING THIS APPLICATION, YOU CONFIRM THAT YOU HAVE READ THIS PRIVACY POLICY, THAT YOU UNDERSTAND ITS CONTENTS, AND THAT YOU ACKNOWLEDGE THE DATA PRACTICES DESCRIBED HEREIN.**

---

*© 2026 EnglishFit. All rights reserved.
