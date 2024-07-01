---
{"dg-publish":true,"permalink":"/the-talisman-campaign/the-token-taxonomy/","noteIcon":""}
---

***Top***
***Order***
***Kind***
***Entia***
***Nominal***

Tops = {
	~1 : Entity,
	~2 : Location,
	~3 : Object,
	~4 : Functional,
	~5 : Tracker,
	~6 : DM Secret}

Orders= {
	'A':  “Ability”,
	'B': “Biome”,
	'C': “Class”,
	'D': “Deity”, 
	'E': “Entity”,
	'F': “Flaw”,,                   
	'G': “Goal”,
	'H': “Hub”,                   
	'I': “Info”,
	'J': “Justice”,
	'K': “Knowledge”,
	'L': “Location”,
	'M': “Material”,
	'N': “Name”,               
	'O': “Object”,        
	'P': “Power”,
	'Q': “Quest” ,
	'R': “Rarity”,
	'S': “Spell”,               
	'T': “Type”, 
	'U': “Utility”,
	'V': “Verb”,
	'W': “Widespread”,
	'X': “Secret”,
	'Y': “Year”,
	'Z': “Zone”,
	'Œ': “Method to Madness”, 
	'¥:' “Landmark”,
	'ř': “Ruin”,
	'¢': “Gold Price”,
	'Æ': “Artifact”,
	'≈': “Network”
	'!': “Notifier”
	'‰': “Quest Progress”
	'ç': “Corruption”,
	'Þ': “Front”}

Kind= {
	"#.#.#.#."
	"1.1.1.1."
	"6.6.6.6."}

Entia= {
	',1': 'Advances 1/day 100%, Yes or No'
	',d2': 'Daily, 2, 50%, Simple errand'
	',d4': 'Daily, 4, 25% Multistage trip'
	',d6': 'Daily, Wild & Safe Zones, 6, 16.66%, Cycles'
	',d8': 'Weekly, Wild & Dungeon Zones, 8, 12.50%, Seasons'
	',d10': 'Weekly,10,10%, Plans of Immortals & Mortals'}

Nominal= {
	Name}

Tops:  Orders
~1: E,A,C,F,G,Œ (Entity, Ability, Class, Flaw, Goal, Method to Madness)
~2: L,B,H,Z, ¥, ř (Location, Biome, Hub, Zone, Landmark, Ruin)
~3: O,M,R,U, ¢, Æ (Object, Material, Rarity, Utility, Gold Price, Artifact)
~4: N,T,V,S, ≈, ! (Name, Type, Verb, Spell, Network, Notify)
~5: J,K,W,Y, ‰, ç (Justice, Knowledge, Widespread, Year, Quest Progress, Corruption)
~6: D,I,P,Q,X,Þ (Deity, Info, Power, Quest, Secret, Front)
