# FAQ's

## 1. How do I create a new order State in DinePlan BackOffice?

To create a new order state to represent order progress or status in the system:

1. Open **BackOffice** and navigate to the **State List**.
2. Select **"Add State"**.
3. In the **Name** field, enter the required name for the state _(Required)_.
4. Configure optional display settings:
   * **Group Code:** Assign a group code to the state.
   * **State Type:** Select the appropriate state classification.
   * **Color:** Assign a display color for the state button.
   * **Display Format:** Specify the display formatting structure.
5. Configure report and ticket display toggles as needed (**Show on End of Day Report**, **Show on Product Report**, **Show on Ticket**).
6. Select **"Save"** to store the new state.

<figure><img src="../../.gitbook/assets/image (434).png" alt=""><figcaption></figcaption></figure>

**Note:** The **Name** field is required when creating a state.

## 2. How do I configure an order State to appear on tickets or reports?

To control where an order state is displayed across reports and receipts:

1. Open **BackOffice** → **State List**.
2. Select **"Add State"** (or select an existing state and click **"Edit State"**).
3. Under the configuration options, locate the report and display checkboxes:
   * Enable **Show on End of Day Report** to include the state on end-of-day summary reports.
   * Enable **Show on Product Report** to feature the state on product performance reports.
   * Enable **Show on Ticket** to print or display the state directly on order tickets.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (435).png" alt=""><figcaption></figcaption></figure>

## 3. How do I edit the configuration of an existing State?

To modify the name, color, or reporting settings of an existing order state:

1. Navigate to the **State List** in BackOffice.
2. Select the state you want to modify from the list.
3. Select **"Edit State"**.
4. Update the **Name**, **Group Code**, **State Type**, **Color**, **Display Format**, or report toggles as required.
5. Select **"Save"** to apply your changes.

<figure><img src="../../.gitbook/assets/image (436).png" alt=""><figcaption></figcaption></figure>

## 4. How do I reorder order States in the State List?

To customize the display sequence of order states:

1. Open the **State List** screen.
2. Select **"Change Sort Order"**.
3. In the sort-order window, arrange the states into your preferred order.
4. Select **"OK"** to apply and save the new sequence.

<figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure>

**Note:** If you do not want to apply your changes, select **"CANCEL"** to exit without saving the new order.

## 5. How do I delete an order State that is no longer needed?

To permanently remove an unneeded state from the system:

1. Open the **State List**.
2. Select the state you want to remove.
3. Select **"Delete State"**.
4. A system confirmation message will appear on screen.
5. Select **"Yes"** to delete the state, or select **"No"** to cancel the operation.

<figure><img src="../../.gitbook/assets/image (438).png" alt=""><figcaption></figcaption></figure>

**Note:** Review the selected state carefully before deleting, as deletion requires explicit confirmation.

## 6. How do I search for a specific State in BackOffice?

To locate a state quickly when managing a long list:

1. Open the **State List** screen.
2. Click inside the **Search** input bar above the list.
3. Type the state name or keyword.
4. The list filters automatically to display matching states.

<figure><img src="../../.gitbook/assets/image (441).png" alt=""><figcaption></figcaption></figure>

## 7. How do I create a new automated Action in BackOffice?

To configure a new system action:

1. Open BackOffice and navigate to the **Action List**.
2. Select **"Add Action"**.
3. In the **Action Name** field, enter a descriptive label for the action _(Required)_.
4. Click the **Action Type** dropdown list and select the appropriate action category.
5. Configure any available fields in the **Parameters** section based on the chosen action type.
6. Select **"Save"** to add the action to the system.

<figure><img src="../../.gitbook/assets/image (442).png" alt=""><figcaption></figcaption></figure>

**Note:** **Action Name** is required when adding a new action.

## 8. How do I configure Parameters for an Action?

Parameters define the specific variables executed by an action:

1. Open **Action List** and click **"Add Action"** (or select an existing action and click **"Edit Action"**).
2. Choose your desired **Action Type**.
3. Locate the **Parameters** section below the Action Type dropdown.
4. Enter or select the required parameter values applicable to that action type.
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (445).png" alt=""><figcaption></figcaption></figure>

## 9. How do I edit or update an existing Action?

To modify the name, type, or parameter values of a saved action:

