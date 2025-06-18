---
description: >-
  This page will describe in detail what is override and how to use it in apollo
  bot
---

# Overrides

## What is an override?

> The function "override" is used to overwrite existing configuration of a role on top of another. To better understand the term please refer to the images shown below.

**Case #1 (override has been disabled)**

In this case I have two roles which have their override setting set to `False`. Which means all of the role's claimtimes will be added individually to calculate the total claimtime.

<figure><img src="../.gitbook/assets/{D8197D16-9BE8-40D9-878C-9846B0773759}.png" alt=""><figcaption><p>roles <code>dummy</code> and <code>mgmt</code> have their overrides set to False</p></figcaption></figure>

<figure><img src="../.gitbook/assets/{A2D38416-2214-46C3-9226-62156CC78D82}.png" alt=""><figcaption></figcaption></figure>

***

**Case #2 (override has been enabled)**

In this case I have three roles including the roles as shown in the previous screenshot(s), but Apollo only calculates for my role which has its override setting enabled. Hence, override allows you to bypass all other claimtime(s) which you may have.

<figure><img src="../.gitbook/assets/{DC37A0EB-F364-4715-B713-CFB23E53FDCA}.png" alt=""><figcaption><p>role <code>owner</code> as its override set to True</p></figcaption></figure>

<figure><img src="../.gitbook/assets/{AB02D2C3-4125-4CF1-86EA-5BA55CEE6B8C}.png" alt=""><figcaption></figcaption></figure>



{% hint style="warning" %}
Override does not look for role ranks. i.e. even a role at the bottom of the role list with an override will replace all existing claimtime with the override specified claimtime.
{% endhint %}

This feature can be used in many ways when you don't want a specific role to have more than desired amount of claimtime.



{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
