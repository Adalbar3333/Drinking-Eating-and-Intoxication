# Homebrew Consume Example

```!svar hbConsume
[{
# `fancyName` will present what you put in for it, so this will present "Example Drink" as it's name. 
"fancyName":"Example Drink",

# `name` sets up the command, so this drink will be called via `!consume hb example-drink`
"name":"example-drink",
# `type` defines it as what type of item it is. Any item with the same type will show up under the same header within the catalogue when presented. 
"type":"Example Drink",

# `cost` sets up the ammount of coins it will take out. 
"cost":"8",

# `coinType` sets the type of coin, and will take out `cost` amount of that type of coin. It must be in cp (Copper Pieces), sp (Silver Pieces), ep (Electurm Pieces), gp (Gold Pieces), or pp (Platnium Pieces) form
"coinType":"cp",

# `intoxLevel` sets the Intoxication Modifire for the item. 
"intox":"+1",
"desc":"This beer is only fancy because it's in glass cup instead of wooden cup."

},{another item set up like above.}]

# Delete all `#` messages when making the svar, or it will error. 
```
