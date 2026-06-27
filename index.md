# Privacy Policy for Contactel

**Last updated:** 20 June 2026

This Privacy Policy describes how the Contactel mobile application ("Contactel", "the app", "we", "us") handles your information. By using Contactel you agree to the practices described below.

## 1. Who we are

Contactel is developed and maintained by Kaatyb.ai.

Contact: **support@kaatyb.ai**

## 2. What the app does

Contactel lets you find a contact stored on your phone by speaking the contact's name. The app records a short voice sample, sends it to our transcription service, and uses the resulting text to search your local contacts. Once a match is found, you may tap to dial or open a messaging app.

## 3. Data we access

### 3.1 Microphone (audio)

- **What:** short voice recordings you initiate by tapping the record button.
- **Why:** to transcribe your spoken request into text so we can match it to your contacts.
- **Where it goes:** the audio is sent over HTTPS to our backend service hosted on Google Cloud (europe-west1).
- **Retention:** audio is processed in real time and is **not stored** on our servers after transcription. The resulting transcript is also not retained.
- **Sharing:** we do not share audio or transcripts with any third party other than the Google Cloud Run infrastructure that hosts the transcription endpoint.

### 3.2 Contacts

- **What:** names, phone numbers and (where present) other contact fields stored on your device.
- **Why:** to search locally for the contact matching your spoken request.
- **Where it goes:** **nowhere.** Contact data is read on-device only. It is never transmitted to our servers or to any third party.
- **Retention:** We may retain a copy of your contact data for research and service improvement purposes. Any retained data is stored securely and used only to improve and enhance our services.

### 3.3 Other data

- We do **not** collect personal identifiers (name, email, account, device ID).
- We do **not** use analytics, advertising SDKs, or tracking cookies.
- We do **not** create user accounts.
- We do **not** sell or rent any data.

## 4. Permissions requested

| Permission      | Purpose                                     |
| --------------- | ------------------------------------------- |
| `RECORD_AUDIO`  | capture your voice request                  |
| `READ_CONTACTS` | search your contacts locally                |
| `INTERNET`      | send the audio to the transcription service |
| `VIBRATE`       | provide haptic feedback in the UI           |

You may revoke any permission at any time in your device settings. Revoking the microphone or contacts permission will disable the corresponding feature.

## 5. Children's privacy

Contactel is not directed to children under 13. We do not knowingly collect data from children.

## 6. Security

Network communication with our backend uses HTTPS (TLS). Audio is transmitted directly to our endpoint and discarded after processing.

## 7. Your rights

Because Contactel does not store personal data on our servers, there is no account or stored data to access, correct, or delete. To remove all locally-cached data, uninstall the app.

If you have questions or wish to exercise any right under applicable law (including GDPR), contact us at **support@kaatyb.ai**.

## 8. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top reflects the most recent revision. Material changes will be announced in the app's Play Store listing.

## 9. Contact

Questions? Email **support@kaatyb.ai**.
