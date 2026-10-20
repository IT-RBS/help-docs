# FAQ's

## 1. How do I create a new Entity Type in DinePlan BackOffice?

To create a new Entity Type (such as Members, Tables, or Customers) to categorize system records:

1. Open **BackOffice** and navigate to the **Entity Type List**.
2. Select **"Add Entity Type"**.
3. In the **Name** field, enter the required name for the entity type _(Required)_.
4. Enter details for **Entity Name**, **Display Format**, **Primary Field Name**, and **Primary Field Format**.
5. Configure account and inventory parameters as needed:
   * **Warehouse Type**
   * **Account Type**
   * **Account Name Template**
   * **Account Balance Display Format**
   * **Stop Merging**
6. Select **"Save"** to store the entity type.

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

**Note:** Entering a **Name** is strictly required when creating an entity type.

## 2. What field is mandatory when creating a new Entity Type?

When setting up a new Entity Type in BackOffice, the **Name** field is strictly required.

If you leave the **Name** field blank, the system will not allow you to save the entity type record.

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

## 3. How do I define a primary field identifier for an Entity Type?

To specify a primary field used to identify individual entities within a category:

1. Open the **Entity Type List** and select **"Add Entity Type"** (or select an existing one and click **"Edit Entity Type"**).
2. Locate the primary field configuration fields:
   * **Primary Field Name:** Enter the label used to identify the entity (e.g., _Table Number_ or _Member ID_).
   * **Primary Field Format:** Enter the required formatting structure for the primary identifier.
3. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

## 4. How do I configure account-related templates and balance formats for an Entity Type?

To link financial account structures to an entity category:

1. Open **Entity Type List** and click **"Add Entity Type"** (or **"Edit Entity Type"**).
2. Under **General Settings**, configure the accounting fields:
   * **Account Type:** Select the account classification associated with this entity type.
   * **Account Name Template:** Enter the template used to auto-generate account names for entities.
   * **Account Balance Display Format:** Enter the format structure used when displaying account balances on screen.
3. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

## 5. How do I add Custom Fields to capture extra information for an Entity Type?

To create custom data fields (such as phone numbers, birthdates, or notes) for an entity category:

1. Open **Entity Type** configuration (**Add Entity Type** or **Edit Entity Type**).
2. Select the **"Custom Fields"** section.
3. Select **"Add Custom Field"**.
4. Configure the field parameters:
   * **Custom Field Name:** Enter the label for the field.
   * **Field Type:** Select the data input type.
   * **Editing Format:** Define the input format.
   * **Values:** Specify available selection options, if applicable.
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

## 6. How do I make a custom field required or hide it from standard screens?

To control user input and field visibility for custom fields:

1. Edit the target **Entity Type** and expand the **Custom Fields** section.
2. Select or highlight the custom field row.
3. Configure the field toggles:
   * Enable **Mandatory** to make filling out this custom field compulsory when creating entities.
   * Enable **Hidden** to hide the custom field from standard display screens.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

## 7. How do I edit an existing Entity Type configuration or its custom fields?

To modify settings or custom fields for a previously created entity category:

1. Go to the **Entity Type List**.
2. Select the entity type you want to modify.
3. Select **"Edit Entity Type"**.
4. Update **General Settings** or add/edit entries under **Custom Fields**.
5. Select **"Save"** to apply the updates.

<figure><img src="../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

## 8. How do I delete an Entity Type that is no longer required?

To permanently remove an unneeded entity type from the system:

1. Navigate to the **Entity Type List**.
2. Select the entity type you wish to remove.
3. Select **"Delete Entity Type"**.
4. A system confirmation message will appear.
5. Select **"Yes"** to confirm deletion, or select **"No"** to cancel.

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

**Note:** Deleting an entity type requires confirmation before removal.

## 9. How do I change the display order of Entity Types in BackOffice?

To organize how entity types are listed on screen:

1. Open the **Entity Type List**.
2. Select **"Sort Entity Types"**.
3. In the sorting window, drag and drop the entity types into your preferred order.
4. Select **"OK"** to save the new sort sequence.

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

## 10. How do I search for a specific Entity Type in BackOffice?

To quickly locate an entity type in a long list:

1. Open the **Entity Type List** screen.
2. Click inside the **Search** field above the list.
3. Type the entity type name or keyword.
4. The list filters automatically to display matching records.

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

## 11. How do I add an individual Entity (like a new Table or Member)?

