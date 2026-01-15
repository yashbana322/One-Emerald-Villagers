# One-Emerald-Villagers
Vanilla commands to convert selected villagers into 1-emerald infinite traders
One Emerald Villagers (Commands Only)

Convert selected villagers into 1-emerald, infinite-trade villagers using vanilla Minecraft commands only.

No datapacks.
No plugins.
No mods.

Designed for builders, creative-style survival, and servers that want freedom without breaking gameplay.

🔹 Features

Set villager trades to cost 1 item / 1 emerald

Infinite trade uses

No price inflation

Safe and controlled (opt-in only)

Works on:

Vanilla

Paper

Aternos

Compatible with Minecraft 1.20+ (including 1.21.x)

🔹 Why this exists

Villager trading is partially hard-coded in Minecraft.
There is no reliable vanilla way to globally set all villager trades to 1 emerald.

This project provides a safe, command-only solution that works consistently on real servers.

🔹 How it works (important)

This system modifies villager trade data directly using NBT commands.

Only villagers explicitly named by the user are affected.

This prevents:

Accidental world-wide changes

Breaking survival progression

Plugin conflicts

🔹 How to use
Step 1 — Prepare the villager

Let the villager generate the trades you want

Trade once to lock them

Do NOT break the workstation

Step 2 — Name the villager

Use a name tag:

OneEmerald

Step 3 — Run the commands

Run the commands from commands.txt once.

That villager is now permanently converted.

🔹 Commands included

The commands:

Reduce all trade prices to 1

Set infinite trade uses

Reset locked trades

Remove demand-based price increases

Each command is explained in detail in explanation.md.

🔹 Why this does NOT use datapacks

Datapacks:

Cannot intercept villager trade creation

Cannot reliably modify trades on generation

Are often overridden by server software and plugins

Commands are the only guaranteed method without plugins.

Full explanation is provided in explanation.md.

🔹 Safety & limitations

Only named villagers are affected

Existing villagers must be converted manually

Plugins that rewrite villager trades may override changes

Commands may need to be re-run if a plugin resets trades

This is a deliberate design choice for safety.

🔹 Who this is for

Builders

Creative-style survival servers

SMPs with shared resources

Players who want freedom without global cheats

🔹 License

This project is free to use and share.
See LICENSE for details.

🔹 Support

If you run into issues:

Double-check the villager name

Ensure trades are already generated

Verify no plugin is overriding villager behavior

You may open an issue or contact the maintainer.
