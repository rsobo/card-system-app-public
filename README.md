# Lasting Impressions Management System - User Guide

This guide provides a detailed walkthrough of the features and workflows in the Lasting Impressions Management System.

## 1. Getting Started

### 1.1. Logging In
When you first start the application, you will see the login screen.

1.  **Enter Credentials:** Type your assigned **Username** and **Password** into the text fields.
2.  **Login:** Click the **"Login"** button. The system will authenticate your credentials.
    *   *Note:* The first login of the day may take 15-20 seconds as the backend service starts up.
3.  **Password Reset:** If you have forgotten your password, click the **"Reset Password"** button. This will open a secure web page where you can follow the instructions to reset your password.

### 1.2. Automatic Logout and Session Management
For your security, the application includes two automatic logout features:
- **Inactivity Timeout:** If you do not move the mouse or type for **15 minutes**, the application will automatically log you out.
- **Session Expiration:** Your session is valid for many hours of continuous use. If the session cannot be renewed in the background, you will be logged out.

## 2. The Main Application

### 2.1. Dashboard
After logging in, you will land on the main **Dashboard**. This screen provides a central welcome point. All application features are accessible from the menu bar at the top of the window.

### 2.2. Navigation Menu
The menu bar at the top contains the following sections:
- **Home:** Returns you to the Dashboard.
- **Membership:** Contains all tools for managing members.
- **Gift Card:** Tools for creating and managing gift cards.
- **Transactions:** Point-of-sale and transaction history tools.
- **Management:** Tools for managing products and services (Manager/Admin only).
- **Logout:** Securely logs you out of the application.

## 3. Membership Management

### 3.1. Create New Membership Card
Use this screen to enroll a new member and issue them a physical card.

1.  **Fill out Details:** Enter the new member's First Name, Last Name, Date of Birth (in MMDDYYYY format), Email, and Phone Number.
2.  **Set Preferences:** Check the boxes to confirm the member's consent for email/text communications and select their preferred contact method.
3.  **Scan Card:** Click the **"Scan Member Card"** button. The system will wait for you to place a blank NFC card on the card reader.
4.  **Create Member:** Once the card is scanned and its serial number appears, click **"Create Member"**.
5.  **Set Up Subscription:** A web browser will open automatically, directing you to the Clover portal. You **must** complete the subscription setup for the member in the browser.
6.  **Activate Card:** After setting up the subscription, return to the application. An alert will ask you to place the card on the scanner to activate it. Leave the card on the scanner until you see a "Success" message.
7.  **Print Card:** The application will automatically navigate to the Print Screen to create the physical membership card. The back of the card will be printed with the member's name, number, and the year they joined.

### 3.2. Membership Status Tracker
This screen is designed to quickly look up a member's treatment history and billing status.

1.  **Find the Member:**
    *   **By Scanning:** Go to the "Scan Membership Card" tab, place the member's card on the reader, and click **"Scan Card"**.
    *   **By Searching:** Go to the "Search by Name/Phone" tab, enter the member's First Name and Last Name, or their Phone Number, and click **"Search"**. If multiple results are found, a table will appear allowing you to select the correct member.
2.  **Review Status:** Once a member is loaded, their information will appear in a clean, organized view.
    *   The member's name is displayed prominently at the top.
    *   **Billing Status** is color-coded: **Green** for "Active", **Red** for any other status.
    *   You can view a list of their most recent **SknLab** treatments, including the date and time of each.
3.  **Search Again:** To look up another member, click the **"Search for Another Member"** button at the bottom.

### 3.3. Member Profile (Update)
Use this screen to update a member's contact information or issue them a replacement card.

1.  **Find the Member:** Use the Scan or Search tabs to load the member's profile.
2.  **Update Information:** Change the First Name, Last Name, Email, Phone, or Contact Preference as needed. Click **"Save Changes"** to save.
3.  **Issue a New Card (Lost/Damaged):** If a member needs a new physical card, click **"Scan Blank Card"** and place a new, unassigned card on the reader. This will link the new card to the member's existing account and prepare it for printing.
4.  **Reprint Existing Card:** If a member's card is fine but the printing has faded, click **"Reprint Member Card"** to go directly to the print screen without changing any card data.

## 4. Transactions (Point of Sale)

### 4.1. New Transaction
This is the main screen for processing sales of products and services.

1.  **Select Payment Method:** At the top, check one or more payment methods (e.g., "Credit Card", "Cash").
    *   If you select **"Gift Card"**, a **"Scan/Search Gift Card"** button will appear. Click it to scan or manually enter a gift card number to check its balance.
2.  **Attach a Member (Optional but Recommended):**
    *   Click **"Scan Card"** to associate a member with the transaction by their card.
    *   Click **"Search"** to open a search dialog and find a member by name or phone.
    *   Once a member is selected, their name and ID will appear.
3.  **Add Items to Cart:**
    *   Use the **"Item"** dropdown to search for and select a product or service.
    *   **Member Discount (Automatic):** If a member is attached to the transaction and you select a **Product**, the **20% Membership discount** will be automatically applied.
    *   Adjust the **Quantity** or **Cost Per** item if needed.
    *   Apply any other manual discounts or price adjustments.
    *   Click **"Add Item"**. The item will appear in the cart below.
4.  **Finalize Sale:**
    *   Review the items in the cart. You can select an item and click **"Remove Selected"** to make changes.
    *   The total amount is displayed at the bottom.
    *   Click **"Submit Final Transaction"** to complete the sale.

### 4.2. Transaction Log (Manager/Admin Only)
This screen provides a powerful way to view and export past transactions.

1.  **Filter Transactions:** Use the search fields at the top to filter by patient name, date range, specific products/services, and more.
2.  **Search:** Click the **"Search"** button to view all transaction line items that match your filters.
3.  **Export Data:** Click **"Export to CSV/Excel"** to download the currently filtered data as a CSV file, which can be opened in Microsoft Excel or other spreadsheet software. The file will be saved to your Desktop or Downloads folder.

## 5. Management (Manager/Admin Only)

### 5.1. Manage Products & Services
This screen allows authorized users to manage the catalog of items available for sale.

1.  **Choose Action:** Select **"Create New"** to add a new item or **"Update Existing"** to modify one.
2.  **Choose Type:** Select whether the item is a **"Product"** or a **"Service"**.
3.  **Find Item (for Updates):** If updating, a search box will appear. Start typing the name of the item to find and select it. Its details will fill the form.
4.  **Enter Details:** Fill out all required fields, such as Name, Price, and Manufacturer.
5.  **Save:** Click the **"Create/Update"** button at the bottom to save your changes to the system.

## 6. Printing
The application is designed to work with Zebra card printers for creating physical membership and gift cards.

- **Automatic Printing:** After successfully creating a new member or gift card, the application will automatically take you to the **Print Screen**.
- **Gift Card Designs:** When printing a gift card, you will be shown a selection of available card designs. Click on the design you wish to use, then click the **"Print Selected Design"** button.
- **Mock Printing:** For testing without a physical printer, an administrator can enable "Print Mocking". This will save a PNG image of what *would* have been printed to your computer's Desktop.
