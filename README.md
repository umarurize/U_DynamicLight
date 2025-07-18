## U-DynamicLight

<code><a href="https://github.com/umarurize/UTP"><img height="25" src="https://github.com/umarurize/U_DynamicLight/blob/master/logo/logo.png" alt="U-DynamicLight" /></a>&nbsp;U-DynamicLight</code>

![Total Git clones](https://img.shields.io/badge/dynamic/json?label=Total%20Git%20clones&query=$&url=https://cdn.jsdelivr.net/gh/umarurize/U_DynamicLight@master/clone_count.txt&color=brightgreen)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/umarurize/U_DynamicLight/total)

### 🔔Introductions
* **30+ glowing items support**
* **Offhand mode support**
* **Localized languages support**
* **No damage to data**: Since dynamic light implemented through network packets delivery, it will not do any damage to your Bedrock level.

### 🔨Installation
<details>
<summary>Check your Endstone's version</summary>
    
- [x] U-DynamicLight [<250619] adapts Endstone 0.7.2 - 0.8.2
- [x] U-DynamicLight [>=250619] adapts Endstone 0.9.0+

</details>

Put `.whl` file into the endstone plugins folder, and then start the server. 

Enter the command `/offhand` to switch glowing items which are allowed by the server to offhand. 

If a player both has glowing items in mainhand and offhand, the light emission level with be set to the greater of the two.

### 💻Download
Now, you can get the release version form this repo or <code><a href="https://www.minebbs.com/resources/u-dynamiclight.11035/"><img height="20" src="https://github.com/umarurize/umaru-cdn/blob/main/images/minebbs.png" alt="Minebbs" /></a>&nbsp;Minebbs</code>.

### 📁File structure
```
Plugins/
├─ u-dynamic-light/
│  ├─ config.json
│  ├─ lang/
│  │  ├─ zh_CN.json
│  │  ├─ en_US.json
```

### 📝Configurations
`config.json`
```json5
{
    "item_allow_offhand": [
        "minecraft:torch",
        "minecraft:soul_torch"
    ],  // items are allowed to be switched to offhand
    "refresh_tick": 20 // light refresh interval in ticks
}
```
Server owner can edit and save `config.json`，and enter the command `/ud` to reload configurations/

### 🌐Languages
- [x] `zh_CN`
- [x] `en_US`

Off course you can add your mother language to U-DynamicLight, just creat `XX_XX.json` (such as `ja_JP.json`) and translate value with reference to `en_US.json`.

You can also creat a PR to this repo to make your mother language one of the official languages of U-DynamicLight.

### 💥Glowing items
<div style="width: 100%; text-align: center;">
  <img src="https://github.com/umarurize/U_DynamicLight/blob/master/images/item_list.png" style="max-width: 100%; height: auto;">
</div>

### :heart_eyes:Specially thanks
- [x] [@zimuya4153](https://github.com/zimuya4153)
- [x] [@KobeBryant114514](https://github.com/KobeBryant114514)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=GlacieTeam&repo=BinaryStream-Python)](https://github.com/GlacieTeam/BinaryStream-Python)

![](https://img.shields.io/badge/language-python-blue.svg) [![GitHub License](https://img.shields.io/github/license/umarurize/UTP)](LICENSE)

