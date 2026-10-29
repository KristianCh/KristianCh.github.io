#Privacy Policy for Media Controls Widget
Last Updated: October 26, 2023
This Privacy Policy describes how your information is handled when you use the Media Controls Widget ("the Application").
1. Information Collection and Use
The Application is designed to provide a home screen widget to control media playback on your device. To function correctly, it accesses certain types of data:
Media Metadata and Playback State
The Application uses the Notification Listener Service to detect active media sessions on your device. This allows the widget to:
•
Display the title and artist of the currently playing media.
•
Show album art associated with the media.
•
Display and update playback progress (duration and current position).
•
Provide playback controls (Play/Pause, Next, Previous).
Important: This data is processed locally on your device in real-time. It is used solely to populate the widget UI and is not stored permanently, uploaded to any servers, or shared with third parties.
Package Information
The Application may query the list of installed applications (QUERY_ALL_PACKAGES) to allow you to select a "Primary Player" or to ignore specific apps from appearing on the widget. This information remains on your device.
2. Permissions
To provide its core features, the Application requires the following permissions:
•
Notification Access: Required to read media metadata and control playback via MediaController.
•
Query All Packages: Required to identify and list media player applications installed on your device for user configuration.
You can revoke these permissions at any time through your device's Android Settings.
3. Data Storage
The Application uses local storage (Shared Preferences) to save your widget configuration, such as:
•
Selected Primary Player.
•
List of ignored players.
•
UI preferences (Theme, Album Art rotation).
This data is stored locally on your device and is not synchronized with any cloud services.
4. Third-Party Services
The Application interacts with third-party media players (e.g., Spotify, YouTube, etc.) installed on your device to facilitate playback control. We do not control how these third-party applications handle your data. Please refer to the privacy policies of your respective media player applications.
5. Security
We value your trust in providing us access to your media session information. We strive to use commercially acceptable means of protecting it. However, remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable.
6. Children’s Privacy
The Application does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children.
7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. You are advised to review this page periodically for any changes.
8. Contact Us
If you have any questions or suggestions about this Privacy Policy, do not hesitate to contact us.
Developer: [Your Name/Company Name]
Email: [Your Contact Email]
Package: com.chovancak.media_controls_widget