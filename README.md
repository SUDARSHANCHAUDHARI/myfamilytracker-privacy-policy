# MyFamilyTracker Privacy Policy

**Last updated: January 1, 2026**

This Privacy Policy applies to the mobile application **MyFamilyTracker**, published by **Sudarshan Tech Labs**.

**Official website:** https://sudarshantechlabs.com  
**Company email:** sudarshantechlabs@gmail.com  
**Developer contact:** sunny.sudarshan@gmail.com

MyFamilyTracker ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use our mobile application.

## Information We Collect

### Location Data
- **Real-time Location**: We collect your device's location data (latitude, longitude) to share with family members in your family group
- **Location History**: 
  - **Pro Users**: Location history is stored in Firebase Realtime Database (cloud storage, last 100 entries per user)
  - **Free Users**: Location history is stored locally on your device using Room database (30 days retention, automatically cleaned up)
- **Location Accuracy**: We collect location accuracy information (in meters) to provide better location services
- **Location Timestamps**: We record when location updates occur
- **Geofences**: If you create geofences, we store their locations, names, types, and radii

### Account Information
- **User Profile**: Name, email, phone number (if provided)
- **Authentication**: User ID from Firebase Authentication (Google Sign-In or Anonymous)
- **Family Group**: Family group membership and invite codes
- **Privacy Settings**: Your privacy preferences including:
  - Invisible mode status
  - Location fuzzing preferences
  - Members to hide the location from
  - Time-based sharing schedules

### Device Information
- **Device ID**: Unique device identifier for location tracking
- **FCM Token**: Firebase Cloud Messaging token for push notifications
- **Battery Level**: Device battery level (optional, for status display)
- **Network Status**: Online/offline status

### Analytics and Crash Data
- **App Usage Analytics**: We use Firebase Analytics to understand how you use the app
  - Events tracked: Sign-in, location sharing toggles, geofence creation, emergency alerts
  - No personally identifiable information is collected in analytics
- **Crash Reports**: We use Firebase Crashlytics to identify and fix app crashes
  - Crash reports include device information, app version, and error details
  - No personal information is included in crash reports

## How We Use Your Information

### Location Sharing
- Share your real-time location with family members in your family group
- Display your location on a map for family members to view
- Provide location-based features and services

### Account Management
- Create and manage your user account
- Manage family group memberships
- Provide profile editing capabilities

### Service Improvement
- Improve app functionality and user experience
- Fix bugs and technical issues (via crash reports)
- Ensure app security and stability
- Analyze app usage patterns (via analytics)
- Optimize app performance

### Emergency Features
- Send emergency alerts with your location to family members
- Store emergency alert data temporarily for family members to view

## Data Storage and Security

### Storage
- **Real-time Location**: Current location data is stored in Firebase Realtime Database (for all users)
- **Location History**:
  - **Pro Users**: Stored in Firebase Realtime Database (cloud storage)
  - **Free Users**: Stored locally on your device using Room database (encrypted local storage)
- **User Profiles**: Stored in Firebase Realtime Database
- **Data Encryption**: 
  - Cloud data: Encrypted in transit (HTTPS/TLS) and at rest (Firebase encryption)
  - Local data: Encrypted using Android's built-in encryption for local databases

### Security
- We use industry-standard security measures
- Firebase provides secure data storage
- Access to data is restricted to authenticated users

### Data Retention
- **Real-time Location**: Current location is stored in real-time in Firebase Realtime Database
- **Location History**:
  - **Pro Users**: Stored in Firebase Realtime Database, keeps the last 100 entries per user
  - **Free Users**: Stored locally on your device, automatically deleted after 30 days
- **User Profile**: Stored in Firebase Realtime Database until you delete your account
- **Privacy Settings**: Stored in Firebase Realtime Database until you delete your account
- **Geofences**: Stored in Firebase Realtime Database until you delete them or your account
- **Emergency Alerts**: Stored temporarily in Firebase Realtime Database until marked inactive
- **Local Storage**: Free users' location history stored locally is automatically cleaned up after 30 days
- **Analytics Data**: Aggregated analytics data is retained by Firebase (see Firebase Privacy Policy)
- **Crash Reports**: Retained by Firebase Crashlytics for analysis
- **Account Deletion**: You can delete your account and all associated data at any time (both cloud and local data)

## Data Sharing

### Family Groups
- Your location is shared only with members of your family group
- Family group members can see your location in real-time
- You can leave a family group at any time

### Third Parties
- **We do not sell your data to third parties**
- **Firebase (Google)**: We use Firebase for:
  - Authentication (Google Sign-In, Anonymous)
  - Realtime Database (data storage)
  - Cloud Messaging (push notifications)
  - Analytics (app usage statistics)
  - Crashlytics (crash reporting)
