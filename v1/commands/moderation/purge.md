---
description: Purge (p) Moody's purge command is explained in detail here!
---

# Purge (p)

## Aliases <a href="#aliases" id="aliases"></a>

* `!purge`
* `!c`
* `!sweep`
* `!clear`
* `!clearchat`
* `!yeetmessages`

{% hint style="danger" %}
THIS COMMAND IS IN BETA FORMAT ONLY BOT PARAMETER WILL WORK!
{% endhint %}

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

![!clear](../../../.gitbook/assets/image.png)

## Format <a href="#format" id="format"></a>

{% hint style="info" %}
### `!purge <NO.-OF-MESSAGES> <USER/PARAMETER>` <a href="#w-purge-less-than-no.-of-messages-greater-than-less-than-user-parameter-greater-than" id="w-purge-less-than-no.-of-messages-greater-than-less-than-user-parameter-greater-than"></a>
{% endhint %}

### `Number of messages` <a href="#number-of-messages" id="number-of-messages"></a>

You must provide this so that Moody actually knows **how many messages** it's going to purge.

* **`!purge X`** is the syntax!

{% hint style="info" %}
**For example,** if you want to purge the last **`100 messages`** sent in a channel, run the command **`!purge 100`** in that specific channel!
{% endhint %}

### `<INPUT>` <a href="#less-than-input-greater-than" id="less-than-input-greater-than"></a>

Input can be the **user/role/bot** depending on what you want to purge. The syntax is **`!purge X <USER>`** where **`X`** is the **number of messages to be purged** and is the **ID/Mention/Name** or the specified user. **For example,** if you want to purge the last **`25 messages`** sent in a channel by a user named **bob**, run the command **`!purge 25 bob`** in that specific channel!

{% hint style="info" %}
You can **mention the member, type out their username, their tag, or even their** [**ID**](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)​You don't have to type the full thing if you are sure it's the only member with a **`username/tag/id`** that starts with what you want to provide, for an example, I only that **juju** is the only member with such a name, I can just do **`!purge 50 ju`** and Moody would delete **`50`** messages sent by **juju**. You can provide a **webbook ID** or even name if you want to target that **webbook's messages**. **You can mention the role, type out's name or event it's ID if you want to target all messages sent by members who happen to have the role.**
{% endhint %}

### `<PARAMETERS>` <a href="#less-than-parameters-greater-than" id="less-than-parameters-greater-than"></a>

Parameters are the purge options you can pass if you want extra input or a custom behaviour. **They must come after the number of messages!**If you want to target **a specific kind of message**, you need to use this parameter and actually provide the **`<PARAMETER>`** you need. If this parameter is used, **`<INPUT>`** has to be just a number!

#### Parameters available are: <a href="#parameters-available-are" id="parameters-available-are"></a>