1. Open the **Action List**.
2. Select the target action from the list.
3. Select **"Edit Action"**.
4. Update the **Action Name**, **Action Type**, or **Parameters** as needed.
5. Select **"Save"** to update the record.

<figure><img src="../../.gitbook/assets/image (443).png" alt=""><figcaption></figcaption></figure>

## 10. How do I change the display and execution sequence of Actions?

To rearrange the order of actions in BackOffice:

1. Open the **Action List**.
2. Select **"Sort Actions"**.
3. In the **Sort Actions** window, drag and drop the actions to arrange them in the required order.
4. Select **"OK"** to apply the new order.

<figure><img src="../../.gitbook/assets/image (446).png" alt=""><figcaption></figcaption></figure>

**Note:** Select **"CANCEL"** in the sorting window if you want to close without applying the new order.

## 11. How do I delete an Action from the Action List?

To remove an action from the system:

1. Open the **Action List**.
2. Select the action you want to remove.
3. Select **"Delete Action"**.
4. When the confirmation window appears, select **"Yes"** to confirm deletion (or **"No"** to cancel).

<figure><img src="../../.gitbook/assets/image (447).png" alt=""><figcaption></figcaption></figure>

## 12. How do I create a new Automation Rule?

To set up an automated rule triggered by system events:

1. Open BackOffice and go to the **Rule List**.
2. Select **"Add Rule"**.
3. Enter a descriptive name in the **Rule Name** field _(Required)_.
4. Click **Event Name** and select the system event that triggers the rule.
5. Configure optional conditions under **Custom Constraint List**.
6. Under **Actions: Select Actions**, select the actions to execute when the rule runs.
7. Open **Mappings** to assign operational parameters.
8. Select **"Save"** to create the rule.

<figure><img src="../../.gitbook/assets/image (448).png" alt=""><figcaption></figcaption></figure>

**Note:** A **Rule Name** must be entered before saving a rule. Rules in the **Rule List** are grouped according to their associated events.

## 13. How do I add Custom Constraints to an Automation Rule?

To enforce specific execution criteria for a rule:

1. Open **Rule List** and select **"Add Rule"** (or **"Edit Rule"**).
2. Locate the **Custom Constraint List** section.
3. Select **"Add Custom Constraint"**.
4. Define the condition logic.
5. In the **Execute rule if** field, specify whether the rule executes when the defined constraint matches.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (450).png" alt=""><figcaption></figcaption></figure>

## 14. How do I map an Automation Rule to specific Terminals, User Roles, Departments, or Ticket Types?

To restrict an automation rule to specific operational environments:

1. On the rule setup screen, select **Mappings**.
2. Define the applicable mapping parameters:
   * **Terminal:** Select the terminal where the rule applies.
   * **User Role:** Select the user role required to trigger the rule.
   * **Department:** Select the target department.
   * **Ticket Type:** Select the applicable ticket type.
3. Click to add multiple mapping rows if needed.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (451).png" alt=""><figcaption></figcaption></figure>

## 15. How do I edit an existing Automation Rule?

To modify rule constraints, events, or actions:

1. Open the **Rule List**.
2. Select the target rule from the list.
3. Select **"Edit Rule"**.
4. Update the **Rule Name**, **Event Name**, **Custom Constraint List**, **Actions**, or **Mappings**.
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (448).png" alt=""><figcaption></figcaption></figure>

## 16. How do I reorder Automation Rules in the Rule List?

To customize rule execution hierarchy and display order:

1. Open the **Rule List**.
2. Select **"Sort Rules"**.
3. In the **Sort Rules** window, drag the rules into your desired order.
4. Select **"OK"** to save the updated order.

<figure><img src="../../.gitbook/assets/image (453).png" alt=""><figcaption></figcaption></figure>

## 17. How do I delete an Automation Rule from the system?

To remove an automation rule:

1. Open the **Rule List**.
2. Highlight the rule you want to remove.
3. Select **"Delete Rule"**.
4. On the confirmation popup, select **"Yes"** to confirm deletion (or **"No"** to cancel).

<figure><img src="../../.gitbook/assets/image (454).png" alt=""><figcaption></figcaption></figure>

## 18. How do I set up a time-based Trigger in BackOffice?

To create a trigger that runs automated processes at scheduled times:

