# FAQ's

## 1. How do I open the Workday module in DinePlan?

To open the **Workday** screen and manage daily restaurant operations:

1. Log in to **"DinePlan"** using your credentials.
2. Navigate to the **"Home"** screen.
3. Click **"Workday"**.

<figure><img src="../.gitbook/assets/image (364).png" alt=""><figcaption></figcaption></figure>

**Result:** The **Workday** screen opens, displaying the current Workday status, date range filters, and available administrative actions.

## 2. Why are the POS and Tickets modules unavailable when I log in?

The **POS** and **Tickets** modules remain unavailable until a **Workday** has been started for the business date and an active **Work Shift** has been initiated on your payment terminal.

To resolve this and begin accepting orders:

1. Open the **"Workday"** module from the **Home** screen.
2. Click **"Start Workday"** to initialize the business day for the restaurant.
3. Open **"Work Shift"** and click **"Start Work Shift"** on your terminal.

<figure><img src="../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

**Note:** Once both the Workday and terminal Work Shift are active, the **POS** and **Tickets** modules will become accessible for processing orders.

## 3. How do I start the Workday for the restaurant?

To initialize the business day so staff can begin operations:

1. Open the **"Workday"** module from the **Home** screen.
2. Review the current Workday status.
3. Click **"Start Workday"**.
4. A confirmation message will appear displaying Workday details. Review the displayed info:
   * **Start User:** Displays the name of the user who started the Workday.
   * **Start Time:** Displays the date and time when the Workday was started.
   * **Business Date:** Displays the business date associated with the Workday.
5. Click **"OK"** to continue.

<figure><img src="../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

**Note:** Ensure no active Workday already exists for the selected business date before clicking **Start Workday**.

## 4. Can I start the Workday from any POS terminal?

Yes. A restaurant can have multiple POS terminals, and the **Workday** can be started from any available terminal.

However, starting the Workday enables operations for the restaurant as a whole; each individual payment terminal must still have its own active **Work Shift** started before it can process customer orders or payments.

## 5. What details are displayed in the confirmation window when a Workday is started?

When you click **Start Workday**, the system displays a confirmation window containing:

* **Start User:** The name of the logged-in user who initiated the Workday.
* **Start Time:** The exact date and timestamp when the Workday was activated.
* **Business Date:** The operational business date assigned to the Workday.

<figure><img src="../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

After reviewing these details, click **"OK"** to confirm and activate the business day.

## 6. How do I start a Work Shift on a POS terminal?

To activate a specific payment terminal for order processing and billing:

1. Open the **"Workday"** module.
2. Click **"Work Shift"** to open the **Work Shift** screen.
3. Click **"Start Work Shift"**.
4. On the **"Opening Cash"** screen, enter the opening cash amount placed in the cash drawer.
5. Verify that the entered amount matches the cash in the drawer.
6. Click **"Start Work Shift"** to activate the shift.
7. Review the **"Work Shift Started"** confirmation details and click **"OK"**.

<figure><img src="../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

## 7. Do I need to start a separate Work Shift on every payment terminal in the restaurant?

Yes. Every payment terminal that accepts customer payments must have its own active **Work Shift**.

Starting a **Work Shift** on one terminal does not automatically start shifts on other terminals in the restaurant. Each cashier or terminal operator must independently start a Work Shift on their designated terminal.

## 8. How do I open the cash drawer to verify opening cash when starting a Work Shift?

When entering your opening cash amount on the **Opening Cash** screen:

1. Click the **"Open Till"** button on the screen.
2. The cash drawer opens automatically.
3. Count or verify the cash placed in the drawer against the amount entered in the system.
4. Click **"Start Work Shift"** to proceed.

<figure><img src="../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

## 9. What details are shown in the confirmation message after starting a Work Shift?

Upon starting a Work Shift, the system displays the **Work Shift Started** confirmation popup containing:

* **Start User:** Name of the user who started the shift.
* **Start Time:** Time at which the shift was initiated.
* **Cash:** Recorded opening cash amount.
* **Business Date:** Current business date associated with the shift.
* **Shift Number:** System-assigned identification number for the shift.

<figure><img src="../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

Click **"OK"** to close the message and proceed to the **POS** module.

## 10. How do I end an active Work Shift at the end of a shift?

To close an active Work Shift on a terminal:

1. Open the **"Workday"** module and click **"Work Shift"**.
2. Click **"End Work Shift"**.
3. When prompted _"Do you want to end Work Shift?"_, click **"Yes"**.
4. On the **"Cash Denomination"** / **"Shift Closing"** screen, enter the closing amounts collected for each payment method (e.g., **Cash**, **Card**, **Visa**, **Master**, **Nets**, **Swiggy**, **Zomato**, **Google Pay**).
5. Click **"End WorkShift"**.
6. When prompted _"Do you want End WorkShift operation?"_, click **"Yes"** to confirm.
7. Click **"OK"** on the final confirmation window.

Refer this link - [End Work Shift](end-work-shift.md)

