# FAQ's

## **1. How do I open the main Report screen in DinePlan?**&#x20;

To access operational, sales, and transaction reports in DinePlan, navigate from the main Dashboard:&#x20;

1. Log in to DinePlan.&#x20;
2. From the Dashboard, select Front Desk.&#x20;

<figure><img src="../../.gitbook/assets/image (168).png" alt=""><figcaption></figcaption></figure>

3. Select Report.&#x20;
4. The Report screen will open, displaying the available Report Categories panel on the left.&#x20;

<figure><img src="../../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>

Note: The available report categories are General, Day Shift, Item, Ticket, Group, Entity, Member, Summary, and Custom.&#x20;

## 2. Why are my report action buttons disabled, and how do I activate them?&#x20;

When you open the Report screen, all action buttons (such as export, print, and view controls) are disabled by default to prevent generating blank reports.&#x20;

To enable the report action buttons:&#x20;

1. Select a category under Report Categories (e.g., General or Day Shift).&#x20;
2. Click the SELECT REPORT dropdown menu.&#x20;
3. Choose the specific report you want to view.&#x20;
4. Once selected, the report data will populate and the action options (such as View, Filter by Condition, Export to PDF, Export to Excel, and Print) will become active.&#x20;

<figure><img src="../../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>

## 3. How do I switch between Compact, Full, and Free report layouts?&#x20;

You can change how report data is displayed on screen by using the View dropdown menu:&#x20;

1. Open and select your desired report from the SELECT REPORT dropdown.&#x20;
2. Click the View dropdown menu.&#x20;
3. Choose one of the following display modes: &#x20;
4. Compact: Displays the report in a condensed format for quick scanning.&#x20;
5. Full: Displays the complete report with all available fields and detailed columns.&#x20;
6. Free: Displays the report without predefined formatting, allowing flexible viewing where applicable.&#x20;

<figure><img src="../../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>

## 4. How do I filter report data by date range or specific operational conditions?&#x20;

Before generating, printing, or exporting a report, you can refine the displayed results using built-in filters:&#x20;

1. Select your report from the SELECT REPORT dropdown.&#x20;
2. Use Filter by Date to specify a custom date or business date range.&#x20;

<figure><img src="../../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

3. Click Filter by Condition to open specific filtering criteria (such as terminal, cashier, product, department, ticket number, or user).&#x20;
4. Apply the required criteria to update the generated report results.&#x20;

<figure><img src="../../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

## 5. How do I export a report as a Microsoft Excel spreadsheet or PDF document?&#x20;

To save a copy of any generated report for offline auditing or management sharing:&#x20;

1. Display the required report on the screen.&#x20;
2. To export as a spreadsheet: Click Export to Excel (saves as a .xlsx file).&#x20;
3. To export as a PDF document: Click Export to PDF (or Export as PDF depending on the report category).&#x20;
4. To output directly to a printer: Click Print.&#x20;

<figure><img src="../../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

## 6. How do I verify POS product pricing, portions, and categories before opening for service?&#x20;

Store managers and cashiers can cross-check POS menu configuration before operations begin using the Product List Report:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Under Report Categories, select General.&#x20;
3. Under SELECT REPORT, select Product List Report.&#x20;
4. Review the displayed columns: &#x20;
5. Category: Menu category assigned to the product.&#x20;
6. Alias Code: Unique alias code assigned to the item.&#x20;
7. Product: Name of the menu item.&#x20;
8. Alias Name: Alternate or localized product name, if configured.&#x20;
9. Portion: Serving size or portion configured for the item.&#x20;
10. Price: Selling price configured in the POS.&#x20;

<figure><img src="../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

## &#x20;7. How do I confirm that new or modified backend menu items have synchronized to the POS?&#x20;

To verify that updates made in the backend system are available for customer billing:&#x20;

1. Go to Front Desk > Report > General.&#x20;
2. Select Menu Items Sync Report from the dropdown.&#x20;
3. Review the Category, Alias Code, Product, Alias Name, Portion, and Price fields.&#x20;
4. Confirm that newly added or updated items appear in the list before starting billing.&#x20;

<figure><img src="../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

## 8. How do I audit system events and staff activities like "New Order" or "Ticket Entity Changed"?&#x20;

Administrators and supervisors can track user activity and system operations using the Log Report:&#x20;

