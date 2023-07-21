Apologies for the confusion. Here's the `settings` command page without code blocks:

---
description: Moody Discord Bot - Settings Command
---

# Settings Command

## Description

The `settings` command in Moody Discord Bot allows you to access the graphical user interface (GUI) to configure various module settings for your server. You can customize settings related to modules such as Bump Reminder, Report System, Audit Logging, Static Roles, Static Channels, and Milky Overflow Control. The GUI provides a user-friendly and interactive way to manage and modify these settings without the need for complex commands.

## Permit

To use the `settings` command and access the GUI, you need to have the **Manager** permit level (Permit level 4) in the server.

## Accessing the GUI

To access the GUI for configuring the module settings, follow these steps:

1. Use the `settings` command with the desired `module` as the parameter.

    ```
    /settings MODULE
    ```

    Replace `MODULE` with one of the following module names:

    - `BUMP`: Bump Reminder module settings
    - `REPORT`: Report System module settings
    - `LOGGING`: Audit Logging module settings
    - `ROLES`: Static Roles module settings
    - `CHANNELS`: Static Channels module settings
    - `MOC`: Milky Overflow Control module settings

2. After using the `settings` command, Moody will display a graphical interface with options to modify the settings for the selected module.

3. Interact with the GUI to configure the specific settings within the module. You can enable/disable features, set channels, and define roles for various functionalities.

4. Save your changes by interacting with the GUI elements accordingly.

## Logging Events

The Audit Logging module allows you to log various events within your server. While the actual configuration of these logging events is done through the GUI, you can still see the list of available logging events that can be configured:

- `CHANNEL_CREATE`
- `CHANNEL_DELETE`
- `ROLE_CREATE`
- `ROLE_DELETE`
- `WEBHOOK_CREATE`
- `WEBHOOK_DELETE`
- `EMOJI_CREATE`
- `EMOJI_DELETE`
- `MESSAGE_UPDATE`
- `MESSAGE_DELETE`

## Note

Keep in mind that the Moody Discord Bot's GUI-based settings provide an intuitive way to manage various aspects of your server without the need for complex commands. Enjoy configuring your modules and enhancing your server's functionalities with ease!