<figure><img src="../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

## 11. How do I record cash and electronic payment closing amounts when ending a Work Shift?

When closing a shift, the **Shift Closing** / **Cash Denomination** screen opens to capture shift totals:

1. Use the **Numeric Keypad** or direct input fields to enter actual collected amounts for each payment line:
   * **Cash:** Total cash collected in the drawer.
   * **Card / Visa / Master / Nets:** Total non-cash card settlements.
   * **Swiggy / Zomato / Google Pay:** Total amounts received via digital/delivery platforms.
2. Verify that all entered values match your physical cash count and digital settlement receipts.
3. Click **"End WorkShift"** to save closing figures.

<figure><img src="../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

## 12. How do I open the cash drawer to count collected cash while closing a Work Shift?

To inspect or count the physical drawer contents during shift closure:

1. On the **Shift Closing** screen, click **"Open Till"**.
2. The cash drawer opens.
3. Count the physical cash collected during the shift.
4. Enter the verified total into the **Cash** field and complete the shift ending procedure.

<figure><img src="../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

## 13. How do I reopen a previously closed Work Shift?

If a closed Work Shift needs to be reopened for corrections:

1. Navigate to **"Workday"** → **"Work Shift"**.
2. Select the required work shift record from the **Work Shift History** list.
3. Click **"Reset Work Shift"**.

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

**Result:** The selected work shift is reopened, allowing authorized users to make necessary adjustments before ending it again.

## 14. How do I end the Workday at the end of the business day?

To officially close the restaurant's business day:

1. Ensure all active **Work Shifts** on all payment terminals have been ended.
2. Open the **"Workday"** module.
3. Click **"End Workday"**.
4. When prompted _"Do you want to end Work Day?"_, click **"Yes"**.
5. When asked _"Do you want to print all information?"_, click **"Yes"** to print summary reports or **"No"** to skip printing.
6. Click **"OK"** when the _"Work Day ends."_ message appears.

<figure><img src="../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

## 15. What should I do if DinePlan displays an open ticket validation message when ending the Workday?

If open customer tickets exist when you click **End Workday**, DinePlan displays a validation message and prevents the business day from closing.

To resolve this issue, perform one of the following actions:

* **Option A (Standard Closure):** Access the **POS/Tickets** module, settle, cancel, or close all open customer tickets, and then attempt to click **End Workday** again.
* **Option B (Advance Orders):** If open tickets represent legitimate advance or overnight orders, click **"Pre Order"** on the Workday screen to enable Pre Order mode, then proceed with **End Workday**.

Refer to this link - [End Workday](end-workday.md)

## 16. How do I allow the Workday to close when customer tickets are still open?

To close the Workday while keeping specific orders active for the next business period (such as catering or advance orders):

1. Open the **"Workday"** module.
2. Click **"Pre Order"**.
3. Proceed to click **"End Workday"**.

<figure><img src="../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

**Result:** Pre Order mode allows the Workday to end successfully without requiring pending tickets to be settled immediately; eligible open tickets remain available in the next business period.

## 17. How do I restore normal order processing so all tickets must be closed before ending the Workday?

To turn off Pre Order mode and enforce strict ticket closure:

1. Open the **"Workday"** module.
2. Click **"Non-Pre Order"**.

<figure><img src="../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

**Result:** The system returns to default order processing behavior, requiring all customer tickets to be fully completed or settled before the Workday can be closed.

## 18. How do I enable Training Mode so new staff can practice using the POS terminal?

To place a terminal into Training Mode for practice or employee onboarding:

1. Open the **"Workday"** module.
2. Click **"Enable Training"**.
3. When prompted _"Do you want Training Mode operation?"_, click **"Yes"**.
4. The system enables Training Mode and automatically redirects you to the login page.
5. Log back in to DinePlan.

<figure><img src="../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

**Result:** The terminal operates in Training Mode. Practice transactions will not affect live sales figures or synchronize with the server.

## 19. How do I confirm if Training Mode is currently active on my terminal?

You can verify whether Training Mode is active by checking the **DinePlan Dashboard**:

* When active, **"Training"** is explicitly displayed as a status label on the dashboard.
* Any transactions entered while this status is visible are treated purely as practice data.

<figure><img src="../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

## 20. How do I disable Training Mode and resume live operations?

To exit Training Mode and return to live sales processing:

1. Open the **"Workday"** module.
2. Click **"Disable Training"**.
3. The system disables Training Mode and automatically redirects you to the login page.
4. Log back in with your credentials.

