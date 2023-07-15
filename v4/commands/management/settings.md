---
description: This GitBook page provides detailed information on how to use Moody Discord Bot's `settings` command to configure module settings and more.
---

# Settings Command

## Description

The `settings` command in Moody Discord Bot allows you to configure various module settings for your server. You can customize settings related to modules such as Bump Reminder, Report System, Audit Logging, Static Roles, Static Channels, and Milky Overflow Control. This command provides a flexible and convenient way to manage and modify these settings.

## Permit

To use the `settings` command, you need to have the **Manager** permit level (Permit level 4) in the server.

## Format

To use the `settings` command, follow the format below:

{% hint style="info" %}
### `/settings <MODULE> <SETTING> <VALUE>`
{% endhint %}

- `<MODULE>`: Select the module/setting you want to configure.
- `<SETTING>`: Customize the specific setting within the selected module.
- `<VALUE>`: Provide the new value for the setting.

## Example

Here's an example of how to use the `settings` command:

```
/settings BUMP 1 true
```

This command configures the Bump module's first setting to `true`.

## Modules and Settings

The `settings` command supports the following modules and corresponding settings:

### Bump Module

- **Setting 1**: Enable/Disable the Bump module.
- **Setting 2**: Enable/Disable auto cleanse.
- **Setting 3**: Configure the Bump channel.
- **Setting 4**: Enable/Disable auto lock.
- **Setting 5**: Configure mentions for Bump notifications.

### Report Module

- **Setting 1**: Enable/Disable the Report module.
- **Setting 2**: Configure the Report channel.
- **Setting 3**: Configure role mentions for reports.

### Audit Logging Module

- **Setting 1**: Enable/Disable the Audit Logging module.
- **Setting 2**: Configure the Audit Logging channel.
- **Setting 3**: Add events to log.
- **Setting 4**: Remove events from log.

### Static Roles Module

- **Setting 1**: Configure the Assistant role.
- **Setting 2**: Configure the Isolated role.
- **Setting 3**: Configure the Moderator role.
- **Setting 4**: Configure the Manager role.

### Static Channels Module

- **Setting 1**: Configure the Moody channel.
- **Setting 2**: Configure the Guild channel.

## Note

Keep in mind that the `settings` command requires the Manager permit level (Permit level 4) to use the command effectively.

Make sure to provide the correct module, setting, and value when using the command to avoid any unintended changes.

