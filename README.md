# 📲 Mobile Push Notification Manual Testing

This repository documents a comprehensive manual QA process for mobile push notification features across Android and iOS platforms. The test cases cover multiple edge cases, app states, user types, and security expectations to ensure high reliability and user experience.

---

## 🧪 Test Coverage Overview

### 1. Authentication & Session States
- Logged-in and logged-out users
- Auto logout due to token expiration, password reset, or admin actions
- Third-party login methods (LDAP, SAML, OAuth)
- Notification behavior during and after session invalidation

### 2. App Lifecycle Events
- App install/uninstall/reinstall
- App version upgrades (manual and auto)
- Notification permission changes

### 3. Multi-Device and Multi-User Testing
- Same user on multiple devices
- Notification read-sync across devices
- Shared device with multiple user accounts

### 4. Notification Behavior
- Deep linking and navigation correctness
- Notification handling in different app states (foreground, background, killed)
- Offline message queue and delivery
- Silent notifications and DND mode testing

### 5. Device Compatibility
- Android (v6 to v14) and iOS (v15 to v18)
- Variety of device manufacturers
- Behavior under low battery / power saving modes

### 6. Load & Performance
- Bulk notification testing
- Cron-triggered delivery
- Handling delivery delays and queuing behavior

---

## 🛠️ Tools & Platforms Used
- Android & iOS devices
- Manual test execution with documented results

---

## 📎 Notes
> This repository is based on generalized QA practices and does **not contain** any confidential, company-specific, or proprietary data. All test cases and observations are shared in a safe and educational context for showcasing QA methodology and skills.

---

## 👩‍💻 Author
**Thilini Kumarawadu**  
Manual QA Engineer | Mobile App Testing | Passionate about edge-case exploration 🚀

---

