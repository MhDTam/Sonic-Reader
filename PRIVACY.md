# Privacy information

**Applies to:** Sonic Reader public distribution, version 1.0.0 / build 16131.

[العربية](PRIVACY.ar.md)

## Local reading and storage

PDF reading, local annotations, notes, bookmarks, library records and reading
position are handled on the device. Files you import or export and app settings
remain in device storage unless you choose an online or sharing feature.
Offline reading does not require a Sonic Reader account.

Storage access supports document discovery/import and saving exports. Where
broad file access is offered for device-wide discovery, Android controls that
permission. You can manage permissions in Android Settings.

## Optional network requests

- **Translation:** requesting translation sends the selected text to Google's
  translation service. The provider also receives normal connection information,
  such as the device's network address. Avoid translating confidential text if
  you do not want it sent to that provider.
- **Cloud Office conversion:** disabled by default in the public APK. If you
  configure and enable a compatible service, selected Office files and the
  service access credential are transmitted to that configured endpoint over
  HTTPS, after the app's cloud-upload consent. Service availability, retention
  and provider-side handling depend on the service operator. No private service
  endpoint, service account or access token is shipped in this public build.
- **Sharing and printing:** recipients and print services are chosen through
  Android. Their handling of the content is outside this app's local storage.

The application code for this release does not configure advertising or
analytics SDKs. This statement does not describe the separate policies of
Android, GitHub, Google or any service you choose to use.

## Removing data and getting support

Use the app's library and note-management controls to manage your documents and
records. Android's app-data controls and uninstallation can remove app-private
data; separately exported files may remain elsewhere on the device.

For support, use this repository's Issues with a synthetic example. Public
issues, comments and attachments are visible to others. Do not submit private
PDFs, credentials, account details or unredacted logs.
