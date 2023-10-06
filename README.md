# ezmullvad
Simple bash front-end for Mullvad VPN.

Copy contents of the ```ezmullvad``` file to your ```.bash_aliases``` file.

Use ```mc <Country code>``` to connect or ```mc``` to connect to default location. You can change default location by changing country code in ```mullvad_connect``` function.

For example:

```
country="${1:-ch}"
```
sets the default location to Switzerland,
```
country="${1:-us}"
```
sets the default location to USA.

Use ```md``` to disconnect.

Use ```ms``` to see the status of your connection.

Use ```ml``` to see and ```ml on``` or ```ml off``` to change local network sharing setting.

You can comment out ```mullvad lockdown-mode set on``` and ```mullvad lockdown-mode set off``` according to your preference.
