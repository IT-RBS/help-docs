# Troubleshooting

The following table lists common issues that may occur while using the Workday module and the recommended actions to resolve them.

| **Issue**                                               | **Possible Cause**                                                                  | **Resolution**                                                                                                                |
| ------------------------------------------------------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Unable to start the Workday                             | A Workday is already active or you do not have the required permissions.            | Verify that no active Workday exists for the current business date. If the issue persists, contact your system administrator. |
| Unable to start a Work Shift                            | The Workday has not been started.                                                   | Start the Workday before attempting to start a Work Shift.                                                                    |
| Unable to start a Work Shift                            | A Work Shift is already active for the current terminal.                            | Verify the current Work Shift status before starting a new Work Shift.                                                        |
| Unable to end a Work Shift                              | Closing payment amounts have not been entered.                                      | Enter the required closing amounts for all applicable payment methods and try again.                                          |
| Unable to end the Workday                               | One or more Work Shifts are still active.                                           | End all active Work Shifts before ending the Workday.                                                                         |
| Unable to end the Workday                               | One or more customer tickets remain open.                                           | Close or resolve all open tickets before ending the Workday, or enable Pre Order mode if open tickets need to remain active.  |
| Changes from Dine Connect are not reflected in the POS. | The latest configuration has not been synchronized.                                 | Use the Pull command to retrieve the latest data from Dine Connect.                                                           |
| Transactions are not synchronized with Dine Connect.    | A temporary network or communication issue has prevented automatic synchronization. | Verify the network connection and use the Push command to manually synchronize pending transactions.                          |
| Transactions are not recorded in reports.               | The POS terminal is operating in Training Mode.                                     | Disable Training Mode before processing live customer transactions.                                                           |

## **Notes** <a href="#notes" id="notes"></a>

* Start the Workday before starting a Work Shift.
* Start a Work Shift on every POS terminal that accepts customer payments.
* Enter the correct Opening Cash amount before starting a Work Shift.
* Verify the Closing Amounts before ending a Work Shift.
* End all active Work Shifts before ending the Workday.
* Resolve all open tickets before ending the Workday, unless Pre Order is enabled.
* Use Training Mode only for practice. Transactions performed in Training Mode are not synchronized with the server.
* Use Push to manually synchronize pending transactions if automatic synchronization fails.
* Use Pull to retrieve the latest menu, pricing, and configuration updates from Dine Connect.
* Use Refresh to display the latest Workday information after completing an operation.
* Use Reset to restore the selected business date to the current business date.
* Print Workday or Work Shift reports for reconciliation, auditing, or record-keeping purposes.