1. Go to Front Desk > Report > General.&#x20;
2. Select Log Report from the dropdown menu.&#x20;
3. Review the audit fields: &#x20;
4. Ticket No: Ticket number associated with the event (if applicable).&#x20;
5. Amount: Transaction value linked to the event.&#x20;
6. Event: Specific POS action performed (e.g., Module Clicked, New Order, or Ticket Entity Changed).&#x20;
7. Event Time: Exact date and timestamp of the event.&#x20;
8. Log: Detailed description of the affected module or item.&#x20;
9. User: Name of the employee who performed the action.&#x20;

<figure><img src="../../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

## 9. How do I check active promotional offers, validity date ranges, and promotion rules?&#x20;

To review currently active discounts and combos in the POS:&#x20;

1. Go to Front Desk > Report > General.&#x20;
2. Select Active Promotions Report.&#x20;
3. Inspect the active promotion details: &#x20;
4. Name: Name of the active promotion.&#x20;
5. Alias Code: Assigned promotion alias code.&#x20;
6. From & To: Start and end date range of the offer.&#x20;
7. Type: Classification (such as Ticket Discount Promotion, Item Discount Promotion, or Combo Promotion).&#x20;
8. Condition: Rules required for the promotion to trigger during billing.&#x20;
9. Description: Offer details and discount percentages.&#x20;

<figure><img src="../../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

## 10. How do I check employee clock-in times, clock-out times, and total working hours?&#x20;

To review staff attendance for payroll or shift verification:&#x20;

1. Go to Front Desk > Report > General.&#x20;
2. Select Time Attendance Report.&#x20;
3. Locate the staff member by Employee ID or Employee Name.&#x20;
4. Review their POS No, Designation, Date, Clock In, Clock Out, daily Working Hours, and accumulated Summary Working Hours.&#x20;

<figure><img src="../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

## 11. How do I generate a complete operational summary for a completed business day?&#x20;

To conduct an end-of-day operational review across all departments, categories, and payment types:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Day Shift under Report Categories.&#x20;
3. Select Work Day Report from the dropdown menu.&#x20;
4. Specify the date range under Filter by Date.&#x20;
5. Review the comprehensive report sections, including Business day details, Receipt number range, Sales summary, Department-wise sales, Payment summary, Ticket summary, Category sales, and Group sales.&#x20;

<figure><img src="../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/att_23_for_3350265859 (1).png" alt=""><figcaption></figcaption></figure>

## 12. How do I review sales, float amounts, and till counts for an individual cashier shift?&#x20;

Cashiers and store managers can verify shift-level performance before ending a shift using the Work Shift Report:&#x20;

1. Go to Front Desk > Report > Day Shift.&#x20;
2. Select Work Shift Report.&#x20;
3. Review the shift-specific metrics: Shift details, Terminal information, Shift number, Float amount, Till count, Sales summary, Department summary, Payment information, and Payment totals.&#x20;

<figure><img src="../../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/att_25_for_3350265859 (1).png" alt=""><figcaption></figcaption></figure>

## 13. How do I identify business days where the End Day process was missed or ended abnormally?&#x20;

Administrators can detect incomplete closing operations using the Abnormal End Day Report:&#x20;

1. Go to Front Desk > Report > Day Shift.&#x20;
2. Select Abnormal End Day Report.&#x20;
3. Review the records showing incomplete closings: &#x20;
4. Business date: Affected business date.&#x20;
5. Workday start date & User who started the workday.&#x20;
6. Seller Name.&#x20;
7. Workday end date & User who ended the workday.&#x20;

<figure><img src="../../.gitbook/assets/image (187).png" alt=""><figcaption></figcaption></figure>

## 14. How do I track cash audit activities, float amounts, and cash shortages or excess amounts?&#x20;

To verify cash movements and audit records during a shift:&#x20;

1. Go to Front Desk > Report > Day Shift.&#x20;
2. Select Cash Audit Report.&#x20;
3. Review the audit details: Audit ID, User, Audit time, Audit value, Cash sales, Float amount, Cash in, Cash out, and Cash difference.&#x20;

<figure><img src="../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

## 15. How do I view a quick financial overview of net sales, taxes, discounts, and table averages?&#x20;

For a high-level summary of restaurant performance without granular line items:&#x20;

1. Go to Front Desk > Report > Day Shift.&#x20;
2. Select Day Summary.&#x20;
3. Review the high-level financial indicators: Total net sales, Total taxes, Total discounts, Total sales, Average sales per table, Division summary, Media summary, Tax summary, and Discount summary.&#x20;

