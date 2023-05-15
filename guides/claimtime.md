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

## Sub Commands for claimtime module

### a!claimtime

> This command checks the claimtime for a user or a role. It gives the claimtime for a role and it gives the total claimtime for a user.

<div align="center">

<figure><img src="../.gitbook/assets/image (25).png" alt="Example Of a!claimtime command"><figcaption><p>Interface for roles</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Interface for users</p></figcaption></figure>

</div>

### a!claimtime add (a!claimtimeconfig add)

> This command adds or updates a specific amount of time (claimtime) to the role mentioned. Use `s` for seconds, `m` for minutes and `h` for hours.

{% hint style="warning" %}
This only works for roles and cannot be set for specific users
{% endhint %}

<figure><img src="../.gitbook/assets/image (15).png" alt="Example of the a!claimtime add command "><figcaption></figcaption></figure>

### a!claimtime remove (a!claimtimeconfig remove)

> This command removes the claimtime set for that particular role. Once this command is used on a role, the whole claimtime is deleted for that specific role completely.&#x20;

<figure><img src="../.gitbook/assets/image (5).png" alt="Example of a!claimtime remove command"><figcaption></figcaption></figure>

### a!claimtimeconfig

> This command shows the configured claimtime for the roles in the server, however this command only shows the claimtime only for the configured roles as shown below.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

##
