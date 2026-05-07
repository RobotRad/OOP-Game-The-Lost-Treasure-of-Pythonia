# OOP Game - The Lost Treasure of Pythonia
**Objective:** Create a text-based adventure game using Python classes and object-oriented programming principles.

**Scenario:** The player is an adventurer searching for the Lost Treasure of Pythonia, hidden deep within a mysterious jungle. The player must navigate through different locations, interact with characters, solve puzzles, and collect items to progress in the game.

### Classes to Implement:
## Player:
**Attributes:** name, health, inventory, current_location\
**Methods:** move(direction), take_item(item), use_item(item), check_inventory(), attack(enemy)
## Location:
**Attributes:** name, description, items, exits, characters, puzzle\
**Methods:** enter_location(), look_around(), get_item(item_name), solve_puzzle(solution)
## Character: (Non-Player Characters - NPCs)
**Attributes:** name, dialogue, item (optional)\
**Methods:** talk(), give_item() (optional)
## Enemy:
**Attributes:** name, health, attack_strength\
**Methods:** attack(player), is_defeated()
## Item:
**Attributes:** name, description, use_function (optional)
## Puzzle:
**Attributes:** description, solution, hint (optional)\
**Methods:** check_solution(attempt)
