# Set-AzureIKEPolicy

This script allows for the creation and setting of Azure VPN IKE policies easily since there is no way to do it within the Portal, in addition to all of the required parameters requires to actually set it through Powershell.

### Installation/Usage

This script requires Powershell v4+ to run properly. 

Prior to running the script, you should log into Azure and select the appropriate Subscription context. 

```powershell
PS> Add-AzureRmAccount
PS> Select-AzureRmSubscription -SubscriptionId
```
This script can be run either within a normal Powershell ISE window or within VSCode. Please note when running inside of VSCode the **help text will not be available.**

The script can be either run as a whole and invoked using

```powershell
PS> Update-VPNIKEPolicy
```
Using this method will prompt you for all of the required parameters needed prior to executing the task. You can use **!?** to get more information on what the prompt is looking for if you aren't sure.
![Example of it running as whole function](https://i.imgur.com/jRf8xtv.gif)

You can also load the script up and run the individual functions. There is a parameter set that allows you to tab complete through the accepted values.
![Tab completion](https://i.imgur.com/OHGrspp.gif)
