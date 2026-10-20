# FAQ's

## 1. How do I access the Tickets screen from the DinePlan Dashboard?

To open the Tickets screen and view transaction records generated during restaurant operations:

1. Log in to **"DinePlan"**.
2. From the main **"Dashboard"**, locate and select **"Tickets"**.
3. The **"Tickets"** screen opens, displaying the centralized list of ticket records.

<figure><img src="../.gitbook/assets/image (221).png" alt=""><figcaption></figcaption></figure>

## 2. How do I filter ticket records by a specific date range?

To narrow down the displayed tickets to a particular operational period:

1. Open the **"Tickets"** screen from the Dashboard.
2. Click the **"From"** date field (or click its **Calendar Icon**) and select the starting date.
3. Click the **"To"** date field (or click its **Calendar Icon**) and select the ending date.
4. Select **"Refresh"** to apply the date filter and reload the ticket list.

<figure><img src="../.gitbook/assets/image (222).png" alt=""><figcaption></figcaption></figure>

**Note:** Always select **"Refresh"** after modifying date fields to ensure the displayed records update.

## 3. Why are my new date or ticket type filter selections not updating the ticket list automatically?

The ticket list does not reload automatically when selection controls are changed.

To update the view:

1. Adjust your **"From"** and **"To"** dates or change the **"Ticket Type"** dropdown option.
2. Select **"Refresh"**.
3. The ticket list reloads and updates based on your newly selected criteria.

<figure><img src="../.gitbook/assets/image (223).png" alt=""><figcaption></figcaption></figure>

## 4. How do I view all active tickets that have not yet been closed?

To isolate open tickets that are still active and may require further processing:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"Only Open Tickets"**.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>

## 5. How do I review completed transaction records for a past business day?

To view closed and finalized ticket transactions:

1. Open the **"Tickets"** screen.
2. In the **"From"** and **"To"** fields, set the required date range.
3. Click the **"Ticket Type"** dropdown and select **"Only Closed Tickets"**.
4. Select **"Refresh"**.
5. Review the matching completed records displayed in the ticket list.

<figure><img src="../.gitbook/assets/image (225).png" alt=""><figcaption></figcaption></figure>

## 6. How do I locate a specific ticket when I know its Ticket Number?

To retrieve a single ticket record using its assigned ticket number:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** filter dropdown and select **"Ticket No"** (or type the ticket number directly into the **"Search"** field).
3. Select **"Refresh"** (if using the filter dropdown).
4. Review the ticket matching the specified **T.No** in the list.

<figure><img src="../.gitbook/assets/image (226).png" alt=""><figcaption></figcaption></figure>

## 7. How do I search for tickets that contain specific notes or order remarks?

To find tickets associated with custom notes or additional operational information:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"Ticket Note"**.
4. Select **"Refresh"**.
5. Review the ticket list to locate records containing relevant notes.

<figure><img src="../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

## 8. How do I view tickets associated with credit transactions?

To review ticket records linked to credit transactions:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"Credit"**.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (229).png" alt=""><figcaption></figcaption></figure>

## 9. How do I filter and view invoice-related tickets?

To locate tickets generated as invoice transactions:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"Invoice"**.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (230).png" alt=""><figcaption></figcaption></figure>

## 10. How do I view all tickets generated from a specific POS terminal?

To audit or review transactions processed on a particular POS terminal:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"Terminal"**.
4. Select **"Refresh"** (or enter the terminal name into the **"Search"** box).
5. Review the matching tickets listed under the **Terminal** column.

<figure><img src="../.gitbook/assets/image (231).png" alt=""><figcaption></figcaption></figure>

## 11. How do I filter for Edine transaction tickets?

To display tickets associated with Edine operations:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"Edine Tickets"**.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (232).png" alt=""><figcaption></figcaption></figure>

## 12. How do I locate tickets that are classified as NonRevenue?

To view non-revenue-generating transactions that are handled separately from regular sales:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"NonRevenue"**.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (233).png" alt=""><figcaption></figcaption></figure>

## 13. How do I identify tickets that failed to sync with an external system?

To locate ticket records that have not been synchronized with external integrations:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"ExternalNotSynced"**.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (234).png" alt=""><figcaption></figcaption></figure>

## 14. How do I find pending unsynced tickets and push them for synchronization?

