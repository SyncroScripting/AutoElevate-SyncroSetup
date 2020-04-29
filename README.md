# Deprecated
A official version from AutoElevate currently exists in the community library, this is just here for reference from before the official script was available.
## AutoElevate Setup Script for SyncroMSP

This script installs AutoElevate using fields pulled from SyncroMSP, reverting to defaults set in the script if the field doesn't exist in Syncro.

Please note that the following variables need to be configured in Syncro (see screenshot below):

|  Variable Name | Variable Type |     Value     |
| -------------- | ------------- | ------------- |
| location_name  | platform      | {{contact_name}} |
| location_id    | platform      | {{contact_id}} |
| company_name   | platform      | {{customer_business_name}} |
| company_id     | platform      | {{customer_id}} |

Also please be sure to upload the MSI and set it to save to C:\AESetup.msi.

![Sycnro Screenshot](https://raw.githubusercontent.com/thegeekkid/AutoElevate-SyncroSetup/master/Screenshots/Syncro-VariableSetup.jpg "Syncro Screenshot")
