![Open Legend RPG Logo](http://www.openlegendrpg.com/assets/img/open_legend_lg_logo.png)

# Open Legend Core Rules

Included here in [YAML format](https://en.wikipedia.org/wiki/YAML) are the rules which are published to the [www.openlegendrpg.com](http://www.openlegendrpg.com) website. Feel free to open a pull request to propose improvements to any of the rules, add new feats, or otherwise start a discussion pertaining to the rules text. Note that any contribution will require that you preserve the valid YAML syntax, otherwise the website will break as a result of your changes. If you're not sure, use [this site](http://yaml-online-parser.appspot.com/) to validate your YAML outputs valid JSON.

## Open Legend Community License

The game rules content of this repository are released under a special open-source license that offers third party publishers the opportunity to use the game rules as well as designated Open Legend logo royalty-free in their own commercial or non-commercial projects via the [Open Legend Community License](https://github.com/openlegend/core-rules/blob/master/LICENSE.md#open-legend-community-license).

## Changelog

Click [Here](https://github.com/openlegend/core-rules/commits/master) to see changes in more detail.

#### 2017 / 02 / 02
-   `Summon Creature` no longer has a permanent option, creating permanent creatures is reserved as an effect for only the `Animation` boon.
-   `Animation` boon now has the additional effect of automatically invoking the `Charmed` bane on a newly created creature.

#### 2017 / 01 / 18
-   `Armory Mastery` feat effect wording changed from Might to Fortitude to match recent armor changes.
-   `Natural Defense` feat Fortitude prerequisites reduced for each tier from 2/3/5 to 0/1/2.
-   `Two Weapon Defense` feat wording clarifies the armor bonus is for the Guard defense.
-   `Defensive` property of weapons now grants a non-stacking +1 armor bonus, regardless of Defensive level. `Defensive Mastery` feat wording clarified for its bonus to stack an addition +1 armor bonus.
-   NPCs now have a new feat open to them (GM Only): Bane Resistance, with two tiers (+5 defense and immunity to a specific bane).
-   `Sylvan Ally` perk renamed `Nature's Ally`.
-   `Shapeshift` boon effect layout clarified for Power Level 2. Also, wording improved for multiple genres.
-   `Multi-Target Attack Specialist` wording fixed to refer to **multi-targeting**, not multi-attacks.

#### 2017 / 01 / 15
-   Added Power Level 2 to `Shapeshift` boon
-   You can now move your `Phantasm` as a free action on your turn, but it must remain within your invocation range.
-   `Defend` action clarified. A single defend action can only be used to defend one target. Movement granted by this action doesn't provoke attack of opportunity, nor does it negate the original attack.

#### 2017 / 01 / 13
-   `Breakfall` now works in two tier. Tier 1 reduces all falling damage if you are not incapacitated. Tier 2 renders you immune to falling damage if you are not incapacitated. Cost increased to 2.

#### 2017 / 01 / 10
-   Recalculated weapon's Wealth Level

#### 2017 / 01 / 08
-   Tweak `Delayed Ready` property to require the ready action before use, so that weapons with `Consumable` property don’t get the free benefit of bypassing the ready action

#### 2017 / 01 / 06
-   Changed armor prerequisites to `Fortitude` instead of `Might`. This addresses a balance concern about `Might` characters having an unfair advantage with their `Guard` defense since armor had a `Might` prerequisite that made it difficult for `Agility` based characters to qualify for. `Fortitude` is useful for ALL characters as it makes you harder to kill with higher `Toughness`, HP, and now armor as well.
-   `Battle Trance` feat modified to provide bonus to armor for characters with an armor bonus less than 3.
-   Removed `Defensive` property from a few weapons since it would prevent them from getting the two-handed bonus to attacks
-   **Unmovable Weapons** are now called `Stationary` since they are ... well ... not unmovable.
-   **Deadly Weapons** now require a minimum wealth level of 4, and `Deadly` does not stack with itself. Only the greatest value among items you wield applies.
-   **Defensive Weapons** no longer gain advantage on attack rolls for dual wielding or being used two-handed. This property no longer stacks.
-   Fix a number of weapon properties and add missing `Longsword` example
-   Fix incorrect cost of `Extraordinary Defense` (now 3 feat points) and `Natural Defense` (now 2 feat points)
-   **Major Change to Evasion / Resilience Defense** - due to the words `Resilience` and `Toughness` being too similar, `Resilience` (formerly `Evasion`) is now called `Guard`

#### 2017 / 01 / 02
-   **Major Change to Weapons** - Weapons now include multiple examples of each type that shares the same properties and now have a `Category` which determines the various ways it can be used.
-   Added a `Building Your Own Weapons` table that shows the process for building a balanced weapon
-   **Major Change to Evasion** - the `Evasion` defense score has been changed and renamed to `Resilience` which is calculated as: `Resilience = 10 + Agility + Might + Armor` and bane defense targets have been changed to accommodate the difference
-   **Major Change to Armor** - For multi-genre purposes, and coinciding with the change from `Evasion` => `Resilience`, Armor now has three categories: `Light`, `Medium`, and `Heavy` and is simplified in the interest of making it easier to understand where armor that is not accounted for on the table should fall on the spectrum
-   `Battle Trance`, `Armor Mastery`, `Natural Defense`, `Two Weapon Defense` are updated to accommodate the new Armor rules
-   `Armor Mastery` cost increased to 3. Tier III removed.
-   `Defensive Mastery` feat added to accompany shields and new weapons with the `Defensive` property
-   Clarify shifting between multiple `Alternate Form`s

#### 2017 / 01 / 01
-   Fix `Invisible` and `Blinded` banes so they don’t violate Open Legend’s "one roll" principle. Also clean up various other issues with both and add a “lesser” Invisible at PL 5.

#### 2016 / 12 / 31
-   Close loophole in `Summon Creature` boon that allowed them to recursively summon others of their type. Also clarified that summoned creatures cannot be revived from zero hit points.
-   `Indomitable Endurance` feat was tweaked to allow access via a Will attribute prerequisite, also removed the immunity to natural fatigue since the feat already shields against the first level of fatigue and 2 feat points for such a potent effect is overpowered.
-   Rename `Berserker` feat to `Battle Trance`, and associated feat name updates (`Deathless Berserker` => `Deathless Trance`, `Destructive Berserker` => `Destructive Trance`, `Entranced Berserker` => `Impervious Trance`, `Reactionary Berserker` => `Reactionary Trance`)
-   `Resilient` was both a feat and a perk, the `Resilient` perk was renamed to `Inner Strength` for clarity
-   `Companion` feat now grants access to 1 feat per tier, selected from the "Simple Build" NPC creation list in Chapter 7: Running the Game
-   Changed wording around handling “advantage zero”, other non-action rolls, and the ability to say “advantage x” for any type of die roll. You can now apply "advantage 1" to a Resist roll, for example, but a roll without attribute dice can not be modified beyond Advantage 1 or Disadvantage 1
-   Tweaked the Power Levels of `Persistent Damage` bane, they are now: 4 (d6) / 6 (d8) / 8 (d10) / 9 (2d6)

#### 2016 / 12 / 30
-   `Lethal Damage` is now part of the `Core Rules`
-   `Critical Hits` are now optional

#### 2016 / 12 / 28
-   Removed `Retributive Barrier` in favor of `Barrier` boon
-   `Forced Move` now moves the target a distance in feet based on power level
-   `Projectile Multi-Targeting` is now `Ranged Multi-Targeting`
-   `Attribute Substitution` cost reduced to 2. This feat has now two tiers. Attack rolls with the primary attribute are only available at tier 2. Restrictions about primary and secondary attribute category lifted.

#### 2016 / 12 / 22
-   `Intimidated` bane renamed to `Provoked` and reordered alphabetically.

#### 2016 / 12 / 21
-   `Boon Focus` wording adjusted in numerous areas, changing references from multi-target to non-single target. Extra text was added to tier 1 to address power level restrictions.
-   Added Boon: `Summon Creature` ([view](http://www.openlegendrpg.com/boons#summon_creature))
-   Clarified that only _damaging attacks_ qualify for bane application when exceeding target defenses by 10 or more
-   Feats reordered alphabetically

#### 2016 / 12 / 19
-   Renamed `Aid` boon to `Bolster` and changed it's duration to `Sustain Persists` to accomodate ongoing augmentations that should last for more than just a short one round burst (formerly `Aid` only lasted 1 round)
-   Reorder Character Creation steps so that `Description` comes first
-   Add `Free Actions` to combat section and explain how they work
-   Clarify that banes do not stack, only one instance of a given bane can be on a target at a given time
-   All references to `Supernatural` have been changed to `Extraordinary` to support some genres like far-future and superheroes that sometimes explain the extraordinary with science rather than magic
-   Fix Druid example missing Creation 3
-   Fix Arcane Protector example missing Movement 3
-   Fix Druid example build referencing removed `Master Shifter` feat, replaced with `Boon Focus 2 (Shapeshift)` which accomplishes the same

#### 2016 / 12 / 12
-   Size categories added

#### 2016 / 12 / 9
-   `Ageless` removed as feat, added as perk
-   `Elemental Mage` is now called `Battle Mage`
-   Clarified Multi-Targeting in Chapter 6, no longer says Multi-Attack when hitting multiple foes with a single attack
-   Missing an attack can now cause 3 damage instead of 5
-   `Haste` updated, now each power level grants an additional 5' of movement. Attack disadvantage changed to static bonus to target evasion based on power level. Extra major actions are now made with disadvantage, if a roll is required.

#### 2016 / 12 / 5
-   `Well-Rounded` updated, now you gain advantage 1 on action roll outside of combat that are not invocations (bane or boon) for attributes with a score of 2 or less
-   XP and level clarified, every XP grants a player 3 attribute points and 1 feat point and every 3 XP results in a level

#### 2016 / 12 / 3
-   `Alternate Form` updated, now you build your alternate form using the normal character creation rules, though attribute and feat points are determined by the tier level of this feat
-   Banes are now inflicted for free on `10 over defense` instead of `10+ damage`

#### 2016 / 11 / 29
-   You can't use a supernatural attribute if the score is zero
-   Area attacks changed, now disadvantage is based on shapes (Cube, Line and Cone)

#### 2016 / 11 / 28
-   `Mimic` doesn't require `Alternate Form` anymore, it instead requires `Deception 3`
-   Can't choose `Alternate Form` when creating the secondary form granted by this feat

#### 2016 / 11 / 25
-   Updated character creation text to reflect new `Toughness = 10 + Fortitude + Will` formula
-   Clarified attribute 9 limitation for `Companion` feat
-   Removed all prerequisites for `Superior Concentration` to accommodate any boon including those inovoked by non-supernatural attributes

#### 2016 / 11 / 24
-   Added `Two Weapon Brute` feat
-   Added rules for dual-wielding weapons with the one-handed property for Advantage 1
-   Close infinite damage loophole in `Multi-Attack Specialist` feat by introducing a limit on the maximum number of additional attacks you can take
-   Clarify the time increment steps of `Boon Focus`, move OR major actions become minor at tier 2
-   Removed all prerequisites from `Energy Resistance` to enable characters with no special training to have bloodline-based resistances

#### 2016 / 11 / 23
-   Modified `Natural Defense` feat to better reward unarmored characters who invest in it (#105)
-   Modified `Craft Beneficial or Baleful Item` feat to allow unlimited invocation at tier 2 and 3x longer creation duration for sentient Tier 3 items. (#143)
-   `Aid` boon and `Demoralized` bane now mirror each other in Power Level and effect
-   Tweaks to `Restoration` boon now allow it to function correctly with `Boon Focus` feat

#### 2016 / 11 / 15
-   Added Aura boon.

#### 2016 / 11 / 13
-   Removed attribute prerequisites for Multi-Target Boon Specialist feat.
-   Decreased first power level of Telekinesis boon from 5 to 4.
-   Fixed loophole with Boon Access (Shapeshift). Now the Alteration score is limited to character level or 5, whichever is higher.

#### 2016 / 11 / 12
-   Closed loophole in Boon Access. Now if a boon has multiple attribute prerequisite options, you choose one attribute when you take this feat.

#### 2016 / 11 / 11
-   Added Barrier boon.

#### 2016 / 09 / 07
-   Life Drain Bane removed, added to Boons. Heals target for half damage dealt.
-   New Feats for movement such as Climbing, Swimming and Flying.
-   Feats that can be lost (Animal Companion, Supernatural Focus, etc) now updated with clause that feat points are regained in the event the item or companion is permanently lost.
-   Flanking added as an example of Advantage.
-   Lucky renamed to Diehard, can now use Fortitude or Presence as prerequisite.
-   Defenses updated with new formulas. Weapon attacks now target Evasion, Supernatural attacks target most relevant defense.
-   Might has replaced Fortitude as the prerequisite for wearing armours.
-   Master Shifter feat removed, Boon Focus and Supernatural Focus made it obsolete.
-   Alteration attribute added to healing boon, definition of healing updated.
