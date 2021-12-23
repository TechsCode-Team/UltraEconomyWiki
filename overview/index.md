# Welcome!
Welcome to the Wiki page of **Ultra Economy**, where you can find all the information and documentation. You can navigate the wiki using the sidebar on the right.
<br>

## Contact
You can communicate with our support team by joining our **[Discord](https://discord.gg/3JuHDm8)**. It is the only way we can give you support once you have verified your purchase.
<br>

## What can you find on the wiki?
- [Commands](/wiki/overview) - The list of commands
- [Permissions](/wiki/overview) - The list of permissions
- [Installation Guide](/wiki/installation) - A quick guide on how to install Ultra Economy
- [Features](/wiki/features) - A list with all the features of Ultra Economy
- [API](/wiki/api) - A guide on how to use the API for developers

# Commands
Here is a list of all the commands that can be used.
<br>

* `/uecon`
  To open the Administrative GUI
* `/balance [Player]`
  To open the ballance view from your self or others
* `/pay <Player> <Currency> <Value>`
  Pay the given value of currency to a player
* `/trade <Player>`
  Trade with a specifick player
* `/trade-accept <Player>`
  Accept a trade request with a specifick player
* `/trade-decline <Player>`
  Deny a trade request with a sepcifick player
* `/balancetop <Currency> | /baltop <Currency>`
  To view the top 10 players balance for the selected currency
* `/addbalance <Player> <Currency> <Value>`
  Add the given value of a currency of a players balance
* `/removebalance <Player> <Currency> <Value>`
  Remove the given value of a currency of a players balance
* `/setbalance <Player> <Currency> <Value>`
  Set the given value of a currency of a players balance
  <br>

## Symbols:
- <> = Required
- [] = Optional

# Permissions
Here is a list of all the permissions that can be used
<br>

* `ultraeconomy.admin`
  The main permission of Ultra Economy
* `ultraeconomy.pay`
  Be able to pay another player
* `ultraeconomy.balancetop`
  Be able to see the top 5 of a balance
* `ultraeconomy.balance.self`
  Be able to see the balance of your self
* `ultraeconomy.balance.others`
  Be able to see the balance of others
* `ultraeconomy.trade`
  Be able to trade with other players
* `ultraeconomy.cheat`
  Cheating balance through GUI

# Placeholders
Below is a list of all available placeholders. Keep in mind these placeholders require **[PlaceholderAPI](https://www.spigotmc.org/resources/6245/)** & a plugin that supports the API!
<br>

* `%uecon_balance_{currency}_total%`
  This will show the total balance of the player
* `%uecon_balance_{currency}_hand%`
  This will show the balance in the players hand
<!--* %uecon_balance_{currency}_bank% Ex. `49.000`
  This will show the balance in the players bank-->
* `%uecon_balancetop_{currency}_name_{place}%`
  This will show the player name on place ... of the balance top
* `%uecon_balancetop_{currency}_balance_{place}%`
  This will show the balance on place ... of the balance top
* `%uecon_balance_{currency}_total_unformatted%`
  This will show the total balance on the whole server unformatted
* `%uecon_balance_{currency}_hand_unformatted%`
  This will show the total hand balance on the whole server formatted
* `%uecon_balance_{currency}_bank_unformatted%`
  This will show the total bank balance on the whole server unformatted
* `%uecon_balance_CURRENCY_server%`
  This will show the entire server balance of a specific currency
* `%uecon_balance_CURRENCY_server_unformatted%`
  This will show the entire server balance of a specific currency unformatted