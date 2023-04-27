# Appcircle _Data Theorem_ component

Upload to Data Theorem

## Required Inputs

- `AC_DT_FILE_PATH`: File path to the IPA or APK to upload.  This variable can for example be set to:
   - `$AC\_APK\_PATH` after the `Android Build` step
   - `$AC\_APK\_PATH` or `$AC\_SIGNED\_APK\_PATH` after the "Android Sign" step
    - `$AC\_IPA\_PATH` after the "Xcode Archive & Export for iOS" step

- `AC_DT_UPLOAD_API_KEY`: Data Theorem Upload API Key. You will need to retrieve your organization's Upload API key from the portal.
