# MyFamilyTracker Privacy Policy

_Last updated: December 25, 2024_

MyFamilyTracker ("we," "our," or "us") is a family location tracking and sharing app for Android devices. This Privacy Policy explains what information the app collects, how it is used, and the choices you have. By installing or using MyFamilyTracker you agree to the practices described below.

## Information We Collect

### Location Data
- **Real-time Location**: We collect your device's location data to share with family members in your family group. Location data includes latitude, longitude, timestamp, and accuracy information.
- **Location History**: Location data is stored temporarily in Firebase Realtime Database to provide real-time location sharing functionality.
- **Location Accuracy**: We collect location accuracy information to provide better location services and display accuracy indicators.

### Account Information
- **User Profile**: Name, email address, and phone number (if provided during account creation or profile editing).
- **Authentication**: User ID from Firebase Authentication (Google Sign-In or Anonymous Sign-In).
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

We do not run ads and do not sell, rent, or monetize your data to third parties.

## Storage and Retention

### Data Storage
- **Location data** is stored in Firebase Realtime Database (Google Cloud infrastructure).
- **User profiles** are stored in Firebase Realtime Database.
- **Family group data** is stored in Firebase Realtime Database.
- **App preferences** (location sharing enabled/disabled) are stored locally on your device.

### Data Retention
- Location data is stored while you use the app and share your location.
- Location data is updated in real-time and previous locations are replaced with new ones.
- You can delete your account and data at any time (contact support).
- Location history retention can be configured (future feature).

### Data Security
- Data is encrypted in transit using HTTPS/TLS.
- Data is encrypted at rest in Firebase Realtime Database.
- Access to data is restricted to authenticated users.
- Firebase provides industry-standard security measures.

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

We do **not** share your data with:
- Advertising networks
- Data brokers
- Analytics services (beyond Firebase Analytics)
- Other third-party services

## Permissions Used

### Required Permissions

* **ACCESS_FINE_LOCATION** (Precise location): Essential for the app's core functionality. Allows MyFamilyTracker to track and share your location with family members. Without this permission, the app cannot function.
* **ACCESS_COARSE_LOCATION** (Approximate location): Used as a fallback when precise location is not available.
* **ACCESS_BACKGROUND_LOCATION** (Android 10+): Required to track your location in the background while the app is not in the foreground. This ensures continuous location sharing with family members.
* **FOREGROUND_SERVICE** and **FOREGROUND_SERVICE_LOCATION**: Required to maintain the location tracking service running in the background. This ensures location updates continue even when the app is in the background.
* **POST_NOTIFICATIONS** (Android 13+): Required to show a persistent notification indicating that the location service is active. This notification cannot be dismissed while the service is running, as required by Android for foreground services.
* **INTERNET**: Required to communicate with Firebase servers for authentication, data storage, and location sharing.
* **ACCESS_NETWORK_STATE**: Used to check network connectivity status.

### Optional Permissions

* **None currently** - All permissions are required for core functionality.

## Your Rights and Controls

### Location Sharing Control
- You can **enable/disable location sharing** in app settings at any time.
- When location sharing is disabled, your location is not updated or shared with family members.
- You control who can see your location by managing family group membership.
- You can leave a family group at any time to stop sharing with that group.

### Account Management
- You can **edit your profile information** (name, email, phone) in the app settings.
- You can **leave family groups** at any time.
- You can **delete your account** (contact support for account deletion).
- You can **sign out** of the app at any time.

### Data Access
- You can view your profile data in the app settings.
- You can see your location data in the app (your current location on the map).
- You can view your family group membership in Family Settings.
- You can export your data (future feature).

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

## About MyFamilyTracker

MyFamilyTracker is a professional Android application for real-time family location tracking and sharing. The app is built with:
- Kotlin programming language
- Firebase for backend services
- Google Maps for map visualization
- Google Location Services for location tracking

The app is designed with privacy in mind - you control who can see your location, and location data is only shared with family group members you explicitly join.

---

**Last Updated:** December 25, 2024

