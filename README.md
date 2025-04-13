# LiveSplit Auto Splitter: Anno 1602 (History Edition)

This Auto Splitter is made for **Anno 1602 - History Edition** and works for most of the single missions.

## 🛠 Features

- ✅ Auto start when the mission starts (startFlag changes from 7 → 0)
- ✅ Auto split when the mission ends (stopFlag changes from 12 → 9)
- 🧪 Designed for mission-based speedruns which end with the ??? indicator

## 🔧 Installation

1. Download Anno1602.asl
2. Place it in your LiveSplit folder under:
   

LiveSplit\Components\LiveSplit.AutoSplitters\Anno1602.asl


3. Open LiveSplit
4. Right-click → Edit Splits
5. Set Game Name to Anno1602
6. Click Activate (if visible), then go to Settings and enable Start and Split

## 💾 Memory Addresses Used

| Label      | Address   | Type | Description                    |
|------------|-----------|------|--------------------------------|
| startFlag  | 0x5C4ECC  | byte | Changes 7 → 0 at mission start |
| stopFlag   | 0x5F10E0  | int  | Changes 12 → 9 at mission end  |

## ✅ Confirmed Working With

- Anno 1602: History Edition (Ubisoft Connect)
- Windows 11
- LiveSplit 1.8.33
- Cheat Engine 7.5 (for address testing)

## 🙏 Credits

Created by **invuln3r4bl3**  
Assisted by **ChatGPT**