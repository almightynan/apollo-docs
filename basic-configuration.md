---
cover: .gitbook/assets/covergradient-1.png
coverY: 0
---

# Basic configuration

### Invite Apollo to your server:

{% embed url="https://dsc.gg/apollo-invite" %}
Click on the text above to invite Apollo.
{% endembed %}

### Quicksetup some configurations

* Use `a!quicksetup` to setup some of the configurations within seconds.

#### Step 1 - Triggers

This will set `g!end`, `!gend`, `g!reroll`, `!greroll` astriggers. You can add/remove triggers using `a!trigger add [trigger]` or `a!trigger remove [trigger]`.

#### Step 2 - Win messages

This will set Congratulations, `{winner(username)}`! You have `{claim_time}` to claim! as the win message. You can change it anytime using `a!winmsg set [message]`. Checkout a!vars to check the variables you can use.

#### Step 3 - Claim time

This will set 10 seconds to claim for everyone as default. You can add claim time to a role using `a!claimtime add [role_id] [time]`. Please note that the total claim time of a member will be the SUM of ALL the claim times of each of the member's roles. So if you have a special role to get Members 13 seconds, add 3s claim time to that role. Apollo will calculate 10s (default) + 3s (role claim time).

#### Step 4 - Final Step

You have to **MANUALLY TYPE** `a!winmsg enable` to enable the win message.