To create an individual operational entity record in DinePlan:

1. Open **BackOffice** and navigate to the **Entity List**.
2. Select **"Add Entity"**.
3. Click **Entity Type** and select the required category _(Required)_.
4. Enter or select the associated **Warehouse**.
5. Enter or select the associated **Account**.
6. Select **"Save"** to create the entity.

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

**Note:** Selecting an **Entity Type** is required when creating an entity.

## 12. Which field is compulsory when creating an individual Entity?

When adding an entity on the **Add Entity** screen, you must select an **Entity Type** from the dropdown menu before saving.

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

## 13. How do I link a Warehouse and an Account to an Entity?

To associate an entity with inventory and financial accounting records:

1. Open **Entity List** and select **"Add Entity"** (or **"Edit Entity"**).
2. Click the **Warehouse** field to enter or choose the associated inventory warehouse.
3. Click the **Account** field to enter or choose the linked financial account.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

## 14. How do I create multiple Entities at once using Batch Create Entities?

To quickly generate multiple entities (such as Tables 1 through 20) simultaneously:

1. Navigate to the **Entity List**.
2. Select **"Batch Create Entities"**.
3. In the text input box, enter the entity names, typing **each entity on a separate line**.
4. Select **"OK"** to create all listed entities at once.

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

**Note:** The system automatically creates a separate entity record for every line entered in the text box.

## 15. How do I edit the details of an existing Entity?

To modify the warehouse, account, or settings of an existing entity:

1. Open the **Entity List**.
2. Select the required entity from the list.
3. Select **"Edit Entity"**.
4. Update the **Warehouse**, **Account**, or other entity details.
5. Select **"Save"** to store your changes.

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

## 16. How do I delete an Entity from the system?

To remove an obsolete entity record:

1. Go to the **Entity List**.
2. Select the entity you want to remove.
3. Select **"Delete Entity"**.
4. When the confirmation prompt appears, select **"Yes"** to delete or **"No"** to cancel.

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

## 17. How do I reorder Entities in the Entity List?

To customize the visual list sequence of entities:

1. Open the **Entity List**.
2. Select **"Change Sort Order"**.
3. Adjust the order of the entities as required.
4. Save the updated layout sequence.

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

## 18. How do I search for a specific Entity in BackOffice?

To locate an entity when managing a large list of records:

1. Open the **Entity List** screen.
2. Click the **Search** input box.
3. Enter the entity name or search keyword.
4. The screen filters dynamically to show matching entities grouped by Entity Type.

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

## 20. How do I edit entity fields directly within the Batch Entity Editor?

To make fast updates across multiple entity records on one screen:

1. Open the **Batch Entity Editor**.
2. Select the required category tab (**"Members"**, **"Tables"**, or **"Customers"**).
3. Locate the target entity row.
4. **Double-click** the specific field cell you want to modify (e.g., **Name**, **Address**, **TaxId**, **CompanyName**, or **Email**).
5. Type the updated text directly into the cell.
6. Select **"Save Changes"** to save all updates together.

<figure><img src="../../.gitbook/assets/image (363).png" alt=""><figcaption></figcaption></figure>

## 21. How do I switch between Members, Tables, and Customers in the Batch Entity Editor?

Click the corresponding category tabs located at the top of the **Batch Entity Editor** window:

* Select **"Members"** to view and edit member entities.
* Select **"Tables"** to view and edit table entities.
* Select **"Customers"** to view and edit customer entities.

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

## 23. How do I search for a record inside the Batch Entity Editor?

To locate a specific entity record while working in the batch grid:

1. Select the required entity tab (**Members**, **Tables**, or **Customers**).
2. Type the entity name or detail into the **"Search"** box above the table.
3. Review the filtered results displayed in the grid.

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

## 24. How do I ensure my updates are saved before closing the Batch Entity Editor?

After editing fields in the grid, click **"Save Changes"** at the bottom of the screen. Once saved, click **"Close"** to exit the editor.

<figure><img src="/broken/files/1xoIrSgalSK6XlMGggWv" alt=""><figcaption></figcaption></figure>

## 25. How do I create a new Entity Screen for table layouts or floor plans?

To build a visual layout screen for displaying entities on POS terminals:

1. Open BackOffice and navigate to the **Entity Screen List**.
2. Select **"Add Entity Screen"**.
3. Enter the screen name in **Name** _(Required)_.
4. Under **General Settings**, select the required **Ticket Type** _(Required)_.
5. Open **Entity List** to select the **Entity Type** and specific entities to display.
6. Open **Mappings** and click **Add** to configure terminal and department routing.
7. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>

