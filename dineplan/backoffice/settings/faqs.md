# FAQ's

## 1. How do I bulk import menu items or table information into DinePlan using a file?

To import menu or table data in bulk using pre-prepared files:

1. Open **BackOffice** and select **"Setup"**.
2. Select **"Import"**.
3. **To import menu data:** Under **"Import Menu"**, select **"File Selection"** to choose your prepared menu file.
4. _(Optional)_ If you need to wipe existing menu data before uploading, select **"Clear Menu"** (or **"Clear Data"**).
5. Select **"Import Menu"** to execute the menu data import.
6. **To import table data:** Under **"Import Table"**, select **"File Selection"** to choose your prepared table file.
7. _(Optional)_ Select **"Clear Table"** if existing table data must be removed first.
8. Select **"Import Table"** to execute the table data import.

<figure><img src="../../.gitbook/assets/image (578).png" alt=""><figcaption></figcaption></figure>

**Note:** Always verify your file format before uploading. Use **"Clear Menu"** or **"Clear Table"** only when existing records must be removed.

## 2. How do I download a template and bulk import Members, Tables, or Customers in Setup Entity?

To import entity records using official Excel/CSV templates:

1. Navigate to **"Setup"** → **"Entity"**.
2. Under **"Entity Type"**, select the target category (**"Members"**, **"Tables"**, or **"Customers"**).
3. Select **"Template"** (or **"Locate Template"**) to download the official import template.
4. Open the template file, enter the required entity details, and save the completed file.
5. Under **"Import File"**, click **"..."** to locate and select your saved file.
6. Select **"Import Data"** to upload the entity information into DinePlan.

<figure><img src="../../.gitbook/assets/image (577).png" alt=""><figcaption></figcaption></figure>

## 3. How do I enable CRM or Pole Setup in BackOffice, and why is a password required?

To activate advanced module features that require administrative security clearance:

* **To enable CRM:** Navigate to **"Setup"** → **"Custom"**, then select **"CRM"**. When prompted, enter the required password and configure or enable the CRM module.

<figure><img src="../../.gitbook/assets/image (576).png" alt=""><figcaption></figcaption></figure>

* **To enable Pole Setup:** Navigate to **"Setup"** → **"Others"**, then select **"POLE SETUP"**. Enter the required password to enable the pole display or assign it to a user profile.

<figure><img src="../../.gitbook/assets/image (575).png" alt=""><figcaption></figcaption></figure>

**Note:** Certain advanced options under **Others** and **Custom** require password authorization before they can be enabled or assigned to a user role.

## 4. How do I create a new service department (such as Take Away or Drive Through) in BackOffice?

To configure separate service departments for distinct operational workflows:

1. Open **BackOffice** and navigate to **"Department"**.
2. Select **"Add Department"** from the **Department List** screen.
3. In the **"Department Name"** field, enter a title (e.g., _Restaurant_, _Take Away_, _Walk Through_, or _Drive Through_).
4. Select the **"Default Ticket Type"** and **"Default Menu"**.
5. Select the **"Ticket Creation Method"**, **"Price Tag"**, and **"Warehouse"**.
6. Enter operational tagging details in **"Group"**, **"Code"**, and **"Tag"**.
7. _(Optional)_ Enable **"NonRevenue"** if the department handles non-revenue activity.
8. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (574).png" alt=""><figcaption></figcaption></figure>

## 5. How do I change the display sequence of service departments using drag and drop?

To customize the order in which departments appear on POS screens:

1. Open **"Department"** in BackOffice.
2. Select **"Sort Departments"**.
3. In the **"Sort Departments"** pop-up window, click and drag the listed departments into your preferred display order.
4. Select **"OK"** to save and apply the new order (or select **"Cancel"** to discard changes).

<figure><img src="../../.gitbook/assets/image (573).png" alt=""><figcaption></figcaption></figure>

## 6. How do I configure a new hardware terminal with printer assignments and opening cash?

To set up a billing counter terminal in BackOffice:

1. Navigate to **"Terminals"** in BackOffice.
2. Select **"Add Terminal"** from the **Terminal List**.
3. Enter the **"Code Name"** and **"Terminal Name"**.
4. Click the dropdowns to select the **"Report Printer"**, **"Transaction Printer"**, and **"Parent Terminal"**.
5. Enter numerical values in **"Opening Cash"** and **"Tolerance"**.
6. Enable operational toggles if required, such as **"Default Terminal"** or **"Collection Terminal"**.
7. Enter the **"TerminalIdentification"** and **"SerialNumber"**.
8. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (572).png" alt=""><figcaption></figcaption></figure>

