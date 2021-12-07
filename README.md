## Fake Generic Pocketable Monster RPG Conflict Resolution System

_Fake Generic Pocketable Monster RPG Conflict Resolution System_ was an exercise incorporating all aspects of programming covered in the class, including but not limited to: either user interaction or external data, classes, iteration, and appropriately named variables. For this exercise I implemented a prototype monster conflict resolution system based loosely on concepts from [Pokémon](https://www.pokemon.com/) and the [Versu](https://versu.com/) interactive storytelling platform using [Tracery](https://tracery.io/); a monster appears, the user selects a representative monster, then the user selects actions for their monster to take to attempt to resolve a conflict with the other monster.

### Concepts Included
- Interaction: The user interacts via mouse presses of instanced buttons.
- External Data: Conflict script and character attributes are loaded from JSON files.
- Classes: Uses modification of pre-existing button class and new character class.
- Iteration: Demonstrates three different JavaScript for-loop syntaxes.
- Appropriately named variables: I hope so!

### Outstanding Issues/Bugs

As is, I am unaware of any immediate "bugs," but am very aware of conceptual shortcomings in this rudimentary prototype that could be expanded in the future.

- Conflict script in sampleTextData.json ends up being very repetitive in the current implementation; in the future, I think it would be better to expand usage of Tracery to allow for further variance of character-specific actions and break more descriptive actions into the separate character files.

- Available character actions should be more dependent on the specific character and reactions to previous actions taken.

- For the scope of this prototype only two Character properties were implemented: introversion and energy. This is a deeply flawed system that should definitely be reconsidered and expanded.

- From a design/experience standpoint, UI feedback is almost nonexistent and would need to be implemented/expanded.

### Instructions On Running The Project

If available, the project should be interactable in the iframe below. Should any issues arise, the project can be cloned and src directory opened in Visual Studio Code via LiveServer.

<iframe src="./src/index.html" width="600" height="500"></iframe>
