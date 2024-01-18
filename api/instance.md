# using the API instance

With the API instance you are able to access the storage, actions and events of Ultra Economy.

## API methods

Down below is the list of available methods inside the Ultra Economy API instance. These methods can be used to access the storage of Ultra Economy.

```java
/**
 * The main instance of the UltraEconomyAPI
 */
public interface UltraEconomyAPI {

    /**
     * Retrieve all registered Player accounts
     */
    AccountList getAccounts();

    /**
     * Retrieve all currencies
     */
    CurrencyList getCurrencies();

    /**
     * Retrieve all transactions made (Currency)
     */
    TransactionList getTransactions();

    /**
     * Retrieve all trades that have been made
     */
    LoggedTradeList getLoggedTrades();

    /**
     * Retrieve all registered bank accounts
     */
    BankAccountList getBankAccounts();

    /**
     * Retrieve the drop money on death system settings
     */
    LoseMoneyOnDeathRegistry getDropMoneyOnDeathRegistry();

    /**
     * Retrieve all the bank feature settings
     */
    BankFeatureRegistry getBankFeatureRegistry();
    
    /**
     * Retrieve all the local settings (Database, Language, and appearance)
     */
    LocalRegistry getLocalRegistry();
    
    /**
     * Retrieve mob drop system settings
     */
    MobDropsRegistry getMobDropsRegistry();
    
    /**
     * Retrieve disabled world for money on death system
     */
    DisabledLoseMoneyOnDeathWorldsRegistry getDisabledLoseMoneyOnDeathWorldsRegistry();
    
    /**
     * Retrieve all trading system settings
     */
    TradeSystemRegistry getTradeSystemRegistry();
    
    /**
     * Rettrieve the currency that is set to Vault
     */
    Optional<Currency> getVaultCurrency();

    /**
     * Get all available servers for Ultra Economy
     */
    ServerList getAvailableServers();
}
```