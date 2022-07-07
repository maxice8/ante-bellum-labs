# ante-bellum-labs

## can-increase-stab

This features replaces the 1000%+ stability cost applied to Francia and Andalusia until they fix their starting crisis with a scripted effect that disables the ability to boost up stability completely.

##### Advantages

- Simpler code, easier to understand and reason about
- Less code
- Custom messages for Francia and Andalusia
- Avoids any possible mana-generation exploits

##### Disavantages

- Not as battle-tested as the old code which just works

### How to install it

1. Copy `common/scipted_functions/00_scripted_functions.txt` from the base game into the Ante Bellum mod folder.
2. replace the `can_increase_stability = { }` block with the one from this repository.
3. Add the 2 lines of localization from this repository to the localization of Ante Bellum, more specifically in `localisation/AB_modifier_l_english.yml`.
