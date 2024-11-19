# Wow-addon
## Wrath of the Lich King 3.3.5
NPC Scan, Ackis Recipe List, ACP, Addon Loader, Afflicted, Altoholic, Ark Inventory, Armory, Atlas, Auctioneer Suit, Auto Repair, BadBoy, BadKitty, Bag Gnon+, Baggins, Bartender4, BindPad, Black List, Buffer, Carbonite, CCR Report, Cellular, Chat MOD, Chatter, Chinchilla, Class Loot, Clique, Cooldown Pulse, Cooldown Count, Crap Away, CritLine, Cromulent, Debuff Filter, Decursive, DBM, DrDamage, Dominos, Easy Loot, Elk Buff Bars, Event Alert, Elitist Group, Fishing Buddy, ForteXorcist, Gather Mate2, Genie, Gladius, Grid, Group Calendar, GTFO, Guild Greet, Handy Notes, Healers Have To Die, Healium, HealBot, IceHUD, Interrupt Bar, Jamba, kg Panels, Lose Control, Mage Nuggets, Map Coords, Mapster, MiniMap Button Frame, Molten AH Fix, Move Anything, Need To Know, Nug Combo Bar, Omen, OmniCC, OPie, Outfitter, Overachiever, Parrot, PitBull4, Poisoner, Postal, Prat, Quartz, Quest Helper, Quick Mark, Raid Roll, Recount, Reflex, Sell O Matic, Sexy Map, Shadowed Unit Frames, Simple Raid Target Icons, Simple Unit Frames, Skada, Skinner, Smart Buff, Spartan UI, Spy, Sunn Art, TBag, Tip Tac, Titan Panel, Tidy Plates, TomTom, Tool Tip Tabs, Totem Timers, Trade Skill Info, Trivial Bot, Volumizer, Vuh Do, WIM, X Loot, X Perl

- ## Cataclysm 4.3.4
NPC Scan, Ackis Recipe List, ACP, Addon Loader, Afflicted, Altoholic, Armory, Ark Inventory, Atlas, Atlas Loot, Auctionator, Auctioneer Suite, Auto Repair, BadBoy, BadKitty, Bag Gnon+, Baggins, Bartender4, BindPad, Black List, Buffer, Capping, Carbonite, CCR Report, Cellular, Chat Sounds, Chatter, Chinchilla, Class Loot, Clique, Collectorator, Cooldown Count, Crap Away, CritLine, Cromulent, DBM, Debuff Filter, Decursive, Doom Cooldown Pulse, Dominos, DoTimer, DrDamage, Easy Loot, Elk Buff Bars, ElvUI Master, ESBG, Event Alert, Extra CD, Fishing Buddy, ForteXorcist, Gatherer, GatherMate2, Genie, GladiatorLOS, Gladius, Grid, Group Calendar, GTFO, Guild 2 Guild, Guild Greet, Handy Notes, HealBot, Healers Have To Die, Healium, Health Warning, IceHUD, Interrupt Bar, Jamba, Juked, kg Panels, Lose Control, Mage Nuggets, Map Coords, Mapster, Mik Scrolling Battle Text, MiniMap Button Frame, MogIt, Move Anything, Need To Know, Nug Combo Bar, OmniCC, OneBag3, Outfitter, Overachiever, Parrot, PitBull4, Poisoner, Postal, Prat, Quartz, Quest Complete List, Quest Helper Lite, Quick Mark, Raid Roll, Recount, Reflex, Reforgenator, Sell O Matic, Sexy Map, Shadowed Unit Frames, Silver Dragon, Simple Raid Target Icons, Simple Unit Frames, Skada, Skinner, Smart Buff, Spy, Sunn Art, Tabard Addict, TBag, Tip Tac, Tidy Plates, Titan Panel, TomTom, Tool Tip Tabs, Total RP 2, Totem Timers, Trade Skill Info, TradeSkillMaster with modules, Trivia Bot, Volumizer, Vuh Do, Weak Auras Cata Master, WIM, X Loot, X Perl

## Mist of Pandaria 5.4.2
NPC Scan, Ackis Recipe List, ACP, Addon Loader, Afflicted, Archy, Arena Spy, Ark Inventory, Armory, Auctionator, Auto Repair, BadBoy, BadKitty, Bartender4, Buffer, Capping, Carbonite, Cellular, Chat MOD, Chat Sounds, Chatter, Collectorator, Crap Away, Cromulent, DBM, Debuff Filter, Decursive, Dominos, Doom Cooldown Pulse, DoTimer, Easy Loot, Elk Buff Bars, ESBG, Event Alert, ForteXorcist, Gatherer, Genie, Grid, Group Calendar, GTFO, Guild 2 Guild, Guild Greet, Handy Notes, Healers Have To Die, Healium, Health Warning, IceHUD, Jamba, Juked, Lose Control, Mage Nuggets, Map Coords, Mapster, Masque, MiniMap Button Frame, MogIt, Move Anything, Need To Know, Nug Combo Bar, Omen, OmniCC, OPie, Outfitter, Postal, Prat, Quartz, Quest Complete List, Quest Helper Lite, Quick Mark, Raid Roll, Recount, Reforgenator, RogueDAR, Scrap, Sell O Matic, Sexy Map, Shadowed Unit Frames, Silver Dragon, Simple Raid Target Icons, Simple Unit Frames, Skada, Skinner, Smart Buff, Spartan UI, Spy, Sunn Art, Tidy Plates, Titan Panel, Tool Tip Tabs, Total RP 2, Totem Timers, Trivia Bot, Volumizer, Weak Auras, WIM, X Loot, X Perl

# ElvUI/WeakAuras Profiles
> Created on 16:10 aspect ratio (1440 x 900px)
- ElvUI-2.94 Heal | WeakAuras-3.2.3 Holy Paladin
    - Party frame ![Party frame.](https://github.com/amansuw/wow-addons/blob/main/Profiles/Heal-HolyPaladinWA-Party.jpg)
    - 10 Man frame ![10 Man Raid frame.](https://github.com/amansuw/wow-addons/blob/main/Profiles/Heal-HolyPaladinWA-10Man.jpg)
    - 25 Man frame ![25 Man Raid frame.](https://github.com/amansuw/wow-addons/blob/main/Profiles/Heal-HolyPaladinWA-25Man.jpg)

- ElvUI-2.94 DPS/Tank - WeakAuras-3.2.3 Unholy Death Knight
![Unholy DK with Pet Frame updated.](https://github.com/amansuw/wow-addons/blob/main/Profiles/DPS-UnholyDKWA.jpg)

# Enchanting Macros
<!-- Auto Enchant Macro -->
<!-- Enchants currently selected enchant to appropriate Item slot and replaces existing enchant as well. -->
<!-- If mouse if hovered over an Item then it'll try to enchant that item instead -->
#show enchanting
/script DoTradeSkill(GetTradeSkillSelectionIndex());
/run GetMouseFocus():Click()
/script ReplaceEnchant();
/click StaticPopup1Button1

<!-- Disenchant Hovered Item -->
#showtooltip Disenchant
/run local f=DeM or CreateFrame("Button","DeM",nil,"SecureActionButtonTemplate") f:SetAttribute("type","click") f:SetAttribute("clickbutton",GetMouseFocus())
/dismount
/cast Disenchant
/click DeM

<!-- Straight up disenchants mentioned item -->
/cast disenchant
/use Black Mageweave Leggings