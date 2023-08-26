---
description: A list of all the commands categorized under Information
---

# ℹ Information

{% tabs %}
{% tab title="/help" %}
## Description

> Get a list of all the commands available of the discord bot.

## Usage

To see all the commands, you have to use the command `/help`

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-16 182109.png" alt=""><figcaption><p>You can use this command to see all the commands.</p></figcaption></figure>

The command will send an embed with a dropdown menu showing all the categories of command.

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-16 182230.png" alt=""><figcaption><p>The command send an embed with a dropdown menu with all the categories of command.</p></figcaption></figure>

{% hint style="info" %}
You don't need any specific permission to use this command.
{% endhint %}
{% endtab %}

{% tab title="/status" %}
## Description

> Get the discord bot and database status.&#x20;

## Usage

To see the discord bot and database status, you have to use the command `/status`

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-16 182755.png" alt=""><figcaption><p>You can use this command to see the discord bot and database status.</p></figcaption></figure>

The command will send an embed with the following information:

* The Discord API latency (in ms).
* The Discord BOT latency (in ms).
* The Database status:
  * `🟢 Connected`
  * `🟠 Conneting...`
  * `🔴 Disconnected`
  * `🟣 Disconnection in progress`
* The uptime (using Discord timestamps).
* And the host IP (will only show: `Host IP`, not the actual IP).

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-08-21 232825.png" alt=""><figcaption><p>The most common status that will appear.</p></figcaption></figure>

{% hint style="info" %}
You don't need any specific permission to use this command.
{% endhint %}
{% endtab %}
{% endtabs %}
