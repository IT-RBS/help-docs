# Screen Commands

## **Order Processing** <a href="#order-processing" id="order-processing"></a>

### **Pre Order** <a href="#pre-order" id="pre-order"></a>

The Pre Order command allows the current Workday to be closed even when one or more customer tickets remain open. This option is useful when orders need to remain active beyond the current business day, such as advance orders or orders that will be completed during the next operational period.

When Pre Order is enabled, the system allows the Workday to be closed without requiring all open tickets to be settled. This provides operational flexibility while ensuring that pending tickets remain available for future processing.

<figure><img src="../.gitbook/assets/att_45_for_3349348540.png" alt=""><figcaption></figcaption></figure>

### **Non-Pre Order** <a href="#non-pre-order" id="non-pre-order"></a>

The Non-Pre Order command returns the system to its default order processing behavior. In this mode, all customer tickets must be completed, settled, or closed before the Workday can be ended.

This option ensures that all transactions for the current business day are finalized before daily operations are closed, reducing the possibility of leaving unfinished orders in the system.

<figure><img src="../.gitbook/assets/att_46_for_3349348540.png" alt=""><figcaption></figcaption></figure>

## **Training** <a href="#training" id="training"></a>

### **Enable Training** <a href="#enable-training" id="enable-training"></a>

The "Enable Training" command places the POS terminal in Training Mode, allowing users to practice restaurant operations without affecting live business data.

While Training Mode is enabled, transactions performed on the terminal are treated as practice transactions and are not synchronized with the server. Training Mode can be used for employee training, demonstrations, and practice before handling live customer transactions.

When Training Mode is enabled, the "Training" status is displayed on the DinePlan dashboard. The system also automatically redirects the user to the login page.

#### **Procedure** <a href="#procedure.4" id="procedure.4"></a>

1. Open the "Workday" module.

<figure><img src="../.gitbook/assets/att_47_for_3349348540.png" alt=""><figcaption></figcaption></figure>

2. Click "Enable Training".

<figure><img src="../.gitbook/assets/att_48_for_3349348540.png" alt=""><figcaption></figcaption></figure>

3. A confirmation message asking "Do you want Training Mode operation?" is displayed.

<figure><img src="../.gitbook/assets/att_49_for_3349348540.png" alt=""><figcaption></figcaption></figure>

4. Click "Yes" to enable Training Mode.

<figure><img src="../.gitbook/assets/att_50_for_3349348540.png" alt=""><figcaption></figcaption></figure>

5. The system enables Training Mode and automatically redirects you to the login page.
6. Log in to continue using DinePlan in Training Mode.
7. Verify that "Training" is displayed on the dashboard to confirm that Training Mode is active.

<figure><img src="../.gitbook/assets/att_51_for_3349348540.png" alt=""><figcaption></figcaption></figure>

#### **Result**

The POS terminal operates in Training Mode. Transactions performed while Training Mode is active are treated as practice transactions and are not synchronized with the server.

### **Disable Training** <a href="#disable-training" id="disable-training"></a>

The "Disable Training" command exits Training Mode and returns the POS terminal to normal operating mode.

After Training Mode is disabled, new transactions are processed as live business transactions and synchronized with the server. Disable Training Mode before resuming regular restaurant operations.

#### **Procedure** <a href="#procedure.5" id="procedure.5"></a>

1. Open the "Workday" module.

<figure><img src="../.gitbook/assets/att_52_for_3349348540.png" alt=""><figcaption></figcaption></figure>

2. Click "Disable Training".

<figure><img src="../.gitbook/assets/att_53_for_3349348540.png" alt=""><figcaption></figcaption></figure>

3. The system disables Training Mode and automatically redirects you to the login page.
4. Log in to continue using DinePlan in normal operating mode.

#### **Result**

Training Mode is disabled, and the POS terminal resumes normal operations. New transactions are recorded as live business transactions and synchronized with the server.

## **Data Synchronization** <a href="#data-synchronization" id="data-synchronization"></a>

### **Push** <a href="#push" id="push"></a>

The Push command manually synchronizes pending transaction data from the POS terminal to Dine Connect.

<figure><img src="../.gitbook/assets/att_54_for_3349348540.png" alt=""><figcaption></figcaption></figure>

Normally, transaction data is synchronized automatically after each completed order or payment. If network connectivity is interrupted, some transactions may remain pending. Use **Push** after connectivity is restored to manually synchronize any unsent data with Dine Connect.

### **Pull** <a href="#pull" id="pull"></a>

The Pull command retrieves the latest operational data and configuration updates from Dine Connect.

Use this command after changes have been made in Dine Connect, such as menu updates, pricing changes, promotional offers, or configuration changes. Pulling the latest data ensures that the POS terminal is working with the most recent information.

<figure><img src="../.gitbook/assets/att_55_for_3349348540.png" alt=""><figcaption></figcaption></figure>

## **Screen Actions** <a href="#screen-actions" id="screen-actions"></a>

### **Refresh** <a href="#refresh" id="refresh"></a>

The Refresh command reloads the current Workday screen and updates the displayed information without changing the selected business date or applied filters.

Use this command to display the latest Workday or Work Shift information after completing an operation, such as starting or ending a Workday or Work Shift.

<figure><img src="../.gitbook/assets/att_56_for_3349348540.png" alt=""><figcaption></figcaption></figure>

### **Reset** <a href="#reset" id="reset"></a>

The Reset command restores the selected business date to the current business date and refreshes the Workday information displayed on the screen.

If historical Workday records have been viewed using different date filters, selecting Reset quickly returns the screen to the current business day's information.

<figure><img src="../.gitbook/assets/att_57_for_3349348540.png" alt=""><figcaption></figcaption></figure>

### **Reports** <a href="#reports" id="reports"></a>

#### **Print**

The "Print" command allows you to print the available Workday or Work Shift information. This can be used when a physical copy of the displayed operational information is required for review or record-keeping.

<figure><img src="../.gitbook/assets/att_58_for_3349348540.png" alt=""><figcaption></figcaption></figure>

#### **Preview**

The "Preview" command allows you to preview the selected Workday or Work Shift information before printing it. This helps you review the information on screen and confirm that the required details are available before generating a printed copy.

#### **Procedure** <a href="#procedure.6" id="procedure.6"></a>

1. Select the required Workday or Work Shift record.

<figure><img src="../.gitbook/assets/att_59_for_3349348540.png" alt=""><figcaption></figcaption></figure>

2. Click "Preview".

<figure><img src="../.gitbook/assets/att_60_for_3349348540.png" alt=""><figcaption></figcaption></figure>

3. The system displays a preview of the selected information.

<figure><img src="../.gitbook/assets/att_61_for_3349348540.png" alt=""><figcaption></figcaption></figure>

4. Review the displayed details.
