# Wow-addon
# ElvUI Profiles
# WeakAuras Profiles

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