<figure><img src="../../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>

## 16. How do I review individual ticket billing details, guest counts, and payment status?&#x20;

To inspect completed transactions for a specific business period:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Ticket under Report Categories.&#x20;
3. Select Tickets Report.&#x20;
4. Review the ticket fields: Ticket Number, Invoice Number, Date and Time, User, Entity (branch), Guest Count, Subtotal, Tax, Discount, Grand Total, and Payment Status.&#x20;

<figure><img src="../../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>

## 17. How do I track customized order tags and tagged item pricing on customer tickets?&#x20;

To review order customizations and special requests placed on customer tickets:&#x20;

1. Go to Front Desk > Report > Ticket.&#x20;
2. Select Tickets Tag Detail Report.&#x20;
3. Review the detailed order modification fields: Ticket Number, Order Tag Group, Order Tag, Tagged Item, Quantity, Price, and User.&#x20;

<figure><img src="../../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

Note: To view overall revenue generated by specific tags across all orders, select Ticket Tag Sales Report instead.&#x20;

## 18. How do I audit voided menu items, void amounts, and void reasons?&#x20;

To investigate removed items or cancelled sales for employee accountability:&#x20;

1. Go to Front Desk > Report > Ticket.&#x20;
2. Select Void Report.&#x20;
3. Examine the void audit fields: &#x20;
4. Ticket Number: Original sales ticket.&#x20;
5. Menu Item: Item removed from the order.&#x20;
6. Quantity: Number of items voided.&#x20;
7. Void Amount: Value of the voided items.&#x20;
8. Void Reason: Explanation entered during the void operation.&#x20;
9. User: Staff member who performed the void.&#x20;

<figure><img src="../../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

## 19. How do I track refunded ticket transactions, refund numbers, and refund reasons?&#x20;

To audit customer refunds and verify financial accuracy:&#x20;

1. Go to Front Desk > Report > Ticket.&#x20;
2. Select Refund Report.&#x20;
3. Inspect the refund columns: Refund Number, Ticket Number, Invoice Number, Refund Amount, Refund Reason, and User.&#x20;

<figure><img src="../../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure>

## 20. How do I audit item-level or ticket-level discounts applied during billing?&#x20;

To verify discount authorizations and review promotional usage:&#x20;

1. Go to Front Desk > Report > Ticket.&#x20;
2. Select Detail Discount Report.&#x20;
3. Review the fields: Ticket Number, Invoice Number, Discount Name, Discount Amount, Date and Time, and User.&#x20;

<figure><img src="../../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

## 21. How do I reconcile sales collections across Cash, Card, and Digital Wallet payment methods?&#x20;

To review payment method distribution and verify tender collections:&#x20;

1. Go to Front Desk > Report > Ticket.&#x20;
2. Select Tender Report.&#x20;
3. Review the breakdown: &#x20;
4. Payment Method: Cash, Card, Digital Wallet, etc.&#x20;
5. Transaction Count: Total orders paid via the method.&#x20;
6. Amount Received: Total currency collected.&#x20;
7. User: Cashier who processed the collection.&#x20;

<figure><img src="../../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>

## 22. How do I verify exchanged menu items and price difference amounts?&#x20;

To inspect transactions where orders were modified or items were exchanged:&#x20;

1. Go to Front Desk > Report > Ticket.&#x20;
2. Select Exchange Report.&#x20;
3. Review the transaction fields: Ticket Number, Original Item, Exchanged Item, Difference Amount (additional payment or refund required), and User.&#x20;

<figure><img src="/broken/files/wuBD4lxQKxkufjQjd7KF" alt=""><figcaption></figcaption></figure>

## 23. How do I view graphical charts for the Top 10 Profitable Items and Top 10 Sold Items?&#x20;

To generate visual charts showing top-performing products:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Item under Report Categories.&#x20;
3. Select Items Sales Report.&#x20;
4. Click the Chart icon/screen element.&#x20;
5. Choose between: &#x20;
6. Top 10 Profitable Items: Displays menu items generating the highest profit.&#x20;
7. Top 10 Sold Items: Displays menu items with the highest sales volume.&#x20;

<figure><img src="/broken/files/Dx0lBt5CbKsxiXmG3pBc" alt=""><figcaption></figcaption></figure>

