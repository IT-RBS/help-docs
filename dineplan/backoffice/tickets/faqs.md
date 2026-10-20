# FAQ's

## 1. How do I create a new Ticket Type in BackOffice for different transaction workflows?

To set up a new ticket type (such as Dine-In, Takeaway, or Delivery) in DinePlan BackOffice:

1. Open **BackOffice** and navigate to **Ticket Types**.
2. Select **"Add Ticket Type"**.
3. In the **"Ticket Type Name"** field, enter a descriptive title for the ticket type.
4. Configure transaction numerators and generators as required:
   * **Transaction Type:** Select the associated transaction type.
   * **Ticket Number Generator:** Select the number generator for tickets.
   * **TicketInvoiceNumerator:** Specify the numerator for ticket invoices.
   * **Order Number Generator:** Select the number generator for orders.
   * **Promotion Numerator:** Specify the numerator for promotions.
   * **FullTaxInvoiceNumerator:** Specify the numerator for full tax invoices.
   * **QueueNumerator:** Specify the numerator for queue numbers.
5. Configure operational toggles:
   * **Tax Included:** Enable or disable whether tax is included for this ticket type.
   * **Pre Order:** Enable if this ticket type is configured for pre-orders.
   * **Allow Zero Price Products:** Enable if zero-price items are allowed on this ticket type.
6. Select **"Entity Type List"**, click **"Select"**, and configure required entity types.
7. Select **"Menu Mapping"** to assign terminals and menus to the ticket type.
8. Select **"Save"** to create the ticket type.

<figure><img src="../../.gitbook/assets/image (512).png" alt=""><figcaption></figcaption></figure>

**Note:** Ensure all required fields, entity types, and menu mappings are verified before selecting **Save**.

#### 2. How do I map a Ticket Type to specific POS terminals and menus?

To make a ticket type available only on specific POS terminals or menu interfaces:

1. Navigate to **Ticket Types** in BackOffice.
2. Select the target ticket type from the **Ticket Type List**.
3. Select **"Edit Ticket Type"**.
4. Open the **"Menu Mapping"** section.
5. Select the required terminals and menus to associate with the ticket type.
6. Select **"Save"** to apply the updated mapping.

<figure><img src="../../.gitbook/assets/image (513).png" alt=""><figcaption></figcaption></figure>

## 3. How do I configure a new Ticket Tag to ask cashiers for tag information before creating a ticket?

To create a ticket tag (e.g., Table Source or Customer Type) and prompt cashiers to select it during order creation:

1. Open **Ticket Tags** in BackOffice.
2. Select **"Add Ticket Tag"**.
3. In **General Settings**, enter the **"Ticket Tag Name"** and **"DisplayName"**.
4. Enable **"Ask Before Creating Ticket"** so the system prompts for the tag before generating a ticket.
5. Enable **"Selection Required"** if selecting the tag is mandatory.
6. Select the **"Tagging Type"**.
7. Configure button colors for **"When Tagged"** and **"When Untagged"** to customize visual display.
8. Select **"Save"** to store the configuration.

<figure><img src="../../.gitbook/assets/image (510).png" alt=""><figcaption></figcaption></figure>

**Note:** A **Ticket Tag Name** is mandatory before saving a ticket tag.

## 4. How do I enable Free Tagging and set a maximum character limit on a Ticket Tag?

To allow cashiers to type custom text notes on a ticket rather than selecting predefined tags:

1. Go to **Ticket Tags** and select **"Add Ticket Tag"** (or select an existing tag and click **"Edit Ticket Tag"**).
2. In **General Settings**, enable **"Free Tagging"**.
3. Enable **"Save Free Tags"** if you want manually entered tags to be stored for future use.
4. Select the required **"Tagging Type"**.
5. In the **"Free Tag Maximum Length"** field, enter the maximum number of characters allowed for manual text entry.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (508).png" alt=""><figcaption></figcaption></figure>

