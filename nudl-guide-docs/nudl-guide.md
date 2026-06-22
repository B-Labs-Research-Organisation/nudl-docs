# Welcome to Nudl Guide

Nudl is a payment app which facilitates payouts to multiple users from your Safe and personal wallet.   

It is easy to access: 
* users access their profile by using the chat command **/nudl**
* admins access the Admin dashboard using the chat command **/nudl-admin**

It is easy to use:
* all dashboard options are designed to be self-explanatory
* buttons and dropdowns speed up the flow
* payment settings are customisable

It is easily adapts to your workflow:
* a selection of payment paths and download options are provided

This screenshot shows the special image ZEBRA-ALPHA-123.

Image file: test_image.png

![ZEBRA-ALPHA-123](nudl-guide-assets/test_image.png)

Image URL:
https://raw.githubusercontent.com/B-Labs-Research-Organisation/nudl-docs/refs/heads/main/nudl-guide-docs/nudl-guide-assets/test_image.png


## 🔍 Installing Nudl on Discord


What to look out for when installing Nudl on your system!

### *1. Install the bot to your server*

To install on your server, click on the installation link (available, soon):

![](nudl-guide-assets/discord-installation-prompt.png)

Then grant permission:

![](nudl-guide-assets/discord-grant-permissions.png)

Nudl is installed:

![](nudl-guide-assets/discord-installation-success.png)


### 2. Customise permissions globally for your **server**

By default, Nudl is granted access to all channels, and all users have access to Nudl. If you wish to restrict this access to a specific channel or users, navigate to your server name at the top left of your screen, click on the “v” next to the server name to open the dropdown menu. Head to:

Server Settings → 

![](nudl-guide-assets/server-settings.png)

Integrations → 

![](nudl-guide-assets/apps-integrations.png)

Bots and Apps

![](nudl-guide-assets/bots-and-apps.png)

Head to **Nudl** and press **Manage** to see the Command Permissions. Here, you can limit Nudl to particular “Channels” as well as “Roles & Members”. Default setting is All channels, All Members. In the “Commands” section you can open or limit access to Nudl commands to certain users or tags. See the Discord domumentation for further details how to use this feature.

>📌 **Note:** By design **Nudl admin** commands can only be accessed by **Discord server admins**. Therefore it is not possible to delegate admins permissions to members without Discord admin rights in your server.


>🛠️ **Work Tip:** Depending on the size of your community, we suggest using a designated channel for Nudl to avoid messages and prompts from going under.


### *3. Private channels: customise permissions locally per **channel***

*Set Nudl:*

*If a channel is set to **private,** you need to add Nudl to the channel manually:*

Head to the chosen channel → Edit channel (⚙️) → “Permissions” → “Add Members or roles”

![](nudl-guide-assets/private-channel.png)

Select Nudl from the **Roles** listing and add:

![](nudl-guide-assets/nudl-bot-tag.png)

*Set Nudl permissions:*

Back on the Permissions  tab scroll down and open the “Advanced Permissions”. Select Nudl to the left and make sure the “View Channel” permission is activated: 

![](nudl-guide-assets/channel-permissions.png)



>✅ ** Congratulations:** You have successfully installed Nudl!


## 👥 User Sections

### What you need to know as a  User

Users can access and manage their profile by typing **/nudl** in the Discord chat. Users retain full control over their data, but are also responsible for keeping it up-to-date, as an Admin cannot add, modify or remove user data. In particular, a user can:

- Add addresses
- Update addresses
- Remove addresses
- View profile


>📌 ***Note:*** While Admins cannot add, modify or remove addresses a user sets in Nudl, they can process, filter and download them into a file to manage them on or offline, among other to process payments or for accounting purposes.


### Getting started

To open your profile type **/nudl** in the Discord chat and enter.

![](nudl-guide-assets/nudl-user-cmd.png)

The user profile provides an overview to add, update or remove an addresses:

![](nudl-guide-assets/nudl-address-overview.png)


### Add Addresses

To add a users wallet address, select **Add / update**.  Set address individually per network using **Select a network** or **Set same addresss on all networks**:

![](nudl-guide-assets/user-prep-address-add.png)

Select a network:

![](nudl-guide-assets/user-set-address-network.png)

