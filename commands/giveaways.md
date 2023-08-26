---
description: A list of all the commands categorized under Giveaways
---

# 🎉 Giveaways

{% tabs %}
{% tab title="/giveaway" %}
## Description

> Start or manage a/the giveaways.

## Usage

To create a giveaway, you have to use the subcommand `/giveaway start duration:(Duration) winners:(Number) prize:(Prize) channel:[Channel (optionnal)]`

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-16 174730.png" alt=""><figcaption><p>You can use this command to create a giveaway (channel is optionnal).</p></figcaption></figure>

{% hint style="info" %}
You have to add the symbol of the time measure you're using (e.g. _1 seconds => 1s ; 1 minutes => 1m_).
{% endhint %}

The giveaway will then be sent.

In that case, the giveaway will have 1 random winner, will last 10 minutes and will be sent in the _**#giveaways**_ channel. The prize will be 1,000 R$.

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-16 175358.png" alt=""><figcaption><p>There will be 1 random winner, the giveaway will last 10 minutes, and the prize is 1,000 R$.</p></figcaption></figure>

After 10 minutes, a random winner will be chosen to win the prize!

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-16 175540.png" alt=""><figcaption><p>A random winner has been chosen.</p></figcaption></figure>

### Giveaway action

You can do multiple action to an existing giveaway. You can:

* **End a giveaway** => `/giveaway actions options:end query:(MSG ID of the giveaway)`
* **Pause a giveaway** => `/giveaway actions options:pause query:(MSG ID of the giveaway)`
* **Unpause a giveaway** => `/giveaway actions options:unpause query:(MSG ID of the giveaway)`
* **Reroll the winner of a giveaway** => `/giveaway actions options:reroll query:(MSG ID of the giveaway)`
* **Delete a giveaway** => `/giveaway actions options:delete query:(MSG ID of the giveaway)`

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-16 180638.png" alt=""><figcaption><p>You can do multiple action to an existing giveaway.</p></figcaption></figure>

{% hint style="info" %}
You need the permission `MANAGE_EVENTS` to use this command.
{% endhint %}
{% endtab %}
{% endtabs %}
