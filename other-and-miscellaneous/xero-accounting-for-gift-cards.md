# Xero Accounting for Gift Cards

## Amazon Shopping Gift Cards

### Step 1 (One-off) – Create an "Amazon Gift Card" Account

1. In your Xero account, go to Accounting → Chart of accounts → Add Account.
2. In the Account set-up:

* Account Type: Current Asset
* Name: Amazon Gift Card
* Tax: No VAT
* (Optional) Description: "Prepaid Amazon gift card balance"
* Make sure to enable it as a payment account (so you can pay bills from it)
* Click **Save.**

<figure><img src="../.gitbook/assets/Screenshot 2026-02-18 at 22.00.09.png" alt=""><figcaption><p>Step 1 – Amazon Account set-up</p></figcaption></figure>

### Step 2 – Record the Amazon gift card as being received

1. Navigate to your Manual journals:
   1. Go to Reporting.
   2. Scroll down. Under Taxes and balances, click Journal Report.
   3. Select Go to manual journals.
2. Click New Journal.
3. Set the gift card amount you received. Add two lines (swap _£50_ for your actual gift card value):

* **Debit:** Amazon Gift Card (Current Asset) — _£50_ — Tax: No VAT
* **Credit:** Other Income / Incentives (or “Other Revenue”) — _£50_ — Tax: No VAT

4. Click **Post.**

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>Step 2 – Amazon gift card manual journal set-up</p></figcaption></figure>

### Step 3 – Each time you buy something off Amazon

**Enter the Amazon invoice as a Bill.**

1. Go to Purchases → Bills → New bill.
2. Set the following fields:

* From: Amazon
* Date: invoice/order date
* Due date: same day or as per invoice
* Amounts are: Tax Exclusive (typical for VAT-registered businesses).

3. **Add line items and code each to the correct category**

* Example:
  * "Printer paper and stationary" → Office Equipment
  * "Wireless keyboard" → Computer Equipment
* Set the VAT rate to match the invoice (e.g., 20% VAT on Expenses) if you are VAT registered.

4. **Approve** the bill.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Step 3 – Enter the Amazon invoice as a bill</p></figcaption></figure>

### Step 4 – Paying the bill

#### If the order total is less than or equal to the gift card balance

* On the bill, use **Make a payment**
* Paid from: Amazon Gift Card (that you set up in Step 1).
* Amount: full invoice total
* Click **Add Payment.**

#### If the order total is greater than the gift card balance

You will need to crate **two payments:**

* First payment:
  * Paid from: Amazon Gift Card
  * Amount: remaining gift card balance (e.g., £50).
  * Click **Add Payment.**
* Second payment:
  * Paid from: Bank account / card account
  * Amount: remaining balance (e.g., invoice total minus £50).
  * Click **Add Payment.**

Result: The bill is fully paid, and Xero shows exactly how much was settled by gift card vs bank.

> **Notice:** If you don't see Amazon Gift Card as a Paid from option, you may have forgotten to select Enable payments to this account in Step 1.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>Adding second payment</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2026-02-18 at 23.18.52.png" alt=""><figcaption><p>Bill fully paid and accounted for</p></figcaption></figure>

### Notes (useful clarifications)

* **VAT:** Amazon invoices are VAT-inclusive in total, but you record them in Xero using net + VAT (if VAT registered). VAT is tied to the _goods purchased_, not the payment method.
* **No direct integration needed:** Amazon gift cards don’t provide a bank feed. The clean approach is treating the gift card as a prepaid balance (Current Asset) and coding each purchase normally.
* **If you receive an additional Amazon gift card** (e.g. by opening another Amazon Pot): simply post a new journal debiting the existing **Amazon Gift Card (Current Asset)** account and crediting Other Income for the voucher amount (do not create a new account) and then continue applying payments from that same gift card balance when recording future Amazon bills.
