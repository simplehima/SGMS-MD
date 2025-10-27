# Privacy Policy

_Last updated: October 2025_

Thank you for using **SGMS** (“the App”, “we”, “our”, or “us”).  
Your privacy is important to us. This Privacy Policy explains how we collect, use, and protect your information when you use our services.

---

## 1. Information We Collect

### 1.1. Personal Information
When you use SGMS, we may collect personal information necessary to create and manage your account, such as:

- **Email address**
- **Name** (if provided during registration)
- **Authentication credentials** (managed securely via Firebase Authentication)

We do **not** collect or store your password in plain text. Authentication is handled directly by **Firebase Auth**, which complies with industry-standard security and encryption practices.

### 1.2. Usage and Log Data
We automatically collect limited technical data to maintain and improve app performance, including:

- Crash reports and error logs (through our internal `crash_logger.dart`)
- Device type and operating system version
- App version and build number
- Timestamps of major user actions (e.g., login, logout, update checks)

This data is anonymous and cannot identify individual users.

### 1.3. Optional Data
If you interact with certain SGMS features (e.g., course progress, account updates, or release publishing), the app may temporarily store related operational data to improve your experience. These records are not shared externally.

---

## 2. How We Use Your Information

We use the collected information to:

- Authenticate users and manage access securely  
- Provide, maintain, and improve the App’s functionality  
- Diagnose crashes, fix bugs, and enhance stability  
- Notify users about important updates or changes  
- Ensure compliance with licensing or version management processes

---

## 3. Data Storage and Security

All user authentication and sensitive operations are handled through **Google Firebase**, which uses encryption in transit (HTTPS) and at rest.

We also apply additional safeguards via:
- Secure key management (`keys_service.dart`)
- Controlled update mechanisms (`update_manager.dart`, `app_update_service.dart`)
- Server-side validation for releases and licenses

No raw credentials or sensitive user data are ever stored locally or transmitted to unauthorized parties.

---

## 4. Data Sharing and Disclosure

We **do not sell, rent, or trade** your personal information.  
Your data is only shared under these limited circumstances:

- **Service Providers:** Firebase Authentication, Cloud Firestore, or similar backends may process data on our behalf under strict privacy terms.
- **Legal Requirements:** If required by law or valid legal process.
- **App Maintenance:** Aggregated or anonymized usage data may be analyzed to improve features.

---

## 5. Your Data Rights

You have the right to:

- **Access** the information associated with your account  
- **Request deletion** of your account and data  
- **Update or correct** your personal information  

To exercise these rights, contact us via the support channel provided in the app or email below.

---

## 6. Data Retention

We retain user account data only for as long as your SGMS account remains active or as necessary to provide you with services.  
Crash and diagnostic logs are stored temporarily for performance analysis and deleted periodically.

---

## 7. Third-Party Services

SGMS may integrate with the following third-party services:

- **Firebase Authentication**
- **Firebase Crashlytics**
- **Google Play Services**

Each service has its own privacy policy:
- [Firebase Privacy & Security](https://firebase.google.com/support/privacy)
- [Google Privacy Policy](https://policies.google.com/privacy)

---

## 8. Children’s Privacy

SGMS is intended for professional and educational use.  
We do not knowingly collect data from children under 13.  
If you believe a child has provided personal information, please contact us so we can remove it.

---

## 9. Updates to This Policy

We may update this Privacy Policy from time to time.  
Any changes will be reflected in this document with a new “Last updated” date.  
Significant updates may also be announced within the app.

---

## 10. Contact Us

If you have any questions or concerns about this Privacy Policy or data handling in SGMS, please contact:

**Email:** hima.azab.eg@gmail.com
**Developer:** SGMS Team  
**Country:** Egypt  

---

© 2025 SGMS. All rights reserved.
