# PRIVACY POLICY

**Phrase Gym — AI-Powered Language Practice Application**

*Last Updated: February 2026*

---

## 1. INTRODUCTION

This Privacy Policy (hereinafter "Policy") describes how Phrase Gym (hereinafter "Application", "App", "we", "us", or "our") handles information when You (hereinafter "User", "You", or "Your") download, install, access, or use the Application.

We are committed to protecting Your privacy. Phrase Gym is designed as an **offline-first application with optional cloud synchronization** — Your data is stored primarily on Your device, and if You choose to create an account, it may also be synchronized to secure cloud storage. This Policy explains what information the Application accesses, how it is used, and Your rights regarding that information.

By using the Application, You acknowledge that You have read and understood this Privacy Policy.

---

## 2. INFORMATION WE COLLECT

### 2.1. Locally Stored User Data

Phrase Gym stores the following information **exclusively on Your device** using local storage mechanisms (SharedPreferences and local file storage):

   (a) **Profile Information**: display name, bio text, and avatar photo, as provided voluntarily by You;

   (b) **Learning Progress**: lesson completion status, scores, vocabulary progress, streak data, and practice history;

   (c) **Application Preferences**: language settings, notification preferences, theme selections, and other user-configurable options.

### 2.2. Information We Do NOT Collect

Regardless of whether You use a guest or registered account, Phrase Gym does **NOT** collect, transmit, or store:

   (a) Location data or geolocation information;

   (b) Device identifiers, advertising IDs, or hardware fingerprints;

   (c) Usage analytics, behavioral tracking data, or telemetry;

   (d) Contacts, calendar, or other personal data from Your device;

   (e) Any data for the purpose of advertising, profiling, or sale to third parties.

### 2.3. Optional Account Registration

Phrase Gym offers optional account creation using email/password or Google Sign-In. You may also use the Application as a guest without any registration.

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

4.1. **Local Storage.** All user data is stored on Your device using Android/iOS standard local storage mechanisms, including SharedPreferences and application-sandboxed file storage. Guest users' data is stored exclusively on the device.

4.2. **Cloud Storage for Registered Users.** If You create an account, the following data is synchronized to Google Cloud Firestore to enable cross-device access and data backup:

   (a) Account information: email address, display name, and profile photo URL;

   (b) Learning progress: completed lessons, scores, and total stars;

   (c) User profile data;

   (d) Unlocked achievements and their unlock dates;

   (e) Theory progress: which lesson theories were opened and which theory quizzes were passed;

   (f) Vocabulary progress: per-word learning status, correct answer counts, and last practice dates;

   (g) Binary Choice exercise progress: iteration counts per exercise;

   (h) Last synchronization timestamp.

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

7.1. Phrase Gym integrates the following third-party services provided by Google:

   (a) **Firebase Authentication** — for secure user account management, login via email/password, and Google Sign-In;

   (b) **Cloud Firestore** — for cloud storage and synchronization of registered users' learning progress and profile data.

These services are subject to [Google's Privacy Policy](https://policies.google.com/privacy) and [Firebase Terms of Service](https://firebase.google.com/terms).

7.2. All lesson content is bundled locally within the Application as JSON assets and does not require network access to function. Firebase services are used exclusively for user account management and data synchronization.

7.3. Phrase Gym does **not** use any advertising networks, behavioral analytics platforms, or crash reporting services. No user data is shared with third parties for advertising or profiling purposes.

7.4. Should future versions of the Application introduce additional third-party service integrations (such as AI-powered features or subscription management), this Privacy Policy will be updated accordingly prior to or concurrent with the release of such features. Users will be notified of material changes as described in Section 10.

---

## 8. CHILDREN'S PRIVACY

8.1. Phrase Gym is a general-audience language practice application. We do not knowingly collect personal information from children under the age of 13 (or the applicable age of digital consent in Your jurisdiction).

8.2. Account registration is optional and not required to use the Application. Guest mode does not collect or transmit any personal information. For registered users under the applicable age of digital consent, parental or guardian consent is required. The Application's data practices are designed to be consistent with children's privacy protections, including the Children's Online Privacy Protection Act (COPPA) in the United States and similar regulations in other jurisdictions.

8.3. If You are a parent or guardian and believe that Your child has provided personal information through the Application beyond what is described in this Policy, please contact us using the information provided in Section 11.

---

## 9. DATA RETENTION AND DELETION

9.1. **Local data** is retained on Your device for as long as the Application is installed. **Cloud data** of registered users is retained on Firebase servers for as long as the user account exists.

9.2. You may delete Your local data at any time by:

   (a) **Clearing Application data** through Your device's system settings (Settings → Apps → Phrase Gym → Clear Data / Clear Storage);

   (b) **Uninstalling the Application**, which removes all locally stored Application data from Your device;

   (c) Using any **in-app data management features**, if available, to reset progress or delete profile information.

9.3. **For registered users**, You may delete Your cloud-stored data by:

   (a) **Deleting Your account** via Settings → Delete Account in the Application. This process includes a two-step confirmation (confirmation dialog followed by typing a confirmation word). Upon deletion, the following data is permanently removed: all cloud data from Firebase servers (Firestore documents), all locally stored data, and the Firebase Authentication account. For Google Sign-In users, the Google account is also disconnected from the Application. If the authentication session has expired, re-authentication (password entry or Google re-sign-in) will be required before deletion can proceed;

   (b) **Contacting the Developer** using the information provided in Section 11 to request data deletion.

9.4. Once deleted, locally stored data cannot be recovered. Cloud data deletion is permanent and irreversible upon completion of the deletion process.

---

## 10. CHANGES TO THIS POLICY

10.1. We reserve the right to update or modify this Privacy Policy at any time. Changes will be reflected by an updated "Last Updated" date at the top of this document.

10.2. Material changes to this Policy — particularly those involving the introduction of data collection, network transmission, third-party service integration, or any change to the local-only data model — will be communicated to Users through:

   (a) A prominent notice within the Application;

   (b) An updated Privacy Policy accessible within the Application and/or its distribution listing (e.g., App Store, Google Play Store).

10.3. Your continued use of the Application following the posting of changes constitutes Your acceptance of such changes.

---

## 11. CONTACT INFORMATION

11.1. For questions, concerns, or requests regarding this Privacy Policy or the Application's data practices, You may contact the Developer through the channels provided within the Application or its distribution listing.

11.2. We will make reasonable efforts to respond to privacy-related inquiries in a timely manner.

---

**BY USING THIS APPLICATION, YOU CONFIRM THAT YOU HAVE READ THIS PRIVACY POLICY, THAT YOU UNDERSTAND ITS CONTENTS, AND THAT YOU ACKNOWLEDGE THE DATA PRACTICES DESCRIBED HEREIN.**

---

*© 2026 Phrase Gym. All rights reserved.