1. Open BackOffice and go to the **Trigger List**.
2. Select **"Add Trigger"**.
3. Enter a label in the **Trigger Name** field _(Required)_.
4. Build the time-based condition in the **Expression** area using the **Common Settings** fields:
   * **Second**, **Minute**, **Hour**, **Day**, **Month**, **Weekday**.
5. Select **"Save"** to store the trigger.

<figure><img src="../../.gitbook/assets/image (455).png" alt=""><figcaption></figcaption></figure>

**Note:** Entering a **Trigger Name** is required when creating a trigger.

## 19. How do I use Common Settings to configure time expressions for a Trigger?

To set specific time intervals for scheduled triggers:

1. Open the Trigger setup window (**Add Trigger** or **Edit Trigger**).
2. Under **Common Settings**, enter specific numerical or cron values into the time fields:
   * **Second:** Set the second value.
   * **Minute:** Set the minute value.
   * **Hour:** Set the hour value.
   * **Day:** Set the day of the month.
   * **Month:** Set the month value.
   * **Weekday:** Set the day of the week.
3. Verify that the generated text populates correctly in the **Expression** field.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (456).png" alt=""><figcaption></figcaption></figure>

## 20. How do I test a Trigger expression before saving it?

To verify that your scheduled time expression is valid before activating it:

1. On the Trigger configuration screen, enter your time parameters under **Common Settings**.
2. Select the **"Test"** button on the screen.
3. Review the test results to ensure the time expression functions as intended.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (457).png" alt=""><figcaption></figcaption></figure>

## 21. How do I edit or modify an existing Trigger?

To adjust time parameters or rename a trigger:

1. Open the **Trigger List**.
2. Select the trigger from the list.
3. Select **"Edit Trigger"**.
4. Modify the **Trigger Name** or **Expression** settings.
5. Select **"Save"** to keep the changes.

<figure><img src="../../.gitbook/assets/image (458).png" alt=""><figcaption></figcaption></figure>

## 22. How do I delete or change the sort order of Triggers?

To manage existing triggers:

* **To Delete:** Select the trigger from the **Trigger List**, click **"Delete Trigger"**, and confirm the prompt.
* **To Change Sort Order:** Select **"Change Sort Order"**, adjust the order of the listed triggers as required, and save/confirm the updated order.
* **To Search:** Type search keywords into the **Search** field above the list.

<figure><img src="../../.gitbook/assets/image (459).png" alt=""><figcaption></figcaption></figure>

## 23. How do I create and save a new Script in BackOffice?

To create a custom system script:

1. Open the **Script List** in BackOffice.
2. Select **"Add Script"**.
3. Enter the script name in the **Name** field _(Required)_.
4. Enter the handler routines in **Handler**.
5. Enter the code content in the **Script** text box.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (460).png" alt=""><figcaption></figcaption></figure>

## 24. What validation error occurs if I try to save a Script without a Name?

The **Name** field is mandatory when saving a script. If you leave **Name** blank and attempt to select **"Save"**, the system will block creation and display the error message:\
`"Name" should not be empty`

## 25. How do I edit, reorder, or delete existing Scripts?

To maintain your script library:

* **To Edit:** Select the script from the **Script List**, click **"Edit Script"**, modify **Name**, **Handler**, or **Script** content, and click **"Save"**.
* **To Delete:** Select the script, click **"Delete Script"**, and select **"Yes"** on the confirmation popup (or **"No"** to cancel).
* **To Reorder:** Click **"Change Sort Order"**, adjust the sequence, and confirm.
* **To Search:** Use the **Search** field to locate scripts by name.

<figure><img src="../../.gitbook/assets/image (461).png" alt=""><figcaption></figcaption></figure>

## 26. How do I create a new Automation Command button for POS operations?

To add a new action button for POS screens:

1. Open BackOffice and go to the **Automation Command List**.
2. Select **"Add Automation Command"**.
3. In the **Name** field, enter the command name _(Required)_.
4. Configure visual and operational settings under **General Settings** (**Button Header Resource Key**, **Color**, **Font Size**, **Button Header**, **Toggle Values**, **Image Path**, **Values**, **Confirmation**, **Group Code**, **Permission**).
5. Open **Mappings** and select **Add** to define where the button appears.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (462).png" alt=""><figcaption></figcaption></figure>

## 27. How do I customize the appearance of an Automation Command button?

