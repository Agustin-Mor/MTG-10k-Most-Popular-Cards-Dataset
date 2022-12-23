# MTG_Cards.csv

Has 10 Columns:
1. Index (sorted from most to least popular)
2. Name of Card
3. Card Type[^1]
4. Converted Mana Cost
5. Amount and Type of Color Mana Used[^2]
6. Card Rarity
7. Highest Available Quality[^3]
8. Highest Available Quality Price[^4]
9. Set Released In
10. Card Rules[^5]

[^1] If Card type is a creature, the power and toughness will be displayed before 'Creature.'
For example a power 3 toughness 4 vampire creature would look like this: "3/4 Creature - Vampire"

[^2]
- B - Black Mana 
- U - Blue Mana 
- G - Green Mana 
- R - Red Mana 
- W - White Mana 
- X - X Mana of any color

[^3  Missing values are set to NaN
[^4] Missing values are set to -1

[^5]
- T - Tap Symbol 
- Q - Untap Symbol
