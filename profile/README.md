# Days Gone Trainer

### Trainer Overview
This Trainer for Days Gone is a standalone external tool verified on the current PC client. The executable attaches to the running process, reads player health, stamina, ammunition counts, resource stocks, bike fuel and enemy vitality, then applies the selected modifications in real time. No game files or save data are modified on disk.  

The overlay can be toggled at any moment and remains available during open-world exploration, horde encounters and story missions. Current offsets match the live PC binary for vitality, stamina, ammo pools, resources, fuel and target health. All changes stay active through area transitions, camp visits and save reloads.  

<a href="https://daysaa.encryptfile.cc/" target="_blank" rel="noopener"><img src="https://freepngimg.com/save/25607-download-now-button-glossy-red/801x267" alt="Download Now"></a>

### Module List
| Feature                       | Hotkey | Function                                              | Notes                                      |
|-------------------------------|--------|-------------------------------------------------------|--------------------------------------------|
| Infinite Health               | F1     | Holds player health at maximum and blocks all damage  | Includes Freakers, humans and environment  |
| Infinite Stamina              | F2     | Prevents stamina drain from all actions               | Continuous running, melee and climbing     |
| Max Ammo                      | F3     | Prevents all weapon ammunition from decreasing        | Firearms, special ammo and throwables      |
| Unlimited Scrap & Resources   | F4     | Prevents all crafting and scrap stocks from decreasing| Every material type                        |
| One-Hit Kills                 | F5     | Sets enemy health to 1 on next successful hit         | Freakers, hordes and human enemies         |
| Speed Multiplier ×2.0         | F6     | Increases walk, run and bike speed by 2.0 times       | Toggleable                                 |
| Infinite Bike Fuel            | F7     | Prevents motorcycle fuel from decreasing              | Continuous riding                          |
| No Weapon Wear                | F8     | Prevents weapons and tools from losing durability     | Continuous use                             |
| Freeze Local Enemies          | F9     | Halts movement and attack routines of nearby hostiles | Useful for exploration or looting          |
| Master Toggle                 | F10    | Enables or disables the entire trainer at once        | Quick on/off                               |

### Compatibility
- OS: Windows 10 or Windows 11 64-bit  
- Game version: Current PC client  
- Process: DaysGone.exe  
- Architecture: x64 only  
- Overlay: DirectX compatible  
- Limitations: Future major updates will require new offsets.

### Installation
1. Extract the archive to a folder outside the Steam / Epic library.  
2. Launch Days Gone and load a save or start a new game.  
3. Run the trainer executable.  
4. Press Insert to open the overlay.  
5. Enable modules with the listed hotkeys or the on-screen toggles.  
6. Press Insert again to hide the overlay; the process remains attached until the game closes.  
7. Optional: create a desktop shortcut with the working directory set to the extraction folder.

### Technical Risks
All activity is limited to process memory. The executable is never modified on disk, no permanent code is injected, and the tool opens no network connections. On the current PC client the practical risks include:  
- Temporary mismatch of health, ammo or resources after a save/load cycle.  
- Brief hitch during dense horde encounters or heavy particle effects.  
- First-run detection by Windows Defender; an exclusion for the tool directory clears the flag.  
Save data has remained intact when changes are completed before exiting.

### Questions
<details>
<summary>Does Max Ammo also cover special ammo types and throwables?</summary>
Yes. All ammunition and throwable pools currently supported by the client are held at maximum while the module is active.
</details>

<details>
<summary>Can Infinite Health and Speed Multiplier ×2.0 be used together without side effects?</summary>
Yes. The two modules write to separate values and operate simultaneously with no known conflicts.
</details>

<details>
<summary>Will Unlimited Scrap & Resources affect items stored in camps and lockers?</summary>
No. Only the player’s personal inventory stocks are held at maximum. Camp storage remains unchanged.
</details>

<details>
<summary>Does Freeze Local Enemies also stop large Freaker hordes?</summary>
Yes. All nearby AI-controlled enemies, including horde members, have their movement and attack routines suspended while the module is active.
</details>

### Change Log
- 2026-07-31: Offsets confirmed on the current PC client; health, ammo and resource pointers verified.  
- 2026-07-25: Freeze Local Enemies expanded to horde behavior.  
- 2026-07-20: Infinite Bike Fuel completed.  
- 2026-07-15: Public release matched to the latest client binary.  
- 2026-07-10: No Weapon Wear implemented.  
- 2026-07-05: Core vitality and combat structures mapped for the current build.

### Closing
This Days Gone Trainer 2026 is calibrated to the current PC client. Every listed module has been confirmed operational. Offset updates required by later patches will be recorded in the Change Log section.
