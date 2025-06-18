---
description: >-
  In this page, you will learn the detailed usage of the message counting
  feature.
---

# Message Counter

## What is message counter?

> This module of apollo lets users track messages on their discord server. Apollo has a very customisable and advanced message tracking system. This module in any way does not track or store your messages in a database. You can also disable this command for yourself if you wish your messages not be counted by apollo.&#x20;

<figure><img src="../.gitbook/assets/imaaaaaaaaaaaaaaaae.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Message Counter is disabled by default for your server, use **a!messages enable** to start counting messages in the server.
{% endhint %}

## Subcommands for the Message Counter Module

### `a!messages (/messages)`

> This command shows the number of messages that has been sent by the user. You can also use this command to check the message sent by other users in the server too by using **a!messages {@user}** or by using **a!messages {userID}.**&#x20;

<figure><img src="../.gitbook/assets/imaaaaaaaaaaaaaaaae (1).png" alt=""><figcaption></figcaption></figure>

### Admin commands for the Claimtime Module

### `a!messages-admin <enable [or] disable>` / `/messages-admin <enable`` ``[or] disable>`

> This command helps to enable or disable the message counting feature in your server, and as mentioned above by default the message counter is off for the given server.

<figure><img src="../.gitbook/assets/image (8).webp" alt=""><figcaption><p>command to enable the counter</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (9).webp" alt=""><figcaption><p>command to disable the counter</p></figcaption></figure>

### `a!messages-admin settings` / `/messages-admin settings`

#### _Blacklist Mode_

> In this mode, Apollo will blacklist the given channels where the messages will not be counted. But the messages in all the other channels will be counted as usual.

<figure><img src="../.gitbook/assets/image.webp" alt=""><figcaption><p>select the dropdown and choose blacklist to enter blacklist mode</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1).webp" alt=""><figcaption></figcaption></figure>

In the example shown above, we have set Apollo to ignore (blacklist) the **#rules** channel and any messages sent in that channel will not be counted. To add a channel to blacklist, just use the dropdown menu to select it.

#### _Whitelist Mode_

> In this mode, Apollo will whitelist the given channels where the messages will be counted. But the messages in all the other channels will not be counted.

<figure><img src="../.gitbook/assets/image.webp" alt=""><figcaption><p>select the dropdown and choose blacklist to enter blacklist mode</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (2).webp" alt=""><figcaption></figcaption></figure>

In the example shown above, we have set Apollo to only count from the **#general** channel and any messages sent in that channel **only** be counted. To add a channel to whitelist, just use the dropdown menu to select it.

{% hint style="info" %}
You can add multiple channels to the blacklist or the whitelist.
{% endhint %}

### `a!messages-admin add` / `a!messages-admin remove`

> This command lets you add or removes messages for a particular user or yourself. Note that this feature can only used by administrators of a server.&#x20;

<figure><img src="../.gitbook/assets/image (3).webp" alt=""><figcaption><p>bot has added 40 messages to user</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (4).webp" alt=""><figcaption><p>bot has removed 30 messages from the user</p></figcaption></figure>

{% hint style="warning" %}
Removing messages greater than the messages a user has will reset their message count back to **zero** and not any negative integer.
{% endhint %}

### `a!messages-admin reset`

This command allows you to reset the messages of a particular user in your server.

<figure><img src="../.gitbook/assets/image (5).webp" alt=""><figcaption><p>bot has successfully reset message count</p></figcaption></figure>

#### `a!messages-admin reset-all`

This command allows you to reset the messages of everyone in your server to **0**. The bot will ask for a confirmation before proceeding.

<figure><img src="../.gitbook/assets/image (6) (1).webp" alt="" width="357"><figcaption></figcaption></figure>

### `a!leaderboard` / `a!lb` / `/leaderboard`

This command shows the messages sent by everyone from greatest to the least. This command uses pagination so you can scroll through through multiple pages to check the message counts.

<figure><img src="../.gitbook/assets/image (7).webp" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