## 24. How do I compare sales performance and profitability across different item portion sizes?&#x20;

To evaluate whether small, medium, or large portion sizes drive higher profits:&#x20;

1. Go to Front Desk > Report > Item.&#x20;
2. Select Items Portion Sales Report.&#x20;
3. Review portion metrics: Alias code, Menu item name, Portion, Quantity sold, Price excluding tax, Sales amount excluding tax, Tax amount, Sales amount including tax, Cost, Total cost, Profit, and User.&#x20;

<figure><img src="/broken/files/sS7yU1FLFFBQkXALtnKx" alt=""><figcaption></figcaption></figure>

&#x20;

## 25. How do I analyze item sales and profitability grouped by menu category?&#x20;

To evaluate the revenue and cost structure of individual menu sections (such as Appetizers or Beverages):&#x20;

1. Go to Front Desk > Report > Item.&#x20;
2. Select Item Sales by Category Report.&#x20;
3. Review the fields: Category, Alias code, Menu item name, Portion, Quantity sold, Sales amount excluding tax, Tax amount, Sales amount including tax, Cost, Total cost, and Profit.&#x20;

<figure><img src="../../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>

## 26. How do I identify peak business hours based on hourly item sales activity?&#x20;

To optimize kitchen prep and staff scheduling based on customer demand throughout the day:&#x20;

1. Go to Front Desk > Report > Item.&#x20;
2. Select Items Hourly Sales Report.&#x20;
3. Set the business date under Filter by Date.&#x20;
4. Review hourly sales trends and transaction volumes across operating hours.&#x20;

<figure><img src="../../.gitbook/assets/image (365).png" alt=""><figcaption></figcaption></figure>

## 27. How do I evaluate employee sales performance and profitability by user?&#x20;

To review sales volume and profit margins generated by individual servers or cashiers:&#x20;

1. Go to Front Desk > Report > Item.&#x20;
2. Select Items User Sales Report.&#x20;
3. Review the fields grouped by user: User, Alias code, Menu item name, Portion, Quantity sold, Sales amount excluding tax, Tax amount, Sales amount including tax, Cost, Total cost, and Profit.&#x20;

<figure><img src="../../.gitbook/assets/image (366).png" alt=""><figcaption></figcaption></figure>

## 28. How do I monitor the sales performance of bundled combo items and sub-items?&#x20;

To analyze popular meal combos and track individual items sold inside combo packages:&#x20;

1. Go to Front Desk > Report > Item.&#x20;
2. Select Combo Sales Report.&#x20;
3. Review the combo breakdown fields: Combo name, Combo group, Sub-item name, Quantity, Sub-item quantity, Price, and Total.&#x20;

<figure><img src="../../.gitbook/assets/image (367).png" alt=""><figcaption></figcaption></figure>

## 29. How do I compare total sales quantity and revenue across menu categories?&#x20;

To evaluate high-level category performance using Group reports:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Group under Report Categories.&#x20;
3. Select Items Category Sales Report.&#x20;
4. Review the category fields: &#x20;
5. Product (Category): Menu category or product group.&#x20;
6. Quantity: Total units sold in the category.&#x20;
7. Amount: Total revenue generated by the category.&#x20;

<figure><img src="../../.gitbook/assets/image (368).png" alt=""><figcaption></figcaption></figure>

## 30. How do I monitor sales generated through tagged menu items?&#x20;

To track sales performance for products classified under specific custom tags:&#x20;

1. Go to Front Desk > Report > Group.&#x20;
2. Select Items Tag Sales Report.&#x20;
3. Review the tagged item fields: Product (tagged item name), Quantity (units sold), and Amount (total sales value).&#x20;

<figure><img src="../../.gitbook/assets/image (369).png" alt=""><figcaption></figcaption></figure>

## 31. How do I track ticket activity, invoice numbers, and payment status for specific tables?&#x20;

To monitor table utilization and order settlement in dine-in service:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Entity under Report Categories.&#x20;
3. Select Ticket Table Report.&#x20;
4. Review table transaction details: ID, Ticket Number, Invoice No, Total, Table, Paid (indicates settled vs. pending status), User, Created Date, and Time.&#x20;

<figure><img src="../../.gitbook/assets/image (370).png" alt=""><figcaption></figcaption></figure>

## 32. How do I review individual member purchase history, tax, and transaction times?&#x20;

