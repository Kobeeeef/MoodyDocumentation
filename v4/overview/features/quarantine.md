---
description: 'This page describes the core component of Moody: Isolation'
---

# Isolation

## Isolation in Moody: Enhancing Safety and Security

Isolation is a critical feature within Moody that plays a fundamental role in maintaining a safe and secure environment within your Discord server. It serves as a core ingredient of Moody's safety mechanism, effectively dealing with rogue administrators, unverified users, and potentially harmful bots. By isolating these accounts, Moody prevents them from causing disruptions and potential harm.

The significance of Isolation can be summarized in the following key points:

### Nuke Attempts

Moody identifies and adds any user with dangerous permissions or flagged as rogue administrators to the quarantine or isolation. This ensures that any attempt to initiate a server-wide destruction (commonly known as a "nuke") is swiftly thwarted.

### Bypassing Isolation

Any attempts to bypass or free users from quarantine without proper permissions are detected by Moody. Such actions trigger a countermeasure, placing the user responsible for the bypassing attempt into isolation as well. This mechanism creates a domino effect, safeguarding the server from potential threats.

### Isolation/Muted Roles and Dangerous Permissions

Assigning dangerous permissions to the Isolation or Muted roles within Moody results in users being immediately added to isolation. This proactive approach prevents any unauthorized escalation of privileges that could compromise server security.

### Dangerous Permissions and "ANY" Role

In cases where the configuration allows for it, Moody isolates users who attempt to grant dangerous permissions to the "ANY" role. This additional layer of protection ensures that no user can exploit the broad authority of the "ANY" role to cause harm or disrupt the server.

### Dangerous Permissions and Static Roles

Moody recognizes the potential risk of granting dangerous permissions to a user's static role while they are currently in isolation. Consequently, Moody takes immediate action by adding the user to isolation to prevent any potential misuse of these permissions.

### Identifying Suspicious Trends

Beyond the specific scenarios mentioned above, Moody continuously monitors server activity for other suspicious trends that may threaten the community's safety. By swiftly responding to such patterns, Moody helps maintain a secure environment for all server members.

With a properly configured Moody setup, users in isolation are rendered virtually powerless. They are restricted from performing any actions within the server, including viewing channels unless specifically granted permission by administrators.

By leveraging the capabilities of Moody's Isolation feature, server administrators can effectively mitigate risks, protect their community, and promote a safe and harmonious environment for all members.
