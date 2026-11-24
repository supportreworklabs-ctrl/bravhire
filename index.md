Privacy Policy for BravHire AI
Effective Date: November 24, 2026
Last Updated: November 24, 2026
BravHire AI ("we", "our", or "us"), available at package name com.bravhire.app, is committed to protecting your privacy. This Privacy Policy explains how our mobile application handles user information and sensitive device data.
1. Overview & Core Privacy Guarantee
BravHire AI is built with an on-device, privacy-first architecture. All core interview practice features, speech synthesis, speech recognition, scoring evaluations, and resume ATS scans execute locally on your device. We do not maintain user tracking databases, sell personal data, or transmit your voice or resume documents to external servers.
2. Information We Access and How We Use It
A. Microphone and Audio Data (RECORD_AUDIO)
•
Purpose: BravHire AI accesses your device's microphone strictly to capture your spoken answers during mock interview practice sessions.
•
Processing: Spoken answers are processed ephemerally on your device via Android's native Speech Recognition API (SpeechRecognizer).
•
Retention & Sharing: Audio recordings are processed in real time and are never uploaded to cloud servers, saved to permanent external storage, or shared with third parties.
B. Files and Documents (Resume ATS Scanner)
•
Purpose: When you choose to use the Resume Enhancer or ATS Scanner, the app accesses the file (PDF, DOCX, or TXT) that you explicitly select using the system file picker.
•
Processing: Resume text extraction, keyword benchmarking, and scoring are performed 100% on-device using local libraries (syncfusion_flutter_pdf and archive).
•
Retention & Sharing: Your resume files and extracted text are processed in local memory only. They are never transmitted over the internet or shared with third parties.
C. In-App Purchases and Billing (BILLING)
•
Purpose: BravHire AI offers optional Pro access passes (such as Mock Packs and Placement Passes).
•
Processing: All payment transactions are processed directly and securely by Google Play Billing (com.android.vending.BILLING). We do not collect, process, or store credit card, debit card, UPI, or bank account details.
•
Entitlement Storage: Your purchase entitlement status is stored locally on your device using encrypted storage (FlutterSecureStorage backed by Android Keystore).
D. Local Storage & Preferences
•
Purpose: The app stores your selected target role, experience level, practice history, streak counters, and readiness scores locally on your device (SharedPreferences and FlutterSecureStorage).
•
Sharing: This data remains entirely on your device and is not synchronized to external analytics or advertising servers.
3. Data Sharing and Third Parties
We do not sell, rent, trade, or share any personal information, voice recordings, or resume contents with third parties.
•
Google Play Services: Used strictly for app distribution, licensing, and processing Google Play in-app purchases in accordance with Google Play Terms of Service.
4. Data Security
We implement industry-standard security measures:
•
Local entitlement and user preference data is secured with hardware-backed encryption (Android Keystore).
•
Network communication with Google Play Billing uses encrypted Transport Layer Security (TLS/HTTPS).
5. Children's Privacy
BravHire AI is intended for career preparation and job seekers aged 18 and older. We do not knowingly collect personal data from children under the age of 13.
6. User Control & Data Deletion
Since your data is stored locally on your device:
•
You can reset or clear all your data, interview transcripts, and resume scans at any time by clearing the app's cache and storage in Android Settings > Apps > BravHire AI > Storage > Clear Data, or by uninstalling the app.
7. Changes to This Privacy Policy
We may update our Privacy Policy periodically. Any changes will be posted on this page with an updated effective date.
8. Contact Us
If you have any questions or feedback regarding this Privacy Policy or our privacy practices, please contact us:
•
Application: BravHire AI (com.bravhire.app)
•
Support Email: supportreworklabs@gmail.com
