# StaffManager

> Copyright © 2026 moha_ali250 (GitHub: mohaali250)  
> Licensed under the PolyForm Noncommercial License 1.0.0  
> See the LICENSE file for details.
# Introduction to StaffManager

StaffManager is a Minecraft plugin designed to help server owners and staff teams manage their staff members, staff progression, and player moderation from one place.

Instead of relying on several different systems to keep track of who is staff, what rank they have, how long they have played, what punishments they have received, and what they need to do to progress, StaffManager brings these systems together into a single plugin.

StaffManager is designed to work alongside other plugins commonly used by Minecraft servers, allowing you to build a staff system around the way your server already works.

---

## What can StaffManager do?

### Staff Management

StaffManager provides tools for managing your staff team throughout their entire lifecycle.

You can promote players into staff, change their staff status, suspend or demote staff members, and permanently remove staff members from the team when necessary.

StaffManager can also keep track of a player's current staff rank and their progression toward another rank.

---

### Staff Progression

StaffManager can be used to create a progression system for your staff team.

When a player is promoted, StaffManager can assign them a staff goal and track their progress toward it.

For example, you could require a trainee to spend a certain amount of time actively playing as staff before they can progress to their next rank.

StaffManager can keep track of this progress for you instead of requiring staff members to manually keep track of their own playtime.

You can also configure how staff progression works, including requirements and how players can activate their staff status after completing them.

---

### Staff Status

StaffManager provides commands that allow staff members and administrators to view a player's current staff status.

The `/status` command can show information such as:

- Current staff rank
- Staff playtime
- Required playtime for progression
- Progress toward the next rank
- Active punishments
- Warnings
- Staff status

The appearance of these screens can also be customized through the configuration.

---

### Moderation

StaffManager also provides moderation functionality.

Depending on how your server is configured, StaffManager can handle or integrate with moderation actions such as:

- Warnings
- Mutes
- Suspensions
- Server bans
- Staff bans

Punishments can be associated with offenses and their corresponding rules, allowing StaffManager to keep additional context about a player's moderation history.

StaffManager can also use different moderation providers, allowing you to choose whether StaffManager, EssentialsX, or LiteBans handles certain moderation actions.

---

### Staff Hierarchy

StaffManager can optionally enforce a staff hierarchy.

When enabled, staff members cannot manage other staff members with an equal or higher rank.

This can be useful for larger staff teams where different ranks have different responsibilities.

StaffManager can use the weights assigned to your LuckPerms groups to determine which staff rank is higher.

---

### Discord Integration

StaffManager can integrate with Discord-related staff requirements.

For example, you can configure StaffManager to require a player to have their Minecraft account linked to Discord before they can be promoted or activate their staff status.

This can be useful for servers where Discord is an important part of the staff team.

---

### LuckPerms Integration

StaffManager can work with LuckPerms to manage a player's staff group.

This allows StaffManager to connect its internal staff system with the permissions system already used by your server.

For example, when a player is promoted, StaffManager can assign them the configured trainee rank while they work toward their staff goal.

This means you can use StaffManager for tracking and managing staff progression without having to create a completely separate permissions system.

---

### Customizable Displays

StaffManager's displays are highly configurable.

You can customize things such as:

- `/status`
- `/listplayers`
- `/apply`
- Progress bars
- Status text
- Punishment summaries
- Warning displays
- Pagination buttons
- Messages

Text can use Minecraft color codes and StaffManager placeholders, allowing you to match the plugin's appearance to your server.

---

## Who is StaffManager for?

StaffManager is primarily intended for Minecraft servers that have an organized staff team and want a centralized way of managing it.

It can be useful for both smaller servers that want a structured staff progression system and larger servers that need more tools for managing staff and moderation.

You do not need to use every feature.

StaffManager is designed to be configurable, so you can enable or disable different parts of its functionality depending on how your server operates.

---

## How does StaffManager fit into a server?

StaffManager is not intended to replace every plugin on your server.

Instead, it can work alongside the plugins you already use.

For example, a server could use:

- **LuckPerms** for permissions and groups
- **Discord integration** for account linking
- **EssentialsX or LiteBans** for moderation
- **StaffManager** for staff management, progression, tracking, and additional moderation context

This allows StaffManager to act as the central system for your staff team while still letting other plugins handle the things they are designed for.

---

## Ready to try StaffManager?

If StaffManager sounds useful for your server, the next step is to install it and configure it for your server.

**→ [How to Install StaffManager](Installation)**

After installing StaffManager, you can continue with the [Getting Started](Getting-Started) guide to configure your first staff ranks and begin setting up your staff system.
