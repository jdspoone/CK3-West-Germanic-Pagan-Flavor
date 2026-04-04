# West Germanic Pagan Flavor **Updated for Crusader Kings 1.19**
A simple mod attempting to add a bit more flavour for West Germanic (e.g. Anglo-Saxon) pagans. 

## Current Features

### **West Germanic Warfare** - New Cultural Tradition
West Germanic cultures now have access to a new cultural tradition **West Germanic Warfare**, which is used in place of **Hirds** for the Anglo-Saxon culture. This cultural tradition unlocks recruitment Huscarls and Gesitha, a new Heavy Infantry unit roughly equivalent to Varangian Veterans.

### **Eseism** - New West Germanic Pagan Faith 
Inspired by [The Fallen Eagle](https://steamcommunity.com/workshop/filedetails/?id=2243307127), this mod adds a new West Germanic pagan faith, **Eseism**, within the broader Germanic Religion.

### Longship Funeral Tradition for Germanic Pagan Faiths
Germanic faiths, namely Asatru and Eseism, now have a new funeral tradition, Longship Funerals.

At present the Longship Funeral tradition is just a clone of the Cremation funeral tradition, but I am planning to implement new longship-focused funeral content.

### West Germanic / Eseist Related Decisions

##### Eseism Conversion Decision
West Germanic Christian rulers whose primary title is within England or Scotland can convert via decision to Eseism. To assist with realm stability (primarily for underwhelming AI rulers), the ruler's capital county will receive a positive modifier and convert to Eseism as well, and the ruler will receive a small army of special soldiers. AI Rulers are required to be a Duke or an Independent Count, while no such restrictions apply to Player Characters. AI rulers have a chance of taking this decision depending on their personality and the cultural era.

The historical record would indicate that Anglo-Saxon lords would intermittently renounce Christianity and re-embrace the Germanic faith well after the supposed wholesale adoption of Christianity. This decision attempts to model this in game. This should have the effect of creating a more dynamic political landscape within England and the lowlands of Scotland.

#### Convert Canterbury Cathedral to a Germanic Temple
Rulers of a Germanic faith can replace the Canterbury Cathedral with a Germanic Temple. An equivalent but inverted decision exists for Christian rulers to restore the Canterbury Cathedral to its original state.

### Re-consecrate Winchester Minster as a Germanic Temple
If [Medieval Arts](https://steamcommunity.com/sharedfiles/filedetails/?id=2452585382) is in your modlist, rulers of a Germanic faith can re-consecrate the Winchester Minster as a Germanic Temple, allowing you to not only enjoy the fantastic 3D model by PiGu, but to reap the benefits of the special building without being of a Christian faith!

#### Discover Norse Longships
West Germanic rulers who are friends with a North Germanic ruler of a faith within the same religious family can discover the Longships innovation for their culture.

At present this decision is fairly simple, but I plan to extend it to include a travel event involving a number of skill checks which will determine the success or failure of the event.

## Dependencies and Recommendations
This mod makes use of content from the [Northern Lords DLC](https://store.steampowered.com/app/1303183/Crusader_Kings_III_Northern_Lords/).

While not required, I strongly recommend using this mod alongside the following mods:
- [Medieval Arts](https://steamcommunity.com/sharedfiles/filedetails/?id=2452585382)
- [Anglo Saxon Flavorization](https://steamcommunity.com/sharedfiles/filedetails/?id=3630785964)

## Compatibility
This mod overrides the following definitions:
- *hostility_group* in *common/religion/doctrine_group_types/00_doctrine_group_types.txt*
- *doctrine_funeral* in *common/religion/doctrine_group_types/00_doctrine_group_types.txt*
- *germanic_religion* in *common/religion/religions/00_germanic.txt*, and associated English language localizations
- *activity_funeral* in *common_activities/activity_types/funeral.txt*
Any other mods overriding these same definitions will likely be incompatible.

## Credits
- [The Fallen Eagle](https://steamcommunity.com/workshop/filedetails/?id=2243307127)'s implementation of Eseism was used as a guide for my own, and I have used their Eseism-specific English localizations without changes.

## Feedback
Please feel free to leave any feedback in the comments!