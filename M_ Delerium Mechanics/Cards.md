Classes -> Gameplay
- Combo - Keep Going
	- Draw 1
	- Draw 2
	- Discard 2, Draw 3
	- All Draw 1
	- All Draw 2
	- All Draw 3
	 
- Discard - Stop Going
	- Target Discard 1
	- Target Discard 2
	- Target Discard 3, Recycle 1
	- All Discard 1
	- All Discard 2
	- All Discard 3

- Recycle - Restart
	- Discard 1, Recycle 1
	- Recycle 1
	- Discard 2, Recycle 2
	- All Discard 1, Recycle 1
	- All Recycle 1
	- All Recycle 2
	
- Turn - Change
	- Reverse Turn
	- Discard 3, Take Turn
	- Target Reverse Turn
	- Target Take Turn
	- Target Skip Turn
	- Target Take 2 Turns


Elements -> Conditions
- Skill Tiers (Score) - Multi
	- (0) - Tier 0 - 1.5x
	- (50) - Tier 1 - 2x
	- (100) - Tier 2 - 3x
	- (150) - Tier 3 - 4x
	- (200) - Tier 4 - 5x
	  
- Fire - Score
	- if Score > Tier Condition, Multiply score by Tier Multi/10
- Earth - Defense
	- if Score > Tier Condition, Unaffected by lower tier
- Ice - Stop
	- if Score > Tier Condition, Negate next tier below
- Wind - Combo
	- if Score > Tier Condition, increase combo count by tier

Status -> Disruption
- Skill Tiers (Score) - Multi
	- (0) - Tier 0 - 1.5x
	- (50) - Tier 1 - 2x
	- (100) - Tier 2 - 3x
	- (150) - Tier 3 - 4x
	- (200) - Tier 4 - 5x
	
	- Sickness/Fatigue/Numb/Blind : Status
		- Divide stats by Tier Multi
		- Turns = Skill Tier
		- 0.5x Score