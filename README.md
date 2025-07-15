# Configure Custom Policy in Microsoft Intune

## Navigation

Go to:  
**Microsoft Intune** → **Devices** → **Manage devices** → **Configuration**

## Create Custom Policy

1. Navigate to:  
   **Policies** → **Create** → **Templates** → **Custom**

2. Under **OMA-URI Settings**, click **Add** and fill in the following:

   - **Name**: `Block CN Providers`  
   - **OMA-URI**: `./Vendor/MSFT/AppLocker/ApplicationLaunchRestrictions/apps/EXE/Policy`  
   - **Data type**: `String` or `String (XML file)`  
   - **Value**: Paste or upload the XML file stored from this repository

## Notes

- Ensure the XML structure complies with AppLocker policy schema.
- Changes may take time to apply depending on sync policies.

