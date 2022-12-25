---
description: 'This page describes the core component of Moody: Isolation'
---

# Isolation



Isolationis a crucial element of Moody. It is a core ingredient of its safety mechanism. Any rogue admins,  unverified users, or bots will be added to it. Any account with dangerous permissions is added to it.

Anyone trying to **free** other users from quarantine will be added to it, thus creating a **Domino Effect**.&#x20;

The importance of Isolation can be briefed in a few points:&#x20;

* **Nuke Attempts:** Moody will add any user with dangerous permissions/rogue admins to quarantine
* **Bypassing Isolation:** Any bypass/freeing attempts without proper permissions will result in the user being quarantined.
* **Adding dangerous permissions to the Isolation/Muted roles:** Adding dangerous permissions to the Isolation/muted roles will result in the user being quarantined.
* **Adding dangerous permissions to ANY role -if enabled-:** Isolate a user that tries to give the ANY role some dangerous permissions.
* **Adding dangerous permissions to a STATIC role:** Giving dangerous permission to a user's static role that is currently in isolation will result in that user being added to isolation as well.
* **Other suspicious trends that we consider unsafe.**

{% hint style="warning" %}
#### With a proper Moody setup, a user in isolation is not capable of doing ANYTHING. They can't even see channels unless the admins allow them to.
{% endhint %}