To locate unsynced tickets and manually trigger system synchronization:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu and select **"NotSynced"**.
3. Select **"Refresh"**.
4. Select the required unsynced ticket records from the **Ticket List**.
5. Select **"Push"** to push the selected tickets for syncing.

<figure><img src="../.gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>

**Note:** The **Push** action is specifically designed to send pending non-synchronized records to external/central databases.

## 15. Why is the "Push" button disabled or greyed out on the Tickets screen?

The **Push** button is context-dependent and will only become active under specific conditions:

* The **Push** option is enabled **only** when **NotSynced** (or non-synchronized) tickets are selected.
* If you are viewing standard closed, open, or fully synchronized tickets, the **Push** button remains disabled.

<figure><img src="../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

## 16. How do I filter tickets by PAX (guest count) transactions?

To view tickets associated with PAX-related transactions:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"PAX"**.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (237).png" alt=""><figcaption></figcaption></figure>

## 17. How do I view tickets that are currently placed on hold?

To locate active tickets that have been temporarily put on hold:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu.
3. Select **"Hold"**.
4. Select **"Refresh"**.
5. Review the on-hold tickets that require further staff action.

<figure><img src="../.gitbook/assets/image (219).png" alt=""><figcaption></figcaption></figure>

## 18. How do I search for all tickets linked to a specific Member record?

