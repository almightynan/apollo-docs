---
description: In this page, you will learn about greet & welcoming newly joining users.
cover: ../.gitbook/assets/covergradient-6.png
coverY: 0
---

# Greet

## What are greet messages?

> Greet messages enable you to set up messages when a user joins your server. Apollo has a very customizable greeting system, with multiple features to help the user make a greet message of their own choice. The bot also provides some variables you can use to customise your greet message even more.&#x20;

{% hint style="info" %}
Greet module is disabled by default. Run `a!greet toggle`/ `/greet toggle`to enable it.
{% endhint %}

## Sub commands for the Greeter Module

### `a!greet toggle`

> This command either enables or disables greet messages. To enable or disable greet throughout the server just use `a!greet toggle`or `/greet toggle`.

### `a!greet message`

> This command sets the message to be used when greeting. You can put anything here and get creative by using apollo's various variables. You can set your custom message buy using **a!greet message \<message>**.

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption><p>greet message in action</p></figcaption></figure>

### `a!greet delafter`

> This command sets the time (in seconds) after which the greet message will be deleted.

<figure><img src="../.gitbook/assets/Screenshot 2023-05-16 at 12.31.37 AM.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
This command only accepts seconds and not any other time format.
{% endhint %}

### `a!greet settings`

> This command shows the configurations that you have set for the greet message, which includes the greet message, greet enabled channels, time after which the greet will be deleted and also a button to test out the greet message.

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

### a!greet reset

> This command resets all your greet configurations for the server and disables the greet module again.

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
