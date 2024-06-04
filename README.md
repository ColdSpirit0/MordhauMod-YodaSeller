# Yoda Seller

Replaces Goblin Seller model from horde to Yoda.


## How to install
1. Create the directory `.../MORDHAUEditor/Mordhau/Mods/YodaSeller`.
2. Move to the directory and open the command prompt.
3. Write `git clone https://github.com/ColdSpirit0/MordhauMod-YodaSeller.git .`


## Config example

```ini
[/Script/Mordhau.MordhauGameSession]
Mods=2713507 ; https://mod.io/g/mordhau/m/yoda-seller

[/Script/Mordhau.MordhauGameMode]
SpawnServerActorsOnMapLoad=/YodaSeller/YodaSellerInit.YodaSellerInit_C
```