To isolate transactions associated with a particular member:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu and select **"Member"** (or type the member's name/ID directly into the **"Search"** bar).
3. Select **"Refresh"** (if using the dropdown).
4. Review the matching member tickets displayed under the **Member** column in the list.

## 19. How do I locate tickets associated with a specific dining Table?

To view tickets generated for a particular table:

1. Open the **"Tickets"** screen.
2. Click the **"Ticket Type"** dropdown menu and select **"Table"** (or enter the table number into the **"Search"** field).
3. Select **"Refresh"** (if using the dropdown).
4. Review the results listed under the **Table** column.

<figure><img src="../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

## 20. How do I search for tickets belonging to a particular Customer?

To find transaction records linked to a customer profile:

1. Open the **"Tickets"** screen.
2. Click **"Ticket Type"** and select **"Customer"** (or type customer details into the **"Search"** field).
3. Select **"Refresh"** (if using the dropdown).
4. Review the filtered results displayed under the **Customer** column.

<figure><img src="../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

## 21. How do I reset all ticket filters to view every ticket record in a date range?

To clear specific classifications and view the complete ticket log:

1. Open the **"Tickets"** screen.
2. In the **"Ticket Type"** dropdown, select **"All Tickets"**.
3. Confirm your **"From"** and **"To"** date range.
4. Select **"Refresh"**.

<figure><img src="../.gitbook/assets/image (217).png" alt=""><figcaption></figcaption></figure>

## 22. What information is displayed under the I.No, T.No, and Q.No columns in the Ticket List?

The **Ticket List** table organizes ticket identifiers into three specific header columns:

* **I.No:** Displays the official **Invoice Number** associated with the ticket.
* **T.No:** Displays the unique **Ticket Number**.
* **Q.No:** Displays the assigned **Queue Number** associated with the ticket, where applicable.

<figure><img src="../.gitbook/assets/image (216).png" alt=""><figcaption></figcaption></figure>

## 23. What do the Reference No. and Alternate ID columns display in the Ticket List?

These two columns store secondary reference identifiers:

* **Reference No.:** Displays the specific reference number attached to the transaction ticket.
* **Alternate ID:** Displays an alternate ID number linked to the ticket, where applicable.

<figure><img src="../.gitbook/assets/image (215).png" alt=""><figcaption></figcaption></figure>

## 24. How do I check the exact opening and closing times of a ticket?

To view the exact operational timestamps for an order:

1. Locate the target ticket row in the **Ticket List**.
2. Find the **"Open-Close"** column.
3. Review the timestamps displayed, which record both the opening time and closing time of the ticket.

<figure><img src="../.gitbook/assets/image (214).png" alt=""><figcaption></figcaption></figure>

## 25. What details are shown in the Department, Terminal, Payment, and User Name columns?

These columns provide operational and staff tracking details:

* **Department:** Displays the operational department from which the ticket originated.
* **Terminal:** Displays the exact POS terminal used to generate the ticket.
* **Payment:** Displays the payment method/information applied to the ticket.
* **User Name:** Displays the name of the staff user who created or processed the ticket.

<figure><img src="../.gitbook/assets/image (211).png" alt=""><figcaption></figcaption></figure>

## 26. How do I search for a ticket using customer, table, invoice, or staff keywords?

To quickly find a record without changing dropdown options:

1. Open the **"Tickets"** screen.
2. Click inside the **"Search"** text field.
3. Type any matching keyword (such as **I.No**, **T.No**, **Q.No**, **Member**, **Table**, **Customer**, **Reference No.**, **Alternate ID**, **Department**, **Date**, **Terminal**, **Payment**, or **User Name**).
4. The **Ticket List** updates automatically to display matching records.

<figure><img src="../.gitbook/assets/image (210).png" alt=""><figcaption></figcaption></figure>

## 27. How do I navigate between pages when there are multiple pages of ticket records?

When a search or filter returns more records than fit on a single screen:

1. Look at the navigation controls on the **Tickets** screen.
2. Select **"Next"** to move forward to the next page/set of ticket records.
3. Select **"Previous"** to move backward to the preceding set of ticket records.

<figure><img src="../.gitbook/assets/image (209).png" alt=""><figcaption></figcaption></figure>

## 28. How do I export the displayed ticket list to an Excel file for reporting?

To export transaction data for administrative reporting or record-keeping:

1. On the **"Tickets"** screen, set your desired **"From"** / **"To"** dates and **"Ticket Type"** filters.
2. Select **"Refresh"** to generate the required list.
3. Select **"Excel"** from the top screen actions.
4. The system exports all ticket information currently displayed in the ticket list into an Excel file.

<figure><img src="../.gitbook/assets/image (208).png" alt=""><figcaption></figcaption></figure>

**Note:** The **Excel** function exports only the records currently loaded in the active result list.

## 29. How do I manually retrieve ticket information from the system using Pull?

To execute a manual data retrieval for ticket records:

1. Open the **"Tickets"** screen.
2. Select or highlight the required ticket record, where applicable.
3. Select **"Pull"**.
4. The system retrieves the ticket information from the backend/connected system where applicable.

<figure><img src="../.gitbook/assets/image (207).png" alt=""><figcaption></figcaption></figure>

## 30. How do I pull online orders from connected gateways like Foodpanda into DinePlan?

To retrieve incoming online orders from third-party delivery platforms directly into the POS:

1. Open the **"Tickets"** screen from the Dashboard.
2. Select **"Call"** from the action menu.
3. The available online order (e.g., an order received through Foodpanda) is retrieved from the connected gateway and instantly added to the ticket list for immediate staff processing.

<figure><img src="../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

## 31. How do I check the total number of tickets in my current filtered view?

To verify how many ticket records match your current filter or search criteria:

1. Filter or search the ticket list as required.
2. Look at the bottom bar of the **Tickets** screen.
3. Locate **"Tickets Count"**, which displays the total number of tickets contained in the current result set.

<figure><img src="../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

## 32. How do I view the combined financial total for all currently displayed tickets?

To see the total monetary value of all filtered tickets combined:

1. Apply your desired date range, ticket type, or search term.
2. Select **"Refresh"**.
3. Look at the bottom right summary area of the screen.
4. Read the **"Total"** field, which displays the calculated sum of all ticket amounts in the current list.

<figure><img src="../.gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>

## 33. How do I close the Tickets screen and return to the main dashboard?

To exit the Tickets management interface:

1. Locate the **"Close"** button on the screen action bar.
2. Select **"Close"**.
3. The Tickets screen closes, returning you to the previous screen or Dashboard.

<figure><img src="../.gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure>

## 34. What search criteria fields can I type into the Search bar to find a ticket?

The **Search** bar supports multi-field lookup. You can enter values corresponding to any of the following fields:

* **Member**
* **Table**
* **Customer**
* **Department**
* **Date**
* **Terminal**
* **Payment**
* **User Name**

<figure><img src="../.gitbook/assets/image (201).png" alt=""><figcaption></figcaption></figure>

## 35. Why does my exported Excel file only contain a subset of my restaurant's total tickets?

The **Excel** export tool is strictly tied to the active screen view:

* **Reason:** The **Excel** button exports **only** the ticket information currently displayed in the ticket list based on your active filters.
* **Solution:** To export a complete set of records, ensure you select **"All Tickets"** under **Ticket Type**, set your full date range in **"From"** / **"To"**, select **"Refresh"**, and then select **"Excel"**.

<figure><img src="../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