| Type        | Info                                                                  | Example          |
| ----------- | --------------------------------------------------------------------- | ---------------- |
| Suspicious  | Target messages sent by **suspicious users**                          | **`!p 50 s`**    |
| Bots        | Target **bot messages**                                               | **`!p 50 b`**    |
| Users       | Target **non-bot messages**                                           | **`!p 50 u`**    |
| No-Avatar   | Target messages sent by members with no PfPs                          | **`!p 50 noav`** |
| No-Role     | Target messages sent by members with 0 roles                          | **`!p 50 nr`**   |
| Embeds      | Target **Embed** messages                                             | **`!p 50 e`**    |
| Attachments | Target **Attachment** messages                                        | **`!p 50 a`**    |
| Links       | Target **Links** (even if they don't show a preview)                  | **`!p 50 l`**    |
| All         | Targets **all** messages and will delete every message in the channel | **`!p all`**     |

### **Embeds** <a href="#embeds" id="embeds"></a>

`!purge 25 embeds`

* This command will purge `25` messages that contain **embeds** in the channel this command was used in.

### **Suspicious** <a href="#suspicious" id="suspicious"></a>

`!purge 25 suspicious`

* This command will purge `25` messages sent by **users deemed suspicious** by moody in the channel this command was used in.

**Alias(es): `sus`**

{% hint style="info" %}
`!p 25 sus`
{% endhint %}

### **Bots** <a href="#bots" id="bots"></a>

`!purge 10 bot`

* This command will purge `10` messages sent by **bots** in the channel this command was used in.

**Alias(es): `bot` / `bots` / `robot` / `robots`**

{% hint style="info" %}
* `!p 10 bot`
* `!p 10 bots`
* `!p 10 robot`
* `!p 10 robots`
{% endhint %}

### **Mention** <a href="#mention" id="mention"></a>

`!purge 25 mention`

* This command will purge `25` messages that contain **mentions** in the channel this command was used in.

**Alias(es): `p / mention / ping / pings / @`**

{% hint style="info" %}
* `!p 25 p`
* `!p 25 mention`
* `!p 25 ping`
* `!p 25 pings`
* `!p 25 @`
{% endhint %}

### **Reactions** <a href="#reactions" id="reactions"></a>

`!purge 25 reactions`

* This command will purge `25` messages that contain **reactions** in the channel this command was used in.

**Alias(es): `r/ reaction / react / reacts`**

* `!c 25 r`

### **Emojis** <a href="#emojis" id="emojis"></a>

`!purge 100 emojis`

* This command will purge `100` messages that contain **emojis** in the channel this command was used in.

**Alias(es): `emote / emotes / emoji`**

* `!p 100 -emote`
* `!p 100 emotes`
* `!p 100 emoji`

### **No Avatars** <a href="#no-avatars" id="no-avatars"></a>

`!purge 70 noav`

* This command will purge `70` messages sent by **users with no avatars** in the channel this command was used in.

**Alias(es): `-na/ noavatar/ nopic`**

* `!p 70 -na`
* `!p 70 noavatar`
* `!p 70 nopic`

### **Text** <a href="#text" id="text"></a>

`!purge 70 text`

* This command will purge `70` messages that only contain **text** in the channel this command was used in.

**Alias(es): `txt / txt / noimage / noembed`**

* `!p 70 txt`
* `!p 70 txt`
* `!p 70 noimage`
* `!p 70 noembed`

### **No Roles** <a href="#no-roles" id="no-roles"></a>

`!purge 25 norole`

* This command will purge `25` messages sent by **users with no roles** in the channel this command was used in.

**Alias(es): `nr / stripped`**

* `!p 25 nr`
* `!p 25 stripped`

### **Attachments** <a href="#attachments" id="attachments"></a>

`!purge 30 img`

* This command will purge `30` messages that contain **images** in the channel this command was used in.

**Alias(es): `pic / image / attach`**

* `!p 30 pic`
* `!p 30 image`
* `!p 30 attach`

### **Links** <a href="#links" id="links"></a>

`!purge 50 links`

{% hint style="info" %}
This command will purge `50` messages that contain _\*\*_ in the channel this command was used in.
{% endhint %}

**Alias(es): `l`**

* `!p 50 l`

!p 100 links

## Logging <a href="#logging" id="logging"></a>

Moody will log any and all **purges** made using it in your **moody-logs** channel, your **mod logs** channel and in the audit logs.

* The **moody-logs** channel will have an embed that will contain information pertaining to the **purge, the mod who purged, the type of purge** and so on.

## More information regarding Purges <a href="#more-information-regarding-purges" id="more-information-regarding-purges"></a>

**`[1.]`** Currently, more than 100 messages cannot be purged using a single command. You'd have to do it using multiple commands.

**`[2.]`** Moody also logs when someone purges message in its `moody-logging` channel

{% hint style="warning" %}
## Due to a Discord limitation, Moody can't delete messages older than 2 weeks! <a href="#due-to-a-discord-limitation-wick-cant-delete-messages-older-than-2-weeks" id="due-to-a-discord-limitation-wick-cant-delete-messages-older-than-2-weeks"></a>
{% endhint %}