Add wallet address:

![](nudl-guide-assets/user-add-address.png)

Upon submitting see overview of all set user addresses:

![](nudl-guide-assets/overview-once-address-set.png)

### Update Addresses

Instead of adding an address you can easily replace an address you have set for a network previously. Proceed as you do when setting an address:

![](nudl-guide-assets/user-prep-address-add.png)


When updating addresses for individual networks you receive this prompt:

![](nudl-guide-assets/user-update-address.png)

When updating addresses for all networks you receive this prompt and can choose between **override all set networks values** or add only to **networks without set values**:

![](nudl-guide-assets/user-update-all-address.png)
    
### Remove Addresses

Select **Remove** which opens the option to removel addresses:

![](nudl-guide-assets/user-prep-address-remove.png)

To remove an individual address, choose **Select network** and then **Yes, remove**:

![](nudl-guide-assets/user-remove-address.png)

To remove all addresses from all networks, choose **Remove all addresses** and then **Yes, remove all**:

![](nudl-guide-assets/user-remove-addresses.png)



tutorial addresses

0x9ebda21de56278951a73f20dc2bac54e3edca6c0

0xf3f24e5fbd6efcdbeddac59bdcdfaf5ee3a720ab


## ⚙️ Admin Sections

### Quickstart

The Quickstart Guide runs you through the steps when setting up Nudl for the first time after initial installation, implementing its core functions.

>📌 **Note:** You need to be a Discord server admin to access the **/nudl-admin** commands.

#### Admin Dashboard

Type **/nudl-admin** in the Discord chat command:

![](nudl-guide-assets/nudl-admin-cmd.png)

 

Press **Enter** to open the Admin dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

#### Manage tokens

Set token addresses which you expect to pay your community with. Tokens are set per network. There is no limit of tokens you can add per network. Start by selecting a network and then press **Add token**:

![Choose your network](nudl-guide-assets/add-or-remove-token.png)

Add you token contract address into the modal and **Submit**.

![Add token contract and Submit](nudl-guide-assets/add-token-contract.png)