**Note:** The **Name** field is required, and both **Ticket Type** and **Entity Type** must be configured before saving.

## 26. Which fields must be configured before saving an Entity Screen?

When creating an Entity Screen, you must configure:

* **Name:** A descriptive name for the screen _(Required)_.
* **Ticket Type:** The ticket classification associated with the screen _(Required)_.
* **Entity Type:** The entity category selected under the **Entity List** tab _(Required)_.

<figure><img src="../../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

## 27. How do I configure row count, column count, and button sizes on an Entity Screen?

To adjust button dimensions and grid capacity for visual floor plans:

1. Open the **Entity Screen** configuration window (**Add Entity Screen** or **Edit Entity Screen**).
2. Under **General Settings**, configure the layout properties:
   * **Row Count:** Specify the number of display rows.
   * **Column Count:** Specify the number of display columns.
   * **Button Height:** Specify the height of entity buttons.
   * **Fly Button Height:** Specify the height of fly buttons.
   * **Page Count:** Specify total display pages.
   * **Font Size:** Set text font size used on buttons.
3. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>

## 28. How do I customize the background image and color of an Entity Screen?

To set custom floor plan graphics or background colors:

1. Open **Entity Screen** setup.
2. Under **General Settings**:
   * **Background Image:** Enter or select the file path for the screen backdrop image.
   * **Background Color:** Choose the screen background color shade.
3. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>

## 29. How do I assign specific Entities to display on an Entity Screen?

To choose which tables or members appear on a specific display screen:

1. Open **Entity Screen** setup and select the **"Entity List"** section.
2. Select the target **Entity Type** from the dropdown menu.
3. Check or select the specific entities that should appear on this screen.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

## 30. How do I map an Entity Screen to specific Terminals, User Roles, or Departments?

To control which POS terminals or staff roles see an entity screen:

1. Open **Entity Screen** setup and go to **Mappings**.
2. Select **"Add"** to create a mapping entry.
3. Select the applicable values for:
   * **Terminal**
   * **User Role**
   * **Department**
   * **Ticket Type**
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

## 31. How do I enable Ask Ticket Type or Use State DisplayFormat on an Entity Screen?

To customize prompt behavior and state styling on entity buttons:

1. Open **Entity Screen** setup and locate **General Settings**.
2. Configure operational toggles:
   * Enable **Ask Ticket Type** to prompt staff to select a ticket type when opening the screen.
   * Enable **Use State DisplayFormat** to format entity button labels according to their active order state.
3. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (362).png" alt=""><figcaption></figcaption></figure>

## 32. How do I configure Search Value Replace Pattern and Refresh Entities on an Entity Screen?

To manage search text formatting and auto-refresh behavior:

1. Open **Entity Screen** setup under **General Settings**.
2. Configure search and refresh settings:
   * **Search Value Replace Pattern:** Enter text pattern rules to replace search values automatically.
   * **Refresh Entities:** Enable or disable automatic entity refreshing on screen.
3. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (361).png" alt=""><figcaption></figcaption></figure>

## 33. How do I edit an existing Entity Screen layout or settings?

To update layout dimensions, buttons, or mappings on an existing screen:

1. Navigate to the **Entity Screen List**.
2. Select the screen you want to modify.
3. Select **"Edit Entity Screen"**.
4. Update **General Settings**, **Entity List**, or **Mappings**.
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (360).png" alt=""><figcaption></figcaption></figure>

## 34. How do I delete an Entity Screen from BackOffice?

To permanently remove an entity screen:

1. Go to the **Entity Screen List**.
2. Select the screen you want to remove.
3. Select **"Delete Entity Screen"**.
4. When the confirmation message displays, select **"Yes"** to delete (or **"No"** to cancel).

<figure><img src="../../.gitbook/assets/image (359).png" alt=""><figcaption></figcaption></figure>

## 35. How do I change the display order of Entity Screens in the list?

To reorganize the order of available Entity Screens:

1. Open the **Entity Screen List**.
2. Select **"Sort Entity Screens"**.
3. Drag and drop the entity screens to arrange them into your preferred sequence.
4. Select **"OK"** to save the new display order.

<figure><img src="../../.gitbook/assets/image (357).png" alt=""><figcaption></figcaption></figure>

