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

### `a!messages enable` / `a!messages disable`

> This command helps to enable or disable the message counting feature in your server, and as mentioned above by default the message counter is off for the given server.

### `a!messages-admin settings`

#### _Blacklist Mode_

> In this mode, apollo will blacklist the given channels where the messages will not be counted. But the messages in all the other channels will be counted as usual.

<figure><img src="../.gitbook/assets/imaaaaaaaaaaaaaaaae (2).png" alt=""><figcaption></figcaption></figure>

In the example shown above, we have set apollo to ignore (blacklist) the **#test-channel-1** channel and any messages sent in that channel will not be counted. To add a channel to blacklist, just use the dropdown menu to select it.

#### _Whitelist Mode_

> In this mode, apollo will whitelist the given channels where the messages will be counted. But the messages in all the other channels will not be counted.

<figure><img src="../.gitbook/assets/Screenshot 2023-05-14 at 11.15.46 PM.png" alt=""><figcaption><p>notice in whitelist mode the "Whitelist mode" button has turned green</p></figcaption></figure>

In the example shown above, we have set apollo to only count from the **#test-channel-1** channel and any messages sent in that channel **only** be counted. To add a channel to whitelist, just use the dropdown menu to select it.

{% hint style="danger" %}
Always click on "Save Changes" to make sure the bot has stored your input
{% endhint %}

{% hint style="info" %}
You can add multiple channels to the blacklist or the whitelist.
{% endhint %}

{% hint style="warning" %}
Count from all channels deletes the existing lists and counts from all channels.
{% endhint %}

### `a!messages add` / `a!messages remove`

> This command lets you add or removes messages for a particular user or yourself. Note that this feature can only used by administrators of a server.&#x20;

<div><figure><img src="../.gitbook/assets/Screenshot 2023-05-14 at 11.30.34 PM.png" alt=""><figcaption><p>adding messages to self</p></figcaption></figure> <figure><img src="../.gitbook/assets/Screenshot 2023-05-14 at 11.31.03 PM.png" alt=""><figcaption><p>removing messages from another user</p></figcaption></figure></div>

{% hint style="warning" %}
Removing messages greater than the messages a user has will reset their message count back to **zero** and not any negative integer.
{% endhint %}

### `a!messages reset`

This command allows you to reset the messages of a particular user in your server.

<figure><img src="../.gitbook/assets/Screenshot 2023-05-14 at 11.49.44 PM.png" alt=""><figcaption><p>Bot has successfully reset message count</p></figcaption></figure>

### `a!leaderboard`

This command shows the messages sent by everyone from greatest to the least. This command uses pagination so you can scroll through through multiple pages to check the message counts.

<figure><img src="../.gitbook/assets/Screenshot 2023-05-14 at 11.58.16 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
