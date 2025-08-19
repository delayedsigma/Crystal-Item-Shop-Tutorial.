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
        "itemGrants": ["EID_CelebrationDance"],
        "price": 0
    },
    "daily2": {
      "itemGrants": [ "Umbrella_Buffet_Silver_P2HUY"],
        "price": 0
    },
    "daily3": {
        "itemGrants": ["EID_Vivid_I434X"],
        "price": 300
    },
    "daily4": {
        "itemGrants": ["Pickaxe_ID_359_CycloneMale"],
        "price": 1500
    },
    "daily5": {
        "itemGrants": ["CID_333_Athena_Commando_M_Squishy"],
        "price": 2000
    },
    "daily6": {
        "itemGrants": ["EID_NeverGonna"],
        "price": 100000
    },
    "featured1": {
        "itemGrants": ["CID_703_Athena_Commando_M_Cyclone"],
        "price": 2000
    },
    "featured2": {
        "itemGrants": ["CID_761_Athena_Commando_M_CycloneSpace"],
        "price": 3500
    },
    "featured3": {
        "itemGrants": ["CID_A_182_Athena_Commando_M_Vivid_LZGQ3"],
        "price": 1500
    },
    "featured4": {
        "itemGrants": ["CID_A_136_Athena_Commando_M_Majesty_YR1GJ"],
        "price": 0
    }   
}
```
Important:
**Please set the item prices thoughtfully, adjusting them based on each skin’s rarity and exclusivity to ensure a balanced and fair shop experience.**


---

## Tips for Editing

* Use a JSON-aware editor like Visual Studio Code for better validation and formatting.
* Use ChatGPT To validate your Json.
