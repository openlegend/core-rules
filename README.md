![Open Legend RPG Logo](http://www.openlegendrpg.com/assets/img/open_legend_lg_logo.png)

# Open Legend Core Rules

Included here in [YAML format](https://en.wikipedia.org/wiki/YAML) are the rules which are published to the [www.openlegendrpg.com](http://www.openlegendrpg.com) website. Feel free to open a pull request to propose improvements to any of the rules, add new feats, or otherwise start a discussion pertaining to the rules text. Note that any contribution will require that you preserve the valid YAML syntax, otherwise the website will break as a result of your changes. If you're not sure, use [this site](http://yaml-online-parser.appspot.com/) to validate your YAML outputs valid JSON.

## Open Legend Community License

The game rules content of this repository are released under a special open-source license that offers third party publishers the opportunity to use the game rules as well as designated Open Legend logo royalty-free in their own commercial or non-commercial projects via the [Open Legend Community License](https://github.com/openlegend/core-rules/blob/master/LICENSE.md#open-legend-community-license).

## Changelog

Click [Here](https://github.com/openlegend/core-rules/commits/master) to see changes in more detail.

#### 2017 / 10 / 06
-   `Ferocious Minions` incorrectly stated `Logic` as a prerequisite attribute. However, that was wrong. It should have said `Alteration` and `Energy`. It is now corrected.

#### 2017 / 08 / 30
-   Now while in `Shapeshift` you acquire only the Agility, Fortitude, Might, and Perception attributes of the new form.

#### 2017 / 08 / 17
-   Moved Action & Attributes Examples to GM chapter
-   Add `Sustenance` boon
-   Removed `Hallucination - Mass` feat. Effects moved to second tier of `Hallucination` feat.
-   `Knockdown` effect updated. Now prone targets get +2 to Guard vs ranged and -2 Guard vs melee attacks.
-   `Ferocious Minions` now works with the attributes you use to invoke *charmed*, *dominated* or *summon creature*.
-   `Destructive Trance` now works with Agility, Energy and Entropy 7.
-   `Domination` bane duration is now based on type of domination (Lesser or Greater).
-   `Natural Defense` now gives a bonus to both Guard and Toughness defenses.
-   `Skill Specialization` now works for rolls that are not for initiative, attacks, invocations, or the defend action.
-   `Attribute Subsitution I` now doesn't work for defend actions.
-   `Craft Extraordinary Items`: *expendable* items now require only one full 8-hour day.
-   `Projectile attacks` are now known as `ranged attacks`.
-   `Barrier` obscuring property now works with the barrier's area of effect rather than the hardcoded 10'.

#### 2017 / 07 / 01
-   `Battlefield Reflexes` renamed to `Battlefield Retribution` since the word "reflexes" doesn't imply reciprocal damage

#### 2017 / 05 / 19
-   Standardized all 9-tier feats (`Attack Specialization`, `Defensive Reflexes`, and `Lethal Strike`) in terms of attribute prerequisite and tier grouping. Each is now Tier 1 - 3: Attribute 3, Tier 4 - 6: Attribute 5, Tier 7 - 9: Attribute 7
-   `Lightning Reflexes` squash prerequisites, no need to have 5 tier bullet points

#### 2017 / 05 / 09
-   `Scrying` bane renamed to `Spying` for multi-genre friendliness (scrying is inherently magical).
-   `Heal` no longer has `Alteration` as a prerequisite attribute. Don't panic, you can still use the `Regeneration` boon, which is more in line with what healing does. `Alteration` allows access to an overly large array of boons.

#### 2017 / 05 / 04
-   `Banes` for weapons now allow the listed banes to be invoked even if the attacking attribute could not normally invoke it. The attacking attribute is used to determine power level.
-   `Baneful` property WL modifier is now dynamic and allows the chosen bane to be invoked even if neither the item, nor wielder can invoke it. The attacking attribute is used to determine power level.

#### 2017 / 04 / 23
-   `Animation` boon can now be accessed via `Logic`. Minor edits to boon text for multi-genre

#### 2017 / 04 / 22
-   Expand ranges of boss defenses on Boss NPC table

#### 2017 / 04 / 20
- Updated the `Artisan` perk to add a cap of wealth level 2 to avoid conflict with `Craft Mundane Item` feat
- `Armor Mastery` feat bonus now specifically an _armor bonus_ rather than directly to Guard (affects `Battle Trance`).
- Clarified that _Reach_ extends range 5'.

#### 2017 / 04 / 10
-   Clarify sustaining a boon applies to all original invocation targets
-   Clarify `Attribute Substitution` replaces the attribute itself, not just the score

#### 2017 / 04 / 01
-   `Truesight` boon modified, Power Level 5 reveals extraordinary effects in the area and new Power Level 8 allows for seeing through solid objects.
-   Added optional rule for `Boss Finale`, allowing a boss to take immediate triggered actions when reduced to 0 HP.
-   Multi-genre perk & flaw friendliness fixes -- `Outlaw` perk becomes `Fugitive`, `Noble` perk becomes `Upper Class`.
-   `Marksman` feat renamed to `Longshot` and modified to include Extraordinary attacks as well.

#### 2017 / 03 / 31
-   Removed option to use Legend Points after a given roll

#### 2017 / 03 / 26
-   `Reckless Frenzy` name changed to `Reckless Attack` and clarified that it only allows a single extra attack per round.
-   `Phantasm` bane area sizes cleaned up. Previously power level 7 area size was the same as power levels 1 - 6.
-   `Provoked` bane can now be invoked via Agility
-   Damaging attacks now deal a minimum of 3 damage. This prevents the un-intuitive phenomenon of having an "exact hit" (roll total equals target's defense) being "success with a twist", which is in part failure, but you hit the target CR so, failing feels wrong.

#### 2017 / 03 / 21
-   `Attack Redirection` clarify that you can't redirect the attack to the attacker or yourself

#### 2017 / 03 / 21
-   `Arcane Bloodline` has been generalized to apply to more groups, name changed to `Legendary Bloodline`
-   `Barrier` boon clarification - you can't trap a target inside of it
-   Tweak `Persistent` extraordinary item trait to prevent abuse.
-   `Stunned` bane wording tweak to clarify extra actions don't work
-   `Sentinel` feat tweak to require that you first spend a defend action

#### 2017 / 03 / 21
- New Chapter Structure (Finalized for going to Print, YAY!)
   -   Introduction
   -   1: Character Creation
   -   2: Actions & Attributes
   -   3: Feats
   -   4: Perks & Flaws
   -   5: Wealth & Equipment
   -   6: Banes & Boons
   -   7: Combat
   -   8: Running the Game
   -   9: Special Equipment
-   `Sentinel` (new feat added) - grants an additional action that can be used only for defend actions once per turn
-   Clarify that `defend` action can only grant bonus movement once per round
-   `Battlefield Sentinel` renamed to `Battlefield Opportunist`, `Battelfield Defender / Reflxes` feat prerequisite dropped, attribute score prerequisite dropped from 5 to 4
-   `Battlefield Defender` renamed to `Battlefield Reflexes` now allowed with `Any Extraordinary` attribute, pending GM approval
-   `Battlefield Punisher - Knockdown`, `Battlefield Punisher - Slowed`, and `Battlefield Punisher - Stunned` are all combined and slightly modified to become `Battlefield Punisher` which requires 10 damage be dealt and can be any bane, this restriction was made necessary by the addition of the `Sentinel` feat which allows additional defend actions, and allows for many uses of the defend action each turn.
-   `Companion` feat fixed to prevent abuse and reduced to 2 feat points. A companion gaining 3 feat points + an extra set of actions for a given turn, means that you spend 3 feat points on a `Companion` and you gain 3 feat points AND a new character. Companions can now buy feats with the character's feat points and get a fraction of the player's attribute points.
-   `Companion` feat point expenditures apply as a feat point reduction in any case where another effect would give you feat points, at present, this applies only to `Alternate Form` as far as we can tell.
-   `Genesis` boon Power Level 5 added (greater quantity of organic matter created)
-   `Genesis` boon invocation times streamlined PL 1 is 10 minutes.

#### 2017 / 03 / 20
-   `Companion` feat fixed to track with the new max attribute limits
-   `Nullify` bane at Power Level 6 effect can not be prevented by any other effect
-   `Multi-Target Attack Specialist` fixed to remove compounded attack complexity and a loophole that could allow you to negate all mutli-attack penalties and combine it with Haste for 9 attacks with no disadvantage.

#### 2017 / 03 / 15
-   `Genesis` added a new feat for creating short-lived matter that deteriorates / decomposes after 1 hour
-   `Marksman` feat modified to confer a single range increment bonus rather than a flat 25'.
-   `Hunter's Foe` feat name changed to `Sworn Enemy` for better genre diversity
-   `Multi-Target Boon Expert` (reversed change) feat prerequisite is now from Multi-Target Boon Specialist II
-   `Attribute Substitution` now requires Tier 2 for the benefit of boon and bane invocation prerequisites.

#### 2017 / 03 / 12
-   `Extraordinary Items` initial release - new chapter `Rewards` for extraordinary items, mounts & vehicles
-   `Craft Extraordinary Item` (formerly `Craft Beneficial or Baleful Item`) feat completely overhauled, now works with the Wealth Level system and the new rules found in Chapter 8
-   `Craft Extraordinary Item` now has Logic as an optional prerequisite
-   `Mounts & Vehicles` section moved from Chapter 4 to Chapter 8
-   `Consumable` weapon property renamed to `Expendable` for consistency with new properties in `Extraordinary Items` section
-   `Deadly` property moved from Chapter 4 (Weapons) to Chapter 8 (Extraordinary Items)
-   Major changes to `Weapons` table via `Extraordinary Items` a number weapons were moved to Extrardinary (`Laser Rifle`, `Rocket Launcher`, `Plasmablade`)

#### 2017 / 03 / 11
-   `Boss NPCs` expanded the table to level 20 (for larger groups of PCs)
-   `Boss NPCs` now have `Boss Edge`, giving them advantage on attacks, as well boss actions
-   `Boss NPCs` now have immunity to Finishing Blows
-   `Phantasm` bane wording changes to clarify that the size effect is limited by power level, but it affects all who see it (though they aren't technically targets)
-   `Fatigued` bane levels of fatigue effects for level 2 and level 4 swapped to prevent easy access to the loss of significant defense bonuses
-   Updated Open Legend Community License for minor name change to `Seventh Sphere Entertainment`
-   `Summon Creature` - added hard limit on max number of summoned creatures (equal to your invoking attribute)
-   `Fast Draw` feat cost reduced from 2 to 1
-   `Multi-Target Boon Expert` feat prerequisite reduced from Multi-Target Boon Specialist II to Multi-Target Boon Specialist I

#### 2017 / 03 / 02
-   Removed `Tech Level` from mounts & vehicles, unneccessary complexity
-   `Craft` feat is renamed to `Craft Mundane Item`
-   `Craft Beneficial or Baleful Item` feat is renamed to `Craft Extraordinary Item`
-   Added caveat that weapons can have multiple properties, allowing the wielder to choose from among them. For example, allowing `Area (X', Y' Cone)` at the wielders options. They are cumulative for determining Wealth Level.
-   Added `Flamethrower` example to the weapons table

#### 2017 / 02 / 26
-   Added genre diversity to the `Wealth Overview` tables and the armor table, removed some armor examples and added others
-   `Telepathy` boon, after much confusion because the effect is both "broadcast" AND "receive", (note "broadcast" should use `Influence` while "receive" should use `Prescience`) it seems best for it to be accessible from both attributes since the effect straddles the two
-   `Summon Creature` boon no longer has the "when you invoke this, other summoned minions are dispelled" limitation
-   `Transmute` boon no longer affects living target's since that domain is covered by `Shapeshift`. Replacing the Power Level 8 and 9 efects, are now the ability to transmute simple items into complex ones
-   `Nullify` bane is simplified to cancel only one boon affecting the target, but it now prevents the target from benefitting from or havhing the book invoked upon them for 1 minute

#### 2017 / 02 / 12
-   Clarify `Area` property's Wealth Level impact
-   Added `Indomitable Resolve` feat that increases your Resolve defense by 1.
-   Clarified that `Forceful` and `Precise` weapons can only be used for bane attacks with that particular attribute
-   `Natural Defense` feat now increases both Guard and Toughness defenses
-   `Immobile` bane now targets Toughness for most bane attacks
-   `Augury` renamed to `Precognition` because augury by definition has ties to the divine. `Precognition` represents
-   `Boon Focus III` clarified to allow boon invocation as a free action, meaning that it only persists if you're conscious to spend an action
-   `Death Blow` feat's tier 3 is removed, 15 HP death threshold is too powerful, and the tier 2 Silenced effect was overly complex. There are now 2 tiers
-   `Ritual Magic` feat is renamed to `Heightened Invocation` to more effectively span non-magically oriented genres
-   `Dispel` bane is renamed to `Nullify` to more effectively span non-magically oriented genres

#### 2017 / 02 / 11
-   Removed redundant `Inner Strength` perk (was a duplicate of `Resilient` perk)
-   Added `Targeted Weapons` property to manually targeted vehicular weapons
-   Modified certain Vehicles to have `Resolve: Immune` to represent mind-influencing banes don't effect them

#### 2017 / 02 / 05
-   Added `Vehicles & Mounts` section at the end of chapter 4
-   Added `Tech Level` callout before Weapons section in chapter 4
-   Add `Deafened` bane to mirror `Blinded` and `Silenced`

#### 2017 / 02 / 03
-   Added rules for `Waiting to Act` that allow for preparing to react to a given trigger and waiting in general
-   Clarify that boons don't stack
-   Renamed `Burst` weapon property to `Area` and significantly changed how it works. These weapons always make attacks in their listed size and shape areas, and suffer no penalties for doing so
-   Add `Agility` as an optional attribute for invoking `Knockdown` and `Forced Move` banes
-   Clarify how hit points are tracked for `Polymorph` bane and `Shapeshift` boon
-   `Polymorph` bane is fixed. Previously had variable and overpowered durations as well as being easily abused to transform the target into a form with all attribute scores being 0.
-   `Banished` bane is removed. An effect so permanent should be part of the GM's discretion and a story choice rather than automatic and permanent exile from a successful roll (done at-will)
-   `Shapeshift` now allows the target to keep their `Alteration` attribute score when they shift.
-   `Shapeshift` is changed so that gaining access to the new forms extraordinary attributes happens at power level 7

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

## Contributors

Ish Stabosz, Barry Dewey-Robertson, Kyle Willey, Mario Lurig, Michael "Hassurunous" Loubier, John Lewis of Demon's Lair RPG