To style command buttons used on terminals:

1. Open the Automation Command setup window.
2. Under **General Settings**, configure display properties:
   * **Button Header:** Enter the exact text displayed on the button.
   * **Color:** Choose the button background color.
   * **Font Size:** Set the label text size.
   * **Image Path:** Specify the file path to an icon or graphic image.
   * **Button Header Resource Key:** Specify a localization resource key if applicable.
3. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (463).png" alt=""><figcaption></figcaption></figure>

## 28. How do I map an Automation Command to specific states and visibilities?

To control when and where a command button appears or is enabled:

1. Open **Automation Command** setup and select **Mappings**.
2. Click **Add** to create a mapping entry.
3. Configure conditional criteria:
   * **Terminal**, **User Role**, **Department**, **Ticket Type**.
   * **Enabled States:** Select order states in which the button is active.
   * **Visible States:** Select order states in which the button is visible.
   * **Visibility:** Specify screen location visibility.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (465).png" alt=""><figcaption></figcaption></figure>

## 29. How do I rearrange Automation Command buttons using drag-and-drop?

To customize button layouts on screen:

1. Go to the **Automation Command List**.
2. Select **"Sort Automation Commands"**.
3. Drag and drop the listed commands into your preferred sequence.
4. Select **"OK"** to save the updated sort order.

<figure><img src="../../.gitbook/assets/image (466).png" alt=""><figcaption></figcaption></figure>

## 30. How do I edit or delete an Automation Command?

To modify or remove command buttons:

* **To Edit:** Select the command from the **Automation Command List**, select **"Edit Automation Command"**, update General Settings or Mappings, and click **"Save"**.

<figure><img src="../../.gitbook/assets/image (468).png" alt=""><figcaption></figcaption></figure>

* **To Delete:** Select the command, click **"Delete Automation Command"**, and select **"Yes"** on the confirmation prompt.

<figure><img src="../../.gitbook/assets/image (467).png" alt=""><figcaption></figcaption></figure>

## 31. How do I search and filter employee clock-in/out records by employee name and date range?

To look up employee time and attendance logs in BackOffice:

1. Open the **Clock Information** screen.
2. In the **Name** field, enter the employee name _(Optional filter)_.
3. Click **From** and select the start date for the audit period.
4. Click **To** and select the end date.
5. Matching records display automatically in the summary table.

<figure><img src="../../.gitbook/assets/image (469).png" alt=""><figcaption></figcaption></figure>

## 32. What information is displayed in the Clock Information summary table?

The **Clock Information** results table displays four specific detail columns for matching records:

* **Code:** Displays the unique system code associated with the clock record.
* **Employee:** Displays the name of the employee.
* **Type:** Displays the type of clock event recorded.
* **Date:** Displays the exact date timestamp of the clock entry.

<figure><img src="../../.gitbook/assets/image (470).png" alt=""><figcaption></figcaption></figure>

## 33. How do I create a new Task Type and configure Custom Fields for it?

To set up custom task classifications (e.g., EVENTLOG or maintenance tasks):

1. Open BackOffice and go to the **Task Type List**.
2. Select **"Add Task Type"**.
3. Enter the category name in **Name** _(Required)_.
4. Under **Custom Fields**, select **Add** to attach custom data fields.
5. Define custom field properties:
   * **Custom Field Name:** Enter the field label.
   * **Field Type:** Select the data type.
   * **Editing Format:** Set the input format structure.
   * **Display Format:** Set the display layout structure.
6. Select **"Save"** to store the task type.

<figure><img src="../../.gitbook/assets/image (471).png" alt=""><figcaption></figcaption></figure>

## 34. How do I edit, reorder, or delete Task Types and Custom Fields?

To manage task classifications and custom data fields:

* **To Edit Task Type:** Select the task type from the **Task Type List**, select **"Edit Task Type"**, modify Name or custom fields, and select **"Save"**.
* **To Delete Custom Field:** Select the field row under Custom Fields and click **Delete**.
* **To Delete Task Type:** Select the task type from the list, click **Delete Task Type**, and select **"Yes"** on the confirmation prompt.
* **To Reorder:** Select **"Change Sort Order"**, drag task types into position, and select **"OK"**.

<figure><img src="../../.gitbook/assets/image (472).png" alt=""><figcaption></figcaption></figure>
