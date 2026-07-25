# 🌟 Minecraft Bedrock Glow Loot Pack

A global resource pack for Minecraft Bedrock that makes all dropped items glow, making them visible through walls. Perfect for Realms servers!

## ✨ Features

✅ **Glowing Items** - All dropped items emit a glowing effect
✅ **See Through Walls** - Items are visible through terrain obstacles
✅ **Realm Compatible** - Works on private Realms without cheats or operator commands
✅ **No Creative Mode Required** - Works in Survival mode
✅ **Simple Installation** - Just add to your resource packs

## 📥 Installation

### For Realms:
1. Download this resource pack
2. Extract the folder
3. Copy the `minecraft-bedrock-glow-loot` folder to:
   - **Windows 10/11**: `%LOCALAPPDATA%\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\resource_packs`
   - **Xbox**: Upload through the Realms menu
   - **Mobile/Switch**: Through the Marketplace or by adding to world settings
4. Open your Realm and enable the pack in World Settings > Resource Packs

### For Single Player:
1. Extract the folder
2. Place in your resource packs folder (same location as above)
3. Create or open a world and enable the pack

## 🎮 How It Works

- **Glow Effect**: Uses Bedrock's native glowing effect on item entities
- **Through Walls**: The glow effect naturally penetrates solid blocks
- **No Cheats Needed**: Works entirely through resource pack materials and textures
- **Automatic**: All dropped items automatically glow once enabled

## 📝 Notes

- **Proximity Sounds**: The ticking sound is a fixed frequency in this version (dynamic proximity detection requires commands/mods)
- **Performance**: Minimal impact - uses only native Bedrock rendering
- **Multiplayer**: All players must have the pack installed to see the glow effect

## 🔧 Technical Details

- Format Version: 2.0
- Requires: Minecraft Bedrock 1.18+
- Compatibility: Windows, Xbox, Mobile, Switch
- Size: Lightweight (~50KB)

## 📦 Pack Structure

```
minecraft-bedrock-glow-loot/
├── manifest.json
├── pack_icon.png
├── textures/
│   └── item_texture.json
├── materials/
│   └── entity.material
├── particles/
│   └── loot_proximity.json
├── sounds/
│   ├── sound_definitions.json
│   └── [sound files]
├── models/
│   └── entity/
│       └── item.json
└── README.md
```

## ⚙️ Troubleshooting

**Items not glowing?**
- Ensure the resource pack is enabled in World Settings
- Check that all players have the pack installed
- Restart the Realm or world

**Performance issues?**
- This pack is optimized for performance
- If lag occurs, check your render distance setting

## 📜 License

Free to use and modify for personal use.

---

**Version**: 1.0.0 | **Last Updated**: 2026
