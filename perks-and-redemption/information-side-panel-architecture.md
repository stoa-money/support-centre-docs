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