>ℹ️ ***Information:*** You can find token contract addresses in the project documentation or on sites such as [coingecko.com](http://coingecko.com) (DYOR!), see e.g.: 
>
>![](nudl-guide-assets/find-contract.png)


>🛠️ ***Work Tip:*** You are flexible when to add a token. You can also add tokens while preparing a payment within the Safe and CSV Airdrop streams.


>ℹ️ ***Information:*** Nudl supports token disbursements based on token addresses. Native gas tokens such as ETH on the Ethereum Mainnet do not possess a token contract and are currently **not** supported.


#### Manage Safes

Set Safe addresses from which you expect to pay your community. Safe addresses are set per network. Nudl currently only supports one Safe per network.

Start by pressing **Add Safe** :

![](nudl-guide-assets/open-manage-safe.png)

Copy address  from [Safe.global](http://Safe.global) as it automatically includes the relevant prefix as part of the wallet address you copy, see as an example:

![](nudl-guide-assets/copy_safe_address.png)


Paste the copied prefix & address to the modal and submit:

![](nudl-guide-assets/set-safe-address.png)


>📌 **Note:** The prefix specifies the network to which the Safe address is associated in Nudl. These are the common prefixes used:
>ETH Mainnet: eth
>Polygon Mainnet: matic
>Arbitrum One: abr1
>Optimism: oeth
>BASE Mainnet: base
>Base Sepolia Testnet: basespe

#### Notify Users

To assist with the onboarding of your community an announcement using Nudl’s built-in **notification tool** by pressing the **Notify missing addresses** button on Admin dashboard.

Selecting the network on which you conduct payments. Choose additional filters to refine:

![Review available notification filters](nudl-guide-assets/notification-filters.png)

Click **Next: choose send channel** to specify in which channel you want to address your community. By default it is the channel in which you currently are, but you can choose another channel, as long as Nudl is enabled there and the notified users have access to it.

![Choose where to send the notification](nudl-guide-assets/notification-filter-set.png)

Once set **Send notification**:

![User facing missing address notification](nudl-guide-assets/address-notification.png)

>✅ ***Congratulations:*** You have succcessfully set up Nudl! 🎉




### Start Payout

#### Introduction

Nudl currently supports disbursements on [SAFE](https://safe.global/), [Disperse](https://disperse.app/), [Smol](https://smold.app/disperse) and Nudl Web.

>ℹ️ ***Information:*** - You can enter decimal values in Nudl by using a decimal point: “**.**” - All disbursement paths allow assigning one numeric payment value per user. - In Nudl Web you additionally have the option to cumulatively or alternatively add point values to users.


#### Conduct a payout on **SAFE** ✅

##### Step 1: Create a payout form in Nudl

Select **Start payout** on the Nudl Admin dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select **Safe**:

![Select Safe](nudl-guide-assets/start-payout-options.png)

Select a network:

![](nudl-guide-assets/safe-payout-network-set.png)

Optionally select channel or role filter do best target the payout group. Press **Set amounts**:

![](nudl-guide-assets/safe-payout-recipient-filter.png)

Add payment values after the comma:

![](nudl-guide-assets/set-user-amounts.png)

Add an optional **Donation** amount to the transaction to support work at Nudl.

Or  **Continue Safe setup**:

![](nudl-guide-assets/safe-donation.png)

Add any donation amount here, **Submit** and then **Continue Safe setup**:

![](nudl-guide-assets/donation-modal.png)

Select a token and Safe address you have set up as described in the **Quickstart** section. Alternatively, set a new token address or set/replace a Safe address:

![Set token and Safe address](nudl-guide-assets/safe-payout-setup.png)

**Set Token**:

![](nudl-guide-assets/safe-payout-set-token.png)

**Set Safe Address**:

![](nudl-guide-assets/safe-payout-set-safe.png)

After setting you have the option to edit both addresses again:

![](nudl-guide-assets/safe-payout-edit.png)

Generate Safe Payout JSON file and download:

![](nudl-guide-assets/safe-payout-file.png)

##### Step 2: Upload Nudl payout form to Safe

Open your [SAFE](https://safe.global/) account and first verify that the address and network correspond with the selections made in the **Safe** disbursement file. After that, click on “New transaction” and then on “Transaction Builder”.

![](nudl-guide-assets/safe-dashboard.png)

 Alternatively, navigate to the “App” section and select “Transaction Builder”.

![](nudl-guide-assets/safe-app-search.png)

Upload the JSON file downloaded in step 1 above by clicking on the “*choose a file*” button located in the bottom right corner:

![](nudl-guide-assets/safe-tx-builder.png)

Press “*Create a Batch*“:

![](nudl-guide-assets/safe-tx-builder-batch.png)

To review individual transactions, click on the pencil icon. If you are familiar with the process, you can make specific edits in the form, such as adjusting the values.

To ensure everything is configured properly, simulate the transaction.

![](nudl-guide-assets/safe-tx-builder-simulate.png)

If the simulation is successful begin the transaction by clicking "Send batch" and follow your usual multisig setup process.


>✅***Congratulations:*** You have succcessfully concluded your SAFE transaction!


#### Conduct a payout using **Disperse** and **Smol dApp** ✅

##### Step 1: Create a payout form in Nudl

Select **Start payout** on the Nudl Admin dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select **Disperse**:

![Select Disperse](nudl-guide-assets/start-payout-options.png)

**Select a network**:

![](nudl-guide-assets/disperse-payout-network-set.png)

Optionally select channel or role filter do best target the payout group. Press S**et amounts**:

![](nudl-guide-assets/disperse-payout-recipient-filter.png)

Add payment values after the comma:

![](nudl-guide-assets/set-user-amounts.png)

Add an optional **Donation** amount to the transaction to support work at Nudl.

Or  **Generate Disperse file**:

![](nudl-guide-assets/disperse-donation.png)

Add any donation amount here:

![](nudl-guide-assets/donation-modal.png)

Generate Safe Payout CSV file and download:

![](nudl-guide-assets/disperse-payout-file.png)

##### Step 2: Upload Nudl payout form to Disperse and Smold.app

###### A. Upload to Disperse

Open [Disperse](https://disperse.app/) and login with your wallet of choice. Set your wallet to the network and wallet address from which you want to make the transfer from.

Select the network on Disperse:

![](nudl-guide-assets/disperse-network-set.png)

Select between ETH or token disbursement. If you choose a token add the token contract address. For more information where to find these see our Quickstart section. Then **load**:

![](nudl-guide-assets/disperse-token-set.png)

Open the Nudl file and **copy** the data which can include the headings.

![](nudl-guide-assets/disperse-copy-csv-data.png)

**Paste** into the “recipients and amounts” field:

![](nudl-guide-assets/disperse-set-recipients.png)

For confirmation the exact payment amounts, total and the wallet balance holding are calculated instantly:

![](nudl-guide-assets/disperse-confirm-values.png)

Approve token and disburse:

![](nudl-guide-assets/disperse-conclude.png)


>✅***Congratulations:*** You have succcessfully concluded your Disperse transaction!
  

###### B. Upload to Smold.app

To begin, choose Disperse at [Smol](https://smold.app/disperse), select the Disperse tab and log in with your preferred wallet.

![](nudl-guide-assets/smold-dashboard.png)

Select your token address. The Smol app allows you to search by token address or you can add one from a third party source. More information on token addresses see Quickstart :

![](nudl-guide-assets/smold-token-set.png)

Upload the CSV file we downloaded from Nudl using **Import Configuration**:

![](nudl-guide-assets/smold-csv-upload.png)

Check the upload details:

![](nudl-guide-assets/smold-confirm-values.png)

Check the total amount, approve and execute the payout:

![](nudl-guide-assets/smold-conclude.png)


>✅***Congratulations:*** You have succcessfully concluded your Smold.app transaction!


>📌 **Note:** If “No token selected” appears in the token field, please check that your wallet holds a balance of the selected token.


#### Conduct a payout using **CSV Airdrop** ✅

##### Step 1: Create a payout form in Nudl

Select **Start payout** on the Nudl Admin dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select **CSV Airdrop**:

![Select Disperse](nudl-guide-assets/start-payout-options.png)


**Select a network**:

![](nudl-guide-assets/csv-airdrop-payout-network-set.png)

Optionally select channel or role filter do best target the payout group. Press **Set amounts**:
        
![](nudl-guide-assets/csv-airdrop-payout-recipient-filter.png)

Add payment values after the comma, then **Submit**:

![](nudl-guide-assets/set-user-amounts.png)

Add an optional **Donation** amount to the transaction to support work at Nudl.
        
Or **Select token**:

![](nudl-guide-assets/csv-airdrop-donation-set.png)


Add any donation amount here and **Submit** then **Select token**:

![](nudl-guide-assets/donation-modal.png)

Select a token you have set up as described in the **Quickstart** section. Alternatively, set a new token address:

![Select existing or set new token](nudl-guide-assets/select-or-add-token.png)

**Generate CSV Airdrop file**:

![](nudl-guide-assets/csv-airdrop-generate.png)

**Generate CSV Airdrop file** and download:

![](nudl-guide-assets/csv-airdrop-payout-file.png)

##### Step 2: Upload Nudl payout form to CSV Airdrop in Safe

Open your [SAFE](https://safe.global/) account and first verify that the address and network correspond with the selections made your Nuld payout file. 

Search for CSV Ardrop under App section.

![](nudl-guide-assets/csv-airdrop-app-search.png)

Select:

![](nudl-guide-assets/csv-airdrop-app-select.png)

Confirm:

![](nudl-guide-assets/csv-airdrop-app-confirm.png)

Upload the Nudl disbursement file downloaded above:

![](nudl-guide-assets/csv-airdrop-dashboard.png)

Upload the Nudl CSV file:

![](nudl-guide-assets/csv-airdrop-file-upload.png)


>📌 ***Note:*** To speed things up you can expand the file field in Nudl (or open the downloaded Nudl file) **copy** the data **including** the headings, and **paste** into the CSV Airdrop data field:


![](nudl-guide-assets/csv-airdrop-copy.png)


Review all entries, check amounts and total in **Summary** then **Submit**:

![](nudl-guide-assets/csv-airdrop-confirm-values.png)

Start the Safe Multisig transaction:

![](nudl-guide-assets/csv-airdrop-safe-tx.png)


>✅ ***Congratulations:*** You have succcessfully started your CSV Airdrop transaction!


#### Conduct a payout using **Nudl Web** ⚠️

##### Step 1: Create a payout form in Nudl Web

Select **Start payout** on the Nudl Admin dashboard:
admin-dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select **Nudl Web:**

![Select Nudl Web](nudl-guide-assets/start-payout-options.png)

**Select a network**:

![](nudl-guide-assets/nudl-web-payout-network-set.png)

Optionally select channel or role filter do best target the payout group. Press **Set amounts**:

![](nudl-guide-assets/nudl-web-payout-recipient-filter.png)

Add payment **values** and/or **points** after the comma, then **Submit**:

![](nudl-guide-assets/set-user-amounts-points.png)

**Generate Nudl Web CSV**:

![](nudl-guide-assets/nudl-web-generate.png)

Download the CSV file/connect to Nudl web:

![](nudl-guide-assets/nudl-web-payout-file.png)
        
##### Step 2: Upload Nudl disbursement to Nudl site

**coming soon**

>✅ ***Success:*** You have succcessfully concluded your Nudl Web transaction!


### Address Directory

Nudl admins can manage payment flows by accessing different filtering options. It also helps discover duplcate addresses.

#### Admin Dashboard

Click the **Address directory** button on the Admin dashboard:

![Select the address directory](nudl-guide-assets/admin-dashboard.png)

The Nudl provides you with different options:

![](nudl-guide-assets/address-directory.png)

#### Browse directory

Select Browse directory, then set the desired filters. Choose amongst Network (mandatory), Role and Channel:

![](nudl-guide-assets/address-directory-browse.png)

This will list the respective wallet holders and their corresponding addresses. You have the option to export your search results as CSV file.


>🛠️ ***Work Tip:*** Make sure you are as specific as possible, as Discord has a character limit in place which may prevent the display of all filtered users.


#### Lookup by address

To clarify whether an address is associated with a user, select **Lookup by address**, add the address to the modal and **Search**:

![](nudl-guide-assets/address-directory-address.png)

#### Lookup by username

To clarify which address is associated with a particular user, select **Lookup by username**:

![](nudl-guide-assets/address-directory-user.png)

This will list the respective wallet holder and their corresponding addresses. You have the option to export your search results as CSV file.


### Notify missing addresses

Nudl features a notification tool to inform users fo your community to add their wallet address to the system. You can use this for general onboarding or when you are about to prepare a disbursement.

Use **/nudl-admin** to open the Nudl **Admin dashboard** and select **Notify missing addresses**:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select a **Network (required)**, fine-tune further using channel and role filters :

![Review available notification filters](nudl-guide-assets/notification-filters.png)

 

**Next: choose send channel**:

![Choose where to send the notification](nudl-guide-assets/notification-filter-set.png)

Modify default channel where to post the notification. Nudl must be enabled there!

Then **Send notification**:

![Send the notification](nudl-guide-assets/send-address-notification.png)

If you send a notification to a channel in which Nudl is not activated:

![Prompt if Nudl is not active in a notified channel](nudl-guide-assets/nudl-not-active.png)

If you send a notification to a channel to which a user has no access:

![A tagged user will not be able to access this channel](nudl-guide-assets/user-no-access.png)

You will receive a confirmation once successfully sent:

![The notification was posted in the designated channel](nudl-guide-assets/notification-sent.png)

Users can choose to use the dedicated **Add address button** or **/nudl** command:

![User facing missing address notification](nudl-guide-assets/address-notification.png)

Press the **Add token address** button to open the modal:

![Add the required wallet address](nudl-guide-assets/notification-modal.png)

Anyone in the channel has button access. A user with an address already set is informed:

![Notification if the entered address is already set](nudl-guide-assets/address-already-stored.png)

Once saved you will receive your address overview:

![Address overview of all your saved addresses](nudl-guide-assets/overview-once-address-set.png)




### Nudl Basics
#### Introduction

At Nudl, using **admin command lines** are restricted to **Discord administrators**. 

What a Nudl Admin can do:

- Create and execute disbursements
- Download files including among other Discord user identifiers, wallet addresses and values/points
- Access and browse the address directory using different filter settings
- Identify and notify users who have not set their address on Nudl
- Manage token and Safe addresses

What a Nudl Admin cannot do:

- Admins are not able to add, modify, or delete wallets users have set within Nudl.


>📌 **Note:** While admins cannot modify any data within Nudl, they can download modifiable JSON and CSV files or modify the date in the respective payment platforms themselves.
>
>The downloadable files containing the following user data, depending on file type:
>Discord display name, unique name, user ID
>Wallet address
>Chain name and chain ID
>Disbursement value and /or points


#### Adding a token during disbursement


Nudl offers two ways to add a token.

**Option 1**: Select Manage tokens, see Quickstart for details.

**Option 2**: Add tokens while building your **Safe** or **CSV Airdrop** disbursement file. The process is identical for all disbursement paths. We will use the Safe disbursement to illustrate.

First, open the **Admin dashboard** with **/nudl-admin** and Select **Start payout**:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)


Select **Safe** or **CSV Airdrop**:

![Select Safe or CSV Airdrop](nudl-guide-assets/start-payout-options.png)

**Set Token Address**:

![Set a token address](nudl-guide-assets/safe-payout-setup.png)

Click on **Choose an existing token or add a new one**:

![Select existing or set new token](nudl-guide-assets/select-or-add-token.png)

Click on **Add a new token (not listed)**:

![Select to add a new token](nudl-guide-assets/add-a-new-token.png)

Add the token contract address and **Submit**:

![Add token contract and Submit](nudl-guide-assets/add-token-contract.png)


>✅ ***Congratulations:*** You have sucessfully added and saved a new token to the Safe or CSV Airdrop payment stream.


>📌 **Note:** The token address is saved and available in the future. To remove it, select **Manage token** in the **Admin Dashboard**.  For further information where to obtain a token contract address refer to Quickstart for further details.


#### Cancelling adding a token

The **Add Token Address** modal was opened but your pressed **Cancel**:

![Add token contract and Submit](nudl-guide-assets/add-token-contract.png)

System considers the cancellation as final and closes the process:

![Ticked circle when cancelling a token add](nudl-guide-assets/cancel-adding-token.png)

  
>📌 **Note:** If for any reason the modal is cancelled without adding a token contract you cannot reopen it again immediately. To reinitiate the process you have two options:


**Option 1**: press **Back to Payout Setup** and re-enter **Set Token Address**:

![Select existing or set new token](nudl-guide-assets/select-or-add-token.png)

**Option 2**: provisionally select another token of your dropdown list:

![Set a placeholder token](nudl-guide-assets/placeholder-token.png)

Then **Edit Token Address** and re-select **Add a new token (not listed)**:

![Edit a token contract address](nudl-guide-assets/edit-token-address.png)


>✅ ***Congratulations:*** You have sucessfully restarted the Add Token Address flow.


#### Remove a token

##### Introduction

How to add tokens and safes is addressed in **Quickstart** and **Adding a token during disbursement** section.

How to **remove** either is addressed in the following.

Start either process by opening the Admin dashboard using **/nudl-admin** and select **Manage tokens** or **Manage Safes**, respectively:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)


##### Remove a token

**Select a network**:

![Choose your network](nudl-guide-assets/add-or-remove-token.png)

Choose **Remove Token**:

![Click Remove Token button](nudl-guide-assets/remove-token.png)

Select the token to be removed:

![Select the token to be removed](nudl-guide-assets/select-token-to-remove.png)

Confirm **Yes, Remove**:

![Confirm removal of selected token](nudl-guide-assets/confirm-token-removal.png)

The removal is confirmed:

![Token removal confirmed](nudl-guide-assets/token-removal-success.png)


>✅ ***Congratulations:*** You have succcessfully removed your token from Nudl!

  

##### Remove a Safe

Select **Remove Safe**:

![Open the Manage Safe dashboard](nudl-guide-assets/manage-safe-dashboard.png)

**Select Safe to remove**:

![Choose the Safe address to be removed](nudl-guide-assets/select-safe-to-remove.png)

Confirm **Yes, remove**:

![Confirm to remove selected Safe](nudl-guide-assets/remove-safe-confirm.png)

The removal is confirmed:

![The Safe removal is confirmed](nudl-guide-assets/safe-removal-confirmation.png)

>✅ ***Congratulations:*** You have succcessfully removed your Safe from Nudl!

  

#### Editing a disbursement file

You can edit any of the final disbursement files to address errors or to simply modify. Press the **Edit CSV** and it will bring you back to the section where you set the amounts for each user. You can adjust any steps as necessary or just click through the steps.

![Edit disbursement file](nudl-guide-assets/edit-disbursement-file.png)


Review any issues found by accessing **Show Last Issues**.

![Show last issues.png](nudl-guide-assets/show-last-issues.png)



>📌 **Note:** The Edit CSV option does not allow you to change the selected network. In this case you willl need to restart the entire disbursement path. 


>🛠️ ***Work Tip:*** In case you need to restart the disbursement process because you selected the incorrect network, you do not need to add all user values afresh:
>- Open **Edit CSV** of your old disbursement form, copy all users and their values.
>- Restart the disbursement path afresh using the updated network.
>- Once you added a network you will see the following options:
> 
> ![](nudl-guide-assets/disbursement-cmd-options.png)
> 
>- Select **Manual paste** which will open the user modal.
>- Past the users and values you copied earlier and proceed as before.
   

#### Manual paste

All payment paths allow to manually ingest user and payment data:

![Enter customised data](nudl-guide-assets/manual-paste.png)

This can be a helpful and speedy way to manage repeat payments to the same recipients with the same values that you have conducted in the past and have stored in a previous disbursement file. Make sure you paste the data in the correct format. 


>📌 **Note:** Discord has a 4000 character limit, which accommodates approximately 100 users if you use Discord ID codes.


#### Nudl formatting errors

##### Truncated Discord IDs

Opening the CSV file often truncates (shorten) the Discord IDs. 

>🛠️ ***Work Tip:*** 
>To prevent this, consider uploading your CSV file to **Google Sheets**. For guidance, visit: [How to Open a CSV File in Google Sheets](https://www.geeksforgeeks.org/how-to-open-a-csv-file-in-google-sheets/).
>
>If you prefer to use **LibreOffice** or **Excel** instead, following these steps:
>1. Double-click on the downloaded CSV file.
>2. The text import editor will appear:
>3. Highlight the Discord ID column and change the formatting to “Text,” then click “OK” to import.


![How to modify the CSV Text Import](nudl-guide-assets/truncated-user-id.png)

##### User address not set

   
>ℹ️ ***Information:** Nudl* can only process users who have registered their wallet addresses in Nudl. If Nudl is unable to locate a user due to misspellings, non-existence, or the absence of a submitted wallet address, an alert ⚠️ will be triggered. The total transfer amount displayed serves as an additional verification tool for you to cross-check against your original disbursement calculations.



![Highlights issues found during processing by Nudl](nudl-guide-assets/address-error-message.png)

##### Value format incorrect


>ℹ️ ***Information:*** Nudl is format sensitive. If you enter the data into the Payout modal without the preset “,“, Nudl will not be able to read the data entry and you will receive an error message:


![Indicates incorrrect formatting upon entry](nudl-guide-assets/formatting-error-message.png)


## 🤍 Donations 

Nudl is free to use. If you find it speeds up your payment processing, consider supporting our work 🤍. For convenience we have integrated a donation option into the payment flow.
The donation wallet address set in the system is: **0x18f89f1cd153644e3ef6e70894c0673f7feb46e9**



# 📚 Glossary & References

## Glossary of Terms

We use the following terms interchangeably in the docs.  

- Disbursement: A formal transfer of funds from an organization’s account, fund, or wallet to pay obligations or allocate money for a specific purpose; used in accounting, legal, and compliance contexts and typically recorded for reconciliation.
- Payout: A transactional transfer of money to a recipient (individual or entity) as the result of an event or entitlement (e.g., earnings, rewards, claims); used in product-facing or operational contexts to describe payments made to users.

## External References

asdfad


# 📅 Calendar & Events

Important dates and upcoming events.

- To be announced on our Discord server

# 💡 Tips & Best Practices

- Visit our announcements on Discord for regular updates
- Track your transactions by saving the disbursement files

# 🤝 Feedback & Support

How users can provide feedback or get help:

- Contact us on [Discord](https://discord.gg/Ze93jKYz) for questions, issues or feedback.
- Regular open office meetings: to be announced on our Discord server