Refer this link - [Disable Training](screen-commands.md#disable-training)

**Result:** Training Mode is deactivated, and all subsequent orders and payments will be processed as live business transactions.

## 21. How do I manually synchronize pending sales data to Dine Connect after a network reconnection?

If internet connectivity was lost during service, offline transactions may remain pending on the local terminal. To push them manually once network connectivity is restored:

1. Open the **"Workday"** module.
2. Click **"Push"**.

<figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

**Result:** The system manually synchronizes all pending offline transaction data from the local terminal to **Dine Connect**.

## 22. How do I pull the latest menu updates and price changes from Dine Connect?

When administrators update menus, prices, or promotional offers in Dine Connect:

1. Open the **"Workday"** module.
2. Click **"Pull"**.

<figure><img src="../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

**Result:** The POS terminal retrieves the latest master configurations and operational updates from **Dine Connect**, ensuring menu items and prices are up to date.

## 23. How do I refresh the Workday screen to see updated information?

To update on-screen status info without altering applied filters or date parameters:

1. Open the **"Workday"** screen.
2. Click **"Refresh"**.

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

**Result:** The screen reloads and updates all status records and shift indicators.

## 24. How do I reset date filter selections back to the current business date?

If you have been reviewing historical records using custom date ranges:

1. Click **"Reset"** on the Workday screen.

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

**Result:** The **Business Date (From)** and **Business Date (To)** fields are automatically restored to the current business date, and the screen reloads today's records.

## 25. How do I preview Workday or Work Shift details on screen before printing?

To inspect report details prior to generating a physical printout:

1. Open **"Workday"** or **"Work Shift"**.
2. Select the specific Workday or Work Shift record from the history list.
3. Click **"Preview"**.

<figure><img src="../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

**Result:** The system renders a preview window showing all operational details for review before printing.

## 26. How do I print Workday or Work Shift information?

To print a physical copy of current or historical operational summaries:

1. Select the required Workday or Work Shift record from the screen list.
2. Click **"Print"**.

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

**Result:** The selected Workday or Work Shift summary report is sent to the printer for auditing and record-keeping.

## 27. How do I view historical Workday records for a specific date range?

To query previous business day records:

1. Open the **"Workday"** module.
2. Set the starting date in **"Business Date (From)"**.
3. Set the ending date in **"Business Date (To)"**.
4. Review matching records listed under **Workday History**.

<figure><img src="../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

## 28. How do I filter historical Work Shift records by date?

To view closed shift records for specific dates:

1. Open **"Workday"** → **"Work Shift"**.
2. Select the target start date in **"Business Date (From)"**.
3. Select the target end date in **"Business Date (To)"**.
4. Review the records displayed in the **Work Shift History** table.

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

**Note:** Click **"Reset"** at any time to clear custom date filters and return to default work shift records.

## 29. What information is displayed in the Workday Information Panel?

The **Workday Information Panel** located on the Workday screen displays:

* **Current Workday Date:** The active operational business date.
* **Start Time:** The exact time the Workday was opened.
* **Total Duration:** The total elapsed operating time for the active business day.

<figure><img src="../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

## 30. What information is tracked in the Work Shift History table?

The **Work Shift History** table provides full accountability for every terminal shift by logging:

* **Terminal:** The specific POS terminal name where the shift was conducted.
* **Start User & End User:** Names of staff members who opened and closed the shift.
* **Start Time & End Time:** Precise timestamps for shift start and conclusion.
* **Cash:** The recorded opening cash value.

<figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

## 31. What should I check if I cannot start a new Work Shift?

If clicking **Start Work Shift** fails, check the following common causes:

1. **Workday Not Started:** Verify that the main **Workday** has been started first. You cannot start a Work Shift while the Workday is inactive.
2. **Active Shift Exists:** Check if a Work Shift is already currently active on that specific terminal.

## 32. What should I check if the system will not let me end an active Work Shift?

If you are unable to close an active Work Shift, verify that you have entered closing amounts for all applicable payment fields on the **Shift Closing** screen. The system requires payment inputs (e.g., Cash, Card) to be completed before allowing shift closure.

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

## 33. What should I check if I am unable to end the Workday?

If the **End Workday** operation fails or is blocked, check the following dependencies:

1. **Active Work Shifts:** Ensure all active Work Shifts across all payment terminals have been officially ended.
2. **Unresolved Open Tickets:** Check if any customer tickets remain open in the POS/Tickets system. Either close/settle all open tickets, or enable **Pre Order** mode if orders must carry over into the next business period.

Refer to this link - [End work day](end-work-shift.md#procedure.2)

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

## 34. What should I do if configuration changes made in Dine Connect are not showing on the POS?

If newly updated menus, prices, or settings from Dine Connect do not appear on your POS screen:

1. Open the **"Workday"** module.
2. Click **"Pull"** to manually pull and apply the latest master data configuration from Dine Connect.

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

## 35. Why are transactions performed on a POS terminal missing from sales reports?

If transactions completed on a terminal do not appear in sales or financial reports, check if the terminal was accidentally operated in **Training Mode**:

* Practice transactions conducted while **Training Mode** is enabled are intentionally isolated and not recorded in live sales reports or synchronized with the server.
* To fix this for future sales, open **"Workday"**, click **"Disable Training"**, and resume normal live billing operations.

Refer to this link - [Disable Training](screen-commands.md#disable-training)

<figure><img src="../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

