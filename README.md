# Lasting Impressions Card System — Staff User Guide

---

## Installation Instructions:
### Download latest version from: [Here](https://github.com/rsobo/card-system-app-public/releases) 
After downloading double click CardSystemUpdater.bat (found on your desktop)

## Getting Started

### Logging In
1. Open the application. You will see the login screen.
2. Type your **Username** and **Password** and click **Login**.
   - The first login of the day may take 15–20 seconds while the system starts up. This is normal.
3. If you forgot your password, click **Reset Password**. A web page will open with instructions.

> **After 10 failed login attempts your account will be locked for 5 minutes.** Wait and try again.

### Automatic Logout
The system logs you out automatically in two situations:
- **No activity for 15 minutes** — simply move the mouse or type to reset the timer.
- **Session expires** — if the system cannot renew your session in the background, you will be logged out and will need to log back in.

---

## Navigation

After logging in you will land on the **Home** screen. Use the menu bar at the top to navigate.

| Menu | What it does |
|---|---|
| **Home** | Returns to the home screen |
| **Membership** | Create cards, look up members, update profiles |
| **Gift Card** | Issue new gift cards |
| **Transactions** | Process sales and (for managers) view history |
| **Referrals** | Record and search referrals |
| **Management** | Manage products & services *(Manager/Admin only)* |
| **Logout** | Securely sign out |

---

## Membership

### Create New Membership Card
Use this to enroll a brand-new member and issue them a physical card.

1. Fill in the member's **First Name**, **Last Name**, **Date of Birth** (MMDDYYYY), **Email**, and **Phone Number**.
2. Check the boxes for the member's communication consent and preferred contact method.
3. Click **Scan Member Card** and place a blank NFC card on the card reader. The card's serial number will appear on screen.
4. Click **Create Member**.
5. A web browser will open to the Clover portal — **complete the subscription setup there before continuing**.
6. Return to the app. A prompt will ask you to place the card on the reader to activate it. Leave the card on the reader until you see a "Success" message.
7. The app will take you to the **Print Screen** automatically to print the physical card.

---

### Membership Tracker
Quickly check a member's billing status and recent treatment history.

**Find the member — two ways:**
- **Scan tab:** Place the member's card on the reader and click **Scan Card**.
- **Search tab:** Enter the member's first and last name, or their phone number, and click **Search**. If multiple results appear, click the correct one in the list.

**What you'll see once a member is loaded:**
- Their name at the top.
- **Billing Status** — green means Active, red means there is an issue.
- A list of their recent SknLab treatments with dates and times.

Click **Search for Another Member** at the bottom when you're done.

---

### Member Profile
Use this to update a member's information or replace their card.

1. Find the member using the **Scan** or **Search** tab.
2. **Update info:** Change name, email, phone, or contact preference and click **Save Changes**.
3. **Replace a lost or damaged card:** Click **Scan Blank Card** and place a new blank card on the reader. This links the new card to the member's account.
4. **Reprint a faded card:** Click **Reprint Member Card** to go straight to the print screen without changing any card data.

---

## Gift Cards

### Create New Gift Card
1. Click **Scan Card** and place a blank NFC card on the reader.
2. Enter the **Value** (dollar amount), **Purchaser Name**, **Recipient Name**, and **Email**.
3. Select the **Payment Method** (Credit Card, Cash, or Other).
4. Click **Create & Write Card**.
5. When prompted, place the card on the reader to activate it. Leave it there until you see a "Success" message.
6. The app will take you to the **Print Screen** automatically to select a card design and print.

---

## Transactions

### New Transaction (Point of Sale)

1. **Choose payment method(s)** — check Credit Card, Cash, or both.
   - If you select **Gift Card**, a **Scan/Search Gift Card** button will appear. Use it to scan or manually enter a gift card number and check its balance.

2. **Attach a member (optional but recommended):**
   - Click **Scan Card** to scan the member's card, or
   - Click **Search** to find a member by name or phone number.
   - The member's name will appear once they are attached.

3. **Add items:**
   - Select a product or service from the **Item** dropdown.
   - If a member is attached and you select a **Product**, the **20% membership discount** is applied automatically.
   - Adjust **Quantity** or **Cost Per** if needed and apply any other discounts.
   - Click **Add Item**. The item appears in the cart below.
   - To remove something, select it in the cart and click **Remove Selected**.

4. Review the total at the bottom, then click **Submit Final Transaction** to complete the sale.

---

### Transaction Log *(Manager/Admin only)*
View and export a history of past transactions.

1. Use the filters at the top to narrow by patient name, date range, product/service, or other fields.
2. Click **Search** to load the results.
3. Click **Export to CSV/Excel** to save the results as a spreadsheet file on your Desktop or Downloads folder.

---

## Referrals

### Create a Referral
Record when a current member refers someone new.

1. Go to **Referrals → Create Referral**.
2. Enter the **Patient Name** (the new person being referred) and **Referred By** (the member who made the referral).
3. Click **Create Referral**. A confirmation message will appear.

### Search Referrals
Look up referral records for a person.

1. Go to **Referrals → Search Referrals**.
2. Type a name in the search box and click **Search**.
3. Matching referrals will appear in the table, showing who was referred, who referred them, and when.

---

## Management *(Manager/Admin only)*

### Manage Products & Services
Add new items to the catalog or update existing ones.

1. Choose **Create New** to add an item or **Update Existing** to change one.
2. Choose whether it is a **Product** or a **Service**.
3. If updating, type in the search box to find the item. Its current details will fill the form.
4. Fill in the name, price, and any other required fields.
5. Click **Create/Update** to save.

> Price must be between $0.00 and $99,999.99. Name fields are limited to 255 characters.

---

## Printing
The system prints to the Zebra card printer automatically after creating a new membership card or gift card.

- **Membership cards** print with the member's name, card number, and the year they joined on the back.
- **Gift cards** — you will be shown a selection of card designs. Click the design you want, then click **Print Selected Design**.

---

## Tips & Troubleshooting

| Situation | What to do |
|---|---|
| Login is slow on the first attempt | Wait up to 20 seconds — the system is starting up in the background |
| Card reader not detecting a card | Remove the card, wait 2 seconds, and place it back flat on the reader |
| Card write fails on first try | The system will retry once automatically; if it fails again, the record is saved but the physical card is blank — contact your manager |
| Printer not found | Restart the app; printer discovery runs at startup |
| Forgot password | Use the **Reset Password** button on the login screen |
| Account locked | Wait 5 minutes, then try again |
