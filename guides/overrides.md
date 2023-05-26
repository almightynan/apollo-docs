---
description: >-
  This page will describe in detail what is override and how to use it in apollo
  bot
---

# Overrides

## What is an override?

> The function "override" is used to overwrite existing configuration of a role on top of another. To better understand the term please refer to the images shown below.

<div>

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption><p><strong>↓</strong></p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption><p><strong>↓</strong></p></figcaption></figure>

</div>

<div align="center">

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption><p>Claimtime with a override role</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption><p>Claimtime without a override role</p></figcaption></figure>

</div>

{% hint style="warning" %}
Override does not look for role ranks. i.e. even a role at the bottom of the role list with an override will replace all existing claimtime with the override specified claimtime.
{% endhint %}

This feature can be used in many ways when you don't want a specific role to have more than desired amount of claimtime. You can also disable this module if you don't want to use it to avoid confusions.



{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
