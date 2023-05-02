# Appcircle _Data Theorem_ component

Scan your app using Data Theorem Mobile Secure.

## Required Inputs

- `AC_DT_FILE_PATH`: File path to the IPA or APK to upload. This variable can for example be set to:
   - `$AC_APK_PATH` after the "Android Build" step
   - `$AC_APK_PATH` or `$AC_SIGNED_APK_PATH` after the "Android Sign" step
   
   - `$AC_EXPORT_DIR/Myapp.ipa` after the "Xcode Archive & Export for iOS" step

- `AC_DT_UPLOAD_API_KEY`: Data Theorem Mobile Secure upload API key. You will need to retrieve your organization's Upload API key from the portal.
