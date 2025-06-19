---
description: Commands which are used to count/manage message counting in a server.
cover: ../.gitbook/assets/Screenshot 2023-05-26 090312.png
coverY: 0
---

# Message Counter

{% hint style="warning" %}
Inorder for message counter to work, you must enable it by using `a!messages enable`
{% endhint %}

### `a!messages`

{% tabs %}
{% tab title="Usage" %}
* `a!messages [user]` - Check your/other user's number of messages in the server.
{% endtab %}

{% tab title="Examples" %}
<figure><img src="../.gitbook/assets/chrome_QO5xVQj1qg.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### `a!messages-admin add`

{% tabs %}
{% tab title="Usage" %}
* `a!messages-admin add <member> <amt>` - Add a certain number of messages to an user.
{% endtab %}

{% tab title="Examples" %}
<figure><img src="../.gitbook/assets/chrome_8PZrXJFuwF.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### `a!messages-admin remove`

{% tabs %}
{% tab title="Usage" %}
* `a!messages remove <member> <amt>` - Remove messages from an user.
{% endtab %}

{% tab title="Examples" %}
<figure><img src="../.gitbook/assets/chrome_f5tAeonCG9.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### `a!messages-admin enable`

{% tabs %}
{% tab title="Usage" %}
* `a!messages enable` - Enables the message counter. _(Refer to top of the page)_
{% endtab %}

{% tab title="Examples" %}
<figure><img src="../.gitbook/assets/chrome_LQh7rXduEb.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### `a!messages-admin disable`

{% tabs %}
{% tab title="Usage" %}
* `a!messages disable` - Disables the message counter if it is enabled.
{% endtab %}

{% tab title="Examples" %}
<figure><img src="../.gitbook/assets/chrome_X0zgLs2AwN.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### `a!messages reset` & `a!messages-admin reset-all`

{% tabs %}
{% tab title="Usage" %}
* `a!messages-admin reset <user>` - Reset a member's message count to 0.
* `a!messages-admin reset-all` - Reset the entire server's message count to 0.

{% hint style="danger" %}
**WARNING - DESTRUCTIVE ACTION**

* Wrong usage of this command can cause all your message data to be reset.
* Make sure to mention the user if you are resetting messages for a single user.
* Erased data cannot be recovered, we do not store backups of deleted data.
{% endhint %}
{% endtab %}

{% tab title="Examples" %}
#### Reset messages for a single user:

<figure><img src="../.gitbook/assets/chrome_wEH1ckMj4U.gif" alt=""><figcaption></figcaption></figure>

#### Reset messages for the entire server:

<figure><img src="../.gitbook/assets/chrome_eEbOX6YH4b.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### `a!messages-admin settings`

{% tabs %}
{% tab title="Usage" %}
* `a!messages settings` - Configure the message settings for the entire server.
{% endtab %}

{% tab title="Examples" %}
<figure><img src="../.gitbook/assets/chrome_YnsfXJSDVY.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### `a!leaderboard`

{% tabs %}
{% tab title="Usage" %}
* `a!leaderboard` - View the current message leaderboard for the server.
{% endtab %}

{% tab title="Examples" %}
<figure><img src="../.gitbook/assets/chrome_oStBAGv5M0.gif" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

{% hint style="info" %}
**Syntax usage:**

`<>` = Required argument (mandatory and must be included)

`[]` = Optional argument (not necessary to be included)
{% endhint %}
