# Underworld
A  Star Wars mod for Unciv. With help from Sullien, and it works well with his Jedi Order and our Galactic Empire. This Underworld mod has mercenaries and smugglers, create your own criminal dynasty.

Changelog
V1 Added prototype for buildings

Galactic-Civil-War-Mod
This is a mod to my and Sullien's mods. This adds extra features not available to the original mods.

"[Guard of The Rock] ability",
for clone: "Guard of the Rock",


{
		"name": "Ryukyu",
		"leaderName": "Sho Hashi",
		"adjective": ["Ryukyu"],
		"startBias": ["Coast"],
		"preferredVictoryType": "Cultural",
		
		"startIntroPart1": "",
		
		"declaringWar": "For the good of The Empire i must declare war!",
		"attacked": "You are making a big mistake.",
		"defeated": "Will this be my last goodbye to you?.",
		"introduction": "Tell me, are you a barbarian, or are you as civilized as we are?",
		
		"neutralHello": "Greetings.",
		"hateHello": "What do YOU want?!",
		
		"tradeRequest": "It appears that you do have a reason for existing – to make this deal with me.",
				
		"outerColor": [240, 209, 36],
		"innerColor": [209, 16, 6],
		"uniqueName": "Shinryo",
		"uniques": ["[+1 Culture] from each Trade Route","[+1 Production] from every [Fishing Boats]"],
		"cities": ["Shuri", "Naha", "Tomari", "Kume", "Okinawa City", "Uruma", "Urasoe", "Ginowan", "Nago", "Tomigusuku", "Itoman", "Miyakojima", "Ishigaki"]
	},
        {
		"name": "The Hisat'sinom",
		"leaderName": "Po'pay",
		"adjective": ["The Hisat'sinom"],
		"startBias": ["Desert"],
		"preferredVictoryType": "Cultural",
		
		"startIntroPart1": "",
		
		"declaringWar": "For the good of my people i must declare war!",
		"attacked": "You are making a big mistake.",
		"defeated": "Will this be my last goodbye to you?.",
		"introduction": "Tell me, are you a barbarian, or are you as civilized as we are?",
		
		"neutralHello": "Hello.",
		"hateHello": "What do YOU want?!",
		
		"tradeRequest": "It appears that you do have a reason for existing – to make this deal with me.",
				
		"outerColor": [56, 41, 29],
		"innerColor": [252, 182, 126],
		"uniqueName": "Kachina",
		"uniques": ["[+2 Food] from each Trade Route","[-25]% Food consumption by specialists [in all cities]"],
		"cities": ["Acoma","Santa Clara","Taos","Laguna","Isleta","Zuni","Hopi","Cochiti","San Ildefonso","Tesuque"]
	},
        {
		"name": "Lada'kwe",
                "replaces": "Composite Bowman",
		"uniqueTo": "The Hisat'sinom",
		"unitType": "Archery",
		"movement": 3,
		"strength": 7,
		"rangedStrength": 12,
		"cost": 75,
		"requiredTech": "Construction",
		"obsoleteTech": "Machinery",
		"upgradesTo": "Crossbowman",
		"attackSound": "arrow"
	},

