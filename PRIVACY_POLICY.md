# MyFamilyTracker Privacy Policy

**Effective Date:** February 15, 2026
_Last updated: November 9, 2026_
**Version:** 2.3.0

MyFamilyTracker ("we," "our," or "us") is a family location tracking and sharing app for Android devices. This Privacy Policy explains what information the app collects, how it is used, and the choices you have. By installing or using MyFamilyTracker you agree to the practices described below.

## Information We Collect

### Location Data
- **Real-time Location**: We collect your device's location data to share with family members in your family group. Location data includes latitude, longitude, timestamp, and accuracy information.
- **Location History**: 
  - **Pro Users**: Location history is stored in Firebase Realtime Database (cloud storage, last 100 entries per user)
  - **Free Users**: Location history is stored locally on your device using Room database (30 days retention, automatically cleaned up)
- **Location Accuracy**: We collect location accuracy information to provide better location services and display accuracy indicators.
- **Location sent to the Google Maps Static API**: when the app shows a location or emergency notification with a small map image in it, the latitude and longitude being shown are sent to `maps.googleapis.com` so Google can generate that image. This is separate from the map inside the app, which is drawn on your device.

### Account Information
- **User Profile**: Name, email address, and phone number (if provided during account creation or profile editing).
- **Authentication**: User ID from Firebase Authentication. You can sign in with Google, with your phone number, or anonymously. **If you sign in with your phone number, that number is sent to Firebase Authentication and Google sends you a verification SMS** — in that case the number is an account identifier, not optional profile data.
- **Family Group**: Family group membership, invite codes, and family group participation.

### Device Information
- **Device ID**: Unique device identifier for location tracking and app functionality.
- **App Usage**: Basic app usage data for functionality (family group membership, location sharing preferences).

## How We Use Your Information

### Location Sharing
- Share your real-time location with family members in your family group.
- Display your location on a map for family members to view.
- Provide location-based features and services.
- Enable "Jump to Location" and "Show All Members" features.

### Account Management
- Create and manage your user account.
- Manage family group memberships (create, join, leave groups).
- Provide profile editing capabilities.
- Maintain authentication state.

### Service Improvement
- Improve app functionality and user experience.
- Fix bugs and technical issues.
- Ensure app security and stability.
- Provide diagnostic information in Location Settings.

MyFamilyTracker shows optional rewarded video ads from Google AdMob when you choose to watch an ad to unlock a feature. We do not sell, rent, or monetize your data to third parties.

## Storage and Retention

### Data Storage
- **Location data** is stored in Firebase Realtime Database (Google Cloud infrastructure).
- **User profiles** are stored in Firebase Realtime Database.
- **Family group data** is stored in Firebase Realtime Database.
- **App preferences** (location sharing enabled/disabled) are stored locally on your device.

### Data Retention
- Location data is stored while you use the app and share your location.
- Location data is updated in real-time and previous locations are replaced with new ones.
- **Location History Retention**:
  - **Pro Users**: Last 100 entries retained in Firebase Realtime Database
  - **Free Users**: 30 days retention in local encrypted storage (Room database)
- You can delete your account and data at any time (contact support).

### Data Security
- Data is encrypted in transit using HTTPS/TLS, to every service named in this policy.
- Data is encrypted at rest in Firebase Realtime Database.
- Access to data is restricted to authenticated users.
- Firebase provides industry-standard security measures.
- Your location, profile and family group data are held by Google (Firebase). Crash and performance data also goes to Sentry, which is a separate company and a separate United States location — see Third Parties for exactly what it receives.

## Data Sharing

### Family Groups
- Your location is shared **only** with members of your family group.
- Family group members can see your location in real-time on the map.
- You can leave a family group at any time, which stops sharing your location with that group.
- You control who can see your location by managing family group membership.

