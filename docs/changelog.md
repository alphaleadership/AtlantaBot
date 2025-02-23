# Changelog

All notable changes to this project will be documented in this file.

## [3.5.0] - 2019-11-07

### Added

*   New `backup` command
*   New `announcement` command
*   New `giveaway` command
*   Users commands cooldown
*   Vote system for `skip` and `stop` commands
*   `-g` option to the help command
*   Translation for commands usage and commands examples
*   The `minecraft` command supports Minecraft Pocket Edition servers

### Changed

*   Now use Discord.js v12.0.0 instead of Discord.js v11.5.0
*   Now use DeepL Translate instead of Yandex Translate
*   Now use MongoDB instead of quick.db
*   Now use Node-Fetch instead of Snekfetch
*   Now use of `let` instead of `var` for a better scoping
*   Clarification of language files
*   Discordbots.org vote is now rewarded with 40 credits
*   Most commands are now available in private messages
*   The `help` command is now paginated
*   `leave` command renamed to `goodbye` command
*   `credits` command renamed to `money` command
*   `warns` command renamed to `sanctions` command
*   All the emojis were updated
*   Update links in the `invite` command
*   Best parse of time

### Removed

*   Blacklist command and blacklist system
*   Dashboard (now in another repository)

## [3.0.0] - 2018-17-04

### Added

*   New `slots` command
*   New `badge` command
*   Welcome and goodbye images
*   New Music category
    * New `play` command
    * New `stop` command
    * New `skip` command
    * New `np` (now playing) command
    * New `pause` command
    * New `resume` command
*   New informations on the `stats` command
*   Support for command aliases
*   Support for translations (english and french)
*   Support for commands in direct messages
*   Two new prefixes: `@Atlanta` and `Atlanta`
*   Warns logs (to have a history of the warns)
*   New available parameters for the `leaderboard` command

### Changed

*   The bot is now 100% open source
*   Cooldown of the work command is now 24h
*   Simplification of the flip command
*   The moderation logs are now more accurate and more beautiful
*   The `ban` command now checks if the user/member is already banned
*   Updates of some controls from an appearance point of view

### Removed

*   Premium version
*   Taxes on the command paid

### Fixed

*   Improved loading speed of the invite command
*   Fix bugs that allowed you to get married to yourself and to get married to two people are fixed
*   Fixed bugs that allowed you to enter any date with the `birthdate` command