To verify member transactions or support customer service inquiries:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Member under Report Categories.&#x20;
3. Select Member Report.&#x20;
4. Review the transaction fields: Member (code), Name (member name), ID, Ticket Number, Date, Time, Tax, and Amount.&#x20;

<figure><img src="../../.gitbook/assets/image (371).png" alt=""><figcaption></figcaption></figure>

## 33. How do I track unpaid or partially settled member tickets and remaining balances?&#x20;

To monitor outstanding customer dues and follow up on pending payments:&#x20;

1. Go to Front Desk > Report > Member.&#x20;
2. To view ticket-by-ticket details: Select Member Open Tickets Report and review Member, Name, Ticket Number, Date, Time, Tax, Amount, and Remaining.&#x20;

<figure><img src="../../.gitbook/assets/image (372).png" alt=""><figcaption></figcaption></figure>

3. To view consolidated balances per member: Select Member Summary Open Report and review Entity, Name, Ticket Count, Total, and Remaining.&#x20;

<figure><img src="../../.gitbook/assets/image (373).png" alt=""><figcaption></figcaption></figure>

## 34. How do I compare payment collections and digital payment trends across POS terminals?&#x20;

To compare collection totals between different billing counters or hardware terminals:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Summary under Report Categories.&#x20;
3. Select Payment Summary by Terminal Report.&#x20;
4. Review terminal collections: Terminal, Cash, Card, Digital Payment (UPI/wallets), and Total.&#x20;

## 35. How do I monitor kitchen preparation time, packing speed, and overall service duration?&#x20;

To analyze service efficiency and evaluate if orders meet service-level time targets:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Custom under Report Categories.&#x20;
3. Select Speed of Service Report.&#x20;
4. Review operational speed metrics: &#x20;
5. Department & POS: Processing area and terminal.&#x20;
6. Staff & Ticket Number: Responsible employee and order ticket.&#x20;
7. Date/Time: Order creation timestamp.&#x20;
8. Order Time: Kitchen preparation duration.&#x20;
9. Packing Time: Order packaging duration.&#x20;
10. Total Time: Total service duration from order to completion.&#x20;
11. Avg Server & Total Avg: Individual and overall service averages.&#x20;
12. Met %: Percentage of orders completed within target timeframes.&#x20;

<figure><img src="../../.gitbook/assets/image (374).png" alt=""><figcaption></figcaption></figure>

## 36. How do I track returned menu items, refund methods, and cashier details?&#x20;

Audit customer returns, verify refund amounts, and check return reasons using the Return Product Report:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Under Report Categories, select Custom.&#x20;
3. Under SELECT REPORT, select Return Product Report.&#x20;
4. Set the date range under Filter by Date.&#x20;
5. Review the return fields: &#x20;
6. Date/Time & Return Product Date: Timestamps of the return.&#x20;
7. Cashier & Return Product By: Staff who processed the return.&#x20;
8. Ticket Number: Original sales ticket.&#x20;
9. Customer Name: Customer requesting the return.&#x20;
10. Menu Code & Menu Name: Item returned.&#x20;
11. Quantity & Amount: Returned quantity and total refunded value.&#x20;
12. Payment Type & Refund Type: Original payment method and refund method used.&#x20;
13. Reason & Detail: Explanation for the product return.&#x20;

<figure><img src="../../.gitbook/assets/image (375).png" alt=""><figcaption></figcaption></figure>

## 37. How do I review menu items that were marked as sold out during a shift?&#x20;

Track stock shortages and monitor inventory depletion using the Sold Out History Report:&#x20;

1. Go to Front Desk > Report > Custom.&#x20;
2. Select Sold Out History Report.&#x20;
3. Specify the reporting period under Filter by Date.&#x20;
4. Inspect the inventory update fields: &#x20;
5. Date & Time: When the item was marked sold out.&#x20;
6. Product & Portion: Menu item and serving size that became unavailable.&#x20;
7. Balance Qty: Remaining stock level before depletion.&#x20;
8. User: Employee who updated the product status.&#x20;
9. Action: Specific activity performed (such as marking or restoring product availability).&#x20;

![](<../../.gitbook/assets/image (384).png>)&#x20;

## 38. How do I track unpaid ticket balances consolidated by customer name across entities?&#x20;

Review consolidated open balances and total pending dues per customer using the Member Summary Open Report:&#x20;

