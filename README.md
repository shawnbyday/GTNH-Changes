# GTNH-Changes

This is a simple collection of my changes to GTNH modpack. These changes are simply to be able to enjoy the modpack more.

# Configuration Changes

* config/endercore/endercore.cfg - B:betterAchievements=false
* config/IguanaTinkerTweaks/main.cfg - B:easyToolRepair=true
* config/holoinventory.cfg - S:bannedTiles <com.rwtema.extrautils.tileentity.TileEntityFilingCabinet>
* config/adventurebackpack.cfg - B:"Enable Overlay"=false
* config/GraviSuite.cfg - I:hudPosition=4
* config/GregTech/Pollution.cfg - B:"Activate Pollution"=false
* config/Thaumcraft.cfg - B:wand_dial_bottom=false
* config/lootgames/games/game_of_light.cfg - I:weight=0
* config/gendustry/overrides/tuning.cfg - cfg Mutatron -> DegradeChanceNatural = 0, cfg Mutatron -> DeathChanceArtificial = 0, cfg MutatronAdv -> DegradeChanceNatural = 0, cfg MutatronAdv -> DeathChanceArtificial = 0, cfg Imprinter -> DeathChanceNatural = 0, cfg Imprinter -> DeathChanceArtificial = 0
* serverutilities/server/ranks.txt - [player, vip, admin] -> serverutilities.claims.max_chunks: 5000, serverutilties.chunkloader.max_chunks: 5000, serverutilities.homes.max: 1000, serverutilities.homes.warmup: 0s, serverutilities.homes.cooldown: 0s, serverutilities.homes.cross_dim: true
* serverutilities/server/serverutilities.cfg - B:enable_backups=false
* config/AppliedEnergistics2/AppliedEnergistics2.cfg - S:CRAFTING_SORT_BY=AMOUNT
* config/AppliedEnergistics2/AppliedEnergistics2.cfg - S:SORT_DIRECTION=DESCENDING
* config/AppliedEnergistics2/AppliedEnergistics2.cfg - I:craftAmtButton2=64
* config/AppliedEnergistics2/AppliedEnergistics2.cfg - I:levelAmtButton2=64
* config/forestry/common.cfg - B:disable.butterfly=true
* config/EnderStorage.cfg - item.storage-size=2
* config/structurelib.cfg - I:autoPlaceBudget=200
* config/structurelib.cfg - I:autoPlaceInterval=50
* config/GregTech/WorldGeneration.cfg - B:generateUndergroundDirtGen=false
* config/GregTech/WorldGeneration.cfg - B:generateUndergroundGravelGen=false
* config/enderio/EnderIO.cfg - I:travelAnchorCooldown=10
* config/enderio/EnderIO.cfg - I:travelAnchorMaxDistance=2048
* config/findit.cfg - S:SearchRadius=64
* config/GTNotLeisure/recipe.cfg - B:enableShowDelRecipeTitle=false

# Client Mod Additions

* Clean View
* Journey Map Unlimited
* Spark (https://github.com/GTNewHorizons/spark)
* Shared Prospecting (https://github.com/GTNewHorizons/SharedProspecting)
* AE2 Web Integration (https://github.com/kuba6000/AE2-Web-Integration)
* Lag Goggles (https://github.com/FalsePattern/LagGogglesLegacy)
* Simple Storage (https://github.com/LITW-Refined/EZStorage)
* Programmable Hatches (https://github.com/reobf/Programmable-Hatches-Mod)
* DEConfig-Integration (https://github.com/Drathonix/DEConfig-Integration)
* Twist Space (https://github.com/Nxer/Twist-Space-Technology-Mod)
* 123 Tech (https://github.com/CallmeSHaobe/123Technology)
* GTNL (https://github.com/GTNotLeisure/GT-Not-Leisure)
* Shadow UI (https://github.com/Ranzuu/Shadow-UI)
* GTNH Outlined Ores (https://github.com/Ranzuu/GTNH-OutlinedOres)
* Twist Space Quest Line (https://github.com/AdityaVG13/Twist-Stuff)
* GTNH World Edit (https://github.com/GTNewHorizons/worldedit-gtnh)

# Server Mod Additions

* Journey Map Unlimited
* Spark (https://github.com/GTNewHorizons/spark)
* Shared Prospecting (https://github.com/GTNewHorizons/SharedProspecting)
* AE2 Web Integration (https://github.com/kuba6000/AE2-Web-Integration)
* Lag Goggles (https://github.com/FalsePattern/LagGogglesLegacy)
* Simple Storage (https://github.com/LITW-Refined/EZStorage)
* Programmable Hatches (https://github.com/reobf/Programmable-Hatches-Mod)
* DEConfig-Integration (https://github.com/Drathonix/DEConfig-Integration)
* Twist Space (https://github.com/Nxer/Twist-Space-Technology-Mod)
* 123 Tech (https://github.com/CallmeSHaobe/123Technology)
* GTNL (https://github.com/GTNotLeisure/GT-Not-Leisure)
* Twist Space Quest Line (https://github.com/AdityaVG13/Twist-Stuff)
* GTNH World Edit (https://github.com/GTNewHorizons/worldedit-gtnh)

# Client Mod Removals

* Default Server List (Don't forget the CFG file too).
* Journey Map Fairplay

# Server Mod Removals

* Default Server List (Don't forget the CFG file too).
* Journey Map Fairplay

# Game Rule Changes
* /gamerule doFireTick false
* /gamerule keepInventory true
