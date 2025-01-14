Skills are defined by their

Type - Damage/Block/Range/Multi/Support
Tier - Determines power
Cost - Limits effects
Condition - Determines Special

(Tier) Skill Name (Cost) - Effect (x# for Multi)
-> Condition {Optional}

(0) Basic Attack (Rand) - D6 PHY {x1}
(0) Basic Block (Rand) - D6 -1 PHY {x1}


#### Tier
Damage = +3 -> +6 -> +9 -> +12
Block/Range = 3 -> 6 -> 9 -> 12
Multi = 2 -> 3 -> 4 -> 5
Effect = +1 -> +2 -> +3 -> +4

Cool-down = Tier
All skills start on cool-down
Cool-downs tick down at the end of the turn

Skills can forgo costs to be random
Unless otherwise stated, min 1 for the result of a random skill
#### Damage
Skills that deal single target pure damage.
Pure Damage = +3 -> +6 -> +9 -> +12
Rand Damage = D6 -> 2D6 -> 3D6 -> 4D6

#### Block
Skills that double defenses and take agro.
Pure Damage = +0 -> +3 -> +6 -> +9
Block Range = 3 -> 6 -> 9 -> 12
Rand Block = D6 -> 2D6 -1 -> 3D6 -2 -> 4D6 -3
-Cost Gauge-
Cost Gauge  = -1 -> -2 -> -3 -> -4

#### Multi
Skills that strike a single target multiple times.
Pure Damage = -2 -> -4 -> -6 -> -8
Multi Strikes = 2 -> 3 -> 4 -> 5
Rand Multi  = D6 -3 -> D6 -2 -> D6 - 1 -> D6
-Cost Damage-

#### Range
Skills that strike multiple targets at once.
Pure Damage = +3 -> +6 -> +9 -> +12
Pure Range = 3 -> 6 -> 9 -> 12
Rand Range = D6 -> 2D6 -1 -> 3D6 -2 -> 4D6 -3
-Cost Health-
Cost Health = -3 -> -6 -> -9 -> -12

#### Support
Skills that aid or hinder without dealing damage.
Support skills are static and do not scale on stats
Stat Change = +3 -> +6 -> +9 -> +12
Rand Change = D6 -> 2D6 -1 -> 3D6 -2 -> 4D6 -3
-Cost Health or Gauge-


#### Conditions
Where **X** is the amount of its effect
and **a** is a tier scale factor
aX of a condition does not stack, it overwrites

Out Numbered -> Gain aX per over
a = .1,.25,.5,1
1 on 1       -> Gain aX; X = 1
a = 5,10,15,20
Took Damage  -> Gain aX per damage taken for 1 turn
a = .1,.25,.5,1
Flawless     -> Gain aX per turn without damage
a = 1,2,3,4
Charged      -> Gain aX per action skipped
a = 1,2,3,4
Did Y        -> Gain aX; X = 1
a = 5,10,15,20  (Varied) 
Spent X      -> Gain aX
a = .1,.25,.5,1 (Varied) 
Acquired x   -> Gain aX 
a = 1, 2, 3, 4  (Varied) 

#### Summons
Summons are skills that gain their own turn.

(Tier) Skill Name (Cost) - (VIT) (POW) (DEF/MDF)
-> Condition {Optional}
Skill {Optional}
{Group} Skill {Optional Group Skill}

Stat Rules
Vit is always equal to tier's damage
1 High stat is equal to tier's damage
2 Low stats are equal to tier below's damage (min 1)

(1) Summon Slime (Rand) - (3) (3) (1/1) x(D6 -4)
-> Charged (1X) - Recast Skill per X
{Group} (1) Slime Rain (Rand) - nD6 + 3n ^Summons

