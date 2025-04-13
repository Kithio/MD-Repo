# General Changes
`CastleHeartDamageMode` changed from `CanBeDestroyedByPlayers` to `CanBeDestroyedOnlyWhenDecaying`.
**Effect**: Players are able to remove completely decayed castles if they are left to rot for an extended period of time.
**Why?**: In order to let people remove a castle from a claimed location they want if someone has forgotten to remove their old castle after moving to a new location and simply left it to decay.

`DeathContainerPermission` changed from `Anyone` to `ClamMembers.`
**Effect**: Allows your clan members to open your death container and loot your corpse in order to help you retrieve your things should they be stuck somewhere you cannot get to or you do not have enough inventory space to hold it yourself.
**Note**: Can be changed to `OnlySelf` if people would rather have that and would be sure they'll completely loot their own corpse and not leave the box sitting around in a location after death.

`RelicSpawnType` changed from `Unique` to `Plentiful`.
**Effect**: Soul Shards are respawned after being claimed by a player, allowing multiple people to get access to them over time on their own.

`InactivityKillEnabled` changed from `true` to `false`.
**Effect**: Your inactive body will not be killed over time while offline and not in a coffin.
**Note**: You will potentially still decay down in health if you logout while not in a coffin, but you won't get killed by an inactivity timer.

`InventoryStacksModifier` changed from `1.0` to `2.0`.
**Effect**: This will allow players to carry twice the amount of items in a stack of items as prior.

`DropTableModifier_Missions` changed from `1.0` to `1.75`.
**Effect**: Increases the amount of resources your servants grant upon a successful hunt.
**Why?**: The brutal difficulty comes with an innate 25% increase to the generic drop multiplier from slain enemies and chests. However this left servants feeling lacking as they got no increase in rewards from Brutal, changing them from 1.0 to 1.75 grants a 75% increase in resources, hopefully making them actually feel worthwhile to use compared to before.

`ClanSize` changed from `4` to `20`.
**Effect**: Changes the maximum amount of slots available for players in a clan, allowing larger groups to play together should they feel like sharing clans and/or resources easily.

`CastleRelocationCooldown` changed from `10800` to `600`.
**Effect**: Makes players able to relocate their castles with a 10 minute cooldown instead of a 3 hour cooldown.

# Crafting / Refining Changes
`RecipeCostModifier` changed from `1.0` to `1.5`.
**Effect**: With the complete removal of durability loss, crafting cost has been increased by 50% as a balancing act.
**Why?**: This was adjusted to make the power gained from never having to repair the items feel justified as a one-time up-front cost instead.
**Note**: This particular change can be changed/reverted based on feedback.

`CraftRateModifier` changed from `1.0` to `2.0`.
**Effect**: Doubles the speed items are crafted at.

`RefinementRateModifier` changed from `1.0` to `2.0`.
**Effect**: Doubles the speed items are refined at.

`ServantConvertRateModifier` changed from `1.0` to `1.5`.
**Effect**: Increases the speed at which servants are converted at by 50%.

# Durability Changes
`DurabilityDrainModifier` changed from `0.5` to `0`.
**Effect**: Durability drain on hit / getting hit has been removed.

`Death_DurabilityFactorLoss` changed  from `0.125` to `0`.
**Effect**: Death no longer reduces any durability on equipment.

`Death_DurabilityLossFactorAsResources` changed from `1.0` to `0`.
**Note**: With no loss of durability, this change shouldn't do anything, but it's changed just in-case.

# Game Time Changes
`DayDurationInSeconds` changed from `1080` to `1440`.
**Effect**: Changes the day-night cycle from 18 minutes to 24 minutes, meaning the time-ratio becomes 1 minute per hour in-game.

`BloodMoonFrequency_Min` changed from `10` to `7`.
`BloodMoonFrequency_Max` changed from `18` to `21`.
**Effect**: The general frequency of blood moons becomes more varied and lets them potentially come back sooner than normal, but may take up to 3 weeks (in-game) to come back.

# Castle Changes
`SafetyBoxLimit` changed from `1` to `4`.
**Effect**: Allows more "Vampire Lockboxes" (Personal Boxes) to be placed within a given castle.

`PrisonCellLimit` changed from `16` to `30`.
**Effect**: Increases the amount of "Prison Cells" players are able to place inside their castles.

`FloorLimit` changed from `50, 140, 240, 360, 550` to `100, 200, 350, 500, 800`
**Effect**: Allows players to build larger castles overall.

`ServantLimit` changed from `4, 5, 6, 7, 8` to  `6, 8, 12, 16, 20`
**Effect**: Allows players to have access to more servants.

`HeightLimit` changed from `3, 3, 3, 3, 3` to `3, 3, 4, 4, 5`.
**Effect**: Allows players to build taller castles as they level up their heart.

`NetherGateLimit` changed from `1` to `2`.
**Effect**: Should allow players to have up to two "Waygate" structures in their castle.

`ThroneOfDarknessLimit` changed from `1` to `4`.
**Effect**: Allows players to place down up to four "Throne of Darkness" structures in their castle.
**Note**: The "Throne of Darkness" is a cosmetic item and has no real function other than being a trophy to show off you've bested the most difficult challenge V Rising has to offer.

# Trader Changes
`StockModifier` changed from `1.0` to `2.5`.
**Effect**: Grants all Traders access to more items available in their shop at a time.

`RestockTimerModifier` changed from `1.0` to `0.5`.
**Effect**: All Traders now restock their items at half the time. Meaning Trades should be more available overall for players looking to spend their coin.

# WarEvent Changes (Incursions)
`Interval` changed from `VeryShort` to `Minimum`.
**Effect**: WarEvent (Incursions) should occur once every 30 minutes.

`MinorDuration` changed from `VeryShort` to `Medium`.
`MajorDuration` changed from `VeryShort` to  `Medium`.
**Effect**: Duration of WarEvents (Incursions) both Tier 1 and Tier 2 have been increased to 30 minutes allowing players to spend a bit more time farming in every incursion and hopefully lets players clear them consistently in time when playing solo.

`ScalingPlayers PointsModifier` changed from `1, 0.5, 0.25, 0.25` to `1, 1, 1, 1`
`ScalingPlayers DropModifier` changed from `1, 0.5, 0.25, 0.25` to `1, 1, 1, 1`
**Effect**: The amount of resources dropped should remain at a factor of 100% when clearing as a party.
