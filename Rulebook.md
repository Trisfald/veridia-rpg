# <a name="main"></a>Veridia Tabletop RPG Rulebook

#### Index:

* [Rules overview](#S-rules_overview)
* [Characters](#S-characters)
* [Character creation](#S-character_creation)
* [Combat](#S-combat)
* [Equipment](#S-equipment)
* [Managing a campaign](#S-campaign)


* [Appendix A: Version numbers](#S-version)
* [Appendix B: Racial bonuses](#S-racial_bonuses)
* [Appendix C: Experience expenditure table](#S-experience)
* [Appendix D: Weapons table](#S-weapons)
* [Appendix E: Defenses table](#S-defenses)

# <a name="S-rules_overview"></a>Rules overview

The number one rule is to have fun. There's no single best way to play the game. A combat intense dungeon crawl, player versus player action, a subtle political struggle, everything is possible as long as your group agrees on the campaign's style.

The recommended group composition for playing Veridia Tabletop RPG is one game master and three to five players.

Should a controversial event happen during a session, we strongly advice to try reaching a common agreement among all participants. Whenever the latter is impossible, the game master has the last word over both the rules and the players' opinions.

Let's now delve into some concrete rules that will help shape your adventures.

* [Rolling the dice](#SS-rolling)
* [Actions and turns](#SS-actions_turns)

## <a name="SS-rolling"></a>Rolling the dice

All rolls are made with multiple **d12**.\
A character rolls a certain amount of dice (the dice pool) and looks for successes and matches.

A **success** is a dice roll equal or greater than 9.

A **match** consists of at least two successes having the same dice roll. Only one combination is considered, that is the one with more repetitions and then the one with the highest rolled number.

Successes give a measure of the action's favorable outcome while matches indicate the presence of possible side effects. Matches are used in many trait abilities.

A roll without successes and with a match of 1's is a **critical failure**. A negative event could befall the player, at the discretion of the game master. Examples of critical failures effects are presented throughout these guidelines.\
In the case you only have one dice in the pool and get a 1, that's a critical failure as well!

For example, given a dice pool of size 5, some possible outcomes are:

Dice rolled | Outcome
----------- | -------------
7, 1, 4, 6, 11 | 1 success, no matches
1, 4, 2, 1, 9 | 1 success, no matches
1, 9, 9, 9, 12 | 4 successes, a triple match of 9's
5, 5, 1, 2, 3 | no successes, no matches
1, 2, 1, 4, 1 | no successes, a triple match of 1's, critical failure

### Advantages and disadvantages

A character can be granted additional dice or can have his dice pool reduced. If the pool's size reaches zero the roll is automatically failed.

A character has an advantage when favourable circumstances make him *better* at what he's doing.\
On the contrary, he has a disadvantage when something or someone hinders him.

### Difficulty level

Difficult actions may require more than one success to be carried out favorably. This is conceptually different from subtracting a dice from a dice pool. Demanding more or less successes reflects how hard the feat is objectively.

An action with +1 difficulty *eats* the success with the lowest rolled number for the purpose of deciding matches and counting successes.

###### Example

> A roll is made with a dice pool of 5 and +2 difficulty.\
> The results are: 4, 11, 11, 11, 12.\
> Since the difficulty is +2 the lowest two successes are voided and the effective results are: 4, 11, 12 (one success and no matches).

### Automatic successes

With the game master's approval, in non-heated situations a roll can be avoided; in such cases the number of successes is equal to one fourth of the dice pool (rounded down), but no matches are obtained.

## <a name="SS-actions_turns"></a>Actions and turns

### Order of initiative

Normally, characters can carry out their deeds without a specific ordering, just following common sense and relying on the game master's arbitrage.

However, if the situation requires fine grained control of the characters' actions (for example in combat), each participant will take his turn starting from the one with the highest roll of *agility + reaction*; resolve ties with matches and, if not yet enough, with a simple dice roll.

### Turns

A character's turn begin when he performs his first action, which could be:

* a normal action
* a contested action
* a free action
* the first of multiple concurrent actions

In each turn a character can perform a maximum of:

* one free action
* one among those:
  * one additional free action
  * one contested action
  * one normal action
  * two or more concurrent actions

The turn ends with the character's last action.

Durations are often expressed in character's turns. A duration of *n* turns expires at the beginning of the *n + 1* turn of the character.\
For instance, a one turn effect affecting a character lasts from the moment it was activated, plus the character's turn, up to the start of the character's following turn.

### Rounds

A round terminates once all characters taking part in the battle finish their turn. The length of one round is (indicatively) six seconds.

### Contested actions

To resolve contested actions both characters roll their respective dice pool. Each success is spent to eliminate an opponent's success, starting with the lowest rolled number. Then, whoever is left with at least one success wins the contest.\
Contested actions can be initiated by either of the parties involved.

### Concurrent actions

Concurrent actions in the same turn are allowed as long as it makes sense for them to be carried out simultaneously. For instance, it's not valid to perform twice the same action or to punch somebody while trying to persuade him. Instead, swinging an axe and dodging a blow is perfectly fine.

To first step is to determine which of their dice pools is the smallest, taking into account advantages and disadvantages. Then, subtract one dice for every action taken after the first. Finally, allocate that amount of dice among all the actions.

###### Example

> Suppose a player wants to attack with a sword (*strength (4) + melee (3)*) while running (*agility (3) + athletics (2)*).\
> The dice pool would be the smallest of the two (5).\
> Now subtract 1 because he's doing two things at the same time.\
> He's left with a dice pool equal to 4, which he can split as he wants.

### Free actions

A maximum of one free action can be taken per turn alongside a normal action. If a character wishes to make an additional free action after the first he must spend his whole turn.\
Free actions don't require a dice roll.

### Instant actions

Instant actions can be executed at any point in time, even in during another character's turn. There's no limit to the number of instant actions per turn.

# <a name="S-characters"></a>Characters

This section explains how both the playable and nonplayable characters are represented within the game.

Each of the following topics describes a different aspect of the characters.

* [Attributes](#SS-attributes)
* [Skills](#SS-skills)
* [Specialties](#SS-specialties)
* [Traits](#SS-traits)
* [Assets](#SS-assets)

## <a name="SS-attributes"></a>Attributes

Attributes define the physical and mental capabilities of an individual.

### Attributes range

For humans, attributes follow a scale going from a minimum of **1** to a maximum of **5**:

*    1: terrible
*    2: mediocre
*    3: good
*    4: great
*    5: superb

Other races can have different minimum or maximum for certain attributes. See [Racial bonuses](#S-racial_bonuses).

#### Fraction attributes

Attributes are the only numerical factor that can be a fraction. When used in conjuction with a skill to determine a dice pool's size, multiply the skill's value by the fraction (rounded down).

###### Example

> A creature rolls strength (1/3) + brawl (6). The final dice pool is: 2.\
> Another creature rolls strength (1/2) + brawl (3). The final dice pool is: 1.

### Primary attributes

##### Physical:

* Agility
* Constitution
* Reaction
* Strength

##### Mental:

* Charisma
* Intuition
* Perception
* Persuasion

### Health

Health is a derived attribute equal to: *5 + constitution * 2*

For fraction constitution follow this table:

Constitution | Health points
:-----------:|:------------:
1/2 | 5
1/3 | 3
1/4 | 1

Health points are grouped in **health levels**. A given health level may entail a penalty to all dice pools and initiative.

Health level | Dice pool penalty
------------ |:----------------:
Healthy | 0
Hurt | 2
Impaired | 4
Incapacitated | no action is possible

Health levels are set by assigning one health point to each of them, starting from *healthy* and ending with *incapacitated*; repeat until no health points are left.

###### Example

> Health levels distribution for a character having nine health points:
> <pre>
> Healthy         xxx
> Hurt            xx
> Impaired        xx
> Incapacitated   xx</pre>

Any additional damage taken after reaching zero health points will cause the character's **death**.

#### Recovering health

The number of rest days needed to heal a point of damage depends on which health level the point to be recovered belongs to:

Health level | Days (rounded down)
------------ |:------------------:
Healthy | 1 / constitution
Hurt | 2 / constitution
Impaired | 3 / constitution
Incapacitated | 4 / constitution

Not resting properly halves the healing rate.

When receiving medical treatment, the person giving treatment rolls *intuition + medicine* and all successes count as additional points of constitution.

While often instantaneous, magical healing can usually cure only the target's current health level damage: the first point of the following level must be healed naturally. A roll of *perception + medicine* can tell if a healing spell will have any beneficial effect at all.

### Virtues and willpower

Willpower is the sum of two special attributes, called **virtues**:

#### Courage

Goes from **1** to **5** and can be increased with experience like attributes.

#### Integrity

Goes from **0** to **7**. Increases and decreases are consequences of the story. A character can actively try to increase integrity, but it requires time (not experience!) and the intent must be backed up by his actions. The game master must decrease a character's integrity score if the latter's behavior demands it; the player should be warned when his course of action will cause an integrity loss.

In summary, willpower can take a value as low as **1** and as high as **12**.

### Defenses

#### Armor

Armor reduces the physical damage taken by a character.

**Inner** armor is applied after standard (**outer**) armor and can't be ignored.

#### Elemental resist

Elemental resist reduces the elemental damage taken by a character.

**Inner** elemental resist is applied after standard (**outer**) elemental resist and can't be ignored.

#### Barrier

A barrier acts as bonus health points. When active, each point of damage is inflicted to the barrier, but it's not reduced by neither armor nor elemental resist; if the protection is not sufficient to absorb all damage, the difference will be treated as normal damage.

## <a name="SS-skills"></a>Skills

Skills define the various proficiencies of a character.

When performing an action roll as many dices as *attribute + skill* and count successes. Matches can cause special side effects, as specified in the ruleset or at the discretion of the game master.

### Skills range

A Skill value goes from a minimum of **0** to a maximum of **7**:

*    0: untrained
*    1: novice
*    2: practiced
*    3: competent
*    4: proficient
*    5: expert
*    6: master
*    7: genius

### Basic skills

The following is a list of commonly known skills together with some example rolls.

If a specific capability of your character can't be expressed by any entry in this list, feel free to add a new skill.

* ##### Alchemy

	* Create explosives: *intuition + alchemy*
	* Concoct potions: *intuition + alchemy*
	* Create poisons: *intuition + alchemy*

* ##### Alertness

    * Spot a sudden danger: *reaction + alertness*
    * Catch an object on the fly: *agility + alertness*

* ##### Animal handling

	* Tame a wild animal: *perception + animal handling*
    * Give an order to a trained animal: *charisma + animal handling*

* ##### Arcana

	* Identify magical effects: *perception + arcana*
	* Read a spellbook: *intuition + arcana*

* ##### Art

	* Sing: *charisma + art*
	* Compose music: *intuition + art*
	* Paint: *intuition + art*
	* Write poetry: *intuition + art*

* ##### Athletics

	* Climb: *strength + athletics*
	* Swim: *agility + athletics*
	* Jump: *strength + athletics*
	* Run: *agility + athletics*
	* Dodge a blow: *reaction + athletics*
	* Endure long physical endeavors: *constitution + athletics*
	* Shoot with a sling: *agility + athletics*

* ##### Brawl

	* Wrestle: *strength + brawl*
	* Perform an unarmed attack: *strength + brawl*
	* Block an unarmed blow: *reaction + brawl*

* ##### Craftsmanship

	* Forge a weapon or a piece of armor: *strength + craftsmanship*
	* Create jewellery: *agility + craftsmanship*
	* Fabricate a trap: *intuition + craftsmanship*
	* Carpentry work: *intuition + craftsmanship*

* ##### Deception

	* Tell a lie: *persuasion + deception*
	* Disguise oneself as somebody else: *intuition + deception*
	* Make a work of forgery: *intuition + deception*
	* Gamble: *perception + deception*

* ##### Diplomacy

	* Conduct negotiations: *persuasion + diplomacy*
	* Mediate between two parties: *persuasion + diplomacy*

* ##### Farming

	* Cultivate the land: *strength + farming*
	* Raise livestock: *intuition + farming*

* ##### Housekeeping

	* Cook a meal: *intuition + housekeeping*
	* Take care of a garden: *intuition + housekeeping*

* ##### Humanities

	* Test one's knowledge about history, philosophy or literature: *intuition + humanities*
	* Make a psychological analysis: *perception + humanities*

* ##### Intimidation

	* Threat someone physically: *strength + intimidation*
	* Force a person to do something: *persuasion + intimidation*

* ##### Investigation

	* Detect lies: *perception + investigation*
	* Lip reading: *perception + investigation*
	* Look for a clue: *intuition + investigation*
	* Interrogate a subject: *persuasion + investigation*

* ##### Law

	* Know the details of a given regulation: *intuition + law*
	* Argue for a case in a trial: *persuasion + law*

* ##### Leadership

	* Manage a settlement: *intuition + leadership*
	* Public speaking: *charisma + leadership*
	* Lead the troops: *charisma + leadership*

* ##### Machinery

	* Create or repair a machine: *intuition + machinery*

* ##### Magitech

	* Design magitech artifacts: *intuition + magitech*

* ##### Marksmanship

	* Shoot with a bow: *strength + marksmanship*
	* Shoot with a magitech weapon: *agility + marksmanship*
	* Shoot with a crossbow: *agility + marksmanship*
	* Fire a gun: *agility + marksmanship*

* ##### Medicine

	* Cure an injury or an illness: *intuition + medicine*
	* Make a medicament: *intuition + medicine*

* ##### Melee

	* Attack with a close combat weapon: *strength + melee*

* ##### Navigation

	* Tie a complex knot: *agility + navigation*
	* Govern a ship in open sea: *perception + navigation*
	* Follow a sea route: *intuition + navigation*

* ##### Occult

	* Fortune telling: *perception + occult*
	* Decipher occultism lore and signs: *intuition + occult*

* ##### Parry

	* Parry a blow with a weapon or a shield: *reaction + parry*

* ##### Performance

	* Dance: *agility + performance*
	* Perform in a circus: *agility + performance*
	* Recite at a play: *charisma + performance*

* ##### Ride

	* Ride a horse: *agility + ride*
	* Jump an obstacle on horseback: *reaction + ride*

* ##### Savoir-faire

	* Captivate somebody's attention: *charisma + savoir-faire*
	* Make a display of good manners: *intuition + savoir-faire*

* ##### Science

	* Predict the planets' motions: *intuition + science*
	* Solve a math exercise: *intuition + science*
	* Forecast tomorrow's weather: *perception + science*

* ##### Sleight of Hand

	* Pick a lock: *intuition + sleight of hand*
	* Steal someone's coin purse: *agility + sleight of hand*
	* Untie oneself: *agility + sleight of hand*

* ##### Stealth

	* Move without being noticed: *agility + stealth*
	* Blend into the crowd: *reaction + stealth*

* ##### Strategy

	* Decide the tactics of a military battle: *intuition + strategy*

* ##### Survival

	* Find food in a wild area: *perception + survival*
	* Catch a fish: *agility + survival*
	* Read tracks left by someone: *perception + survival*

* ##### Theology

	* Perform a religious ceremony: *charisma + theology*
	* Read the scriptures: *intuition + theology*

* ##### Throwing

	* Throw a javelin or an axe: *strength + throwing*
	* Throw a dagger: *agility + throwing*

* ##### Trade

	* Bargain with someone: *persuasion + trade*
	* Plan a business: *intuition + trade*

## <a name="SS-specialties"></a>Specialties

Specialties are advanced disciplines that require specific training.
Like attributes, specialties can take a value from **1** to **5**.

#### Resource pool

Where indicated, learning a specialty gives access to a new expendable resource. After a full rest, your character recovers up to half of the pool's total points (rounded up).\
A disrupted respite halves the recovery.

### Magic branches

Any branch can't have a value higher than: *arcana - 1*.

Having at least one point in any branch enables a shared resource pool: **Mana** (equal to *twice the highest branch level + arcana*)

##### Grey magic

Incantations that don't fall into a specific category. The most heterogeneous of all branches. Many wizards start their career learning basic spells of this kind.

##### Chromatic magic

Spells that make use of the power of the elements.

##### White magic

The magic of healing living beings.

##### Silver magic

Graceful class of offensive spells.

##### Natural magic

A magic branch that tries to harmonize itself with nature.

##### Crude magic

Raw form of spellcrafting, primitive yet effective.

##### Black magic

All forbidden or extremely wicked spells fall inside this category.

### Knightly ways

The sum of all ways values can't be higher than: *integrity - 1*.\
If the character's integrity decreases and becomes less than how much would be required for a certain way level, that level and all related traits are unavailable until the lost virtue is regained.

Having at least one point in any way enables a shared resource pool: **Fervor** (equal to *twice the highest way level + integrity*)

##### Way of the blood

*Hope lies in being alive.*

##### Way of the mage

*Hope lies in exceeding reality.*

##### Way of the time

*Hope lies in the relentless flow.*

##### Way of the psychic

*Hope lies in understanding.*

##### Way of the sun

*Hope lies in the gifts from above.*

##### Way of the wilderness

*Hope lies in the miracles of nature.*

### Martial arts paths

Having at least one point in any path enables a shared resource pool: **Focus** (equal to *twice the highest path level + intuition*)

##### Feral path

Can't be higher than: *courage + 1*

*Sharpen the spirit to become as ferocious as a wild beast.*

##### Devil path

Can't be higher than: *persuasion + 1*

*Quicken the mind to obtain the devil's cunning.*

##### Myth path

Can't be higher than: *perception + 1*

*Deepen the consciousness to revive hopes long lost.*

## <a name="SS-traits"></a>Traits

Traits are the finest way to add flavor to your character. There are more than one hundred in the ruleset and each of them adds something special, in a positive or negative manner.\
Even more so than for skills, don't hesitate to create new traits to better define a character.

See [Traits](Traits.md) for the list of all traits.

## <a name="SS-assets"></a>Assets

Assets are fundamental to found adventures, journeys or just the normal living expenses. They are composed of three parts: liquidity, income, properties.

### Liquidity

The amount of deli (the standard Veridian currency) owned by the character. It is recommended writing down currency stored away in a safe place separately or under properties.

### Income

The (usually monthly) sum of money produced by the character's revenues.

### Properties

All equipment currently held or deposited somewhere. Also, all other possessions like houses, companies, animals, etc.

# <a name="S-character_creation"></a>Character creation

1) #### Create a character concept

Try to flesh out the character concept as well as possible. It doesn't have to be absolutely complete, but more you know about it the easier will be completing the creation process.

The best resource to get yourself familiar with all kind of possible character concepts in Veridia is the [official setting book](https://books2read.com/b/mY1OaV?edit=maybe-later&store=null).\
Alternatively, you can read the [lore book](Lore-book.pdf) for the videogame that inspired this tabletop RPG.

1) #### Fill out the racial minimum attributes

The vast majority of the characters will start with one in each attribute. Check your [race bonuses](#S-racial_bonuses) and update the attributes accordingly.

3) #### Spend experience to increase attributes, skills and specialties

Use the free experience points to define your character proficiencies and abilities.

Indicative starting experience points for building a new character:

Character competence | Starting experience
-------------------- |:------------------:
Novice | 150
Journeyman | 250
Veteran | 350

See the [Experience expenditure table](#S-experience) to known how much does a new point cost.

1) #### Spend experience to acquire background and traits:

If you desire so, add one [background](Traits.md#S-background) and one or more starting [traits](Traits.md) to your character.

1) #### Use the starting money to purchase equipment:

The amount of starting money is the sum of:
* your background's starting money
* any additional starting money given by traits (it can be also negative!)

You can find the full list of purchasable items and their cost in [Prices and wages](Prices_and_wages.md).

# <a name="S-combat"></a>Combat

This section goes in depth about the combat mechanics in Veridia Tabletop RPG.

Before continuing make sure to have read the [Rules overview](#S-rules_overview).

* [Common actions](#SS-common)
* [Maneuvers](#SS-maneuvers)
* [Fighting at range](#SS-range)
* [Mounted combat](#SS-mounted)
* [Dual wielding](#SS-dual)
* [Cover](#SS-cover)
* [Surprise attacks](#SS-surprise)
* [Tips](#SS-tips)

## <a name="SS-common"></a>Common actions

### Wait

Delays the character's turn, by as many position as he desires. A character can't delay his action against a character with higher initiative who decided to act after him.

### Movement

A character can move up to 9 meters per turn, before and after taking other actions.

Running is a normal action and it allows to travel a distance equal to 9 + roll of *agility + athletics*.

### Unsheath a weapon

Free action.

### Pick up an object

Takes one turn. Requires rolling *strength + athletics* if done as concurrent action.

### Stand up

Takes one turn. Requires rolling *agility + athletics* if done as concurrent action.

### Attack

A basic attack takes one turn and is made by rolling the appropriate *attribute + skill* for the weapon held. One success is enough to hit. Damage is equal to the number of successes plus the weapon damage; all attacks deals physical damage, unless explicitly stated. The damage inflicted is then reduced by the target's armor and any additional defences.

When attacked in melee by someone with higher initiative, a player must say if he will in turn try an offensive melee action against his aggressor. This's needed for resolving **exchanges**.

###### Example

> A character attacks with a sword, rolling strength (4) + melee (2).\
> He obtains the following result: 5, 11, 1, 3, 10. In summary, two successes.\
> The target is wearing mail armor, thus the damage inflicted is: weapon base (2) + successes (2) - armor (3) = 1.

## <a name="SS-maneuvers"></a>Maneuvers

### Parry, block and dodge

Parry, block and dodge are contested actions used in response to various types of attack.

A character can parry melee strikes if his weapon allows it. Roll *reaction + parry* to detract successes from an attacker.

Blocking works in the same manner as parrying with the only difference being the use of a shield. It's possible to block missile attacks.

It's also possible to dodge incoming missiles and close combat blows. The roll is *reaction + athletics*.

### Exchange

An exchange happens when two characters attack each other in close quarters (either a normal attack or another maneuver), both trying to overcome the opponent's defense yet still paying attention to not leave openings.

The two combatants perform their rolls with an additional penalty of one dice (offense and defense together count as concurrent action), subtracting successes from the opponent's pool.

Exchanges are not triggered automatically: at least one of the players involved must state the intention to transform his offensive action into an exchange. Once one side has declared the exchange the other side can't back off anymore and action resolution happens immediately (only for the exchange itself, other concurrent actions will be resolved following the normal order of turns).

###### Example

> Eric attacks Mark with a sword. Mark has three options: he can try to avoid taking damge (via dodge, block or parry), he can attack Eric in close quarters or he can perform another type of action.\
> Either one of the first two moves must be declared before Eric resolves his offensive action.\
> Let's say Mark decides to attack Eric with his dagger; at this point, anyone of the two can trigger an exchange.\
> In this case, Eric doesn't want to take too many risks and goes for an exchange.\
> Eric rolls strength (4) + melee (3) - exchange penalty (1), getting two successes. Mark rolls strength (3) + melee (3) - exchange penalty (1) and gets only one success.\
> The winner is Eric, with one success left; he inflicts damage equal to: weapon base (2) + successes (1) - armor (1) = 2.

### Knock out

Perform an attack like you would normally do. Instead of dealing damage check if the injury inflicted would have made the target reach the health level *incapacitated* or worse; if so, the opponent is knocked out. Be careful: matches inflict real damage and can even kill the other person.

### Grapple

To attempt a grapple roll *strength + brawl*. Remember that the opponent could trigger an exchange when attacked with a grapple.

The character must be able to momentarily free one hand. Of course, holding any kind of tool in your hands is an impediment. The disadvantage is two dice for one-handed or versatile weapons and four dice for two-handed weapons.

The number of successes can be spent to perform a follow-up action, a *lock* or both; matches indicates how strong is the grapple. A target willing to liberate himself must roll *strength + brawl* with difficulty increased by the number of matches (+1 for a double match, +2 for a triple match, etc.).\
Normally, a grapple doesn't end until the attacker let go or the defender breaks free; if grapple holds, on his next turn the attacker can roll again *strength + brawl* to do more follow-ups without incurring the risk of entering an exchange.

### Aimed strike

A character can attack a specific body part of a target. Doing so increases the roll's difficulty, as following:

Body part's size | Difficulty to hit
---------------- |:----------------:
Large (torso, arm, leg) | +1
Medium (head, hand, feet) | +2
Small (eye, ear) | +3

#### Follow-ups

* **Lock**: hinder your opponent, adding 1 difficulty per success to all his rolls (except for breaking free from the grapple).
* **Disarm**: spend more successes than the target's melee skill to disarm him.
* **Knock down**: spend more successes than the opponent's strength to knock him prone, ending the grapple.
* **Breach armor**: each success spent decreases the target's armor against *bash* by one point until the grapple is broken.
* **Bash**: hit the target's vitals with your weapon, dealing damage equal to *weapon damage + successes / 2 (rounded down)*.

## <a name="SS-range"></a>Fighting at range

### Optimal and maximum range

As you can see in [Appendix D: Weapons table](#S-weapons), each missile weapon has an **optimal range**, in other words the distance at which it can hit a human sized target with good precision.

It's possible to try hitting a target farther away. For every six meters over the optimal range the attacker has a disadvantage of one dice. The **maximum range** is thus the distance obtained by taking the disadvantage that would leave only one dice in the pool.

### Ammunition

Arrows, bolts and other kind of projectiles are needed by missile weapons. Keeping track of how many of them are at a character's disposal is optional, simply do what suits better your group playstyle.

Regarding magitech weapons, however, it's recommended to accurately manage the amount of crystals used. The reason is that crystals are a resource both expensive and hard to acquire.

## <a name="SS-mounted"></a>Mounted combat

Mounts get scared easily, especially by supernatural effects. In such occasions the rider must roll *agility + animal handling*, failure means getting tossed on the ground.

Actions performed on horseback follow the usual rules with few caveats. For instance, every skill is capped to the character's score of animal handling. Also, keep in mind that a horse has a much higher movement speed than a person, even though the animal is a target on its own. Grappling and performing a *known down* will unseat the rider.

## <a name="SS-dual"></a>Dual wielding

Dual wielding is the practice of fighting with one melee weapon in each arm. Usually, the off-hand holds a dagger or a very small sword.

Parries and exchanges have an advantage of two dice and one dice respectively. Also, on every attack, the character can choose with which weapon he wants to strike.

## <a name="SS-cover"></a>Cover

When a character is taking cover behind a physical object it is much harder to hit him. Use the following table as a reference:

Part of the body in cover | Difficulty to hit
:------------------------:|:----------------:
1/4 | +1
2/4 | +2
3/4 | +3

## <a name="SS-surprise"></a>Surprise attacks

A character is caught off guard when he is ambushed and he fails the perception roll to notice the danger. The attackers are entitled to a bonus round, after which the usual initiative rules are in place.\
When a character is caught by surprise he can't take contested actions nor trigger exchanges.

## <a name="SS-tips"></a>Tips

* If your target is engaged in close combat with another creature, hitting him with a ranged attack is difficult; consider the target as if he were taking cover.
* Multiple combatants fighting against one enemy in close quarters might interfere with each other; you can give a disadvantage of one dice per each fighter after the first one.

# <a name="S-equipment"></a>Equipment

See [Appendix D: Weapons table](#S-weapons) and [Appendix E: Defenses table](#S-defenses) to known which kind of equipment is available.

Equipment beyond weapons and armors, together with a list of purchase prices can be found in [Prices and wages](Prices_and_wages).

### Objects of inferior quality

It's possible to acquire objects with a lower quality than usual. While probably cheaper, they come with some disadvantage:

* Armors might provide less protection or have a worse agility penalty
* Weapons might lack a quirk, deal less damage or have a disadvantage to the attack roll
* Other items might not always function properly

### Objects of superior quality

Far less common are objects of superior quality, truly masterpieces. These are made by the best artisans through long processes and using only the purest of materials; even then, success is not guaranteed.\
Their worth is not easily evaluated. Prices can range from hundreds of times the cost of a similar, lesser quality item to virtually any price in case of famed artifacts.

* Armors might provide additional physical protection or have a lesser agility penalty
* Weapons might deal more damage or have an advantage to the attack roll

### Magical items

Objects infused with magical properties are very rare and expensive. Even more costly is the maintenance needed to keep their enchant working, the more often, the better; the limit is six months, after which the enchant can't be reinforced anymore.

### Equipment damage

#### Armor

Repeatedly taking hits will eventually wear out your character's armor.\
Each time physical damage taken surpasses your armor rating (consider enchantments but not inner armor), mark one point of wear.\
It's possible to patch the item while it's not yet broken, but this operation can only repair one stage, which means that a battered armor will never be as good as new.

The following table shows all possible armor conditions:

Stage | Wear points | Protection penalty
----- |:-----------:|:------------------:
New | 0-9 | 0
Damaged | 10-19 | 1
Battered (patched) | 20-39 | 1
Battered | 20-39| 2
Broken | 40 | unusable

To patch an armor you must have access to a set of craftsman's tools. You also need a number of days of work and a craftsmanship skill score equal to the armor's original protection.

#### Other equipment

Other kinds of items can get damaged as well. For instance, it's common for weapon to break whenever an attack ends up with a critical failure. Of course, the decision is up to the game master.

# <a name="S-campaign"></a>Managing a campaign

This section is aimed at game masters. It gives some insights about how to creating and leading an enjoyable campaign.

* [Campaign ideas](#SS-ideas)
* [Rewarding the players](#SS-rewards)

## <a name="SS-ideas"></a>Campaign ideas

There are many possibilities for exciting campaigns in Veridia. In this section we present some ideas that could be useful to both new and veteran groups.

One important aspect is the historical era in which the group wants to play. The assumption is that the majority of the campaigns will take place in the present, so let's start with ideas suited for the year 1220:

* You are a group of adventurers. No matter your backgrounds you have found yourselves on the southern border of Belusa to seek riches in the Unknown lands. Themes:
    * *Exploration*
    * *Fighting*
* As a newly formed mercenary band you are trying to gain fame in Rasantis. Pick a side or work for the highest bidder, it's your choice. Themes:
	* *Political intrigue*
    * *War*
* The situation is becoming restless in Racusa, Aegos Islands. You have been sent by one of the main factions' headquarters to put an end to the power struggle. Themes:
	* *Social drama*
    * *Political intrigue*
* You hunt outlaw wizards for a living. The Council has put you on a difficult case that will require a journey through Veridia. Themes:
	* *Mystery*
    * *Magic*
* You belong to an Order of knights. Your job is to aid the people of Belusa against oppression and misfortune. Themes:
    * *Crime*
    * *Vigilante*
* The life of a free orc is hard; Garga is too small for you and the only choice is to venture in the continent, against all odds. Themes:
    * *Racism*
    * *Fighting*
* To be a noble means to have many responsibilities. You must constantly prove yourself to both the king and your subjects. Themes:
    * *Politics and diplomacy*
    * *Fighting*
* The pirates and the merchants' guilds are always fighting each other on the sea. On which side are you? Themes:
    * *Sea*
    * *Swashbuckling*
* You are proud members of a Cerunian school of elemental magic. Prestige and knowledge are everything. Themes:
    * *Magic*
    * *Intrigue*
* The Magitech Ministry is pushing for even more radical changes in society. The rebellion might come to fruition and what it needs the most are heroes. Themes:
    * *Dystopia*
    * *Rebellion*

As stated before, another option is to set the campain in the past. Here's some hints:

* The Crusade, year 839. Fight for humans' survival... or for their subjugation. Themes:
    * *Epic*
    * *War*
* It's the sixth century and you are citizens of the mighty empire. Your fortune lies somewhere in the known world, you only have to find it. Themes:
    * *Adventure*
    * *Slice of life*
* Year 601. A group of novel knights is on a mission to colonize hostile lands. Will they be successful? Themes:
    * *Adventure*
    * *Fighting*
* It's the 925. The first Rasantish descendants war has reached its climax. You try to carry on despite the endless bloodshed. Themes:
    * *War*
    * *Tragedy*
* We are way before the Cerunian' calendar start. Since young age you always fought in Xanas arenas. What will you do now that the country is shaken by tremendous disasters? Themes:
    * *Fighting*
    * *Apocalypse*

## <a name="SS-rewards"></a>Rewarding the players

To give a sense of progression and accomplishment, the players should be rewarded accordingly with their actions.

The main way to do so is giving experience point that they can use to improve their character. There isn't a correct amount of experience points to give per session, but try to settle a pace at which you want your characters to grow. Two to five points is a good choice for most campaigns.

Monetary rewards are another important aspect. While obtaining them depends heavily on the players' seeking opportunities, it could be useful to have a plan regarding the party's finances; an unexpected treasure, the scarcity of funds or a property in need of care can spice up a campaign.

Last but not least, keep in mind that some traits can be given as reward as well.

# <a name="S-version"></a>Appendix A: Version numbers

Version number is made up by 3 digits. They are updated according to these rules:

* First digit: major ruleset revision
* Second digit: minor ruleset revision
* Third digit: errata

# <a name="S-racial_bonuses"></a>Appendix B: Racial bonuses

##### Humans:

* No bonuses

##### Orcs:

* +1 to minimum and maximum constitution
* +1 to minimum and maximum strength
* -1 to maximum agility
* -1 to maximum charisma
* -1 to maximum intuition

##### Small orcs:

* +1 to minimum and maximum agility
* +1 to minimum and maximum reaction
* -1 to maximum strength
* -1 to maximum charisma
* -1 to maximum intuition

# <a name="S-experience"></a>Appendix C: Experience expenditure table

Point type | Cost
---------- | ----
Attribute | 2 x point level
Courage | 2 x point level
Integrity | 1 x point level (possible only at creation)
Skill | 1 x point level
Specialty | 3 x point level
Knightly way | 3 x resulting sum of all ways levels
Trait | depends on the trait

# <a name="S-weapons"></a>Appendix D: Weapons table

### Melee weapons

Weapon | Damage | Quirks
------ |:------:| ------
Axe | 2 | devastating
Dagger | 1 | nimble
Club | 1 |
Great sword | 4 | two-handed
Gun-sword (edge) | 1 | dual mode
Longsword | 3 | balanced, versatile
Mace, Warhammer | 1 | armor piercing
Polearm | 3 | armor piercing, two-handed
Short sword | 1 | balanced
Side-sword | 2 | balanced, nimble
Spear | 2 | threatening, versatile
Sword | 2 | balanced
Unharmed | 0 | barehanded

### Missile weapons

Weapon | Optimal range (meters) | Damage | Quirks
------ |:----------------------:|:------:| -----
Bow | 60 | 2 | drawn, two-handed
Chain crossbow | 36 | 1 | loaded (3, 3), two-handed
Crossbow | 54 | 2 | armor piercing, loaded (1, 2), two-handed
Gun-sword (pistol) | 60 | 2 | dual mode, loaded (2, 1), magitech
Hand crossbow | 36 | 1 | loaded (1, 2)
Javelin | 21 | 2 | disposable, multipurpose
Magi-pistol | 45 | 2 | loaded (2, 1), magitech
Magi-rifle | 60 | 3 | loaded (3, 1), magitech, two-handed
Sling | 54 | 0 | armor piercing, drawn, two-handed
Throwing axe | 12 | 2 | disposable, multipurpose
Throwing dagger | 12 | 0 | disposable, multipurpose

### Quirks

* **Armor piercing**: ignore half of the target's armor damage reduction (rounded down)
* **Balanced**: advantage of one dice during exchanges and parries
* **Barehanded**: can't parry or exchange blows against a weapon
* **Devastating**: matches add extra damage (a match +1, a triple match +2, ...)
* **Disposable**: the weapon is gone after attacking, but might be retrieved on the battlefield
* **Drawn**: requires one turn of preparation before shooting (roll *strength + athletics* if used as concurrent action)
* **Dual mode**: can switch operating mode, requires one free action
* **Loaded (*size*, *reload*)**: can attack *size* times, then needs *reload* turns of reloading (roll *agility + mechanics* if used as concurrent action)
* **Magitech**: powered by crystals, a precious resource
* **Multipurpose**: can be used as a melee weapon
* **Nimble**: if the character's agility is higher than his strength, one bonus dice for all rolls involving this weapon
* **Threatening**: all melee attackers suffer a disadvantage of two dice, doesn't apply if taken by surprise
* **Two-handed**: requires both hands
* **Versatile**: requires both hands, but can be used with one albeit with a disadvantage of two dice

# <a name="S-defenses"></a>Appendix E: Defenses table

### Armors

Armor | Physical reduction | Athletics rolls disadvantage
----- |:------------------:|:---------------------------:
Robes | 0 | 0
Light armor (leather, gambeson) | 2 | 1
Medium armor (mail) | 3 | 2
Heavy armor (brigandine, coat of plates) | 4 | 3
Plate armor | 5 | 3

### Other defenses

Object | Elemental reduction | Notes
------ |:-------------------:| -----
Boots of celerity | 0 | Grants +1 initiative, needs periodic reinforcement
Elemental resistant tunic | 1 | Needs periodic reinforcement
Elemental resistant cloak | 1 | Needs periodic reinforcement
Shield | - |  Allow blocking of missile attacks, attackers suffer +1 difficulty