### Third Parties
- We use **Firebase** (Google) for backend services (authentication, database, cloud messaging).
- We use **Google Maps** for map visualization and location services.
- We use **Google Location Services** for location tracking.
- See [Google's Privacy Policy](https://policies.google.com/privacy) for their data practices.
- See [Firebase Privacy Policy](https://firebase.google.com/support/privacy) for Firebase data practices.
- We use **Firebase Crashlytics** (Google) to collect crash reports. When the app crashes, Crashlytics may collect the crash details, your device model, Android OS version, app version, and a Crashlytics installation ID. We use this only to find and fix bugs.
- We use **Sentry** for crash and performance monitoring. **Sentry is not a Google service**, and this app sends to a United States endpoint (`ingest.us.sentry.io`). Sentry receives crash details and stack traces, performance traces for roughly one in ten app sessions, and breadcrumbs recording which buttons and controls you tapped before an error — those breadcrumbs name the control, so they can include the label shown on it. **Screenshots are switched off.** The app sets no identity for you in Sentry and sends it no location data, no family group data and no profile fields. We use it only to find and fix bugs and slow screens. See [Sentry's Privacy Policy](https://sentry.io/privacy/).
- Sentry can also be sent the layout of the screen an error happened on, which on this app's screens can include member names and place labels shown in the layout. **This is switched off from app version 2.2.2 onward.** In version 2.2.1 and earlier it is switched on, so if you are running one of those versions it applies to you until you update.
- We use the **Google Maps Static API** to draw the small map image inside a location or emergency notification. To do that, the app sends the latitude and longitude being shown to `maps.googleapis.com`. This is a Google web service and is separate from the map you see inside the app, which is drawn on your device.
- We use **Firebase Cloud Functions** (Google) to run server-side code that sends notifications to your family members and validates purchases. Those functions read the data needed for the notification, and their diagnostic logs record account identifiers.
- We use **Google Play Billing** for subscriptions and in-app purchases, including validating them and restoring them, and for the rewards in the referral programme. Google Play processes purchase status; we never receive or store your payment details.
- We use **Google AdMob** to show optional rewarded ads. The AdMob SDK may collect your device's advertising ID and other device identifiers, IP address, device and app information, and how you interact with ads. Google uses this to deliver and measure ads, limit how often you see them, and prevent fraud.
- You can reset or delete your advertising ID in your device's Google settings.
- See [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites) for AdMob data practices.

We do **not** share your data with:
- Advertising networks other than Google AdMob (we do not pass your location, profile, or family group data to AdMob)
- Data brokers
- Any service not named in this section

Every processor this app sends data to is named above: Google (Firebase Authentication, Realtime Database, Cloud Messaging, Cloud Functions, Analytics, Crashlytics, Maps, Play Billing, AdMob) and Sentry. There are no others.

## Permissions Used

### Required Permissions

* **ACCESS_FINE_LOCATION** (Precise location): Essential for the app's core functionality. Allows MyFamilyTracker to track and share your location with family members. Without this permission, the app cannot function.
* **ACCESS_COARSE_LOCATION** (Approximate location): Used as a fallback when precise location is not available.
* **ACCESS_BACKGROUND_LOCATION** (Android 10+): Required to track your location in the background while the app is not in the foreground. This ensures continuous location sharing with family members.
* **FOREGROUND_SERVICE** and **FOREGROUND_SERVICE_LOCATION**: Required to maintain the location tracking service running in the background. This ensures location updates continue even when the app is in the background.
* **POST_NOTIFICATIONS** (Android 13+): Required to show a persistent notification indicating that the location service is active. This notification cannot be dismissed while the service is running, as required by Android for foreground services.
* **INTERNET**: Required to communicate with Firebase servers for authentication, data storage, and location sharing.
* **ACCESS_NETWORK_STATE**: Used to check network connectivity status.
* **VIBRATE**: Used for haptic feedback.

### Permissions added by Android libraries

The app declares the nine above. The finished build carries six more, declared by the libraries it is built on rather than by the app's own code. They appear in the permission list you see on the Play Store, so they are listed here for completeness:

* **ACCESS_ADSERVICES_AD_ID**, **ACCESS_ADSERVICES_ATTRIBUTION**, **ACCESS_ADSERVICES_TOPICS** and **com.google.android.gms.permission.AD_ID**: Android's Privacy Sandbox advertising APIs, declared by the Google AdMob and Firebase Analytics libraries. Unlike most of our apps, these are genuinely advertising-related here: MyFamilyTracker shows rewarded ads, described under Third Parties above. They let AdMob read your advertising ID, measure which ads led to an install or an action, and use Android's Topics API. You can reset or delete your advertising ID in your device's Google settings.
* **WAKE_LOCK**: Declared by Firebase Cloud Messaging. Lets a push notification wake the device enough to be delivered.
* **com.google.android.finsky.permission.BIND_GET_INSTALL_REFERRER_SERVICE**: Declared by the Google Play libraries. Lets Google Play tell the app which link or campaign the install came from.

Verified against the merged manifest of the release build rather than the app's own manifest file.

### Optional Permissions

* **None currently** - All permissions the app declares are required for core functionality. The six library permissions above are not requested from you and cannot be revoked individually; they are granted at install time.

## Your Rights and Controls

### Location Sharing Control
- You can **enable/disable location sharing** in app settings at any time.
- When location sharing is disabled, your location is not updated or shared with family members.
- You control who can see your location by managing family group membership.
- You can leave a family group at any time to stop sharing with that group.

### Account Management
- You can **edit your profile information** (name, email, phone) in the app settings.
- You can **leave family groups** at any time.
- You can **delete your account** using the methods described in the Data Deletion section.
- You can **sign out** of the app at any time.

### Data Access
- You can view your profile data in the app settings.
- You can see your location data in the app (your current location on the map).
- You can view your family group membership in Family Settings.
- You can export your data (future feature).

### GDPR Rights (EU Users)
If you are in the European Union, you have additional rights:
- **Right to Access**: Request a copy of your personal data
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of your data
- **Right to Restrict Processing**: Limit how we use your data
- **Right to Data Portability**: Receive your data in a portable format
- **Right to Object**: Object to certain types of processing

To exercise these rights, contact us using the methods in the Contact Us section.

### Permissions
- You can revoke location permissions in Android Settings → Apps → MyFamilyTracker → Permissions.
- Note: Revoking required permissions will prevent the app from functioning.
- You can disable location sharing in the app settings without revoking permissions.

## Children's Privacy

- Our app is **not intended for children under 13**.
- We do not knowingly collect data from children under 13.
- If you are a parent or guardian and believe your child has provided personal information, please contact us to request deletion.
- Parents should supervise their children's use of location-sharing apps.

## Security

- Data is encrypted in transit using HTTPS/TLS.
- Data is encrypted at rest in Firebase Realtime Database.
- Firebase provides industry-standard security measures.
- Access to data is restricted to authenticated users.
- Location data is only accessible to family group members.
- We use secure authentication methods (Google Sign-In, Firebase Authentication).

## Changes to This Policy

We may update this Privacy Policy to reflect new features, legal requirements, or changes in our practices. Significant changes will be:
- Noted in the app release notes (CHANGELOG.md)
- Displayed in the app (if significant)
- Updated with a new "Last updated" date

The "Last updated" date at the top of this policy indicates when revisions occurred. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, wish to request data deletion, or have privacy concerns:

* **GitHub Repository:** https://github.com/SUDARSHANCHAUDHARI/myfamilytracker-privacy-policy
* **Email:** sunny.sudarshan@gmail.com
* **Main App Repository:** https://github.com/SUDARSHANCHAUDHARI/MyFamilyTracker

We will respond as quickly as possible, typically within 48 hours.

## Data Deletion

### How to Delete Your Account:
You have **multiple options** to delete your account and all associated data:

#### Option 1: In-App Deletion
1. Open MyFamilyTracker app
2. Go to **Profile Settings**
3. Select **"Delete Account"**
4. Confirm deletion in the pop-up

This removes your location history, your profile, your family group membership, your geofences, your notification and privacy settings, your sharing schedule, your movement statistics and your battery status.

**One thing it does not yet remove: the sign-in record itself**, which is the entry in Firebase Authentication holding the identifier you sign in with. Deleting your account from inside the app signs you out and leaves that record in place. An app update that removes it in the same step is in progress; until it ships, email us as in Option 2 and we will delete it. We would rather say this plainly than let you believe it is already gone.

#### Option 2: Email Deletion Request
Send an email to: **support@sudarshantechlabs.com**
- Subject: "Account Deletion Request"
- Include: Your registered email address
- We'll process deletion within 48 hours

#### Option 3: Clearing the App's Local Data
- Android Settings > Apps > MyFamilyTracker > Storage > Clear Data, or uninstall the app
- This removes the app's local copy on your device, including the locally stored location history that free accounts keep. It does not delete anything held in Firebase, so use Option 1 or Option 2 for that.

There is no deletion form on this page. This page is a static document with no scripts and no forms; email is how a request reaches us.

### What Gets Deleted:
- ✅ All location history, both the cloud copy and the copy on your device
- ✅ User profile information
- ✅ Family group membership
- ✅ Geofence data
- ✅ Notification preferences, privacy settings, sharing schedule, movement statistics and battery status
- ✅ The sign-in record holding your identifier — today by email request, see Option 1

### Data Retention After Deletion:
- **Immediate:** Account becomes inaccessible
- **30 days:** Data completely removed from servers
- **Backup:** No backups retained after deletion

To request deletion of your data:

1. Open the MyFamilyTracker app
2. Go to Settings → Profile
3. Contact support via email: sunny.sudarshan@gmail.com
4. Request account and data deletion
5. All your data will be permanently deleted, including:
   - User profile
   - Location data
   - Family group membership
   - All associated data

## Firebase and Google Services

This app uses Firebase and Google services. Please review their privacy policies:

- [Firebase Privacy Policy](https://firebase.google.com/support/privacy)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Maps Terms of Service](https://cloud.google.com/maps-platform/terms)
- [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites)

## About MyFamilyTracker

MyFamilyTracker is a professional Android application for real-time family location tracking and sharing. The app is built with:
- Kotlin programming language
- Firebase for backend services
- Google Maps for map visualization
- Google Location Services for location tracking
- Google AdMob for optional rewarded ads

The app is designed with privacy in mind - you control who can see your location, and location data is only shared with family group members you explicitly join.

---

**Last Updated:** November 9, 2026

---

## Recent Updates (Version 2.3.0 - November 9, 2026)

- **Disclosed Sentry.** The app sends crash reports, performance traces for about one session in ten, and breadcrumbs naming the controls you tapped to Sentry, which is **not a Google service** and receives them at a United States endpoint. This had never been disclosed, and the previous wording of this section denied using "Analytics services (beyond Firebase Analytics)" and "Other third-party services" — both of which were untrue while Sentry was in the app. That denial is replaced with a list of every processor and the statement that there are no others.
- **Said that the screen layout can go to Sentry too**, which on this app's screens can include member names and place labels, and that this is switched off from app version 2.2.2 onward. It is on in 2.2.1 and earlier.
- **Disclosed the Google Maps Static API.** When a notification shows a small map image, the latitude and longitude being shown are sent to `maps.googleapis.com` to generate it. The policy previously said only that we "use Google Maps for map visualization", which reads as the on-device map.
- **Disclosed Firebase Cloud Functions and Google Play Billing**, neither of which was named, and the referral programme's rewards.
- **Listed the six permissions Android libraries merge in.** The app declares nine; the finished build carries fifteen. Unlike our other apps the advertising ones are genuinely advertising-related here, since MyFamilyTracker shows rewarded ads, so they are explained rather than waved away.
- **Said that phone sign-in sends your number to Firebase and triggers a verification SMS.** The policy named only Google and anonymous sign-in and treated a phone number as optional profile data.
- **Corrected the account-deletion section.** Deleting your account in the app does not yet remove the sign-in record holding your identifier; it signs you out and leaves that record. The policy now says so and tells you to email us until the app update lands. Also removed "Option 3: Web Deletion", which gave step-by-step instructions — enter your email, click Delete My Account, confirm via email link — for a form that has never existed on this page. It is replaced with how to clear the app's local data, which is a real option and matters here because free accounts keep location history on the device.

## Recent Updates (Version 2.2.0 - October 19, 2026)

- **Advertising Disclosure**: Disclosed the optional Google AdMob rewarded ads and the data the AdMob SDK may collect
- **Crash Reporting Disclosure**: Disclosed Firebase Crashlytics crash reports and listed the VIBRATE permission

## Recent Updates (Version 2.1.0 - February 15, 2026)

- **Enhanced Account Deletion**: Added multiple deletion methods (in-app, email, web)
- **GDPR Compliance**: Added comprehensive GDPR rights section for EU users
- **Local Storage for Free Users**: Free users' location history is now stored locally on their device using encrypted local storage (Room database) with 30-day automatic retention
- **Pro Users**: Pro users continue to have unlimited cloud storage in Firebase Realtime Database with the last 100 entries retained
- **Improved Data Retention**: Clear explanation of data retention policies for both free and pro users
- **Better User Rights**: Enhanced section on user controls and data access rights