## 7. How do I add and configure a DineFly waiter app or DineMenu tablet device?

To register mobile ordering apps or customer tablet menus in DinePlan:

1. Open **"Devices"** in BackOffice.
2. Select **"Add Device"**.
3. Click **"Device Type"** and select either **"DineFly"** _(waiter ordering app)_ or **"DineMenu"** _(customer tablet menu)_.
4. Enter the device **"Name"**.
5. Select the assigned **"Terminal"**, **"Menu"**, and **"Department"**.
6. Configure settings under **"General Settings"** and **"Tags"**.
7. Under **"Printer"**, select the appropriate **"Bill Template"** and **"Printer"**.
8. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (571).png" alt=""><figcaption></figcaption></figure>

## 8. How do I configure PAX and Hold functions on a DineFly waiter ordering device?

To enable table guest counts and course timing controls on a waiter's handheld device:

1. Open **"Devices"** and select or edit the target DineFly device.
2. Enable **"PAX"** when the device needs to prompt servers to capture the number of customers seated at a table.
3. Enable **"Hold"** when servers need to hold specific order items for later kitchen preparation (for example, sending starters first while holding main courses until requested).
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (570).png" alt=""><figcaption></figcaption></figure>

## 9. How do I add a new Foreign Currency with an exchange rate and rounding value?

To support secondary payment currencies in your restaurant:

1. Navigate to **"Foreign Currency"** in BackOffice.
2. Select **"Add Foreign Currency"**.
3. Enter the currency title in the **"Name"** field.
4. Enter the symbol in **"Currency Symbol"**.
5. Enter the numerical exchange value in **"Exchange Rate"**.
6. Enter the rounding value in **"Rounding"**.
7. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (569).png" alt=""><figcaption></figcaption></figure>

## 10. How do I update the application logo image and verify the database connection string?

To configure global terminal branding and database connectivity:

1. Open **"Local Settings"** and select **"General"**.
2. Click **"Terminal Name"** to select the active terminal for the current computer.
3. In **"Logo Path"**, enter or browse to select the logo image file used by the application.
4. Verify the application and SQL Server database connection string under **"Connection String"**.
5. Configure display toggles like **"DisplayTaxName"**, **"DisplayItemPriceWithTax"**, **"DisplayItemPrice"**, **"Show Sold Out"**, or **"Order Tag SoldOut"**.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (568).png" alt=""><figcaption></figcaption></figure>

## 11. How do I disable the Multiple Databases setting if it cannot be turned off from the Local Settings UI?

If **"Multiple Databases"** was previously enabled under Local Settings General, the UI prevents turning it off directly.

**Procedure to disable Multiple Databases:**

1. Close the DinePlan application.
2. Locate the program data XML configuration file on the system host.
3. Open the XML file in a text editor.
4. Find the `MultipleDatabases` XML node and update its value from `true` to `false`.
5. Save the XML file.
6. Relaunch DinePlan to verify that multiple database support is disabled.

**Note:** Always exercise care when modifying XML configuration files, as incorrect edits can impact application startup.

## 12. How do I adjust screen scaling, resolution, and bold font settings in Local Settings?

To fix visual display issues or adjust layout sizing for high-resolution monitors:

1. Open **"Local Settings"** and select **"Display"**.
2. Enter the required scaling numerical value in **"Window Scale"**.
3. Select or enter the screen resolution in **"Resolution"**.
4. Enable or disable **"Bold Font"** according to readability requirements.
5. Set the entity refresh time in **"Refresh Entity (Seconds)"**.
6. Specify active ticket status values in **"Ticket Filter Status (Separated by Comma)"**.
7. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (566).png" alt=""><figcaption></figcaption></figure>

## 13. How do I customize which ticket columns are displayed or hidden in the POS list?

To control the column layout of active order tickets on POS terminals:

1. Open **"Local Settings"** → **"Display"**.
2. Select **"Edit Ticket Column Settings"**.
3. In the column settings window, locate the list of available ticket columns.
4. Set columns to **True** if you want them visible on screen, or **False** if you want them hidden.
5. Select **"Save"** to apply the updated column visibility settings.

<figure><img src="../../.gitbook/assets/image (566).png" alt=""><figcaption></figcaption></figure>

## 14. How do I configure IP address, PORT, and connect DinePlan to the Messaging Server?

To establish local network communication and API integration services:

