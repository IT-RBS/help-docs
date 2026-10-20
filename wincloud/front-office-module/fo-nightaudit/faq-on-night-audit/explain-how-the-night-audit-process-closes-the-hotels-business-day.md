# Explain how the Night Audit process closes the hotel's business day ?

The Night Audit process is the essential transition that **closes the current account date and opens a new one**, ensuring all financial activity for the day is finalized and accurate. Because the system prevents any modifications or postings to a date once it is closed, the process involves rigorous verification steps.

1. **Mandatory Pre-Audit Verification**

Before the audit can be executed, the system requires several checks to ensure data integrity:

* **Guest & Registration Audit:** Staff must verify that all expected arrivals have been checked in and assigned registration numbers.
* **Financial Accuracy:** Room tariffs and rate codes for all in-house guests must be reviewed for errors. Additionally, all settled and voided bills from all outlets must be cross-referenced with system reports.
* **Revenue Posting:** All miscellaneous revenues, such as telephone calls or room service, must be properly posted to guest ledgers.
* **Final Tariff Posting:** The **"Post Tariff All"** function must be run to charge the night's room rates to all in-house guests. This can only be performed after **10:00 PM**.

2. **Clearing "Pending Jobs"**

The system will block the Night Audit if specific "jobs" remain incomplete. These common blockers include:

* **Overdue Departures:** Guests scheduled to leave today who have not yet checked out or extended their stay.
* **Unpaid Bills:** Final bills that were generated for checked-out guests but never settled.
* **Pending KOTs & Bills:** Unresolved Kitchen Order Tickets or unsettled bills in the Restaurant or Room Service outlets.

3. **Executing the Audit**

Once the **Night Audit Checklist** shows no pending jobs, the audit can be started (typically after **23:59**) through the following steps:

* **Create Night Balance:** This consolidates the day's financial data.
* **Open New Day:** The user enters and confirms the new accounting date.
* **Finalize:** The system creates the new business day and provides an alert upon successful completion.

4. **Post-Audit Activities**

Immediately following the audit, the system generates the **Night Audit Report**, which provides a detailed breakdown of revenues, collections, and City Ledger settlements for the day, month-to-date, and year-to-date. Finally, the **NA GL Posting** option is used to transfer the audited revenue figures to the General Ledger.

<figure><img src="../../../.gitbook/assets/image (1065).png" alt=""><figcaption></figcaption></figure>
