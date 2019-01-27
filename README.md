Even after the patch that removed many leather types, I felt like the game had too many leathers.
Many were almost identical in stats, but different enough to make me want to min-max them.
In theory, that would be an interesting little puzzle.
However, most leathers are out-classed by a few good leathers or devilstrand, which is relatively easy to grow.
Thus, most leathers in the game are effectively clutter / vendor-trash, that you need to work around constantly
in your stockpiles, recipes, etc.
I've removed, renamed, or reworked all the leathers, so that there's less of them total.

Another problem in the base game, is patchleather.
The only reason for it to be in the game, is so that players can consolidate different piles of leather,
which are otherwise too small to make a piece of clothing from.
However, the stats for patchleather are so bad, that no player would ever want to use it;
It's got worse stats than even the worst leathers, and it's worse than basic cloth for temperature.
It's just vendor-trash.
Since I've removed most of the leather types, there shouldn't be much need for patchleather recipes.

Animals which produce wools now no longer have special leathers.
You can either butcher them for wool and some plainleather, or keep them alive to sheer wool.
This was partly to remove clutter, but also because it seemed weird, that I could harvest hairs from an alive animal,
but when butchered the hairs were somehow magically attached to the skin, completely impossible to remove.
It also differentiates them more from animals whose hide is thick enough, or the hairs short enough,
that the hairs are always attached to the hide, like wolf pelts or bear hides.

Some animals now give other materials when butchered, which can be used as replacements in some recipes.
Birds give down feathers, which can be used in jackets and parkas.
Insects and tortoises give shells, which can be used in plate armor, armor vests, and flak pants and jackets.

# TODO
## Colors
With the removal of so many leathers, there's less options for coloring clothing and chairs.
Instead of cluttering up the balance-space of numbers, I've added colored variants of the leathers, and recipes to change colors.
I haven't figured out a way to set the color of a leather just with a recipe in XML, so these will actually be seperate leather types in the game,
unlike how cloth colors work in the game.
To keep them from cluttering up the UI, they're in new categories like "Red Leathers", so that players can click around them quickly.

## Butcher
- wools
- insect shells
- tortoise shells
