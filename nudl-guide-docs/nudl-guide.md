# Welcome to Nudl Guide

Nudl is a payment app which facilitates payouts to multiple users from your Safe and personal wallet.   

It’s easy to understand, straightforward to use, and flexible enough to fit your workflow.

All you need to do is choose your preferred transaction path.

## 🔍 Installing Nudl on Discord ✅


What to look out for when installing Nudl on your system!

### *1. Install the bot to your server*

To install on your server, click on the installation link (available, soon):

![Installation prompt](nudl-guide-assets/Installation-prompt.png)

Then grant permission:

![Grant permissions](nudl-guide-assets/Grant-permissions.png)

Nudl is installed:

![Successful installation](nudl-guide-assets/Successful-installation.png)


### 2. Customise permissions globally for your **server**

By default, Nudl is granted access to all channels, and all users have access to Nudl. If you wish to restrict this access to a specific channel or users, navigate to your server name at the top left of your screen, click on the “v” next to the server name to open the dropdown menu. Head to:

Server Settings → 

![image.png](nudl-guide-assets/image%203.png)

Integrations → 

![image.png](nudl-guide-assets/image%204.png)

Bots and Apps

![image.png](nudl-guide-assets/image%205.png)

Head to **Nudl** and press **Manage** to see the Command Permissions. Here, you can limit Nudl to particular “Channels” as well as “Roles & Members”. Default setting is All channels, All Members. In the “Commands” section you can open or limit access to Nudl commands to certain users or tags. See the Discord domumentation for further details how to use this feature.

>📌 **Note:** By design **Nudl admin** commands can only be accessed by **Discord server admins**. Therefore it is not possible to delegate admins permissions to members without Discord admin rights in your server.


>🛠️ **Work Tip:** Depending on the size of your community, we suggest using a designated channel for Nudl to avoid messages and prompts from going under.


### *3. Private channels: customise permissions locally per **channel***

*Set Nudl:*

*If a channel is set to **private,** you need to add Nudl to the channel manually:*

Head to the chosen channel → Edit channel (⚙️) → “Permissions” → “Add Members or roles”

![grafik.png](nudl-guide-assets/grafik.png)

Select Nudl from the **Roles** listing and add:

![image.png|86](nudl-guide-assets/image%206.png)

*Set Nudl permissions:*

Back on the Permissions  tab scroll down and open the “Advanced Permissions”. Select Nudl to the left and make sure the “View Channel” permission is activated: 

![grafik.png](nudl-guide-assets/grafik%201.png)



>✅ ** Congratulations:** You have successfully installed Nudl!


## 👥 User Sections

### What you need to know as a  User ✅

Nudl is easy and safe to use. A user can access and manage their profile using a single command and retain full control over their data. An Admin cannot add, modify or remove user data. In particular, a user can:

- Add addresses
- Update addresses
- Remove addresses
- View profile


>📌 ***Note:*** Admins cannot add, modify or remove addresses a user sets in Nudl, but they can process, filter and download them into a file to manage them on or offline, among other to process payments or for accounting purposes.


### Getting started

To open your profile type **/nudl** in the Discord chat.

![image.png](nudl-guide-assets/image%207.png)

Press Enter to open your profile:

![image.png](nudl-guide-assets/image%208.png)


### Add Addresses

To add your wallet address, select **Add / update**.  You can set individual addresses for each network or set the same address for all networks.

![image.png](nudl-guide-assets/image%209.png)

To set an individual address per network **Select a network**. 

![image.png](nudl-guide-assets/image%2010.png)

Or select **Set same addresss on all networks**:

![image.png](nudl-guide-assets/image%2011.png)



### Update Addresses

Before you update individual or all networks, review options before confirming.

When updating individual networks:

![image.png](nudl-guide-assets/image%2012.png)

When updating all networks choose between **override all set networks values** or add only to **networks without set values**:

![image.png](nudl-guide-assets/image%2013.png)
    
### Remove Addresses

You have the option to remove individual or all addresses:

![image.png](nudl-guide-assets/image%2014.png)

To remove an address, select a network and then **Yes, remove**:

![image.png](nudl-guide-assets/image%2015.png)

Or select **Remove all addresses** and then **Yes, remove all**:

![image.png](nudl-guide-assets/image%2016.png)

### View Profile

After setting your addresses, access your ****profile using **←Back** button or **/nudl** command.

**Show full** to expand:

![image.png](nudl-guide-assets/image%2017.png)


tutorial addresses

0x9ebda21de56278951a73f20dc2bac54e3edca6c0

0xf3f24e5fbd6efcdbeddac59bdcdfaf5ee3a720ab


## ⚙️ Admin Sections

### Quickstart ✅

The Quickstart Guide runs you through the steps when setting up Nudl for the first time, inplementing its core functions.

#### Install Nudl

 Follow the "Installing Nudl" chapter above to set up Nudl on your Discord server.

#### Admin permissions


>📌 **Note:** You need to be a Discord server admin to run Nudl admin commands.

#### Admin Dashboard

Type **/nudl-admin** into the Discord chat:

![image.png](nudl-guide-assets/image%2018.png)

 

Press **Enter** to open the Admin dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

#### Manage tokens

Preset the tokens you customarily disburse to speed up the payment process. Tokens are added to each network. There is no limit of tokens you can add per network. Start by selecting a network and then press **Add token**:

![image.png](nudl-guide-assets/image%2020.png)

Add you token contract address into the modal and **Submit**.

![image.png](nudl-guide-assets/image%2021.png)

>ℹ️ ***Information:*** You can find token contract addresses in the project documentation or on sites such as [coingecko.com](http://coingecko.com) (DYOR!), see:

![image.png](nudl-guide-assets/image%2022.png)


>🛠️ ***Work Tip:*** You can also add tokens while conducting a payment in the Safe and CSV Airdrop payment stream.



#### Manage Safes

Preset your payment Safe address. Nudl currently only supports one Safe per network.

Start by selecting a network and then press **Add Safe**:

![image.png](nudl-guide-assets/image%2023.png)

Copy address  from [Safe.global](http://Safe.global) to enclude the network prefix:

![Copy Safe Address.png](nudl-guide-assets/Copy_Safe_Address.png)

![image.png](nudl-guide-assets/image%2024.png)

Add to modal and submit:

![image.png](nudl-guide-assets/image%2025.png)

#### Notify Users

When setting up Nudl in your community, ensure to onboard as many users as possible. Make an announcement and use Nudl’s built-in **notification tool** by pressing the **Notify missing addresses** button on Admin dashboard.

To address all community members select a **Network**. Choose additional filters to refine:

![image.png](nudl-guide-assets/image%2026.png)

Click **Next: choose send channel** to specify in which channel you want to address your community. Make sure Nudl is enabled there.

![image.png](nudl-guide-assets/image%2027.png)

Then **Send notification**:

![Nudl Notification.png](nudl-guide-assets/Nudl_Notification.png)

>✅ ***Congratulations:*** You have succcessfully set up Nudl! 🎉



### Admin Introduction ✅

At Nudl, access to **admin command lines** is restricted to **Discord administrators**. 

What a Nudl Admin can do:

- Create and execute disbursements
- Identify and notify users who have not set their address on Nudl
- Access and browse the address directory using different filter settings
- Manage token and Safe addresses

What a Nudl Admin cannot do:

- Admins are not able to add, modify, or delete wallets users have set in Nudl.

>ℹ️ ***Information:*** Nudl supports token transfers based on token addresses. Native gas tokens such as ETH on the Ethereum Mainnet or SOL on Solana do not possess a token contract and are currently **not** supported.

>💡 ***Donations:***  
You have the option to support the work at Nudl.
The donation wallet address set in the system is: **0x18f89f1cd153644e3ef6e70894c0673f7feb46e9**


### Nudl Administration ✅

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

![image.png](image%2031.png)

Click on **Add a new token (not listed)**:

![image.png](image%2032.png)

Add the token contract address and **Submit**:

![image.png](image%2021.png)


>✅ ***Congratulations:*** You have sucessfully added and saved a new token to the Safe or CSV Airdrop payment stream.


>📌 **Note:** The token address is saved and available in the future. To remove it, select **Manage token** in the **Admin Dashboard**.  For further information where to obtain a token contract address refer to Quickstart for further details.


#### Cancelling adding a token

The **Add Token Address** modal was opened but your pressed **Cancel**:

![image.png](image%2021.png)

System considers the cancellation as final and closes the process:

![image.png](image%2033.png)

  
>📌 **Note:** If for any reason the modal is cancelled without adding a token contract you cannot reopen it again immediately. To reinitiate the process you have two options:


**Option 1**: press **Back to Payout Setup** and re-enter **Set Token Address**:

![image.png](nudl-guide-assets/image%2031.png)

**Option 2**: provisionally select another token of your dropdown list:

![image.png](nudl-guide-assets/image%2034.png)

Then **Edit Token Address** and re-select **Add a new token (not listed)**:

![image.png](nudl-guide-assets/image%2035.png)


>✅ ***Congratulations:*** You have sucessfully restarted the Add Token Address flow.

#### Editing a disbursement file

You can edit any of the final disbursement files to address errors or to simply modify. Press the **Edit CSV** and it will bring you back to the section where you set the amounts for each user. 

![Edit disbursement file](nudl-guide-assets/edit-disbursement-file.png)


Review any issues found by accessing **Show Last Issues**.

![Show last issues.png](nudl-guide-assets/show-last-issues.png)

##### Editing

To modify your payment file select **Edit CSV**.  This will bring you back to the start of the payment process stating witht he modal of selected recipients. You can adjust any steps as necessary or just click through the steps.


>📌 **Note:** The Edit CSV option does not allow you to change the selected network. In this case you willl need to restart the entire disbursement path. 


>🛠️ ***Work Tip:*** In case you need to restart the disbursement process because you selected the incorrect network, you do not need to add all user values afresh:

- Open **Edit CSV** of your old disbursement form, copy all users and their values
- Restart a new disbursement path with the correct network
 - Once you added a network you will see the following options:

![image.png](nudl-guide-assets/image%2036.png)

- Select **Manual paste** which will open the user modal.
- Past the users and values you copied earlier and proceed as usual.
   
#### Remove a token

To remove a token open the **Admin dashboard**, select **Manage tokens** and **Select a network**:

![Select a network|505](nudl-guide-assets/remove-token-network-select.png)

Click **Remove Token**, then **Select a token to remove** and choose a token from the list:

![Select the token to be removed|418](nudl-guide-assets/select-token-to-remove.png)

Confirm **Yes, Remove**:

![Confirm removal of selected token|550](nudl-guide-assets/confirm-token-removal.png)

You have the options to manage further tokens:

![Token removal confirmed|422](nudl-guide-assets/token-removal-success.png)

  
>✅ ***Congratulations:*** You have sucessfully removed a token from Nudl.

#### Manual paste

All payment paths allow to manually ingest user and payment data:

![Enter customised data](nudl-guide-assets/manual-paste.png)

This can be a helpful and speedy way to manage repeat payments to the same recipients with the same values that you have conducted in the past and have stored in a previous disbursement file. Make sure you paste the data in the correct format. 


>📌 **Note:** Discord has a 4000 character limit, which accommodates approximately 100 users if you use Discord ID codes.



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

![image.png](nudl-guide-assets/image%2042.png)

Optionally select channel or role filter do best target the payout group. Press **Set amounts**:

![image.png](nudl-guide-assets/image%2043.png)

Add payment values after the comma:

![image.png](nudl-guide-assets/image%2044.png)

Add an optional **Donation** amount to the transaction to support work at Nudl.

Or  **Continue Safe setup**:

![image.png](nudl-guide-assets/image%2045.png)

Add any donation amount here, **Submit** and then **Continue Safe setup**:

![image.png](nudl-guide-assets/image%2046.png)

Select a token and Safe address you have set up as described in the **Quickstart** section. Alternatively, set a new token address or set/replace a Safe address:

![Set token and Safe address](nudl-guide-assets/safe-payout-setup.png)

**Set Token**:

![image.png](nudl-guide-assets/image%2048.png)

**Set Safe Address**:

![image.png](nudl-guide-assets/image%2049.png)

After setting you have the option to edit both addresses again:

![Safe - Edit Addresses.png](nudl-guide-assets/Safe_-_Edit_Addresses.png)

Generate Safe Payout JSON file and download:

![Safe - Payment file.png](nudl-guide-assets/Safe_-_Payment_file.png)

##### Step 2: Upload Nudl payout form to Safe

Open your [SAFE](https://safe.global/) account and first verify that the address and network correspond with the selections made in **/admin_safe_payout**. After that, click on “New transaction” and then on “Transaction Builder”.

![grafik.png](nudl-guide-assets/grafik%202.png)

 Alternatively, navigate to the “App” section and select “Transaction Builder”.

![grafik.png](nudl-guide-assets/grafik%203.png)

Upload the JSON file downloaded in step 1 above by clicking on the “*choose a file*” button located in the bottom right corner:

![grafik.png](nudl-guide-assets/grafik%204.png)

Press “*Create a Batch*“:

![grafik.png](nudl-guide-assets/grafik%205.png)

To review individual transactions, click on the pencil icon. If you are familiar with the process, you can make specific edits in the form, such as adjusting the values.

To ensure everything is configured properly, simulate the transaction.

![grafik.png](nudl-guide-assets/grafik%206.png)

If the simulation is successful begin the transaction by clicking "Send batch" and follow your usual multisig setup process.


>✅***Congratulations:*** You have succcessfully concluded your SAFE transaction!


#### Conduct a payout using **Disperse** and **Smol dApp** ✅

##### Step 1: Create a payout form in Nudl

Select **Start payout** on the Nudl Admin dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select **Disperse**:

![Select Disperse](nudl-guide-assets/start-payout-options.png)

**Select a network**:

![image.png](nudl-guide-assets/image%2050.png)

Optionally select channel or role filter do best target the payout group. Press S**et amounts**:

![image.png](nudl-guide-assets/image%2051.png)

Add payment values after the comma:

![image.png](nudl-guide-assets/image%2044.png)

Add an optional **Donation** amount to the transaction to support work at Nudl.

Or  **Generate Disperse file**:

![image.png](nudl-guide-assets/image%2052.png)

Add any donation amount here:

![image.png](nudl-guide-assets/image%2046.png)

Generate Safe Payout CSV file and download:

![Disperse - Payment file.png](nudl-guide-assets/Disperse_-_Payment_file.png)

##### Step 2: Upload Nudl payout form to Disperse and Smold.app

###### A. Upload to Disperse

Open [Disperse](https://disperse.app/) and login with your wallet of choice. Set your wallet to the network and wallet address from which you want to make the transfer from.

Select the network on Disperse:

![image.png](nudl-guide-assets/image%2053.png)

Select between ETH or token disbursement. If you choose a token add the token contract address. For more information where to find these see our Quickstart section. Then **load**:

![image.png](nudl-guide-assets/image%2054.png)

Open the Nudl file and **copy** the data which can include the headings.

![image.png](nudl-guide-assets/image%2055.png)

**Paste** into the “recipients and amounts” field:

![image.png](nudl-guide-assets/image%2056.png)

For confirmation the exact payment amounts, total and the wallet balance holding are calculated instantly:

![Disperse - Payment grid.png](nudl-guide-assets/Disperse_-_Payment_grid.png)

Approve token and disburse:

![grafik.png](nudl-guide-assets/grafik%207.png)


>✅***Congratulations:*** You have succcessfully concluded your Disperse transaction!
  

###### B. Upload to Smold.app

To begin, choose Disperse at [Smol](https://smold.app/disperse), select the Disperse tab and log in with your preferred wallet.

![grafik.png](nudl-guide-assets/grafik%208.png)

Select your token address. The Smol app allows you to search by token address or you can add one from a third party source. More information on token addresses see Quickstart :

![image.png](nudl-guide-assets/image%2057.png)

Upload the CSV file we downloaded from Nudl using **Import Configuration**:

![image.png](nudl-guide-assets/image%2058.png)

Check the upload details:

![image.png](nudl-guide-assets/image%2059.png)

Check the total amount, approve and execute the payout:

![image.png](nudl-guide-assets/image%2060.png)


>✅***Congratulations:*** You have succcessfully concluded your Smold.app transaction!


>📌 **Note:** If “No token selected” appears in the token field, please check that your wallet holds a balance of the selected token.


#### Conduct a payout using **CSV Airdrop** ✅

##### Step 1: Create a payout form in Nudl

Select **Start payout** on the Nudl Admin dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select **CSV Airdrop**:

![Select Disperse](nudl-guide-assets/start-payout-options.png)


**Select a network**:

![image.png](nudl-guide-assets/image%2061.png)

Optionally select channel or role filter do best target the payout group. Press **Set amounts**:
        
![image.png](nudl-guide-assets/image%2062.png)

Add payment values after the comma, then **Submit**:

![image.png](nudl-guide-assets/image%2063.png)

Add an optional **Donation** amount to the transaction to support work at Nudl.
        
Or **Select token**:

![image.png](nudl-guide-assets/image%2064.png)

Add any donation amount here and **Submit** then **Select token**:

![image.png](nudl-guide-assets/image%2046.png)

Select a token you have set up as described in the **Quickstart** section. Alternatively, set a new token address:

![image.png](nudl-guide-assets/image%2065.png)

**Generate CSV Airdrop file**:

![image.png](nudl-guide-assets/image%2066.png)

**Generate CSV Airdrop file** and download:

![CSV Airdrop - Disbursement file.png](nudl-guide-assets/CSV_Airdrop_-_Disbursement_file.png)

##### Step 2: Upload Nudl payout form to CSV Airdrop in Safe

Open your [SAFE](https://safe.global/) account and first verify that the address and network correspond with the selections made your Nuld payout file. 

Search for CSV Ardrop under App section.

![image.png](nudl-guide-assets/image%2067.png)

Select:

![image.png](nudl-guide-assets/image%2068.png)

Confirm:

![image.png](nudl-guide-assets/image%2069.png)

Upload the Nudl disbursement file downloaded above:

![image.png](nudl-guide-assets/image%2070.png)

Upload the Nudl CSV file:

![CSV - Paste Values.png](nudl-guide-assets/CSV_-_Paste_Values.png)


>📌 ***Note:*** To speed things up you can expand the file field in Nudl (or open the downloaded Nudl file) **copy** the data **including** the headings, and **paste** into the CSV Aridrop data field:


![CSV Airdrop File.png](nudl-guide-assets/CSV_Airdrop_File.png)


Review all entries, check amounts and total in **Summary** then **Submit**:

![image.png](nudl-guide-assets/image%2071.png)

Start the Safe Multisig transaction:

![CSV Airdrop - Safe Upload.png](nudl-guide-assets/CSV_Airdrop_-_Safe_Upload.png)


>✅ ***Congratulations:*** You have succcessfully started your CSV Airdrop transaction!


#### Conduct a payout using **Nudl Web** ⚠️

##### Step 1: Create a payout form in Nudl Web

Select **Start payout** on the Nudl Admin dashboard:
admin-dashboard:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select **Nudl Web:**

![Select Nudl Web](nudl-guide-assets/start-payout-options.png)

**Select a network**:

![image.png](nudl-guide-assets/image%2073.png)

Optionally select channel or role filter do best target the payout group. Press **Set amounts**:

![image.png](nudl-guide-assets/image%2074.png)

Add payment **values** and/or **points** after the comma, then **Submit**:

![image.png](nudl-guide-assets/image%2075.png)

**Generate Nudl Web CSV**:

![image.png](nudl-guide-assets/image%2076.png)

Download the CSV file/connect to Nudl web:

![Nudl_Web - Create file.png](nudl-guide-assets/Nudl_Web_-_Create_file.png)
        
##### Step 2: Upload Nudl disbursement to Nudl site

**coming soon**

>✅ ***Success:*** You have succcessfully concluded your Nudl Web transaction!


### Address Directory ✅

Nudl admins can manage payment flows by accessing different filtering options. It also helps discover duplcate addresses.

#### Admin Dashboard

Click the **Address directory** button on the Admin dashboard:

![Select the address directory](nudl-guide-assets/admin-dashboard.png)

The Nudl provides you with different options:

![image.png](nudl-guide-assets/image%2077.png)

#### Browse directory

Select Browse directory, then set the desired filters. Choose amongst Network (mandatory), Role and Channel:

![image.png](nudl-guide-assets/image%2078.png)

This will list the respective wallet holders and their corresponding addresses. You have the option to export your search results as CSV file.


>🛠️ ***Work Tip:*** Make sure you are as specific as possible, as Discord has a character limit in place which may prevent the display of all filtered users.


#### Lookup by address

To clarify whether an address is associated with a user, select **Lookup by address**, add the address to the modal and **Search**:

![image.png](nudl-guide-assets/image%2079.png)

#### Lookup by username

To clarify which address is associated with a particular user, select **Lookup by username**:

![image.png](nudl-guide-assets/image%2080.png)

This will list the respective wallet holder and their corresponding addresses. You have the option to export your search results as CSV file.


### Nofity missing addresses ✅

Nudl features a notification tool to inform users fo your community to add their wallet address to the system. You can use this for general onboarding or when you are about to prepare a disbursement.

Use **/nudl-admin** to open the Nudl **Admin dashboard** and select **Notify missing addresses**:

![Open the admin dashboard](nudl-guide-assets/admin-dashboard.png)

Select a **Network (required)**, fine-tune further using channel and role filters :

![image.png](image%2081.png)

 

**Next: choose send channel**:

![image.png](image%2082.png)

Modify default channel where to post the notification. Nudl must be enabled there!

Then **Send notification**:

![image.png](image%2083.png)

If you send a notification to a channel in which Nudl is not activated:

![image.png](image%2084.png)

If you send a notification to a channel to which a user has no access:

![image.png](image%2085.png)

You will receive a confirmation once successfully sent:

![image.png](image%2086.png)

Users can choose to use the dedicated **Add address button** or **/nudl** command:

![Notification notice.png](Notification_notice.png)

Press the **Add token address** button to open the modal:

![image.png](image%2087.png)

Anyone in the channel has button access. A user with an address already set is informed:

![Notification - already added.png](Notification_-_already_added.png)

Once saved you will receive your address overview:

![image.png](image%2088.png)



### Manage tokens and Safes ✅

#### Introduction

How to add tokens and safes is discussed in **Quickstart** section.

We will review how to **remove** each here.

Open the Admin dashboard using **/nudl-admin** and select **Manage tokens** or **Manage Safes**:

![image.png](image%2089.png)


#### Removing a token

Select a network:

![image.png](image%2090.png)

Choose Remove Token

![image.png](image%2091.png)

Select the token to be removed:

![image.png](image%2092.png)

Confirm **Yes, Remove**:

![image.png](image%2093.png)

The removal is confirmed:

![image.png](image%2094.png)


>✅ ***Congratulations:*** You have succcessfully removed your token from Nudl!

  
#### Removing a Safe

Select **Remove Safe**:

![Safe overview.png](nudl-guide-assets/Safe_overview.png)

**Select Safe to remove**:

![image.png](nudl-guide-assets/image%2095.png)

Confirm **Yes, remove**:

![Remove Safe confirm.png](nudl-guide-assets/Remove_Safe_confirm.png)

The removal is confirmed:

![Safe removal confirmation.png](nudl-guide-assets/Safe_removal_confirmation.png)

>✅ ***Congratulations:*** You have succcessfully removed your Safe from Nudl!


Leftover docs:

The donation wallet address is: 0x18f89f1cd153644e3ef6e70894c0673f7feb46e9

>💡 ***Pro Tip:***  fill as required


>ℹ️ ***Information:*** Nudl supports token transfers based on token addresses. Native gas tokens such as ETH on the Ethereum Mainnet or SOL on Solana do not possess a token contract and are currently **not** supported.

 
>📌 **Note:** You can also manually add this data using Discord display or unique names, which may be quicker for smaller groups. Enter one line per entry. Please note that there is a 4000 character limit, which accommodates approximately 100 users if you use Discord ID codes.

  
### Nudl Flow Visualisation

#### **SAFE**

#### **Disperse / Smold**

#### **Nudl Web**


# 📚 Glossary & References

## Nudl Editing and formatting

## Truncated Discord IDs

  
>🛠️ ***Work Tip:*** Generating the CSV file often truncates (shorten) the Discord IDs. To prevent this, consider uploading your CSV file to Google Sheets. For guidance, visit: [How to Open a CSV File in Google Sheets - GeeksforGeeks](https://www.geeksforgeeks.org/how-to-open-a-csv-file-in-google-sheets/).

If you use LibreOffice or Excel instead, following these steps:

1. Double-click on the downloaded CSV file.
2. The text import editor will appear:
3. Highlight the Discord ID column and change the formatting to “Text,” then click “OK” to import.


![Truncated User ID.png](nudl-guide-assets/Truncated_User_ID.png)

## Error messages

   
>ℹ️ ***Information:** Nudl* can only process users who have registered their wallet addresses in Nudl. If Nudl is unable to locate a user due to misspellings, non-existence, or the absence of a submitted wallet address, an alert ⚠️ will be triggered. The total transfer amount displayed serves as an additional verification tool for you to cross-check against your original disbursement calculations.



![Error message.png](nudl-guide-assets/Error_message.png)

## Formatting


>ℹ️ ***Information:*** Nudl is format sensitive. If you enter the data into the Payout modal without the preset “,“, Nudl will not be able to read the data entry and you will receive an error message:


![grafik.png](nudl-guide-assets/grafik%209.png)

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