1. Open **"Local Settings"** and select **"Service"**.
2. Enter or select the local service IP in **"IP Address"**.
3. Enter the communication port number in **"PORT"**.
4. Enter server details in **"Messaging Server Name"** and **"Messaging Server Port"**.
5. Enable required integration options (such as **"API Server"**, **"DineCall"**, **"Auto Sync Connect"**, **"eDine"**, **"GloriaFood"**, or **"ExternalOrder"**).
6. Select **"Connect to Message Server"** to initiate the server connection.
7. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (565).png" alt=""><figcaption></figcaption></figure>

## 15. How do I configure local billing actions (Bill Job) for the DineFly waiter ordering app?

To define what document or printing action occurs when a server requests a bill on DineFly:

1. Open **"Local Settings"** and select **"DineFly"**.
2. Enter entity screen rules in **"Fly Entity Screens"**.
3. Click the **"Bill Job"** dropdown menu.
4. Select the required billing action or document required for DineFly processing (options include _Print Ticket_, _Print Invoice_, _Print Kitchen_, _Print Kitchen Display_, _Print Bill_, or Pole options).
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (564).png" alt=""><figcaption></figcaption></figure>

## 16. How do I configure the menu image folder path for the DineMenu tablet application?

To link tablet menus to the folder where dish photos are stored:

1. Open **"Local Settings"** and select **"DineMenu"**.
2. Locate the **"Dine Menu ImagePath"** field.
3. Select **"Browse"** to navigate to and select the folder directory containing your menu images.
4. Verify that the configured path is accessible to the DinePlan network.
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (563).png" alt=""><figcaption></figcaption></figure>

## 17. How do I configure layout columns, rows, and font sizes for the DineQueue customer display?

To customize the visual grid layout of customer-facing order queue screens:

1. Open **"Local Settings"** and select **"DineQueue"**.
2. Enter a descriptor in **"Name"**.
3. Set grid dimensions: enter column width in **"Columns"** and row height in **"Rows"**.
4. Select the display font in **"Font"**.
5. Set typography sizes in **"Header Font Size"** and **"Queue Number Font Size"**.
6. Specify ticket limits in **"Number Of Tickets Per Page"**.
7. _(Optional)_ Configure **"ConnectionString Separate Queue"** and check **"Activate Separate Queue"** if using a dedicated queue database.
8. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (562).png" alt=""><figcaption></figcaption></figure>

## 18. How do I configure auto-refresh intervals, page size, and view modes for the web-based Ticket Queue display?

To control customer-facing web queue displays and ready order notifications:

1. Open **"Local Settings"** and select **"Ticket Queue"**.
2. Enter the refresh frequency in **"Auto Refresh Interval Seconds"**.
3. Enter the display record count in **"PageSize"**.
4. Set display duration for finished orders in **"Last Order Ready Interval Seconds"**.
5. Set **"SortField"** and **"SortDirection"**.
6. Set transition timing in **"Slider Interval Seconds"**.
7. Choose the visual presentation format under **"View Mode"**.
8. Enable **"Order Ready Item View"** if needed.
9. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (561).png" alt=""><figcaption></figcaption></figure>

**Note:** Use **"Reset Ticket Queue"** only when you need to clear or reset the active queue display.

## 19. How do I check system file paths (App Path / User Path) or locate import templates in Setup?

To view application installation paths or find built-in import template files:

1. Open **"Setup"** in BackOffice.
2. Look at the utility action options located along the bottom of the screen.
3. **To find import templates:** Select **"Locate Template"**.
4. **To view application executable paths:** Select **"Display App Path"**.
5. **To view user profile folder paths:** Select **"Display User Path"**.
6. Select **"Close"** when finished to exit the Setup window.

<figure><img src="../../.gitbook/assets/image (560).png" alt=""><figcaption></figcaption></figure>

## 20. How do I safely delete a service department, terminal, device, or foreign currency in BackOffice?

To remove outdated or disconnected infrastructure elements from BackOffice:

1. Open the target management screen (**Department**, **Terminals**, **Devices**, or **Foreign Currency**).
2. Highlight and select the specific record you wish to remove from the list.
3. Select the applicable delete button (**"Delete Department"**, **"Delete Terminal"**, **"Delete Device"**, or **"Delete Foreign Currency"**).
4. Review the system confirmation message asking whether to delete the selected item.
5. Select **"Yes"** to confirm deletion (or select **"No"** to cancel).

<figure><img src="../../.gitbook/assets/image (559).png" alt=""><figcaption></figcaption></figure>
