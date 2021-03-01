## Commands and Permissions


* **/uecon** to open the Administrative GUI
  (Requires ``ultraeconomy.admin``)
* **/balance** to open the Balance View
  (To use the balance set functionality you need to have ``ultraeconomy.cheat``)
* **/pay (Player) (Currency) (Value)**
  Pay the given *vaulue* of *currency* to a player
  (To use the pay command you need to have ``ultraeconomy.pay``)
* **/trade (Player)** to trade with a specific player 
  To use this feature you need to have ``ultraeconomy.trade``
  
<br />

### Other Commands
* **/addbalance (Player) (Currency) (Value)**
  Add the given *value* as *currency* to the *players* balance
* **/removebalance (Player) (Currency) (Value)**
  Add the given *value* as *currency* to the *players* balance
* **/setbalance (Player) (Currency) (Value)**
  Set a value as *currency* to the *players* balance  
* **/balancetop (currency) | /baltop (currency)**
  Look at the top 10 players balance for the selected currency.
  (To use the balancetop command you need to have ``ultraeconomy.balancetop``)
  
### Placeholders
``%uecon_balance_###_total%`` 
To get the total balance of a player
``%uecon_balance_###_hand%``
To get the hand balance of a player
``%uecon_balance_###_bank%``
To get the bank balance of a player
``%uecon_balancetop_<currency>_name_<place>``
To get the name of a player who is in a specific place from baltop
``%uecon_balancetop_<currency>_balance_<place>``
To get the top amount of a specific currency a player in a specific spot has
``%uecon_balance_<currency>_total_unformatted%``
Get the total balance of a player without formating like color or name.
``%uecon_balance_<currency>_hand_unformatted%``
Get the total hand balance of a player without formating like color or name.
``%uecon_balance_<currency>_bank_unformatted%``
Get the total bank balance of a player without formating like color or name.
   
<br />

All of these commands require the ``ultraeconomy.admin`` permission, if you plan to use them manually.
