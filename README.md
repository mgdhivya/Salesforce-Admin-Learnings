⚡ Salesforce Learning Journey — Day 7

Topic: Tabs & Apps in Salesforce Lightning Experience
🗓️ Self Study Notes | 💻 Practical Done in Developer Org | 🎯 Salesforce Admin Track


📌 Table of Contents

What are Tabs?
Types of Tabs
How to Create Each Tab
How to Verify Tabs
What are Apps?
Types of Apps
How to Create Each App
How to Verify Apps
Key Takeaways


📌 What are Tabs?

Used to navigate between objects in Salesforce
Always present at the top of the Salesforce app

Where can you see Tabs?
PlaceWho uses itPurposeInside your App — Top Navigation BarUserNavigate between objectsSetup → TabsAdminManage and create tabs

📌 Types of Tabs
1️⃣ Standard Tabs

Default tabs created by Salesforce
Cannot be deleted
Eg: Accounts, Contacts, Opportunities

2️⃣ Custom Tabs

Created by Admin for Custom Objects
Without this — custom object won't be visible in the App!
Eg: Student__c, Order__c

3️⃣ Web Tabs

Opens a Website inside Salesforce
Eg: Google.com, Wikipedia.com

4️⃣ Visualforce Tabs

Shows a custom UI page inside Salesforce
Created by a Developer
Eg: Custom designed UI page

5️⃣ Lightning Component Tabs

Opens a Lightning Component (LWC or Aura)
Eg: Custom LWC component

6️⃣ Lightning Page Tabs ⚡

Created by Admin
Points to a Lightning App Page built in App Builder
A page can have multiple components laid out together
Only works with App Page type (NOT Home Page or Record Page)
Tab is auto-created when you Activate the page


📌 How to Create Each Tab
✅ Custom Tab
Step 1: Setup → Quick Find → Tabs
Step 2: Custom Object Tabs section → Click New
Step 3: Choose Object from dropdown → Choose Style → Next
Step 4: Choose Profile Visibility:
        - Default ON  → Tab visible automatically
        - Default OFF → User enables manually
        - Hidden      → Tab invisible to that profile
