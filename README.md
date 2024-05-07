# FlagsDex Discord Bot | Privacy Policy

------------------------------------------------------------------------------------------------------------------------------------------------------------------
**The following document explains what data is collected by FlagsDex.**

### Things to Note

- "Application" or "Discord Application" is referred to the Discord bot user. Its associated owners and the servers is has
- "Data" is referred to data stored by an individual instance, including personal data
- "Bot" or "Instance" is referred to the copy of the code running the Discord application, with its own data
- "Collectible" is referred to any object that is meant to be collected, in that case those are flags, a virtual sort of a currency.
- "Application Owner" is referred to the owner of the Discord application, meaning the one with any form of access to the application's authentication method and data belonging to the instance
- "FlagsDex Staff Team" or "Staff Team" is referred to the owner of the Discord application and the users they may chose to be part of the staff team. You may find a list of these users on the [Official FlagsDex Discord Server](https://discord.gg/3bBwY9AYWU).

### Open Source

The code of FlagsDex is available and taken from https://github.com/laggron42/BallsDex-DiscordBot. A copy of the licence can be found in there.

**The instance is guaranteed to be running an exact copy of the code made open source.** The version may not be the latest available, but no local changes will be made. This may change, but users should be notified in the [Official FlagsDex Discord Server](https://discord.gg/3bBwY9AYWU) about any changes.

You may check the source code and see how the data is managed, in addition to the following policy.

### What data is collected?

FlagsDex **only** collects the following data from Discord:
- **User IDs** | This is used to identify you inside our database
- **Server (or Guild) IDs** | This is used to store settings necessary to the bot's operation
- **Channel IDs** | This is used to know in which channel should the collectibles spawn

Additionally, the following data proper to FlagsDex is both created and used:
- **The list of collectibles owned by a user of the service**
- **A history of trades done on collectibles, including the users that once owned the said collectible but do not anymore**

### How the data is stored?
All data is stored on a PostgreSQL server, running on a Docker Desktop Virtual Machine hosted by kotobc, the owner of FlagsDex.

Interaction between the bot and the database server is exclusively local using [Tortoise ORM](https://github.com/tortoise/tortoise-orm).

### Access to the data
The only person who is allowed to access the data is the application owner.

An application owner may interact with the bot and the administrator interface. Only `kotobc` has direct access on the hosting machine.

The FlagsDex staff team **do not have access to the data.**

**The data is never going to be made available to the public**. Access to the data must and will be secured accordingly.

### Your rights

You may request a copy or the delection of your personal data held by the application by contacting the application owner. This can be done by joining our [Official FlagsDex Discord Server](https://discord.gg/3bBwY9AYWU) and DM kotobc. Sending a request to the application owner (kotobc) is also available.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
`Privacy Policy was lastly updated: ??? | Created on: 07/05/2024 (7th May, 2024)`
