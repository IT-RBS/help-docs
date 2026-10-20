# FAQ's

## 1. What is the complete step-by-step payment flow in DinePlan POS?

The complete payment workflow follows a structured sequence from table selection to final bill settlement.

**To execute the complete payment flow:**

1. Select the required **"Table"** from the POS table screen.
2. Select **"Print Bill"** to generate the guest bill.
3. Allow the customer to review and confirm the bill details.
4. Select the same **"Table"** again after customer confirmation.
5. Select the required bill to proceed to the Payment page.
6. Select **"Pay"** to open the Payment screen.
7. Select the required payment option (**All**, **Split**, **1/n**, or **Settle**).
8. Select the required **Payment Method** (e.g., Cash, Nets, Visa, or Master).
9. Verify all payment details, items, amounts, and change.
10. Complete the payment and verify that the bill is settled.

Refer this link - [Workflow](./#complete-payment-flow)

**Note:** Always allow the customer to review and confirm the bill before finalizing payment.

## 2. What prerequisites must be met before starting the payment process?

Before initiating the payment process in DinePlan POS, several preliminary order conditions must be verified.

**Prerequisites checklist:**

* The customer order is created in the system.
* All required items and item quantities are verified.
* Any required order modifications or changes are completed.
* The order total amount is reviewed for accuracy.
* The customer is ready to review and settle the bill.

<figure><img src="../../.gitbook/assets/image (255).png" alt=""><figcaption></figcaption></figure>

## 3. How do I print the customer bill for verification before taking payment?

Printing the bill allows the customer to review and confirm all items and charges prior to payment.

**To print the bill:**

1. From the POS table screen, select the required **"Table"**.
2. Select **"Print Bill"**.
3. The bill prints automatically for the customer to review.
4. Hand the printed bill to the customer for verification and confirmation.

<figure><img src="../../.gitbook/assets/image (256).png" alt=""><figcaption></figcaption></figure>

## 4. What does a Brown table color mean on the POS screen, and what action should I take next?

Table status is visually tracked using status colors on the POS table screen.

**Table color meaning and workflow:**

* A **Brown** table color indicates that **"Print Bill"** has been executed and the bill is printed and ready for payment.
* Once the customer confirms the bill, tap the **Brown** table.
* Select the required bill to transition directly to the Payment page.

<figure><img src="../../.gitbook/assets/image (257).png" alt=""><figcaption></figcaption></figure>

**Note:** The table color automatically changes to **Brown** after selecting **"Print Bill"**.

## 5. How do I process a complete payment in full using a single payment method?

Use the **"All"** payment option when a customer pays the entire bill balance using one payment method.

**To process payment in full:**

1. From the Payment page, select **"All"**.
2. Select the required payment method under **Payment Method** (e.g., Cash, Nets, Visa, or Master).
3. Enter the amount received using the **Number Pad**, if required.
4. Verify the payment amount and change, if applicable.
5. Complete the payment.
6. Verify that the payment is recorded successfully and the bill status is settled.

<figure><img src="../../.gitbook/assets/image (258).png" alt=""><figcaption></figcaption></figure>

## 6. How do I split a payment between cash and card when a customer wants to pay using different payment methods?

Use **"Split"** when a customer pays the bill using different amounts or multiple payment methods.

**To perform a split payment:**

1. On the Payment page, enter the first amount to be paid using the **Number Pad**.
2. Select **"Split"**.
3. Verify that the entered amount appears in the **Total Amount** field.
4. Select the required payment method for this first partial amount.
5. Complete the payment for the first portion.
6. Repeat the steps for the remaining balance using the required second payment method.
7. Continue until the full bill is settled.

<figure><img src="../../.gitbook/assets/image (259).png" alt=""><figcaption></figcaption></figure>

**Note:** For example, on a bill of 279.08, the customer can pay 100.00 in cash and the remaining 179.08 by card.

## 7. How do I correct an incorrect amount entered during a split payment?

If an wrong tender amount is entered or selected while configuring a split payment, the amount can be reset.

**To correct a split amount:**

1. Select **"Split"** again.
2. The selected amount is reset automatically.
3. Enter the correct amount using the **Number Pad**.
4. Continue with the payment process.

<figure><img src="../../.gitbook/assets/image (260).png" alt=""><figcaption></figcaption></figure>

## 8. How do I divide a bill equally among multiple customers using the 1/n option?

Use **"1/n"** when a group of guests wants to divide the total bill into equal payment shares.

**To divide a bill equally:**

1. Enter the total number of customers (**n**) using the **Number Pad**.
2. Select **"1/n"**.
3. Review the calculated share amount displayed for each customer.
4. Select the required payment method.
5. Complete the payment for each customer share sequentially.

<figure><img src="../../.gitbook/assets/image (261).png" alt=""><figcaption></figcaption></figure>

## 9. What does 'n' represent in the 1/n payment option, and how is an equal bill calculated?

In DinePlan POS, **n** represents the total number of customers sharing the bill.

**Calculation rule and example:**

* The system divides the bill total by **n** to calculate an equal share per customer.
* **Example:** If the total bill is 120.96 and there are 6 customers (**n = 6**), entering **6** and selecting **"1/n"** divides the bill into 6 equal payments of 20.16.

<figure><img src="../../.gitbook/assets/image (262).png" alt=""><figcaption></figcaption></figure>

## 10. How do I process a payment for a single specific item instead of the entire order?

Use **"Settle"** from the Order page when a guest wants to pay for their individual item only.

**To pay for an individual item:**

1. From the Order page, select the specific item to be paid for.
2. Select **"Settle"**.
3. The Payment page is displayed.
4. Allow the customer to review and confirm the item bill.
5. Select **"All"**.
6. Select the required payment mode on the right.
7. Verify the payment amount.
8. Complete the payment.
9. If remaining items exist on the order, repeat the process for remaining items or balances.

<figure><img src="../../.gitbook/assets/image (263).png" alt=""><figcaption></figcaption></figure>

## 11. How do I settle payment for a specific quantity of similar items (for example, 1 coffee out of 3)?

Use quantity adjustment controls when a guest pays for a portion of identical ordered items.

**To pay for similar items:**

1. On the Order page, select the required item.
2. Select **"(-)"** or **"(+)"** to decrease or increase the item quantity.
3. Continue adjusting until the exact quantity to be paid is displayed.
4. Select **"Settle"**.
5. The Payment page is displayed.
6. Allow the customer to review and confirm the bill.
7. Select **"All"**.
8. Select the required payment mode on the right.
9. Verify the payment amount and complete the payment.

<figure><img src="../../.gitbook/assets/image (264).png" alt=""><figcaption></figcaption></figure>

**Note:** For example, if an order contains 3 coffees and the customer wants to pay for only 1 coffee, use **"(-)"** to adjust the quantity to 1 before selecting **"Settle"**.

## 12. How do I apply a percentage-based discount to a bill on the Payment page?

Use **"Discount %"** when applying a discount as a percentage of the total bill amount.

**To apply a percentage discount:**

1. On the Payment page, enter the required discount percentage using the **Number Pad**.
2. Select **"Discount %"**.
3. Verify the updated **Total Amount** displayed on screen.
4. Continue with the payment process.

<figure><img src="../../.gitbook/assets/image (265).png" alt=""><figcaption></figcaption></figure>

**Note:** For example, enter **50** and select **"Discount %"** to apply a 50% discount to the bill.

## 13. How do I apply a specific fixed dollar discount amount to a bill on the Payment page?

Use **"Discount"** when applying a discount as a specific currency value.

**To apply an amount discount:**

1. On the Payment page, enter the required discount amount using the **Number Pad**.
2. Select **"Discount"**.
3. Verify the updated **Total Amount** on screen.
4. Continue with the payment process.

<figure><img src="../../.gitbook/assets/image (266).png" alt=""><figcaption></figcaption></figure>

**Note:** For example, enter **50.00** and select **"Discount"** to apply a 50.00 discount.

## 14. What is the exact step-by-step procedure for handling cash payment receipts?

Cash transaction receipt distribution follows specific store verification and filing steps.

**To handle cash receipts:**

1. The first bill receipt prints automatically for verification.
2. Complete the cash payment and discard the verification copy.
3. Two official bill receipts are then printed by the system.
4. Place one bill receipt copy in the bill sleeve and hand it to the customer.
5. Place the second bill receipt copy in the designated merchant filing place.

## 15. What is the exact step-by-step procedure for handling credit card payment receipts?

Credit card transaction handling requires pairing card terminal slips with POS receipts.

**To handle credit card receipts:**

1. The first bill receipt prints for verification.
2. Complete the payment and discard the verification copy.
3. The POS printer and card terminal generate receipt copies.
4. Staple the customer POS receipt and customer card slip together.
5. Place the customer copies in the bill sleeve and hand them to the guest.
6. Staple the merchant POS receipt and merchant card slip together.
7. Place the merchant copies in the designated merchant storage location.
8. If a signature is required, place the card slip in the bill folder and pass it to the customer for signature.

## 16. How do I return to the POS Order page from the Payment page without completing the payment?

To exit the Payment page and revert back to the Order screen without processing a transaction:

**Steps:**

1. On the Payment page, select **"C"**.
2. Select **"Close"**.
3. The Order page is displayed.

<figure><img src="../../.gitbook/assets/image (267).png" alt=""><figcaption></figcaption></figure>

## 17. What information is displayed in the "Total Amount" screen element on the Payment page?

The **Total Amount** screen element displays the full balance due for the selected bill or transaction.

<figure><img src="../../.gitbook/assets/image (268).png" alt=""><figcaption></figcaption></figure>

## 18. What is the function of the "Tender Here" field on the Payment page?

The **Tender Here** field displays the exact numerical amount currently being entered or tendered for payment by the user.

<figure><img src="../../.gitbook/assets/image (277).png" alt=""><figcaption></figcaption></figure>

## 19. What does the "Amount" field display on the Payment page?

The **Amount** field displays the active payment amount currently selected for transaction settlement.

## 20. What is the purpose of the "All" button on the Payment page?

The **All** button selects the complete bill amount for payment in full in a single click.

## 21. What does the "Split" button on the Payment page do?

The **Split** button divides the payment total so the customer can pay different amounts using different payment methods.

## 22. What does the "1/n" button on the Payment page do?

The **1/n** button divides the total bill balance into equal shares based on the specified number of customers.

## 23. What function does the Number Pad serve on the Payment page?

The **Number Pad** allows cashiers to manually enter specific numerical values, tender amounts, guest counts, or discount figures.

<figure><img src="../../.gitbook/assets/image (276).png" alt=""><figcaption></figcaption></figure>

## 24. Which payment methods are displayed under Payment Method on the Payment page?

The **Payment Method** section displays available payment options configured for the restaurant, such as **Cash**, **Nets**, **Visa**, or **Master**.

<figure><img src="../../.gitbook/assets/image (275).png" alt=""><figcaption></figcaption></figure>

**Note:** Available payment methods depend on individual restaurant system configuration.

## 25. What is the difference between the "Discount %" and "Discount" buttons on the Payment page?

The two discount buttons handle different discount calculation types:

* **Discount %:** Calculates and applies a discount based on a percentage value entered.
* **Discount:** Applies a discount based on a specific dollar amount entered.

<figure><img src="../../.gitbook/assets/image (274).png" alt=""><figcaption></figcaption></figure>

## 26. What happens when I select "Cancel PAYMENTS" on the Payment page?

Selecting **"Cancel PAYMENTS"** cancels the active payment process currently in progress on the Payment page.

<figure><img src="../../.gitbook/assets/image (273).png" alt=""><figcaption></figcaption></figure>

## 27. How do I know if a bill has been settled and the payment recorded successfully?

After clicking to complete payment, check that the system confirms the payment has been recorded successfully and that the bill status updates to settled.

## 28. How do I adjust item quantities using the (-) or (+) buttons when paying for similar items?

When a customer wants to pay for a specific quantity of identical items on an order:

1. Highlight the item on the Order page.
2. Click **"(-)"** to decrease quantity or **"(+)"** to increase quantity.
3. Once the target quantity is displayed, click **"Settle"**.

<figure><img src="../../.gitbook/assets/image (272).png" alt=""><figcaption></figcaption></figure>

## 29. How do I reset a split amount entry if I enter the wrong tender amount?

If an incorrect tender amount is entered during a split payment:

1. Click **"Split"** again.
2. The selected amount resets automatically.
3. Type the correct amount and continue payment.

<figure><img src="../../.gitbook/assets/image (271).png" alt=""><figcaption></figcaption></figure>

## 30. Why might the available payment methods or options differ between different restaurant outlets?

The payment methods (such as Cash, Nets, Visa, Master) and payment options available on the Payment page depend directly on each restaurant's specific DinePlan system configuration.

<figure><img src="../../.gitbook/assets/image (270).png" alt=""><figcaption></figcaption></figure>
