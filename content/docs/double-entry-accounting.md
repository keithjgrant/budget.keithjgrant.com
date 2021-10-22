---
title: "Double-entry accounting"
weight: 4
---
# Double-entry accounting
My system is based on [double-entry accounting](https://en.wikipedia.org/wiki/Double-entry_bookkeeping) to track expenses.
This is a bookkeeping method used by accountants to keep accounts balanced, particularly for large companies.

To be clear, most accountants will suggest that double-entry accounting is overkill for a home budget.
That is why I have automated away most of the complexity, so **you don't have to understand double-entry accounting to use this spreadsheet** (thank goodness).

Instead of entering two records for an expense, for instance, you will [enter it once](/docs/usage/expense-entry), then select a budget category.
Behind the scenes, the spreadsheet will track the second entry for you.
I've done my best to balance usability with robust financial practice.

## Technical mumbo jumbo
If you are familiar with double-entry accounting and want to understand the details with proper technical jargon, here you go:

* Your "budget accounts" are treated as expense accounts
* Your "available funds" are your equity account
* "Uncleared expenses/income" are accounts payable/receivable

For a full snapshot, look at the _Ledger_ sheet to see how it all works.
Again, this is all generated automatically.
You don't have to worry about it — or even fully understand it — when using the spreadsheet.

![Ledger showing summary of all accounts, including debits, credits, and running balances](/images/ledger.png)
