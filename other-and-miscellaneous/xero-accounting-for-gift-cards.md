# Xero Accounting for Gift Cards

## Amazon Shopping Gift Cards

### Overview

**Conceptually:**\
An Amazon gift card is treated as a **prepaid asset** in Xero.

* When you receive the gift card, you increase a prepaid balance.
* When you purchase items from Amazon, you record the full invoice and apply the gift card as a payment method.
* The accounting category is determined by what you buy – not by the gift card.

### Step 1 (One-off) – Create an "Amazon Gift Card" Account

1. In your Xero account, go to Accounting → Chart of accounts → Add Account.
2. In the Account set-up:

* Account Type: Current Asset
* Name: Amazon Gift Card
* Tax: No VAT
* (Optional) Description: "Prepaid Amazon gift card balance"
* Tick **Enable payments to this account** so you can select it when recording bill payments
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

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Step 2 – Amazon gift card manual journal set-up</p></figcaption></figure>

This increases your Amazon Gift Card balance in Xero and recognises the incentive income.

> **Notice:** Alternatively, instead of posting a manual journal, you can record the voucher using a negative bill and then apply payment into the existing **Amazon Gift Card (Current Asset)** account. See [Step 2 Alternative](xero-accounting-for-gift-cards.md#step-2-alternative-record-the-amazon-gift-card-using-a-bill-instead-of-a-manual-journal) below for full instructions.

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

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption><p>Step 3 – Enter the Amazon invoice as a bill</p></figcaption></figure>

### Step 4 – Paying the bill

#### If the order total is less than or equal to the gift card balance

* On the bill, use **Make a payment**
* Paid from: Amazon Gift Card (that you set up in Step 1).
* Amount: full invoice total
* Click **Add Payment.**

#### If the order total is greater than the gift card balance

You will need to create **two payments:**

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

* **VAT:** Amazon invoices display a VAT-inclusive total, but in Xero (if VAT registered) you enter the net amount and apply the appropriate VAT rate so Xero calculates the VAT separately. VAT relates to the goods purchased, not the payment method used.
* **No direct integration needed:** Amazon gift cards don’t provide a bank feed. The clean approach is treating the gift card as a prepaid balance (Current Asset) and coding each purchase normally.
* **If you receive an additional Amazon gift card** (e.g. by opening another Amazon Pot): simply post a new journal debiting the existing **Amazon Gift Card (Current Asset)** account and crediting Other Income for the voucher amount (do not create a new account) and then continue applying payments from that same gift card balance when recording future Amazon bills.
  * I.e., do Step 2 each time you receive an Amazon gift card (as a result of you opening a new Amazon Pot).
  * Do Steps 3 and 4 each time you buy something off Amazon.
* If you are **not VAT registered**, simply enter the full invoice total and select **No VAT** – you will not separate net and VAT.

### Example #2 for entering Amazon invoice data

Given the below example:

<figure><img src="../.gitbook/assets/WhatsApp Image 2026-01-21 at 20.28.53.jpeg" alt=""><figcaption></figcaption></figure>

You would enter the fields when creating a Bill like so:

* From: Amazon
* Date: 3 January 2026
* Due date: 3 January 2026
* Line Item:
  * Description: Wireless keyboard, for e.g.
  * Qty: 1.00
  * Amount: £29.82
  * Account: 720 - Computer Equipment
  * Tax rate: 20% (VAT on Expenses), _should auto-populate_

### Step 2 Alternative: Record the Amazon gift card using a Bill (instead of a Manual Journal)

1. **Create (or use) an “Incentives / Rewards” income account**

* Go to Accounting → Chart of accounts
* Ensure you have a Revenue account such as **Other Income – Incentives** (No VAT)

2. **Create a new Bill**

* Go to Purchases → Bills to pay → New Bill
* **From:** create a contact like `Stoa Incentive` (or `Stoa Rewards`)
* **Date:** voucher received date
* **Due date:** same day (or any valid date)

3. **Add a negative line item to recognise the voucher**

* **Description:** “Amazon voucher received”
* **Account:** **Other Income – Incentives**
* **Amount:** -£50.00 (swap £50 for your gift card value – enter as a negative number)
* **Tax rate:** No VAT
* Ensure the bill total shows **-£50.00**

4. **Approve the Bill**

* Click **Approve**

5. **“Pay” the Bill into the Amazon Gift Card account (to increase the balance)**

* On the approved bill, click **Make a payment**
* **Paid from:** Amazon Gift Card (Current Asset)
* **Amount:** £50.00 (similarly, make sure it matches your gift card value).
* **Add Payment**

✅ Result: the **Amazon Gift Card account balance increases by £50**, and the income is recorded to **Other Income – Incentives**, without needing a manual journal.
