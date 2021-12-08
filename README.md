## Fake Generic Pocketable Monster RPG Conflict Resolution System

_Fake Generic Pocketable Monster RPG Conflict Resolution System_ was an exercise incorporating all aspects of programming covered in UCF's Fall 2021 Programming for Digital Media class, including but not limited to: either user interaction or external data, classes, iteration, and appropriately named variables. For this exercise I implemented a prototype monster conflict resolution system based loosely on concepts from [Pokémon](https://www.pokemon.com/) and the [Versu](https://versu.com/) interactive storytelling platform using [Tracery](https://tracery.io/); a monster appears, the user selects a representative monster, then the user selects actions for their monster to take to attempt to resolve a conflict with the other monster.

### Concepts Included
- Interaction: The user interacts via mouse presses of instanced buttons.
- External Data: Conflict script and character attributes are loaded from JSON files.
- Classes: Uses modification of pre-existing button class and new character class.
- Iteration: Demonstrates three different JavaScript for-loop syntaxes.
- Appropriately named variables: I hope so!

### Outstanding Issues/Bugs

As is, I am unaware of any immediate "bugs," but am very aware of conceptual shortcomings in this rudimentary prototype that could be expanded in the future.

- Conflict script in sampleTextData.json ends up being very repetitive in the current implementation; in the future, I think it would be better to expand usage of Tracery to allow for further variance of character-specific actions and break more descriptive actions into the separate character files. This ties heavily into the next bullet point.

- Available character actions should be more dependent on the specific character and reactions to previous actions taken. In other words, the conflict JSON may better be represented as conflict "events," while available "actions" and their effects may be better dictated by the predilections of specific characters.

- For the scope of this prototype only two Character properties were implemented: introversion and energy. This is a deeply flawed system that should definitely be reconsidered and expanded.

- How the antagonistic monster chooses actions should be reconsidered with application of the monster's properties included in its decision-making process (currently random based on available options in the current text node).

- Action effects should be rebalanced and made more systemically meaningful. 

- From a design/experience standpoint, UI feedback is almost nonexistent and would need to be implemented/expanded.

### Instructions On Running The Project

If you are viewing this page on its associated [GitHub Pages implementation](https://thatwhichis.github.io/pfdm_fp_conflict-resolution/) (not the base repository on [GitHub dot com](https://github.com/thatwhichis/pfdm_fp_conflict-resolution)), it should be playable in the iframe below. Should any issues arise, the project can be [cloned](https://github.com/thatwhichis/pfdm_fp_conflict-resolution.git) and src directory opened from [Visual Studio Code](https://code.visualstudio.com/) via [LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).

<iframe src="./src/index.html" width="600" height="500"></iframe>