1. Go to Front Desk > Report > Member.&#x20;
2. Select Member Summary Open Report.&#x20;
3. Review the open summary fields: &#x20;
4. Entity: Business location or outlet.&#x20;
5. Name: Member's name.&#x20;
6. Ticket Count: Total open tickets pending for the member.&#x20;
7. Total: Combined original value of all open tickets.&#x20;
8. emaining: Unpaid balance requiring collection.&#x20;

<figure><img src="../../.gitbook/assets/image (383).png" alt=""><figcaption></figcaption></figure>

## 39. How do I analyze sales performance for items categorized by specific tag groups?&#x20;

Evaluate sales generated by custom item classifications using the Items Tag Sales Report:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Group under Report Categories.&#x20;
3. Select Items Tag Sales Report.&#x20;
4. Product: Tagged menu item name.&#x20;
5. Quantity: Total units sold for the tagged item.&#x20;
6. Amount: Total revenue generated by the tagged item.&#x20;

<figure><img src="../../.gitbook/assets/image (382).png" alt=""><figcaption></figcaption></figure>

## 40. How do I evaluate item sales and profit margins grouped by restaurant department?&#x20;

Compare revenue and cost structures across departments (e.g., Kitchen vs. Bar) using the Items Department Sales Report:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Item under Report Categories.&#x20;
3. Select Items Department Sales Report.&#x20;
4. Review the departmental metrics: Department, Alias code, Menu item name, Portion, Quantity sold, Price excluding tax, Sales amount excluding tax, Tax amount, Sales amount including tax, Cost, Total cost, and Profit.&#x20;

<figure><img src="../../.gitbook/assets/image (380).png" alt=""><figcaption></figcaption></figure>

## 41. How do I verify discounts applied at the item level versus order tag discount prices?&#x20;

Audit individual menu item discounts and order tag adjustments using the Items Discount Report:&#x20;

1. Go to Front Desk > Report > Item.&#x20;
2. Select Items Discount Report.&#x20;
3. Inspect discount details: Ticket number, Invoice number, Menu item name, Portion, Quantity, Unit price, Order tag price, Order tag discount price, Discount price, Price after discount, Entity, Date, and User.&#x20;

<figure><img src="../../.gitbook/assets/image (379).png" alt=""><figcaption></figcaption></figure>

## 42. How do I check sales trends across custom time intervals like weekly or monthly periods?&#x20;

Track long-term revenue trends over flexible time intervals using the Sales by Period Report:&#x20;

1. Go to Front Desk > Report > Summary.&#x20;
2. Select Sales by Period Report.&#x20;
3. Under Filter by Condition, choose your interval (such as hourly, daily, weekly, or monthly).&#x20;
4. Review period metrics: Period, Ticket Count, Pre Tax Total, Tax Total, Post Tax Total, and Total.&#x20;

## 43. How do I evaluate sales generated through specific marketing promotions or campaigns?&#x20;

Measure promotional effectiveness and sales driven by active campaigns using the Sales Promotion Report:&#x20;

1. Go to Front Desk > Report.&#x20;
2. Select Ticket under Report Categories.&#x20;
3. Select Sales Promotion Report.&#x20;
4. Review campaign fields: &#x20;
5. Promotion Name: Applied promotional campaign.&#x20;
6. Ticket Number: Order utilizing the promotion.&#x20;
7. Discount Value: Value discounted by the offer.&#x20;
8. Sales Amount: Final bill total after applying the promotion.&#x20;
9. User: Staff member who processed the promotional order.&#x20;

<figure><img src="../../.gitbook/assets/image (378).png" alt=""><figcaption></figcaption></figure>

## 44. How do I check terminal-wise daily sales totals, pre-tax amounts, and tax totals?&#x20;

Compare daily financial performance across individual billing stations using the Daily Terminal Sales Summary Report:&#x20;

1. Go to Front Desk > Report > Summary.&#x20;
2. Select Daily Terminal Sales Summary Report.&#x20;
3. Review terminal metrics per business date: &#x20;
4. Date: Reporting date.&#x20;
5. Ticket Count: Orders processed through the terminal.&#x20;
6. Pre Tax Total: Sales value before taxes.&#x20;
7. Tax Total: Total tax collected at the workstation.&#x20;
8. Post Tax Total: Billed amount after tax calculations.&#x20;
9. Total: Final sales total recorded for the terminal.&#x20;

<figure><img src="../../.gitbook/assets/image (377).png" alt=""><figcaption></figcaption></figure>
