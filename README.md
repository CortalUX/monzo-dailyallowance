# monzo-dailyallowance
This was an example of using Logic Apps in Microsoft Azure to give yourself a daily allowance, and automate saving.
This is no longer required with the Monzo Release of [salary sorter and bills pots](https://monzo.com/blog/2019/09/26/introducing-salary-sorter-and-bills-pots/).

## Setup

Monzo Daily Allowance is created with Microsoft Azure Logic Apps.

In order to set this up, you'll need:
 * A Monzo developer account
 * A Microsoft Azure subscription with developer credit
   * The ability to create logic apps
   * The ability to create custom connectors

## Security and Effects

Monzo Daily Allownace runs in Azure - the API only allows you to move money into/out of pots.

It is your responsibility to ensure that your budget is set correctly, to ensure that funds are available when Direct Debits are posted to your account, rather than being hidden in pots.

No support is provided.