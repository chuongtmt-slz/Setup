<h3 align="center">Email Adapter Setup</h3>

---

## 📝 Table of Contents
- [Google Cloud Storage Setup](#cloud_storage_setup)
- [Settings](#settings)

## Google Cloud Storage Setup <a name = "cloud_storage_setup"></a>

 - Log into https://console.cloud.google.com/storage/browser?project=ujet-dev-shared (double check that you’re on the ujet-dev-shared project)

 - At Bucket > click Create 

 - Configure the bucket name with the format name ujet-(devname). 
   - This name must be globally unique, so you may need to add your last name
 - Configure bucket as follows:

<img src="https://github.com/chuongtmt-slz/Setup/blob/main/Google%20Cloud%20Storage/google.png" alt="Google Cloud Storage Setup">

<img  src="https://github.com/chuongtmt-slz/Setup/blob/main/Google%20Cloud%20Storage/name.png" alt="name">

<img  src="https://github.com/chuongtmt-slz/Setup/blob/main/Google%20Cloud%20Storage/location.png" alt="location">
<img  src="https://github.com/chuongtmt-slz/Setup/blob/main/Google%20Cloud%20Storage/storage.png" alt="storage">
<img  src="https://github.com/chuongtmt-slz/Setup/blob/main/Google%20Cloud%20Storage/control.png" alt="control">
<img  src="https://github.com/chuongtmt-slz/Setup/blob/main/Google%20Cloud%20Storage/protect.png" alt="protect">

## Settings <a name = "settings"></a>
- Settings > Email > Enable Email channel

<img src="https://github.com/chuongtmt-slz/Setup/blob/main/Email%20Adapter%20Setup/Channel.png" alt="Enable Email channel"></a>

- Settings > Developer Settings > Email Account Management > Manage Email Account

- Tab Email Data Storage 
  - From the 1Password Engineering vault, download the service account json key titled “ujet-dev-shared local dev service account”
  - Add "Email Data Storage", "Folder Path" and upload “ujet-dev-shared.json" download at above step > Test connection

<img src="https://github.com/chuongtmt-slz/Setup/blob/main/Email%20Adapter%20Setup/Email-Account.png" alt="Email Account Management"></a>
<img src="https://github.com/chuongtmt-slz/Setup/blob/main/Email%20Adapter%20Setup/Bucket.png" alt="Bucket"></a>

- Tab Email account list > Add email account
<img src="https://github.com/chuongtmt-slz/Setup/blob/main/Email%20Adapter%20Setup/Account.png" alt="Account"></a>

- Settings > Queue > Clicking to Email 
  - Edit Email Menu Structure
  - Enable Channel Settings, Update email address, Assign agents for Human agents
<img src="https://github.com/chuongtmt-slz/Setup/blob/main/Email%20Adapter%20Setup/Structure.png" alt="Structure"></a>
