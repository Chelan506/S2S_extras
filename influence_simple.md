# INFLUENCE SYSTEM

The influence system is an optional rule in S2S that formalizes the large scale acquisition of wealth and political power. It defines how powerful an adventuring guild is, independent of the combat prowess of its actual adventurers. The influence system operates across various domains, from the smallest villages to entire planets. The influence system is good for groups who enjoy political games, long term power scaling, and the interacting with the game world. It is not good for groups who prefer a focus on game balance, combat, and the journey of a lone band of heroes.

[This spreadsheet can be used to keep track of your holdings and influence.](https://docs.google.com/spreadsheets/d/1s1hLqJW0dc8jWIaone807tDiubQNjvdqNuYCgu4clwI/edit?usp=sharing)

## SIMPLE AND COMPLEX INFLUENCE

The influence system comes with two sets of rules, the simple rules and complex rules. You are reading the simple rules, which are designed to be straightforward and to need less recordkeeping. However, they are less powerful than the complex rules. More than likely, unless you have the same flavor of autism as me, you will have no need or desire to read the complex rules. But they are made available just in case.

## INFLUENCE SLOTS

The currency of the influence system is influence slots. Influence slots are a representation of your guild's power to make things happen for you. Your holdings provide you a number of influence slots that may be used during downtime (or, if the circumstances allow, during a game) and which regenerate to full every week. Influence slots represent lasting power, not favors called in from a patron. 

Influence slots are shared by the entire guild. Any member may contribute gold to their acquisition, and any member may use them as they see fit.

Influence Capacity is a representation of how far your influence can stretch. It is provided by Influence Extender holdings, and is necessary to build holdings at levels higher than City.

## DOMAINS

Your influence varies by location. The domains are City, Province, Nation, Continent, and Planet. You start by buying holdings at the City level, which increases your influence only within the city. Once you have enough influence, you can spend it in exchange for the ability to buy holdings at a higher level domain. So, once you have enough influence at the City level, you may expend it to gain influence at the Province level, and this can continue recursively.

There is a limit to how much influence you can buy. Unless your GM says otherwise, your City Influence Capacity is set at 25 and thus you cannot acquire more than 100 City influence slots. This subsequently limits your Provincial, National, etc influence.

When using influence slots to take influence actions, you can take those actions within the domain that your influence applies in for no penalty. You can also take those actions at the domain one level higher, at a cost of doubling the influence slots required.

For example, if you have 30 City influence and 10 Province influence, you can do any of the following things:

* use 40 influence slots within your City
* use 30 influence slots within your City and 10 within your Province
* use 25 influence slots within your Province (10 + 30/2)
* use 15 influence slots within your Province (30/2) and 5 influence slots within your Nation (10/2)
* or any other combination of those things. 

## HOLDINGS

When you buy a holding, you must specify the domain at which you buy it. If you are just starting out, only the City domain is available. If you wish to sell a holding (to liquidate your assets or to replace it with a different kind of holding), you can do so at one half of the buying price. 

#### Military Holding
```
You buy land and construct a fortress or training ground. Soldiers stationed in this holding will fly your banner and fight in your name.

Cost: 2500 GP, 1 Influence Capacity

+4 Military Influence Slots

+4 General Influence
```
#### Economic Holding
```
You buy a large farm or a high-end shop in town. The holding will generate income for you every week, and the manager can help you locate rare items for sale.

Cost: 3000 GP, 1 Influence Capacity

+4 Economic Influence Slots

+4 General Influence
```
#### Diplomatic Holding

You buy an estate and hire a staff of diplomats and spies to represent your guild. They can be tasked to negotiate with other factions or to uncover valuable information.
```
Cost: 2000 GP, 1 Influence Capacity

+4 Diplomatic Influence Slots

+4 General Influence
```
#### Influence Extender
```
You buy several small parcels of land over a wide area and set up satellite locations to coordinate far-away operations with your diplomatic holdings. You must have at least one diplomatic holding for every influence extender you buy. 

Cost: 5000 GP

+1 Influence Capacity at level n+1 for every 4 General Influence at level n
```
## INFLUENCE ACTIONS

### Military

#### Order a Strike

You order a detachment of your soldiers to attack a target. The target can be a group, person, or location. If the location of the target is not public knowledge, you must determine the target's location yourself or use your diplomatic influence to do so. It will become common knowledge that your guild was responsible for the attack. The strike can be executed during downtime or planned in advance to occur at a specific time.

Cost before modifiers: 1 military influence per 4 soldiers sent

##### Modifiers:

**Rush**. You send an urgent message to rally the troops. You must use this modifier if you wish to order an attack *during* an adventure and have it occur before the adventure ends. (You do not need to take this modifier if you order the strike at the *beginning* of the adventure, before leaving your base.) The influence cost of the strike is doubled.

**Covert strike**. You order your soldiers to act with subterfuge. If your soldiers are undiscovered, the party responsible for the attack will not be known. However, there is a risk of discovery and subsequent failure. This option is more effective with smaller scale attacks. The influence cost of the attack is doubled.

**Influence reach.** Standard modifier for extending your influence to a higher level domain. The influence cost is doubled.

##### Adjudication:

**In session.** If the ordered attack occurs in a session, each point of military influence equals four soldiers (use the Foot Soldier statblock) who will obey the orders of the players. In a covert attack, each point equals two soldiers with expertise in stealth.

**Standard**. Estimate the military influence of the target. Sample ranges are provided below.

* 0: undefended commoner
* 1: a minor noble with a bodyguard, a traveling party on a road
* 2-4: a guard outpost, a bandit camp, a very tiny village, a low-mid level adventurer
* 4-8: a small fortress, a small village, a powerful bandit gang, a mid-high level adventurer
* 8-16: a fortress, a mid sized village, a platoon in an army, a small adventurer guild
* 16-32: a large fortress, a small town, a company of an army, a mid sized adventurer guild
* 32-64: a citadel, a mid sized town, a batallion of an army, a huge adventurer guild
* 64-128: a large city, a small standing army
* 128-256: a capitol city, a mid sized army
* 256-512: a small nation
* 512-1024: a mid sized nation

For monsters, you can also use the rule that 300xp = 1 military influence.

To calculate the modifier for the attack, start with 0. Divide the attacker's influence by the defender's influence. For every 10% above 100%, increase the modifier by 1; for every 5% below 100%, decrease it by 1. Round down. Then, roll 1d20 plus the modifier. The DC for the attack to succeed is 10.

**Covert**. You must first roll to see if the attackers are discovered.

Consult the table for the stealth modifier.

* 2 influence: +5
* 4 influence: +4
* 6 influence: +3
* 8 influence: +2
* 10 influence: +1
* \>10 influence: 0

Roll 1d20 plus the modifier. The stealth DC is 10.

If the stealth check succeeds, roll for the attack as in a standard attack, but make the roll with advantage. Nobody will know who was responsible for the attack, whether it is successful or not. If the check fails, the responsible party is revealed, and the attack roll is made with disadvantage.

##### Aftermath:

If an attack fails, the target will shore up its defenses. Apply a -1 modifier to the next attack on the same target; this is cumulative with multiple failures. Remove the modifier if the guild finds a way to attack in a new or different way. If the attack succeeds, the guild may do as it wishes with the subdued target. It may be destroyed, looted, forced out of its home, etc. If appropriate, the GM may allocate a gold reward to the guild representing looted items. 4-10 GP per influence of the target is suggested.

The players may order their soldiers to do illegal things or to attack targets that are important to other factions. Consider the power and interest of the higher level domains, and decide how they will respond. You can have the players' military holdings attacked, have their base raided, or have forces attempt to arrest a player during a session.

#### Patrol an Area

You order a detachment of soldiers to patrol an area. The area can be as small as a single building or as large as the detachment's entire domain. The soldiers will follow your orders, so it is up to you what they do while on patrol. You can order them to attack certain people on sight, prevent access to an area, shake down civillians for coin, enforce local laws—anything you want, though you will be held responsible for their actions. One common thread is that they will always report back to you about anything noteworthy in their patrol area.

##### Detemining a patrol area:

You can decide how widely spread you want your soldiers to be. You can cover more ground by spreading them thin, but if there's troble, they will be less able to respond with force. Your options are as follows:

* **Entire Domain.** Your City soldiers will patrol the entire city, your Province soldiers will patrol the entire province, etc.
* **Subdomain/Domain part.** Your City soldiers will patrol a single neighborhood. Your Province soldiers will patrol a single city, or a single part of the province.
* **Location.** Your soldiers, regardless of domain, will be stationed at a single location.

Unlike other influence actions, it is not possible to spend extra influence to allow soldiers to patrol outside of their domain.. 

##### Adjudication:

**In session.** Use your best judgement to determine where guards will be if the players travel to a patrolled location. Some rules of thumb:
* If the players travel to a Location where guards are stationed, all of the guards should be there.
* If the players travel to a Subdomain where guards are patrolling, around 1/2 to 1/4 of the guards should be in the players' immediate area during any given time. So, if 3 influence was spent to patrol a neighborhood of a city, between 3 and 6 guards should be present if a fight were to break out in that area.
* If the players travel to a Domain where guards are patrolling, around 1/8 to 1/16 of the guards should be in the players' immediate area during any given time. So, if 5 influence was spent to patrol a Province, 1 or 2 guards should be present if a fight were to break out in that area.

**Intelligence.** If there is important information that is obvious to the eye of an unknowing observer, it is always reported to the guild. If there is information that is not obvious, but can be discerned with some luck or skill, roll a D20 plus 0 for Entire Domain patrols, plus 2 for Subdomain patrols, and plus 5 for Location patrols. The DC for finding and reporting the information is 10 (or some other number if you feel that is appropriate for the information at hand.)

**Encounters.** If a hostile force enters the patrolled territory, the soldiers will attempt to attack and drive away the force. Determine the intruders military influence per the examples in the Order a Strike action. Then, take the influence spent on patrolling the area. Halve it if the area is an Entire Domain. Double it if the area is a Location. If the patrollers' adjusted influence is equal to or higher than the influence of the intruding force, the intruders are driven off and the incident is reported to the guild. If it is lower than the influence of the intruding force, the patrollers are forced to retreat and the intruders may act with impunity.

**Law.** The players may order their soldiers to do illegal or unpopular things while on patrol. Consider the power and interest of the higher level domains, and decide how they will respond. You can have the players' military holdings destroyed, have their base raided, or have forces attempt to arrest a player during a session.

### Economic

#### Pay Out Gold

For every 1 influence spent paying out gold, 150 GP of profit is made. The players should decide in advance whether they would like these profits to be distributed equally among players or to be deposited in a common guild fund for future developments. 

#### Purchase an Item

### Diplomatic

#### Order a Search

#### Negotiate