{
		"name": "The Franks",
		"leaderName": "Charlemagne",
		"adjective": ["Franks"],
		"startBias": ["Forest"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": "",
		
		"declaringWar": "For the good of my people i must declare war!",
		"attacked": "You are making a big mistake.",
		"defeated": "Will this be my last goodbye to you?.",
		"introduction": "Tell me, are you a barbarian, or are you as civilized as we are?",
		
		"neutralHello": "Greetings.",
		"hateHello": "What do YOU want?!",
		
		"tradeRequest": "It appears that you do have a reason for existing – to make this deal with me.",
				
		"outerColor": [23, 20, 74],
		"innerColor": [255, 210, 120],
		"uniqueName": "Holy Roman Emperor",
		"uniques": ["[+5]% [Faith] [in capital]","[+10]% [Production] [in capital]","[+1 Faith, +1 Production] from every [Grand Temple]","[+1 Faith, +1 Production] from every [Workshop]","[+1 Faith, +1 Science] from every [University]"],
		"cities": ["Aachen",
"Paris",
"Reims",
"Trier",
"Cologne",
"Strasbourg",
"Lyon",
"Tours",
"Rouen",
"Orleans"]
	},
{
		"name": "Paladin",
                "uniqueTo": "The Franks",
		"replaces": "Knight",
		"unitType": "Mounted",
		"movement": 4,
		"strength": 25,
		"cost": 120,
		"requiredTech": "Chivalry",
		"obsoleteTech": "Military Science",
		"upgradesTo": "Cavalry",
		"requiredResource": "Horses",
		"uniques": ["[+20]% Strength <during a Golden Age>","Can move after attacking","No defensive terrain bonus","[-33]% Strength <vs cities> <when attacking>", "Never appears as a Barbarian unit"],
		"attackSound": "horse"
	},
	{
		"name": "The Modoc",
		"leaderName": "Kintpuash",
		"adjective": ["The Modoc"],
		"startBias": ["Desert"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": "",
		
		"declaringWar": "For the good of The Empire i must declare war!",
		"attacked": "You are making a big mistake.",
		"defeated": "Will this be my last goodbye to you?.",
		"introduction": "Tell me, are you a barbarian, or are you as civilized as we are?",
		
		"neutralHello": "Greetings.",
		"hateHello": "What do YOU want?!",
		
		"tradeRequest": "It appears that you do have a reason for existing – to make this deal with me.",
				
		"outerColor": [43, 36, 32],
		"innerColor": [151, 191, 96],
		"uniqueName": "Hell With The Fire Out",
		"uniques": ["[+2 Food] in cities on [Hill] tiles","[+1 Food, +1 Faith] from every [Mountain]"],
		"cities": ["Captain Jack's Stronghold","Agawesh","Kumbat","Pashha","Wachamshwash","Nushalt-Hagak-ni","Kalelk","Nakoshkeni","Wukakeni","Keuchishkeni"]
	},
	{
		"name": "Kilosh",
		"uniqueTo": "The Modoc",
		"replaces": "Rifleman",
		"unitType": "Gunpowder",
		"movement": 2,
		"strength": 34,
		"cost": 225,
		"requiredTech": "Rifling",
		"obsoleteTech": "Replaceable Parts",
		"uniques":["[+25]% Strength <when fighting in [Rough terrain] tiles>","Earn [50]% of killed [Wounded] unit's [Cost] as [Culture]"],
		"upgradesTo": "Great War Infantry",
		"attackSound": "shot"
	},
	{
        "name": "The Olmecs",
        "leaderName": "U Kix Chan",
        "adjective": ["The Olmecs"],
        "startBias":["Jungle"],
        "preferredVictoryType": "Domination",


        "startIntroPart1": "",
        "startIntroPart2": "",

                "declaringWar": "We cannot tolerate you anymore",
        "attacked": "The war has hardened us, but it has not broken us",
        "defeated": "This cannot happen!",
        "introduction": "Welcome to our land",
        "neutralHello": "Hello.",
        "hateHello": "We do not fear war",
        "tradeRequest": "Check out this",
        "outerColor": [66, 245, 149],
        "innerColor": [7, 31, 18],
        "uniqueName": "Venus Cycle",
        "uniques": ["[+25]% [Culture] [in all cities] <for [5] turns> <upon constructing [Temple]>","[+5]% [Science] [in all cities] <for [5] turns> <upon constructing [Shrine]>"],
        "cities": ["Coatzacoalcos", "Tonalá", "Papaloapan", "Tzapotl", "Tuxtlas", "Tak'alik A'baj", "Oxtotitlán", "Chalcatzingo"],
        "spyNames": ["Tangaroa"]
    },
    building: ball court

{
		"name": "Turkiye",
		"leaderName": "Mustafa Kemal Atatürk",
		"adjective": ["Turkiye"],
		"startBias": ["Plains"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": "",
		
		"declaringWar": "For the good of my people i must declare war!",
		"attacked": "You are making a big mistake.",
		"defeated": "Will this be my last goodbye to you?.",
		"introduction": "Tell me, are you a barbarian, or are you as civilized as we are?",
		
		"neutralHello": "Greetings.",
		"hateHello": "What do YOU want?!",
		
		"tradeRequest": "It appears that you do have a reason for existing – to make this deal with me.",
				
		"outerColor": [255, 65, 59],
		"innerColor": [255, 255, 255],
		"uniqueName": "The Six Arrows",
		"uniques": ["[+1 Culture, +1 Science] from every specialist [in all cities] <during a Golden Age>","[+40]% Production when constructing [Siege] units [in all cities] <during a Golden Age>"],
		"cities": ["Ankara",
"Istanbul",
"Izmir",
"Bursa",
"Antalya",
"Konya",
"Adana",
"Gaziantep",
"Kayseri",
"Trabzon"]
	},
{
		"name": "Rediff Infantry",
                "uniqueTo": "Turkiye",
		"replaces": "Rifleman",
		"unitType": "Gunpowder",
		"movement": 2,
		"strength": 34,
		"cost": 225,
		"requiredTech": "Rifling",
                "uniques": ["[+25]% Strength decreasing with distance from the capital","[+30]% to Flank Attack bonuses"],
		"obsoleteTech": "Replaceable Parts",
		"upgradesTo": "Great War Infantry",
		"attackSound": "shot"
	},
{
		"name": "Chola",
		"leaderName": "Rajendra Chola I",
		"adjective": ["Chola"],
		"startBias": ["Coast"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": "",
		
		"declaringWar": "For the good of The Empire i must declare war!",
		"attacked": "You are making a big mistake.",
		"defeated": "Will this be my last goodbye to you?.",
		"introduction": "Tell me, are you a barbarian, or are you as civilized as we are?",
		
		"neutralHello": "Greetings.",
		"hateHello": "What do YOU want?!",
		
		"tradeRequest": "It appears that you do have a reason for existing – to make this deal with me.",
				
		"outerColor": [203, 214, 245],
		"innerColor": [39, 42, 51],
		"uniqueName": "Samayam",
		"uniques": ["[+25]% Strength <for [Melee Water] units>","[+5]% Strength <for [Wounded] units>","[+1 Gold] from each Trade Route"],
		"cities": ["Thanjavur",
"Chennai",
"Bangalore",
"Hyderabad",
"Coimbatore",
"Thanjavur",
"Kanchipuram",
"Tiruchirappalli",
"Kozhikode",
"Mysore",
"Vijayawada",
"Visakhapatnam",
"Pondicherry",
"Salem",
"Erode"
],
	},
{
		"name": "Thirisadai",
                "uniqueTo": "Chola",
		"replaces": "Galleass",
		"unitType": "Melee Water",
		"movement": 3,
		"strength": 22,
		"cost": 180,
		"requiredTech": "Compass",
		"obsoleteTech": "Navigation",
		"upgradesTo": "Frigate",
		"uniques": ["[+25]% Strength <vs [Galleass] units>","Cannot enter ocean tiles"],
		"attackSound": "arrow"
	},
{
		"name": "Urumi Swordsman",
                "uniqueTo": "Chola",
		"replaces": "Swordsman",
		"unitType": "Sword",
		"movement": 2,
		"strength": 16,
		"cost": 78,
		"requiredTech": "Iron Working",
		"upgradesTo": "Longswordsman",
		"obsoleteTech": "Steel",
		"requiredResource": "Iron",
                "uniques": ["[1] additional attacks per turn"],
		"hurryCostModifier": 20,
		"attackSound": "metalhit"
	},
	{
		"name": "Cree",
		"leaderName": "Poundmaker",
		"adjective": ["Cree"],
		"startBias":["None"],
		"preferredVictoryType": "Domination",


        "startIntroPart1": "",
        "startIntroPart2": "",

                "declaringWar": "We cannot tolerate you anymore",
		"attacked": "The war has hardened us, but it has not broken us",
		"defeated": "This cannot happen!",
		"introduction": "Welcome to our land",
		"neutralHello": "Hello.",
		"hateHello": "We do not fear war",
		"tradeRequest": "Check out this",
		"outerColor": [22, 28, 61],
		"innerColor": [185, 255, 115],
		"uniqueName": "Wahkohtowin",
		"uniques": ["New [Okichitaw] units start with [20] XP [in capital] <hidden from users>","[+1 Production] from every [Camp]","[+2 Gold] from every [Pasture]",
		"[+1 Production] from every [Camp] <after discovering [Gunpowder]>",
	    "[+1 Production] from every [Pasture] <after discovering [Gunpowder]>"],
		"cities": ["Mikisiw-Wacîhk", "Ahtahkakoop", "Pihtokahanapiwiyin", "Mistahi-Sipihk", "Mistawasis", "Wihkasko-Kiseyin", "Makwa-Sakahikan", "Maskotew", "Paskwaw-Askihk"],
        "spyNames": ["Saki"]
    },
	{
		"name": "Okichitaw",
		"uniqueTo": "Cree",
		"replaces": "Scout",
		"unitType": "Scout",
		"movement": 2,
		"strength": 8,
		"cost": 25,
		"obsoleteTech": "Scientific Theory",
		"uniques": ["[-100]% maintenance costs","Comment [Starts with 20 XP]","May upgrade to [Archer] through ruins-like effects", "Never appears as a Barbarian unit"],
		"promotions": ["Ignore terrain cost"],
		"attackSound": "nonmetalhit"
	},
	{
		"name": "Khmer",
		"leaderName": "Jayavarman VII",
		"adjective": ["Khmer"],
		"startBias": ["Jungle"],
		"preferredVictoryType":"Diplomatic",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "You are in my way, you must be destroyed.",
		"attacked": "As a matter of fact I too grow weary of peace.",
		"defeated": "You have somehow become my undoing! What kind of beast are you?",
		"introduction": "Hello stranger!",

		"neutralHello": "Greetings!",
		"hateHello": "What?",

		"tradeRequest": "My friend, does this seem reasonable to you?",

		"outerColor": [242, 206, 153],
		"innerColor": [133, 46, 0],
		"uniqueName": "Great Barays of Angkor",
		"uniques": ["[+1 Faith, +1 Food] from each Trade Route","[+10]% [Culture] [in all cities]","[+10]% [Food] [in all cities]"],
		"cities": ["Angkor Thom", "Yasodharapura", "Hariharalaya", "Nagara Jayasri", "Rajavihara", "Isvarapura", "Banteay Kdei", "Jayendranagari", "Pre Rup"],
	},
{
		"name": "State of Israel",
		"leaderName": "David Ben-Gurion",
		"adjective": ["State of Israel"],
		"startBias": ["Desert"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": "",
		
		"declaringWar": "This is the end for you!",
		"attacked": "You are joking? I will destroy you!.",
		"defeated": "It is over. have mercy with my people.",
		"introduction": "Hello great leader, you are as civilized as us?",
		
		"neutralHello": "Greetings.",
		"hateHello": "What do YOU want?!",
		
		"tradeRequest": "It appears that you do have a reason for existing – to make this deal with me.",
				
		"outerColor": [237, 237, 237],
		"innerColor": [71, 102, 255],
		"uniqueName": "Aliyah",
		"uniques": ["[+1 Gold, +1 Production] per every [5] [Faith]","[+1 Science] per every [9] [Faith]","[+1 Science] per every [4] [Faith] <starting from the [Modern era]>","[+1 Gold, +1 Production] per every [5] [Faith] <starting from the [Modern era]>"],
		"cities": ["Jerusalem", "Tel Aviv", "Haifa", "Rishon LeZion", "Petah Tikva", "Netanya", "Ashdod", "Bnei Brak", "Beersheba", "Holon", "Ramat Gan", "Beit Shemesh", "Ashkelon", "Rehovot", "Bat Yam", "Herzliya", "Hadera", "Kfar Saba", "Modi'in-Maccabim-Re'ut"],
	},
	{
		"name": "The Maldives",
		"leaderName": "Muhammad Thakurufaanu",
		"adjective": ["The Maldives"],
		"startBias":["Coast"],
		"preferredVictoryType": "Domination",
	
	
		"startIntroPart1": "",
		"startIntroPart2": "",
	
				"declaringWar": "We cannot tolerate you anymore",
		"attacked": "The war has hardened us, but it has not broken us",
		"defeated": "This cannot happen!",
		"introduction": "Welcome to our land",
		"neutralHello": "Hello.",
		"hateHello": "We do not fear war",
		"tradeRequest": "Check out this",
		"outerColor": [222, 255, 234],
		"innerColor": [21, 38, 27],
		"uniqueName": "State of the Mahal Dibiyat",
		"uniques": ["[+15]% [Gold] from every [Coast]","[+15]% [Faith] from every [Coast]","[+25]% Strength <for [Melee Water] units>"],	
		"cities": ["Malé", "Addu", "Kulhudhuffushi", "Fuvahmulah", "Thinadhoo", "Ungoofaaru", "Dhidhdhoo", "Thulusdhoo", "Funadhoo", "Manadhoo"],
		"spyNames": ["Saki"]
	},
	{
		"name": "Coral Stone Mosque",
		"uniqueTo": "The Maldives",
		"replaces": "Temple",
		"faith": 2,
		"culture":1,
		"happiness":1,
		"requiredBuilding": "Shrine",
		"maintenance": 2,
		"hurryCostModifier": 25,
		"requiredTech": "Philosophy",
		"uniques": ["Only available <when religion is enabled>", "Destroyed when the city is captured"]
	},
  