- **Google Maps**: Used for map visualization and location services
- **Data Processing**: Firebase and Google Maps process data on our behalf to provide services
- See [Firebase Privacy Policy](https://firebase.google.com/support/privacy) and [Google Privacy Policy](https://policies.google.com/privacy) for their data practices

## Your Rights and Controls

### Location Sharing Control
- **Enable/Disable**: You can enable/disable location sharing in app settings at any time
- **Time Limits**: You can set location sharing to expire after a specific duration (1 hour to 30 days, or never)
- **Privacy Controls**: Advanced privacy features allow you to:
  - Hide your location from specific family members
  - Use location fuzzing to show the approximate location instead of the exact
  - Set time-based sharing schedules (only share during specific times)
  - Enable invisible mode to hide your online status
- **Family Group Control**: You control who can see your location (family group members only)
- **Leave Groups**: You can leave family groups at any time, which stops sharing with that group

### Account Management
- You can edit your profile information
- You can leave family groups
- You can delete your account (contact support)

### Data Access
- **Profile Data**: You can view and edit your profile data in the app (Settings → Profile)
- **Location Data**: You can view your current location and location history in the app
- **Privacy Settings**: You can view and modify your privacy settings (Settings → Privacy & Security)
- **Data Export**: You can export your location history in CSV or JSON format (Settings → Location Settings → Location History → Export)
- **Account Deletion**: You can request account deletion (contact support)

## Children's Privacy

- **Age Requirement**: Our app is not intended for children under 13 (or under 16 in the EU)
- **No Child Data**: We do not knowingly collect data from children under 13
- **Parental Consent**: If you are a parent or guardian and believe your child has provided us with personal information, be sure to get in touch with us immediately
- **Account Deletion**: We will delete any child's data if we become aware that it has been collected

## Changes to This Policy

- We may update this Privacy Policy from time to time
- We will notify you of significant changes
- Continued use of the app after changes constitutes acceptance

## Contact Us

If you have questions about this Privacy Policy, your data, or wish to exercise your rights:

- **Email**: [Add your contact email here]
- **GitHub Issues**: [Add your GitHub repository URL here]
- **In-App Support**: Settings → Help & Support → Contact Support

**Data Protection Inquiries**: For questions about data protection, data access, or account deletion, don't hesitate to get in touch with us using one of the methods above.

## Firebase and Google Services

This app uses Firebase and Google services. Please review:
- [Firebase Privacy Policy](https://firebase.google.com/support/privacy)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Maps Terms of Service](https://cloud.google.com/maps-platform/terms)

## Data Deletion and Your Rights

### Right to Deletion
You have the right to request deletion of your account and all associated data:
1. Open the app
2. Go to Settings → About → Contact Support
3. Request account deletion
4. All your data will be permanently deleted within 30 days

### What Gets Deleted
When you delete your account, we will delete:
- Your user profile (from Firebase)
- All location data (current and history from Firebase)
- All local location history (if you're a free user, local database entries are deleted)
- All privacy settings
- All geofences
- All emergency alerts
- Family group membership

### What May Remain
- Aggregated, anonymized analytics data (cannot be linked to you)
- Crash reports (anonymized, no personal data)
- Data required by law or for legitimate business purposes

### GDPR Rights (EU Users)
If you are in the European Union, you have additional rights:
- **Right to Access**: Request a copy of your personal data
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of your data
- **Right to Restrict Processing**: Limit how we use your data
- **Right to Data Portability**: Receive your data in a portable format
- **Right to Object**: Object to certain types of processing

To exercise these rights, contact us using the methods above.

## Permissions Explained

### Location Permissions
- **ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION**: Required to track and share your location
- **ACCESS_BACKGROUND_LOCATION**: Required for continuous location tracking when the app is in the background
- **Why**: Core functionality of the app requires location access

### Notification Permission
- **POST_NOTIFICATIONS** (Android 13+): Required to send push notifications
- **Why**: To notify you of family member locations, geofence events, and emergency alerts

### Network Permission
- **INTERNET**: Required to connect to Firebase and Google Maps
- **ACCESS_NETWORK_STATE**: Required to check network connectivity
- **Why**: App requires an internet connection to function

### Vibration Permission
- **VIBRATE**: Used for haptic feedback in emergency alerts
- **Why**: Provides tactile feedback for important alerts

---

## Security Measures

- **Encryption**: All data is encrypted in transit (HTTPS/TLS) and at rest (Firebase encryption)
- **Authentication**: Access to data requires Firebase Authentication
- **Firebase Security Rules**: Database access is restricted based on authentication and ownership
- **API Keys**: API keys are stored securely and not exposed in the app
- **Regular Updates**: We regularly update the app to address security vulnerabilities

---

## Changes to This Policy

- We may update this Privacy Policy from time to time
- **Significant Changes**: We will notify you of significant changes via:
  - In-app notification
  - Email (if provided)
  - App update release notes
- **Continued Use**: Continued use of the app after changes constitutes acceptance
- **Last Updated**: This policy was last updated on January 1, 2026

---

**Note:** This privacy policy is current as of version 2.0.3. Please review it periodically for updates.

## Recent Updates (Version 2.0.3 - January 1, 2026)

- **Local Storage for Free Users**: Free users' location history is now stored locally on their device using encrypted local storage (Room database) with 30-day automatic retention. This provides privacy and reduces cloud storage costs while still allowing free users to access their location history.
- **Pro Users**: Pro users continue to have unlimited cloud storage in Firebase Realtime Database with the last 100 entries retained.


## About MyFamilyTracker

MyFamilyTracker is a professional Android application built with:
- Kotlin
- Firebase backend services
- Google Maps
- Google Location Services

The app is designed with privacy in mind. You control who sees your location, and data is shared only with family members you explicitly join.

---

## Repository Purpose

This repository hosts the official privacy policy for the MyFamilyTracker Android application and is intended for public access and Google Play Store linking.
