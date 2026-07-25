# 🌟 Minecraft Bedrock Glow Loot Pack

A complete resource pack for Minecraft Bedrock that makes all dropped items glow and emit proximity-based ticking sounds!

## ✨ Features

✅ **Glowing Items** - All dropped items emit a bright glow effect
✅ **See Through Walls** - Items are visible through terrain obstacles
✅ **Proximity Sounds** - Ticking sounds that increase in speed as you get closer
✅ **Realm Compatible** - Works on private Realms without cheats
✅ **No Operator Commands** - Requires no special permissions
✅ **Survival Mode** - Works perfectly in Survival mode
✅ **Simple Installation** - Just extract and enable

## 🎵 Proximity Sound System

- **Far (30+ blocks)**: Slow tick (0.5 seconds apart)
- **Medium (15-30 blocks)**: Medium tick (0.3 seconds apart)
- **Close (5-15 blocks)**: Fast tick (0.15 seconds apart)
- **Very Close (<5 blocks)**: Rapid tick (0.08 seconds apart)

## 📥 Installation Guide

### Step 1: Download
Download the `glow-loot-pack` folder from this repository.

### Step 2: Extract
Extract the folder to a known location on your computer.

### Step 3: Add to Minecraft
Copy the `glow-loot-pack` folder to:

**Windows 10/11:**
```
%LOCALAPPDATA%\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\resource_packs
```

**How to access:**
1. Press `Win + R`
2. Paste the path above
3. Paste the `glow-loot-pack` folder here

### Step 4: Enable in Realm
1. Open your Realm
2. Go to **World Settings**
3. Select **Resource Packs**
4. Find **Glow Loot Pack**
5. Toggle it **ON**
6. Click **Activate** and confirm

## 🎮 How to Use

1. Enable the resource pack in your Realm
2. Drop any items on the ground
3. Items will automatically glow with a golden/yellow hue
4. You'll hear ticking sounds that increase in speed as you approach items
5. Items are visible through walls, caves, and obstacles

## ⚙️ Technical Details

- **Format Version**: 2.0
- **Minimum Version**: Minecraft Bedrock 1.18+
- **Compatibility**: Windows 10/11, Xbox, Mobile (iOS/Android), Nintendo Switch
- **File Size**: ~150KB
- **No Dependencies**: Works standalone without behavior packs

## 📋 Pack Contents

```
glow-loot-pack/
├── manifest.json              (Pack identification)
├── pack_icon.png              (Pack icon)
├── README.md                  (This file)
├── textures/
│   └── item_texture.json      (Item texture definitions)
├── materials/
│   └── entity.material        (Glow material settings)
├── particles/
│   └── loot_proximity.json    (Glow particle effects)
├── models/
│   └── entity/
│       └── item.json          (Item model with glow)
└── sounds/
    ├── sound_definitions.json (Sound configurations)
    ├── loot_tick_far.ogg      (Far distance sound)
    ├── loot_tick_medium.ogg   (Medium distance sound)
    ├── loot_tick_close.ogg    (Close distance sound)
    └── loot_tick_very_close.ogg (Very close distance sound)
```

## 🆘 Troubleshooting

### Items not glowing?
- Ensure the resource pack is enabled in World Settings
- Restart your game or Realm
- Check that you're in the same world as the pack is enabled

### Not hearing ticking sounds?
- Check your volume settings in Minecraft
- Ensure "Master Volume" is not muted
- Verify the pack is enabled

### Performance issues?
- This pack is highly optimized and lightweight
- If lag occurs, try reducing render distance
- Disable other resource packs temporarily

### Only works for me, not other players?
- All players on the Realm must download and enable the pack
- Each player needs to activate it in their World Settings
- Glow effects are visible to all who have the pack enabled

## 🔧 Customization

To modify glow colors or adjust proximity distances, edit:
- `models/entity/item.json` - For glow brightness
- `sounds/sound_definitions.json` - For sound volumes

## 📝 Notes

- This pack modifies client-side rendering only
- No cheats or commands are needed
- Compatible with all game modes
- Works on Realms and local worlds
- Safe for Survival mode without breaking any rules

## 🎁 Credits

Created for Minecraft Bedrock Edition 1.18+

**Version**: 1.0.0
**Last Updated**: 2026

---

**Enjoy finding your loot with enhanced visibility! 🌟**
