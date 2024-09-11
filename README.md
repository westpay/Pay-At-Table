# Pay@Table
Pay@Table is PAaS module that runs on Westpay terminals that allows you accept payments at the table. This repo describes how this can be used and implemented

# What is Pay@Table?
Pay@Table is a module that runs on Westpay payment terminals.  It is intended for use with the C100 or C150 terminals that include WiFi and a printer.

Pay@Table is intended for use in a hospitality environment.  The terminal can be taken to a customer’s table for them to pay their bill.  The module offers:

- Waiter ID entry.
- Table listing and selection.
- Part or full payment.
- Payment by card or supported alternative payment methods (e.g. Swish)
- Bill splitting.
- Order summary at the point of payment for easy verification.
- Pro-forma printing.
- Table receipt printing for accounting purposes.
- Department and mode selection for restaurants with different areas and purposes, e.g. seating area vs bar vs takeaway queue.

Pay@Table does not work in isolation.  It requires a server that provides information on:

- Amount to pay
- Table status
- Order details

**_Westpay does not provide this server._**  It is the responsibility of integrators to develop a server for this purpose, and one purpose of this document is to make that easier to achieve.

---

## Read more about the protocol and how to implement this in our [Wiki](https://github.com/westpay/Pay-At-Table/wiki)