## 5. How do I add Sub Tags and set Alias Names for a Ticket Tag?

To create nested child tags under a main ticket tag:

1. Open **Ticket Tags** and select **"Add Ticket Tag"** or **"Edit Ticket Tag"**.
2. Select **"Sub Tags"**.
3. Select **"Add Tag"**.
4. Enter the sub tag title in the **"New Tag"** field.
5. Enter an optional display label in the **"Alias Name"** field.
6. Select **"Save"** to save the ticket tag with its new sub tags.

<figure><img src="../../.gitbook/assets/image (507).png" alt=""><figcaption></figcaption></figure>

## 6. How do I map a Ticket Tag to specific terminals, user roles, departments, and ticket types?

To restrict or assign ticket tag visibility across operational stations:

1. Open **Ticket Tags** and select **"Add Ticket Tag"** or **"Edit Ticket Tag"**.
2. Select **"Mappings"**.
3. Select **"Add"**.
4. Select the specific values for **"Terminal"**, **"User Role"**, **"Department"**, **"Ticket Type"**, and **"DefaultValue"**.
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (506).png" alt=""><figcaption></figcaption></figure>

## 7. How do I create an Order Tag Group with selection limits for menu options?

To set up a group of order modifiers (e.g., Meat Temperature or Dressing Options) with minimum and maximum selection constraints:

1. Open **Order Tag Group** and select **"Add Order Tag Group"**.
2. In **General Settings**, enter the group title in the **"Name"** field.
3. Enter an optional **"Alias Name"**.
4. Set selection limits:
   * **Min Selected Items:** Enter the minimum number of tags a cashier must select.
   * **Max Selected Items:** Enter the maximum number of tags allowed.
   * **MaximumItemSelect:** Enter the maximum count per individual item.
5. Configure display settings under **Display Settings**.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (505).png" alt=""><figcaption></figcaption></figure>

**Note:** A **Name** is strictly required when creating an order tag group.

## 8. How do I add individual order tags, prefixes, and suffixes to an Order Tag Group?

To configure modifier choices and prep instructions (e.g., "No", "Extra", "On Side") inside an Order Tag Group:

1. Open **Order Tag Group** and select **"Add Order Tag Group"** (or **"Edit Order Tag Group"**).
2. Open **"Order Tag List"** and select **"Add Order Tag"** to add individual modifier items.
3. Open **"Prefix List"** and select **"Add Prefix"** to add modifier prefixes (e.g., "No" or "Extra").
4. Open **"Suffix List"** and select **"Add Suffix"** to add modifier suffixes (e.g., "On Side").
5. Select **"Save"** to store all group components.

<figure><img src="../../.gitbook/assets/image (504).png" alt=""><figcaption></figcaption></figure>

## 9. How do I map an Order Tag Group to specific products, categories, or departments?

To attach order modifier groups to specific menu items or departments:

1. Open **Order Tag Group** and select **"Add Order Tag Group"** or **"Edit Order Tag Group"**.
2. Open **"Mappings"** and select **"Add"**.
3. Select the required criteria across **"User Role"**, **"Department"**, **"Ticket Type"**, **"Product Group"**, **"Sub Product Group"**, **"Category"**, and **"Product"**.
4. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (503).png" alt=""><figcaption></figcaption></figure>

## 10. How do I create a new Payment Type and configure its button appearance and toggles?

To set up a new payment method (e.g., Cash, Credit Card, or Voucher) in BackOffice:

1. Navigate to **Payment Type** and select **"Add Payment Type"**.
2. Under **General Settings**, enter the payment name in **"Name"**.
3. Select the **"Account Transaction Type"** and associated **"Account"**.
4. Enter an **"Account Code"**, **"Group"**, **"Tender Type"**, **"Payment Tag"**, or **"Alternate Names"** if applicable.
5. Configure visual button settings:
   * **Button Color:** Choose the button background color.
   * **Font Size:** Specify the font size displayed on the button.
   * **Image Path:** Enter the image file path if an icon is used.
