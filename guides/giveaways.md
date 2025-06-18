---
description: In this page, you will learn about hosting & managing giveaways using Apollo.
cover: ../.gitbook/assets/covergradient-5.png
coverY: 0
---

# Giveaways

As you know apollo has a very sophisticated and advanced giveaway system. This page will walk through each and every command in detail so you can use the most out of apollo giveaway system.

## Giveaway Management Commands

### `a!wins`

> This command shows the amount of win counts of giveaways hosted in the particular server and in all the servers apollo is in. In addition to the count, this command also shows what prize has been won by that particular user.

<figure><img src="../.gitbook/assets/image (2) (1).webp" alt=""><figcaption></figcaption></figure>

### `a!glist`

> This command shows all the active and ended giveaways in the particular server across all channels. This command also shows other information like giveaway host, giveaway winner of ended giveaways, and the channel the giveaway is in.&#x20;

<figure><img src="../.gitbook/assets/image (5) (1).webp" alt=""><figcaption></figcaption></figure>

This command sends a button to view all the giveaways in paginator (page embed) form, as shown above.&#x20;

### `a!gwin-role` / `/gwin-role`

> This command shows the roles that are to be added to the winner after they have won a giveaway. a!winrole set adds a new role to be added to the winners whereas a!winrole remove will delete the role to be added to winners.

<figure><img src="../.gitbook/assets/image (6) (2).webp" alt=""><figcaption></figcaption></figure>

## Giveaway Host Commands

### `a!gcreate`

> This command can be used to start a giveaway step-by-step and also add requirements in detail. You can add requirements like account age, user must not have won any giveaways before, must've sent `<x: int>` amount of messages, etc.,

<figure><img src="../.gitbook/assets/image (33).png" alt="" width="563"><figcaption><p>Apollo will send a panel like this at first, you can configure everything from here</p></figcaption></figure>

**Adding requirements:**

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption><p>you will be shown a variety of options from which you can choose from. a detailed info about each requirement is listed below</p></figcaption></figure>

> * Message count: Participant must have sent `x` amount of messages to enter the giveaway.
> * Joined days: Participant must have stayed in the server for `x` amount of days.
> * Account age: Participant's discord account must be `x` amount of days old.
> * Role: Participant must have a specific role (say `@supporter`) in the server.
> * Not role: Participant must NOT have a specific role (say `@giveaway banned`) in the server.
> * No win: Participant must NOT have won any giveaways in the server.
> * Bypass: Participant with a specific role (say `@booster`) can bypass all requirements if any.

**Setting basic info for the giveaway:**

> To setup basic info like giveaway name, number of winners and duration click on the "Edit" button in the message and you will be prompted with a pop-up (or modal). You can fill it up and click submit to end the giveaway creation process.

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption><p>popup (or modal) to fill inorder to end the giveaway creation process</p></figcaption></figure>

After setting everything you can click on the "Start Giveaway" button to start the giveaway.

<figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

### `a!gstart`

> This command is used to start giveaways in a particular channel. The format to use this command is `a!gstart <time> <winners> <prize>`. Once you have entered the parameters, Apollo will automatically delete your message and start a giveaway in that particular channel.\
> \
> For Example to host a giveaway with 2 winners, time of 1 hour and prize of Gold, we type in `a!gstart 1h 2 Gold`



<figure><img src="../.gitbook/assets/a!gstart.gif" alt=""><figcaption><p>Example giveaway</p></figcaption></figure>

### `a!gend`

> This command is used to end a particular giveaway in a particular channel. If there are more than one giveaways running at the same time then you can use `a!gend <messageid>` to end that particular giveaway, as we replace `<messageid>` with the id of the giveaway.

<figure><img src="../.gitbook/assets/a!gend.gif" alt=""><figcaption><p>Ending giveaway</p></figcaption></figure>

### `a!greroll`

This command rerolls the winner of a perticular giveaway. When multiple giveaways are running then you can use `a!greroll <messageid>` to reroll that particular giveaway. Here `<messageid>` is the id of the message of the giveaway.

<figure><img src="../.gitbook/assets/a!greroll.gif" alt=""><figcaption><p>Rerolling Giveaway</p></figcaption></figure>

## Giveaway Control Commands

### `a!gblacklist`

> This command blacklists a particular user from reacting/participating in giveaways by automatically removing reactions to giveaways in the particular server. This command only applies to the local server and not the global giveaway blacklist (i.e. the user can still participate in other giveaways hosted by apollo in other servers)\
> \
> Just type in `a!gblacklist <@user>` to blacklist them from all giveaways in your server.

<figure><img src="../.gitbook/assets/image (8) (1).webp" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (9) (1).webp" alt=""><figcaption><p>run the command again to unblacklist the user</p></figcaption></figure>

To view all blacklisted users, run `a!gblacklist` or `/gblacklist` without mentioning any users.

<figure><img src="../.gitbook/assets/image (10) (1).webp" alt=""><figcaption></figcaption></figure>

### `a!gcheck`

> Checks if the user has met the specific requirement to enter the giveaway. Requirements include messages, account age, etc., and can be set up using the gcreate command.

<figure><img src="../.gitbook/assets/image (12).webp" alt=""><figcaption></figcaption></figure>

### `a!gdelete`

This command deletes the giveaway log from the a!glist database. To delete a particular giveaway just use the a!gdelete command followed by the giveaway message id that can be obtained either directly from the message or from the [a!glist](giveaways.md#a-glist) command.

<figure><img src="../.gitbook/assets/image (11).webp" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