Step 5: Choose which Apps this tab appears in → Save
✅ Web Tab
Step 1: Setup → Tabs → Web Tabs section → Click New
Step 2: Choose Tab Layout → Next
Step 3: Give Tab Label → Auto fills Tab Name → Choose Style → Next
Step 4: Enter URL (Eg: https://www.google.com)
Step 5: Choose Profile Visibility → Next
Step 6: Choose Apps → Save
✅ Visualforce Tab
Step 1: Setup → Tabs → Visualforce Tabs section → Click New
Step 2: Choose Visualforce Page from Dropdown
Step 3: Give Tab Label → Auto fills Tab Name
Step 4: Choose Style → Next
Step 5: Choose Profile Visibility → Next
Step 6: Choose Apps → Save
✅ Lightning Component Tab
Step 1: Setup → Tabs → Lightning Component Tabs → Click New
Step 2: Choose Lightning Component from Dropdown
Step 3: Give Tab Label → Auto fills Tab Name
Step 4: Choose Style → Next
Step 5: Choose Profile Visibility → Save
✅ Lightning Page Tab
Step 1: Setup → Quick Find → Lightning App Builder
Step 2: Click New → Select App Page → Next
Step 3: Give Label Name (Eg: Sales Dashboard) → Next
Step 4: Choose Layout → Finish
Step 5: Drag & Drop Components onto the page
Step 6: Click Save → Click Activate
        ✅ Tab is auto-created!

📌 How to Verify Tabs
Setup → Quick Find → Tabs

You will see all tabs listed:
┌─────────────────────────────────┐
│ Custom Object Tabs              │
│ → Your Custom Tab ✅            │
│                                 │
│ Web Tabs                        │
│ → Your Web Tab ✅               │
│                                 │
│ Visualforce Tabs                │
│ → Your Visualforce Tab ✅       │
│                                 │
│ Lightning Component Tabs        │
│ → Your Component Tab ✅         │
│                                 │
│ Lightning Page Tabs             │
│ → Your Page Tab ✅              │
└─────────────────────────────────┘
Also verify in App:
9 dots (top left) → App Launcher → Open your App
→ Look at Navigation Bar at TOP
→ Your tabs appear here! ✅

📌 What are Apps?

A collection of tabs grouped together for a specific purpose
Visible to specific users based on their Profile
Accessible from App Launcher

Where to find Apps:
Top Left → 9 dots → App Launcher → All Apps

📌 Types of Apps
1️⃣ Standard Apps

Pre-built by Salesforce
Cannot be Deleted — only hidden
Can be Edited (add/remove tabs)
Eg: Sales, Service, Marketing

2️⃣ Custom Apps

Created by Admin for business needs
Can be Created, Edited and Deleted
Assign specific tabs + profiles
Eg: Student App, HR App

3️⃣ Connected Apps

Connects third party tools to Salesforce via OAuth 2.0
Admin controls who can access the connection
Eg: Google Workspace, Microsoft Teams


What is OAuth 2.0?
Secure way to give permission to an external app to access your Salesforce data without sharing your password
How it works:
User → Clicks Connect → Third Party App → Asks Permission
     → User Approves → Token Generated → Secure Access ✅

4️⃣ Packaged Apps

Downloaded from AppExchange (Salesforce's own Marketplace)
Like a Play Store for Salesforce 📱
Two Types:

Managed Package — Code is locked/Protected
Unmanaged Package — Code is open/Editable


Advantages:

Ready made solution
Save time & money
Extend Salesforce features
Trusted & tested




📌 How to Create Each App
✅ Custom App
Step 1: Setup → Quick Find → App Manager
Step 2: Click New Lightning App
Step 3: App Details → Name, Description, Logo, Style
Step 4: App Options → Navigation, Form Factor
Step 5: Utility Items → Add Utility Bar (optional)
Step 6: Navigation Items → Add Tabs to the App
Step 7: User Profiles → Assign Profiles:
        - Visible    → App appears in App Launcher
        - Default ON → App opens automatically on login
        - Not assigned → Profile cannot see the app
Step 8: Save and Finish ✅
✅ Connected App
Step 1: Setup → Quick Find → App Manager
Step 2: Click New External Client App
Step 3: Give External Client Name → Auto generates API Name & Email
Step 4: Enable OAuth Settings → Fill Callback URL & OAuth Scope
Step 5: Click Save ✅
✅ Packaged App (Install from AppExchange)
Step 1: Browser → https://appexchange.salesforce.com
Step 2: Search for any App (Eg: DupeCatcher)
Step 3: Click "Get it Now"
Step 4: Login with Salesforce credentials
Step 5: Choose Install For:
        - Admins Only
        - All Users
        - Specific Profiles
Step 6: Click Install → Approve → Continue ✅

📌 How to Verify Apps
✅ Custom App & Standard App
Setup → Quick Find → App Manager
→ All apps are listed here ✅
→ Use Arrow → View to see app details
✅ Connected App
Setup → Quick Find → External Client Apps
→ Your External Client App is listed here ✅
✅ Packaged App
Setup → Quick Find → Installed Packages
→ Your installed app is listed here ✅
→ Check Package Type → Managed or Unmanaged
Also verify in App Launcher:
9 dots (top left) → App Launcher
→ Search your App Name
→ Your App appears here! ✅

📌 How to Manage Apps
ActionStepsCreate new AppApp Manager → New Lightning AppEdit existing AppApp Manager → Arrow → EditDelete Custom AppApp Manager → Arrow → DeleteHide Standard AppApp Manager → Arrow → EditView App detailsApp Manager → Arrow → View

📌 Key Takeaways
✅ Tabs    = Navigate between objects
✅ Apps    = Group of tabs for a specific team
✅ OAuth   = Secure permission without password sharing
✅ AppExchange = Salesforce Marketplace (like Play Store)

✅ Right Tabs + Right App = Right team sees Right information! 🎯

Verify Tabs → Setup → Tabs
Verify Apps → Setup → App Manager
## 📸 Practical Screenshots

### 📒 My Notes:
![Notes 1](Notes%201.png)
![Notes 2](Notes%202.png)
![Notes 3](Notes%203.png)
![Notes 4](Notes%204.png)
![Notes 5](Notes%205.png)
![Notes 6](Notes%206.png)
![Notes 7](Notes%207.png)
![Notes 8](Notes%208.png)
![Notes 9](Notes%209.png)

### 💻 Dev Org Screenshots:
![Screenshot 1](Screenshot%202026-06-01%20112556.png)
![Screenshot 2](Screenshot%202026-06-01%20112610.png)
![Screenshot 3](Screenshot%202026-06-01%20112741.png)
![Screenshot 4](Screenshot%202026-06-01%20112846.png)
![Screenshot 5](Screenshot%202026-06-01%20114203.png)
![Screenshot 6](Screenshot%202026-06-01%20172830.png)
 Packaged App installed


