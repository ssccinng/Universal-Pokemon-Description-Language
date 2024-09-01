Universal Pokémon Description Language (UPDL) Syntax Documentation
1. Overview
The Universal Pokémon Description Language (UPDL) provides a standardized method to describe Pokémon attributes, abilities, stats, and movesets. This documentation outlines the syntax used to accurately represent a Pokémon's details in UPDL.

2. Syntax Structure
A UPDL description includes the following components:

Name, Gender, and Item
Ability
Level
Shiny Status
Tera Type
Effort Values (EVs)
Nature
Individual Values (IVs)
Moves
3. Example
Here is an example UPDL representation:

scss
Copy code
Primarina (F) @ Aguav Berry  
Ability: Torrent  
Level: 70  
Shiny: Yes  
Tera Type: Dark  
EVs: 4 HP / 44 Atk / 4 Def / 4 SpA / 4 SpD / 4 Spe  
Mild Nature  
IVs: 0 HP / 0 Atk / 0 Def / 0 SpA / 0 SpD / 0 Spe  
- Acrobatics  
- Chilling Water  
- Haze  
- Ice Beam
4. Component Descriptions
Name, Gender, and Item

Format: <Name> (<Gender>) @ <Item>
Description: Represents the Pokémon's name, gender (if specified), and the held item.
Example: Primarina (F) @ Aguav Berry
Ability

Format: Ability: <AbilityName>
Description: Indicates the Pokémon's ability.
Example: Ability: Torrent
Level

Format: Level: <LevelNumber>
Description: Specifies the Pokémon's level.
Example: Level: 70
Shiny Status

Format: Shiny: Yes/No
Description: Indicates whether the Pokémon is shiny.
Example: Shiny: Yes
Tera Type

Format: Tera Type: <Type>
Description: Specifies the Pokémon's Tera type.
Example: Tera Type: Dark
Effort Values (EVs)

Format: EVs: <HP EV> HP / <Atk EV> Atk / <Def EV> Def / <SpA EV> SpA / <SpD EV> SpD / <Spe EV> Spe
Description: Represents the Pokémon's distribution of Effort Values across its stats.
Example: EVs: 4 HP / 44 Atk / 4 Def / 4 SpA / 4 SpD / 4 Spe
Nature

Format: <Nature> Nature
Description: Specifies the Pokémon's nature.
Example: Mild Nature
Individual Values (IVs)

Format: IVs: <HP IV> HP / <Atk IV> Atk / <Def IV> Def / <SpA IV> SpA / <SpD IV> SpD / <Spe IV> Spe
Description: Represents the Pokémon's distribution of Individual Values across its stats.
Example: IVs: 0 HP / 0 Atk / 0 Def / 0 SpA / 0 SpD / 0 Spe
Moves

Format: - <Move1>, - <Move2>, etc.
Description: Lists the Pokémon's moves.
Example:
diff
Copy code
- Acrobatics  
- Chilling Water  
- Haze  
- Ice Beam
5. Additional Notes
Order: The components must be listed in the specified order: Name, Gender, and Item; Ability; Level; Shiny Status; Tera Type; EVs; Nature; IVs; Moves.
Newlines: Each component is separated by a newline.
Moves: Moves are listed with a hyphen and a space before each move name.
Optional Components: Gender and Shiny Status are optional; if not specified, they can be omitted.
This syntax ensures a comprehensive and consistent description of Pokémon, making it easier to share and understand complex builds.