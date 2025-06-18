---
description: In this page, you will learn the basics of claimtime and its usage.
cover: ../.gitbook/assets/covergradient-3.png
coverY: 0
---

# Claimtime

## What is claimtime ?

> Whenever you host a giveaway using apollo, each user is given a set "claimtime" i.e the time that they have to claim the "set prize". Using apollo's advanced claimtime manager helps you to give extra claim time to set users/roles. In this section we will go through the details of the claimtime.
>
> Please refer to the [**overrides**](overrides.md) section if you are not familiar with it as claimtime uses overrides.

## Subcommands for the Claimtime Module

### `a!claimtime`

> This command checks the claimtime for a user or a role. It gives the claimtime for a role and it gives the total claimtime for a user.

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption><p>claimtime for a member</p></figcaption></figure>

<figure><img src="../.gitbook/assets/200B798B-3218-41FC-AF10-DD836EA92C8C.png" alt=""><figcaption><p>claimtime for a specific role</p></figcaption></figure>

### Admin commands for the Claimtime Module

### `a!claimtime-admin add` (`/claimtime-admin add`)

> This command adds or updates a specific amount of time (claimtime) to the role mentioned. Use `s` for seconds, `m` for minutes and `h` for hours.

{% hint style="warning" %}
This only works for roles and cannot be set for specific users
{% endhint %}

<figure><img src="../.gitbook/assets/EB5A431F-95EE-4E0A-A6CF-1837567B15BD.png" alt=""><figcaption><p>running the command will prompt you with an override selection. if you are unsure, please read our guide on <a href="overrides.md">overrides</a></p></figcaption></figure>

<figure><img src="../.gitbook/assets/4D08C3D4-BF5B-4114-A359-B1FB24B45DDB.png" alt=""><figcaption><p>once an override has been selected, the bot will acknowledge your selection</p></figcaption></figure>

### `a!claimtime-admin remove` (`/claimtime-admin remove`)

> This command removes the claimtime set for that particular role. Once this command is used on a role, the whole claimtime is deleted for that specific role completely.&#x20;

<figure><img src="../.gitbook/assets/{A2BB8199-B48A-407B-BB09-0C7E43A1819D}.png" alt=""><figcaption></figcaption></figure>

### `a!claimtime-admin display (/claimtime-admin display)`

> This command shows the configured claimtime for the roles in the server, however this command only shows the claimtime only for the configured roles as shown below.

<figure><img src="../.gitbook/assets/{AEC4D014-89AD-4F81-AF46-9A421D4AA068}.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