6. Configure operational **Toggles**:
   * **No Change Display:** Hide change calculation on screen.
   * **Display Value in Shift Close:** Include payment totals in shift reports.
   * **No Refund:** Prevent refund processing on this payment type.
   * **Auto Payment:** Automatically complete payment upon selection.
   * **Non Editable:** Lock payment amount editing.
   * **Enable Tip:** Allow tipping.
   * **Requires Authentication:** Require manager authorization.
   * **Allow Over Tender:** Allow cashiers to accept tender above the bill total.
   * **Active:** Enable or disable the payment method.
7. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (501).png" alt=""><figcaption></figcaption></figure>

**Note:** Both **Name** and **Account Transaction Type** are compulsory fields when creating a payment type.

## 11. How do I add a Payment Processor and set terminal/department mappings for a Payment Type?

To link integrated card terminals or restrict payment types by terminal and department:

1. Open **Payment Type** and select **"Add Payment Type"** (or **"Edit Payment Type"**).
2. Open **"Payment Processors"** and select **"ADD"**.
3. Configure the processor settings, including processor **Name** and **Description**.
4. Open **"Mappings"** and select **"Add"**.
5. Select the required **"Terminal"**, **"User Role"**, **"Department"**, and **"Ticket Type"**.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (500).png" alt=""><figcaption></figcaption></figure>

## 12. How do I set up a Change Payment Type for handling payment method replacements?

To configure change payment templates for replacing or converting payment methods:

1. Navigate to **Change Payment Type** and select **"Add Change Payment Type"**.
2. Enter the template title in **"Template Name"**.
3. Select the **"Account Transaction Type"**.
4. Select the associated **"Account"**.
5. Open **"Mappings"** and select **"Add"**.
6. Assign the required **"User Role"**, **"Department"**, and **"Ticket Type"**.
7. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (499).png" alt=""><figcaption></figcaption></figure>

**Note:** **Template Name** and **Account Transaction Type** are required to save a Change Payment Type.

## 13. How do I create a new Calculation Type for applying discounts or service charges to tickets?

To define calculation rules for discounts, surcharges, or rounding rules:

1. Open **Calculation Type** and select **"Add Calculation Type"**.
2. Enter the title in **"Template Name"**.
3. Select the **"Account Transaction Type"**.
4. Select the **"Calculation Method"** (e.g., Rate, Amount, or Fixed).
5. Enter the numerical value in **"Rate or Amount"**.
6. Configure calculation behavior toggles:
   * **Include Tax:** Include tax in the calculation.
   * **Decrease Amount:** Treat calculation as a discount/deduction.
   * **Use Plain Sum:** Use raw unadjusted sums.
   * **Toggle Calculation:** Allow toggling on/off during order taking.
   * **Use Original Item Price:** Calculate based on original base prices.
   * **Change On Department:** Adjust calculation when changing departments.
   * **Use Sub Total:** Apply calculation to ticket subtotal.
   * **Ask Reference:** Prompt cashier for a reference note.
7. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (498).png" alt=""><figcaption></figcaption></figure>

**Note:** **Template Name** and **Account Transaction Type** are required when setting up a calculation type.

## 14. How do I associate a Tax Template with a Calculation Type?

To apply specific tax rules to discounts or service charges:

1. Open **Calculation Type** and select **"Add Calculation Type"** (or **"Edit Calculation Type"**).
2. Locate the **"Tax Template"** section.
3. Select **"Add"**.
4. Choose the required tax template from the **Tax Templates** selection window.
5. Select **"OK"** to link the tax template.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (497).png" alt=""><figcaption></figcaption></figure>

## 15. How do I create a Calculation Selector button for POS screens?

To group calculation types into accessible POS screen buttons (e.g., "10% VIP Discount" or "Service Charge"):

