# Homebrew Consume Example

Please use this as an example only! This is not designed to be used as is, and you are fully capable of editing it.

**JSON example**
```json
[
  {
    "fancyName": "Example Drink",
    "name": "example-drink",
    "type": "Example Drink",
    "cost": "8",
    "coinType": "cp",
    "intox": "+1",
    "desc": "This beer is only fancy because it's in glass cup instead of wooden cup."
  },
  "Another Item Like Above"
]
```

**YMAL IS SUPPORTED**
```yaml
!svar hbConsume 
---
- fancyName: Example Drink
  # `fancyName` will present what you put in for it, so this will present "Example Drink" as it's name. 
  name: example-drink
  # `name` sets up the command, so this drink will be called via `!consume hb example-drink`
  type: Example Drink
  # `type` defines it as what type of item it is. Any item with the same type will show up under the same header within the catalogue when presented. 
  cost: '8'
  # `cost` sets up the ammount of coins it will take out.
  coinType: cp
  # `coinType` sets the type of coin, and will take out `cost` amount of that type of coin. It must be in cp (Copper Pieces), sp (Silver Pieces), ep (Electurm Pieces), gp (Gold Pieces), or pp (Platnium Pieces) form
  intox: "+1"
  # `intoxLevel` sets the Intoxication Modifire for the item. 
  desc: This beer is only fancy because it's in glass cup instead of wooden cup.
- Another Item Like Above
```
**__Delete all `#` messages when making the svar, or it will error.__**
