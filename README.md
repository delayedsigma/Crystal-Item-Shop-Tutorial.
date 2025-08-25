# Crystal Item Shop Tutorial!

> **Note:**
> All Fortnite cosmetics are available at [Fortnite.gg](https://fortnite.gg/cosmetics?game=br&type=outfit&season=1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19).

---

## Configuration File Structure

The item shop is defined by a JSON file containing slots for daily (`daily1` through `daily6`) and featured (`featured1` through `featured4`) items. Each slot includes:

**How To Get ID: To get the CID, etc for an item, go to Fortnite.gg, click on any item, and copy the ID shown at the bottom right of the pop-up. Use that ID to replace "CID_TBD" in your config.**
```json
{
    "//": "BR Item Shop Config",
    "daily1": {
        "itemGrants": ["StreetFashionEclipseBundle"],
        "price": 0
    },
    "daily2": {
      "itemGrants": [ "CID_A_040_Athena_Commando_F_Temple"],
        "price": 1500
    },
    "daily3": {
        "itemGrants": ["CID_921_Athena_Commando_F_ParcelPetal"],
        "price": 0
    },
    "daily4": {
        "itemGrants": ["CID_926_Athena_Commando_F_StreetFashionDiamond"],
        "price": 3000
    },
    "daily5": {
        "itemGrants": ["Pickaxe_ID_359_CycloneMale"],
        "price": 1500
    },
    "daily6": {
        "itemGrants": ["Glider_ID_349_GimmickMale_MC92O"],
        "price": 30
    },
    "featured1": {
        "itemGrants": ["EID_RichFam"],
        "price": 1000
    },
    "featured2": {
        "itemGrants": ["EID_Chuckle"],
        "price": 0
    },
    "featured3": {
        "itemGrants": ["CID_A_335_Athena_Commando_M_SleekGlasses_8SYX2"],
        "price": 1000
    },
    "featured4": {
        "itemGrants": ["CID_660_Athena_Commando_F_BandageNinjaBlue"],
        "price": 4500
    }   
}
```
Important:
**Please set the item prices thoughtfully, adjusting them based on each skin’s rarity and exclusivity to ensure a balanced and fair shop experience.**


---

## Tips for Editing

* Use a JSON-aware editor like Visual Studio Code for better validation and formatting.
* Use ChatGPT To validate your Json.