1. Open **Calculation Selector** and select **"Add Calculation Selector"**.
2. Enter the selector title in **"Name"**.
3. Enter the display text in **"Button Header"**.
4. Set visual style options (**Button Color** and **Font Size**).
5. Configure **"Confirmation"** if manager confirmation is required.
6. Enter or select a **"Group"**.
7. Enable **"Restrict Promotion"** if promotion restrictions apply.
8. Under **"Calculation Type"**, select **"Add"**, pick the applicable calculation types from the list, and select **"OK"**.
9. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (496).png" alt=""><figcaption></figcaption></figure>

**Note:** A **Name** is mandatory when creating a calculation selector.

## 16. How do I restrict a Calculation Selector by terminal, user role, department, and ticket type using Mappings?

To control which POS terminals or staff roles can see and click a calculation selector button:

1. Open **Calculation Selector** and select **"Add Calculation Selector"** (or **"Edit Calculation Selector"**).
2. Open **"Mappings"**.
3. Select **"Add"**.
4. Configure mapping restrictions across **"Terminal"**, **"User Role"**, **"Department"**, and **"Ticket Type"**.
5. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (495).png" alt=""><figcaption></figcaption></figure>

## 17. How do I configure Number Generators for transaction types like tickets, orders, and invoices?

To customize auto-numbering formats for tickets, orders, promotions, or tax invoices:

1. Open **Number Generator** in BackOffice.
2. Select **"Add Number Generator"**.
3. Enter a descriptive title in **"Name"** (e.g., Ticket Number Generator or Full Tax Invoice Generator).
4. Enter the generation sequence rules in **"Number Format"**.
5. Enter the final displayed format structure in **"Output Format"**.
6. Select **"Save"**.

<figure><img src="../../.gitbook/assets/image (494).png" alt=""><figcaption></figcaption></figure>

**Note:** A **Name** must be provided when creating a number generator.

## 18. How do I change the display order (sort order) of Ticket Types, Payment Types, or Ticket Tags?

To rearrange how transaction items, payment methods, or ticket tags are listed on screen:

1. Open the target management screen in BackOffice (e.g., **Ticket Types**, **Payment Type**, **Ticket Tags**, or **Number Generator**).
2. Select the sorting action button: **"Sort Ticket Types"**, **"Sort Payment Types"**, **"Sort Ticket Tags"**, or **"Change Sort Order"**.
3. Click and drag the listed items into your preferred display sequence.
4. Select **"OK"** (or **"Save"**) to apply the new display order.

<figure><img src="../../.gitbook/assets/image (493).png" alt=""><figcaption></figcaption></figure>

## 19. How do I search for specific configuration records in BackOffice Ticket settings?

To quickly locate a specific ticket type, tag, payment method, or calculation selector in a long list:

1. Open any Ticket management screen (e.g., **Ticket Types**, **Payment Type**, **Ticket Tags**, **Order Tag Group**, **Change Payment Type**, **Calculation Type**, or **Calculation Selector**).
2. Locate the **"Search"** input box positioned above the list.
3. Type the keyword, template name, or tag name into **"Search"**.
4. The system automatically filters the list to show matching records.

<figure><img src="../../.gitbook/assets/image (492).png" alt=""><figcaption></figcaption></figure>

## 20. How do I safely delete an unneeded Payment Type, Ticket Tag, or Calculation Type?

To remove outdated configuration records from BackOffice:

1. Open the target settings screen (e.g., **Payment Type**, **Ticket Tags**, **Calculation Type**, **Change Payment Type**, or **Number Generator**).
2. Highlight the specific item you want to remove from the list.
3. Select the delete action button (e.g., **"Delete Payment Type"**, **"Delete Ticket Tag"**, **"Delete Calculation Type"**, or **"Delete Number Generator"**).
4. A confirmation message box will appear on screen asking for confirmation.
5. Select **"Yes"** to permanently delete the item.

**Note:** Deleting any system configuration record strictly requires user confirmation before the item is removed.
