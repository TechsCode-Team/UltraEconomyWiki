## Troubleshooting guide
<br>

**`My plugin is not connecting to MySQL`**
* If your plugin is not connecting to MySQL or is taking to long to test the connection it means that you have filled in the wrong credentials, or haven't setup your MySQL correctly on your hosting provider's end.
<br>

**`Proxy isn't connected`**
* If your proxy isn't connected you need to do it manually.
  First, we need the MySQL key from a connected server. 
  This can be found in there *\SERVER_DIRECTORY\plugins\UltraEconomy*. 
  Here you need to copy the MySQL key, and paste it inside the config of the proxy (same directory as above).
<br>

**`NOTE:` This key can continue on a second line, so make sure to copy it all!**
<br>

**`The /pay command is tab completed wrong, how do I fix it?`**
*  This is a common problem when combining **UltraEconomy** and **CMI**.
   Open your **CMI plugin folder**, then the **Settings folder** in which
    open the **Alias.yml file**.
   Find the command **/pay** and change the status of the following elements:
    `Enabled:` **false**
    `Tab:` **false**   
<br>

**`I am experiencing issues with syncing currency with my other servers on the proxy.`**
*  Increase your ingame max connections value.
*  Follow this path to know how to increase the value:
   `Phpmyadmin >> settings >> variables >> max connections`