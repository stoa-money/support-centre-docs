---
hidden: true
---

# Information (Side Panel) Architecture

## Pot Info

**\{{ description \}}** \[n]

*   **\{{ if(subscription) \}}** \[1]:&#x20;

    With this Pot, you can unlock a **\{{ name \}}** gift card by depositing the required amount into your Stoa account.

    * **\{{ if offers\[0].subtitle contains "month" \}}** For example, depositing **\{{ offers\[0].depositAmount \}}** unlocks a **\{{ name \}}** gift card worth **\{{ offers\[0].price \}}** — enough to cover 12 months of **\{{ offers\[0].title \}}** at **\{{ offers\[0].subtitle \}}**.
    * else: For example, depositing **\{{ offers\[0].depositAmount \}}** unlocks a **\{{ name \}}** gift card worth **\{{ offers\[0].price \}}** — enough to cover 12 months of **\{{ offers\[0].title \}}.**
*   **\{{ if(oneOff) \}}** \[1]:

    For every **\{{ offers\[0].price \}}** of gift card value, you'll need a **\{{ offers\[0].depositAmount \}}** deposit.\
    For example, a **\{{ offers\[0].price \}}** card requires **\{{ offers\[0].depositAmount \}}**, a **\{{ offers\[0].price \* 2 \}}** card requires **\{{ offers\[0].depositAmount \* 2 \}}**, and so on. The maximum you can deposit is **\{{ switch(offers\[0].subtitle) \}}** for **\{{ switch(offers\[0].subtitle) \}}** worth of credit (note that this may be distributed to you in multiple cards).

Your deposit is held securely for **12 months**.\
Thirty days before your Pot is due to mature, you’ll have two options:

* **Renew** for another 12-month term (you may need to adjust your deposit amount based on the latest Perk value), or
* **Withdraw** your deposit once the 12-month term has elapsed.

## Redemption Instructions

**\{{ redemptionInfo \}}** \[n]

## Terms & Conditions

Please see [here](https://app.stoa.money/terms-and-conditions) for the Stoa Pots Terms & Conditions.

### Gift Card Terms & Conditions

**\{{ mechantTermsAndConditions \}}** \[n]

## Notes

**Netflix example for Pot Info:**\
[**Netflix**](https://www.netflix.com) is one of the world’s leading streaming services, offering unlimited movies, TV shows, and original content across every genre — ready to watch anytime, anywhere.

With this Pot, you can unlock a **Netflix** gift card by depositing the required amount into your Stoa account. For example, depositing £3,000 unlocks a Netflix gift card worth £155.88 – enough to cover 12 months of Netflix Standard at £12.99/month.

**Variations for switch (in Pot Info for One Off Perks):**

* If subtitle contains "£50,000": The maximum you can deposit is £1m for £50k worth of credit (note that this may be distributed to you in multiple cards).
* If subtitle contains "£20,000": The maximum you can deposit is £400k for £20k worth of credit (note that this may be distributed to you in multiple cards).
* If subtitle contains "£10,000": The maximum you can deposit is £200k for £10k worth of credit (note that this may be distributed to you in multiple cards).

## \[VERSION 2]

## Pot Info Placeholder – Subscription Perks

With this Pot, you can unlock a **{merchantName}** subscription by depositing the required amount into your Stoa account.\
For example, by making the specified deposit, you’ll receive a 12-month subscription to {merchantName}, giving you uninterrupted access to all included benefits for the full term.

Your deposit is held securely for 12 months.\
Thirty days before your Pot is due to mature, you’ll have two options:

* **Renew** for another 12-month term (you may need to adjust your deposit amount based on the latest Perk value), or
* **Withdraw** your deposit once the 12-month term has elapsed.

## Pot Info Placeholder – One Off Perks

With this Pot, you can unlock **{merchantName}** gift cards by depositing the required amount into your Stoa account.

For every £50 of gift card value, you'll need a £1,000 deposit.\
For example, a £50 card requires £1,000, a £100 card requires £2,000, and so on. The maximum you can deposit is **{maxDeposit}** for **{maxPerkValue}** worth of credit (may be distributed to you in multiple cards).

Your deposit is held securely for 12 months.\
Thirty days before your Pot is due to mature, you’ll have two options:

* **Renew** for another 12-month term (you may need to adjust your deposit amount based on the latest Perk value), or
* **Withdraw** your deposit once the 12-month term has elapsed.

## Redemption Instructions Placeholder – Brand Perks

You will receive an email from Stoa containing your **{merchantName}** gift code or subscription link. Simply follow the step-by-step instructions provided to redeem your Perk. Our support team is available 8am - 11pm, Monday to Sunday, to be on hand to help.

Your **{merchantName}** Perk can only be redeemed through the official website or app. It cannot be exchanged, resold, or redeemed for cash.

## Redemption Instructions Placeholder – Apple-enabled Perks

We make this Perk available to you using Apple gift card credit. Simply redeem the credit to your Apple account and subscribe to the relevant plan from your Apple device.

For reference, please see the instructions provided by Apple [here](https://support.apple.com/en-gb/118242?device-type=iphone).

1. **Redeem the Apple gift card:**
   1. Open the **App Store** on iPhone or iPad.
   2. Tap your profile picture (top right).
   3. Tap **“Redeem Gift Card or Code”**.
   4. Enter the code. The balance is now added to your Apple ID account.
2. **Check that your Apple ID balance is visible:**
   1. In the App Store → tap profile → the **Apple ID balance** should now show under your name.
   2. This balance is what Apple uses first for app purchases and subscriptions.
3. **Start or renew your subscription:**
   1. Go to the **{merchantName}** app → select the relevant subscription plan.
   2. Confirm with Face ID / Touch ID.

If you are an existing user on the web, then you will need to cancel your membership and sign up from your Apple device once your current plan expires (don't worry though - this should cause minimal service interruption since you can resume your plan the moment it expires).

If you are an existing user and signed up on your Apple device, simply redeem your Apple gift card, and payments will be drawn down from your Apple account balance.

#### How payment is applied

* Apple will always **use Apple ID balance first**.
* If your balance covers the full subscription cost, **no card is charged**.
* If your balance is not enough, Apple will charge the **remaining amount** to your backup payment method (for Apple devices, you will always need to choose a backup payment method).

For additional information, please refer to the relevant section in our Support Centre [here](redeeming-apple-and-google-play-enabled-perks.md#how-to-use-an-apple-gift-card-to-redeem-your-perk). Additionally, our support team is available 8am - 11pm, Monday to Sunday, to be on hand to help.

## Redemption Instructions Placeholder – Google-enabled Perks

We make this Perk available to you using Google Play gift card credit. Simply redeem the credit to your Google Play account and subscribe to the relevant plan from your Android device.

For the best redemption experience, we recommend that you redeem in the checkout of the **{merchantName}** app. We have included photo instructions of how to do this [here](redeeming-apple-and-google-play-enabled-perks.md#option-1-recommended-redeem-your-google-play-gift-card-in-the-checkout-of-your-chosen-perk).

If you are an existing user on the web, then you will need to cancel your membership and sign up from your Android device once your current plan expires (don't worry though - this should cause minimal service interruption since you can resume your plan the moment it expires).

If you are an existing user and signed up on your Android device, simply redeem your Google Play gift card, and update your preferred payment method to Google Play balance.

For additional information, please refer to the relevant section in our Support Centre [here](redeeming-apple-and-google-play-enabled-perks.md#how-to-use-a-google-play-gift-card-to-redeem-your-perk). Additionally, our support team is available 8am - 11pm, Monday to Sunday, to be on hand to help.
