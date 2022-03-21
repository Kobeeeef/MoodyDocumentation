---
description: Moody's purge command is explained in detail here!
---

# Purge (p)

## Description <a href="#description" id="description"></a>

You can target any type of message you want and delete them in bulk by using Moody's awesome clear command. All scenarios are covered too.

* We also tried our best to make the command super easy for people but also super customizable for advanced users as well.

## Permit <a href="#permit" id="permit"></a>

Members able to use the purge commands are:

* Server Owner and Extra Owners. _`[Permit level 5]`_
* Trusted Admins _`[Permit level 4]`_
* Members with the Admin role **set in Moody**. _`[Permit level 3]`_
* Members with the Moderator role **set in Moody**. _`[Permit level 2]`_

## Preview <a href="#preview" id="preview"></a>

![/clear 10](../../../.gitbook/assets/image.png)

## Format <a href="#format" id="format"></a>

{% hint style="info" %}
### `/clear <AMOUNT OF MESSAGE> [TYPE] [USER/ID]` <a href="#w-purge-less-than-no.-of-messages-greater-than-less-than-user-parameter-greater-than" id="w-purge-less-than-no.-of-messages-greater-than-less-than-user-parameter-greater-than"></a>

* \<AMOUNT OF MESSAGE> is required&#x20;
* \[TYPE] and \[USER] is optional
{% endhint %}

### Parameters - \[TYPE]

|            |                                                                  |                     |
| ---------- | ---------------------------------------------------------------- | ------------------- |
| Type       | Explanation                                                      | Examples            |
| Mentions   | Clear messages sent by member that contains mentions             | /clear 1 Mentions   |
| Non-Role   | Clear messages sent by members with 0 roles                      | /clear 1 Non-Role   |
| Non-Member | Clear message sent by members that does not exists in the server | /clear 1 Non-Member |
| Bots       | Clear **bot messages**                                           | /clear 1 Bots       |

{% hint style="info" %}
### Mentions

`/clear 50 Mentions`

* This command will purge `50` messages that contain **mentions** in the channel this command was used in.
{% endhint %}

{% hint style="info" %}
### Non-Role

`/clear 50 Mentions`

* This command will purge `50` messages that sent by user with 0 roles in the channel this command was used in.
{% endhint %}

{% hint style="info" %}
### Non-Member

`/clear 50 Non-Member`&#x20;

* This command will purge `50` messages that sent by user which is not exists in the server.
{% endhint %}

{% hint style="info" %}
### Bots

`/clear 50 Bots`

* This command will purge `50` messages that sent by the bot
{% endhint %}

## More information regarding Purges <a href="#more-information-regarding-purges" id="more-information-regarding-purges"></a>

**`[1.]`** Currently, more than 100 messages cannot be purged using a single command. You'd have to do it using multiple commands.

**`[2.]`** Moody also logs when someone purges message in its `moody-logging` channel

{% hint style="danger" %}
### Due to Discord limitation, Moody can't delete messages older than 2 weeks! <a href="#due-to-a-discord-limitation-wick-cant-delete-messages-older-than-2-weeks" id="due-to-a-discord-limitation-wick-cant-delete-messages-older-than-2-weeks"></a>
{% endhint %}
