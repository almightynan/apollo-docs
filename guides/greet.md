---
description: In this page, you will learn about greet & welcoming newly joining users.
cover: ../.gitbook/assets/covergradient-6.png
coverY: 0
---

# Greet

## What are greet messages?

> Greet messages enable you to set up messages when a user joins your server. Apollo has a very customisable greeting system, with multiple features to help the user make a greet message of their own choice. The bot also provides some variables you can use to customise your greet message even more.&#x20;

## Sub commands for the Greeter Module

### `a!greet`

> This command either enables or disables greet messages in a particular channel. To enable or disable greet in any other channel just use **a!greet <#channel-ID>**. If you just use **a!greet** in the channel you currently are on, it just enables or disables for that particular channel.

<div>

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.20.48 AM.png" alt=""><figcaption><p>greet enabled for current channel</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.20.08 AM.png" alt=""><figcaption><p>greet disabled for current channel</p></figcaption></figure>

</div>

<div>

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.15.39 AM.png" alt=""><figcaption><p>greet enabled for a different channel</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.15.55 AM.png" alt=""><figcaption><p>greet disabled for a different channel</p></figcaption></figure>

</div>

### `a!greet message`

> This command sets the message to be used when greeting. You can put anything here and get creative by using apollo's various variables. You can set your custom message buy using **a!greet message \<message>**.

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.27.40 AM.png" alt=""><figcaption><p>Writing a custom welcome/greet message</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.29.21 AM.png" alt=""><figcaption><p>Message sent by apollo</p></figcaption></figure>

### `a!greet delafter`

> This command sets the time (in seconds) after which the greet message will be deleted.

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.31.37 AM.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
This command only accepts seconds and not any other time format.
{% endhint %}

### `a!greet show`

> This command shows the configurations that you have set for the greet message, which includes the greet message, greet enabled channels, time after which the greet will be deleted and also a button to test out the greet message !

<div>

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.34.56 AM.png" alt=""><figcaption><p>greet config</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.37.01 AM.png" alt=""><figcaption><p>testing greet</p></figcaption></figure>

</div>

{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
