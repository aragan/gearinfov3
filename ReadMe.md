# ** I am no longer supporting this addon **
Gearinvov3
Aragan version



![Gi logo](https://i.imgur.com/g0iJMJk.jpg# )

This is a multi-purpose addon that tracks your currently equipped gear and buffs to display valuable information.

![Imgur](https://i.imgur.com/L27g5JD.png)  
The addon can be used in conjunction with Gearswap to facilitate gear swapping.

Please check out the [the wiki](https://github.com/sebyg666/GearInfo/wiki) for all the information you'll need to get you started.

usage:

 //gi r | reload                     - Reload addon
 //gi help                           - Show help menu
 //gi parse                          - Reload inventory to file (after rank change)
 //gi parse back                     - Parse GearSwap back augments (save only)
 //gi parse back apply               - Parse GearSwap back augments (apply now)
 //gi parse escha                    - Parse Escha/Reisen augments (save only)
 //gi parse escha apply              - Parse Escha/Reisen augments (apply now)
 //gi parse all                     - Parse back+escha augments (save only)
 //gi parse all apply                - Parse back+escha augments (apply now)
 //gi rank                           - Show current unity rank
//gi rank #                         - Set unity rank
//gi theme Aragan                   - Set theme
//gi theme 1..30                    - Set theme (numeric templates; 1..6 map to custom1..custom6)
//gi theme reset                    - Reset theme to default
//gi autoparse on | off             - Auto parse GearSwap augments on load
//gi safe [on|off]                  - Safe mode: block GearSwap augment parsing

Command shortcuts:
//gi show | //gi so | //gi s ...    - Show command (note: //gi s wstp|job stays Save for compatibility)
//gi save | //gi sa                 - Save command
//gi add | //gi a                   - Add command
//gi remove | //gi rm               - Remove command
//gi hide | //gi hi | //gi hd       - Hide command
//gi job | //gi j                   - Job command
//gi mode | //gi m                  - Mode command
//gi parse | //gi p                 - Parse command
//gi reload | //gi re               - Reload command
//gi help | //gi he                 - Help command
//gi ... extra | ... e | ... ex     - `extra` shortcut in show/save/job/add/remove/hide contexts
//gi ... mode | ... m | ... mo      - `mode` shortcut in show/save/job/add/remove/hide contexts
<!-- Displays only augmented gear details when using the GearInfo addon's "/gi show augonly" command. -->
 /gi show augonly
 //gi gsdir <path>                   - Set GearSwap data folder for parsing
 //gi back                           - Parse GearSwap back augments (apply now)
 //gi escha                          - Parse Escha/Reisen augments (save only)
 //gi escha apply                    - Parse Escha/Reisen augments (apply now)

 //gi stp #                          - Manual Store TP adjust
 //gi dw #                           - Manual Dual Wield adjust
 //gi ghaste #                       - Manual gear haste adjust
 //gi  mhaste #                       - Manual magic haste adjust
 //gi jahaste #                      - Manual JA haste adjust
//gi dwn #                          - Manual DW needed adjust
//gi show main                      - Toggle main boxes (Haste/DT/TP/Acc/Att/Eva/Def/STP)
//gi show block 1..13               - Toggle main blocks by layout order
 //gi save wstp                      - Save current TP/hit line
//gi save job                       - Save visible boxes for current job (slot 1)
//gi save job [1-9]                 - Save visible boxes for current job slot
//gi save job extra [1-9]           - Save visible boxes for current job extra slot
//gi save job mode healer|magic attack|tank|pet|dd|test [1-9] - Save visible boxes for current job mode slot
//gi job [1-9]                      - Load saved boxes for current job slot
//gi show job extra [1-9] [only]    - Load saved boxes for current job extra slot (no number = job preset)
//gi job mode healer|magic attack|tank|pet|dd|test [1-9] [only] - Load saved boxes for current job mode slot
//gi job [1-9] [only]               - Load saved boxes for current job slot
//gi mode 1..8 [only]               - Set display mode; repeat to restore
//gi mode calc                      - Auto-show only boxes with value > 0 (open calc mode)
//gi mode <1..8> calc              - Calc mode + set display layout mode (1=4,2=8,3=12,4=6,5=3,6=2,7=1,8=16)
 //gi reset job                      - Reset to default boxes for current job
 //gi delete wstp                    - Delete saved TP/hit line

 //gi update                         - Force one GearSwap update
 //gi updategs | ugs                 - Toggle send info to GearSwap
 //gi updategs true | false          - Force updategs on/off
 //gi debug                          - Toggle debug mode
 //gi dnc                            - Toggle Haste Samba (main DNC)

 //gi brd #                          - Set March bonus
 //gi brd add name bonus             - Save a BRD
 //gi brd delete name                - Delete a BRD
 //gi cor #                          - Set Phantom Roll bonus
 //gi cor add name bonus             - Save a COR
 //gi cor delete name                - Delete a COR
 //gi geo #                          - Set Geomancy bonus
 //gi geo add name bonus             - Save a GEO
 //gi geo delete name                - Delete a GEO

 //gi hide                           - Hide all display
//gi show all                       - Show all display
//gi show reset                     - Reset all display boxes to defaults
 //gi show logo                      - Toggle logo
 //gi show haste                     - Toggle haste block
 //gi show tp                        - Toggle TP calculator
 //gi show acc                       - Toggle accuracy block
 //gi show eva                       - Toggle evasion block
 //gi show def                       - Toggle defense block
 //gi show att                       - Toggle attack block
 //gi show dt                        - Toggle DT block
 //gi show stp (STP/DTA)             - Toggle STP/DTA block
 //gi show dw                        - Toggle DW block
 //gi show ma                        - Toggle MA block
 //gi show cor                       - Toggle rollTracker chat
 //gi show da | ta | qa              - Toggle DA/TA/QA blocks
 //gi show scb                       - Toggle SCB
 //gi show scd                       - Toggle SCD
 //gi show mab                       - Toggle MAB
 //gi show mbd                       - Toggle MBD
 //gi show mbd2                      - Toggle MBD II
 //gi show pdl                       - Toggle PDL
 //gi show sird                      - Toggle SIRD
 //gi show int                       - Toggle INT
 //gi show macc                      - Toggle M.Acc
 //gi show regen                     - Toggle Regen
 //gi show regain                    - Toggle Regain
 //gi show refresh                   - Toggle Refresh
 //gi show parry                     - Toggle Parry
 //gi show enmity                    - Toggle Enmity
 //gi show critrate                  - Toggle Crit Rate
 //gi show critdmg                   - Toggle Crit Dmg
 //gi show sb                        - Toggle Subtle Blow
 //gi show sb2                       - Toggle Subtle Blow II
 //gi show mdmg                      - Toggle Magic Damage
 //gi show mdef                      - Toggle Magic Def. Bonus
 //gi show meva                      - Toggle Magic Evasion
 //gi show counter                   - Toggle Counter
 //gi show cmp                       - Toggle Conserve MP
//gi show extra                     - Toggle extra stats group (MAB/MBD/MBD2/INT/MAcc/M.Dmg + PDL/SCB/SCD + Crit/SB + Regen/Refresh/Parry/Enmity/M.Def/M.Eva/SIRD + Regain/Counter/C.MP)
//gi show extra2 + TH/FC/CP/CP2/ECHR/Waltz/BR/Zanshin/TPB/Killer/Samba/HMS/Cursna) - Toggle extra2 group

Values shown (main boxes):
G-Haste, M-Haste, JA-Haste, Total Haste, DT/PDT, MDT/BDT, TP/swing, X-hit, Accuracy, Attack, Evasion, Defense,
STP/DTA, DA, TA, QA, SCB/SCD, PDL, CRIT/CRTD, SB/SB2, MA (Multi-attack), Needed (DW/Needed), and any enabled extras.
//gi show extra3                    - Toggle PDL + SCB/SCD + Phalanx/QC/CST/HMCT/SS/RS/EMCT/INQ/EMED/Steal/SA/TA/Songs/SED/SST
//gi show extra33                   - Toggle PDL + SCB/SCD
//gi show extra4                    - Toggle Crit Rate/Dmg + SB/SB2 + Pet/BP stats
//gi show extra34                   - Toggle Crit Rate/Dmg + SB/SB2
//gi show extra5                    - Toggle Regen/Refresh/Parry/Enmity/M.Def/M.Eva/SIRD
//gi show extra6                    - Toggle Regain/Counter/Conserve MP
 //gi show extra7                    - Toggle stats boxes (STR/DEX/VIT/AGI/INT/MND/CHR)
 //gi show stats | stat | vitals     - Toggle stats boxes (same as extra7)
 //gi show extra8                    - Toggle Treasure Hunter
 //gi show th                        - Toggle Treasure Hunter (same as extra8)
 //gi show extra9                    - Toggle Fast Cast
 //gi show fc                        - Toggle Fast Cast (same as extra9)
 //gi show extra10                   - Toggle Cure Potency + Cure Potency II
 //gi show cp                        - Toggle Cure Potency
 //gi show cp2                       - Toggle Cure Potency II
 //gi show extra11                   - Toggle Enemy Critical Hit Rate
 //gi show echr                      - Toggle Enemy Critical Hit Rate (same as extra11)
 //gi show extra12                   - Toggle Waltz
 //gi show waltz                     - Toggle Waltz (same as extra12)
 //gi show extra13                   - Toggle Block Rate
 //gi show br                        - Toggle Block Rate (same as extra13)
 //gi show extra14                   - Toggle Zanshin
 //gi show zanshin                   - Toggle Zanshin (same as extra14)
 //gi show extra15                   - Toggle TP Bonus
 //gi show tpbonus | tpb             - Toggle TP Bonus (same as extra15)
 //gi show extra16                   - Toggle Killer
 //gi show killer                    - Toggle Killer (same as extra16)
//gi show extra17                   - Toggle Samba
//gi show samba                     - Toggle Samba (same as extra17)
//gi show extra18                   - Toggle Healing Magic Skill
//gi show hms                       - Toggle Healing Magic Skill (same as extra18)
//gi show extra19                   - Toggle Phalanx
//gi show phalanx                   - Toggle Phalanx (same as extra19)
//gi show extra20                   - Toggle casting-time stats (Quick Cast/CST/HMCT)
//gi show qc                        - Toggle Quick Cast
//gi show cst                       - Toggle Cure spellcasting time
//gi show hmct                      - Toggle Healing magic casting time
//gi show extra21                   - Toggle Snapshot/Rapid Shot
//gi show snapshot                  - Toggle Snapshot (same as extra21)
//gi show ss                        - Toggle Snapshot (same as extra21)
//gi show rapidshot                 - Toggle Rapid Shot (same as extra21)
//gi show rs                        - Toggle Rapid Shot (same as extra21)
//gi show extra22                   - Toggle Elemental magic casting time
//gi show emct                      - Toggle Elemental magic casting time (same as extra22)
//gi show extra23                   - Toggle Inquartata
//gi show inq                       - Toggle Inquartata (same as extra23)
//gi show extra24                   - Toggle Enhancing magic effect duration
//gi show enh                       - Toggle Enhancing magic effect duration (same as extra24)
//gi show emed                      - Toggle Enhancing magic effect duration (same as extra24)
//gi show extra25                   - Toggle Steal/Sneak Attack/Trick Attack
//gi show steal                     - Toggle Steal (same as extra25)
//gi show sa                        - Toggle Sneak Attack (same as extra25)
//gi show ta                        - Toggle Trick Attack (same as extra25)
//gi show extra26                   - Toggle song stats (All songs/SED/SST)
//gi show all songs                 - Toggle All songs (same as extra26)
//gi show songs                     - Toggle All songs (same as extra26)
//gi show allsongs                  - Toggle All songs (same as extra26)
//gi show allsong                   - Toggle All songs (same as extra26)
//gi show sed                       - Toggle Song effect duration (same as extra26)
//gi show sst                       - Toggle Song spellcasting time (same as extra26)
//gi show extra27                   - Toggle pet/indicolure stats
//gi show pr|pet regen|pet r         - Toggle Pet: Regen (same as extra27)
//gi show pet dt                    - Toggle Pet: Damage taken (same as extra27)
//gi show petdt                     - Toggle Pet: Damage taken (same as extra27)
//gi show ied                       - Toggle Indicolure effect duration (same as extra27)
//gi show extra28                   - Toggle Blood Pact/Pet stats
//gi show bpd                       - Toggle Blood Pact Delay (same as extra28)
//gi show bpd2                      - Toggle Blood Pact Delay II (same as extra28)
//gi show bpdmg                     - Toggle Blood Pact Damage (same as extra28)
//gi show apc                       - Toggle Avatar Perpetuation Cost (same as extra28)
//gi show pmab                      - Toggle Pet: Magic Atk. Bonus (same as extra28)
//gi show patt                      - Toggle Pet: Attack (same as extra28)
//gi show pda                       - Toggle Pet: Double Attack (same as extra28)
//gi show pacc                      - Toggle Pet: Accuracy (same as extra28)
//gi show pmacc                     - Toggle Pet: Magic Accuracy (same as extra28)
//gi show sms                       - Toggle Summoning Magic skill (same as extra28)
//gi show pbpd                      - Toggle Pet: Blood Pact Damage (same as extra28)
//gi show pmdmg                     - Toggle Pet: Magic Damage (same as extra28)
//gi show extra29                   - Toggle Pet PDT/MDT
//gi show pet pdt                   - Toggle Pet: Physical Damage Taken (same as extra29)
//gi show pet mdt                   - Toggle Pet: Magic Damage Taken (same as extra29)
//gi show extra30                   - Toggle Pet: Haste
//gi show pet h                     - Toggle Pet: Haste (same as extra30)
//gi show pethast                   - Toggle Pet: Haste (same as extra30)
//gi show extra31                   - Toggle Cursna
//gi show cursna                    - Toggle Cursna (same as extra31)
//gi show extra all                 - Toggle all extra groups
//gi show extraall                  - Toggle all extra groups
//gi pdtmode                        - Toggle DT added into PDT only
//gi pdtsource                      - Print PDT sources (gear + set bonus) and totals
//gi pdtcheck [equipped|all]        - Scan suspicious PDT cache values
//gi check                          - Print computed non-zero stats for each equipped item
//gi style [box|flat [1-40]]        - Display style (boxed or flat text themes)
//gi size 1..9                      - Display size (5 = default)
//gi label 1..9                     - Label text size (5 = default)
//gi value 1..9                     - Value text size (5 = default)
//gi bg 0..9                        - Flat background alpha (0 = transparent)
//gi bg a..h                        - Background image (images/<letter>.png)
//gi bg reset                       - Reset background to default
//gi font <name>|a..k               - Label font name or preset (a..k)
//gi font reset                     - Reset label font to default
//gi numfont <name>|a..k            - Value font name or preset (a..k)
//gi numfont reset                  - Reset value font to default
//gi style reset                    - Reset style to default
//gi test                           - Toggle test mode (mode 8, show all boxes, center display)
//gi test job                       - Toggle test job mode (mode 8, job boxes only, center display)
//gi test haste [g|m|j|a] <value%|value|cap> - Set test haste override (test mode only)
//gi test haste cap all             - Set all test haste to cap (test mode only)
//gi style|size|label|value|bg|font|numfont|mode reset - Reset display settings to defaults
//gi mode 1..8                      - Display layout mode (1=4,2=8,3=12,4=6,5=3,6=2,7=1,8=16 blocks per row)
//gi mode calc                      - Auto-show only boxes whose current value is > 0
//gi mode <1..8> calc              - Auto-show only >0 boxes and set layout mode (1=4,2=8,3=12,4=6,5=3,6=2,7=1,8=16)
//gi pdtdebug                       - Print DT/PDT/MDT/BDT source

abbreviations:
 da     = Double Attack  
 ta     = Triple Attack  
 qa     = Quadruple Attack  
 dta    = DA+TA+QA total  
 scb    = Skillchain Bonus  
 scd    = Skillchain Damage  
 mab    = Magic Attack Bonus  
 mbd    = Magic Burst Damage  
 mbd2   = Magic Burst Damage II  
 pdl    = Physical Damage Limit  
 sird   = Spell Interruption Rate Down  
 macc   = Magic Accuracy  
 int    = INT  
 mdmg   = Magic Damage  
 mdef   = Magic Defense Bonus  
 meva   = Magic Evasion  
 stp    = Store TP  
 dw     = Dual Wield  
 ma     = Multi-Attack  
 dt     = Damage Taken  
 eva    = Evasion  
 def    = Defense  
 acc    = Accuracy  
 att    = Attack  
 tp     = TP Calculator  
 cmp    = Conserve MP  
 sb     = Subtle Blow  
 sb2    = Subtle Blow II  
 critrate = Critical Hit Rate  
 critdmg  = Critical Hit Damage  
 th     = Treasure Hunter  
 fc     = Fast Cast  
 cp     = Cure Potency  
 cp2    = Cure Potency II  
 echr   = Enemy Critical Hit Rate  
 waltz  = Waltz  
 br     = Block Rate  
 zanshin = Zanshin  
 tpb    = TP Bonus  
 killer = Killer  
 samba  = Samba  
 hms    = Healing Magic Skill  
 phalanx = Phalanx  
 qc     = Quick Cast  
 snap/rsht = Snapshot / Rapid Shot  
 p.reg/p,dt = Pet Regen / Pet DT  
 peth   = Pet Haste  
 cst    = Cure Spellcasting Time  
 hmct   = Healing Magic Casting Time  
 ss     = Snapshot  
 rs     = Rapid Shot  
 emct   = Elemental Magic Casting Time  
 inq    = Inquartata  
 enh    = Enh. Mag. Effect Duration  
 emed   = Enh. Mag. Effect Duration  
 steal  = Steal  
 sa     = Sneak Attack  
 ta2    = Trick Attack  
 songs  = All Songs  
 sed    = Song Effect Duration  
 sst    = Song Spellcasting Time  
 pr     = Pet: Regen  
 petdt  = Pet: Damage Taken  
 ied    = Indicolure Effect Duration  
 bpd    = Blood Pact Delay  
 bpd2   = Blood Pact Delay II  
 bpdmg  = Blood Pact Damage  
 apc    = Avatar Perpetuation Cost  
 petpdt = Pet: Physical Damage Taken  
 petmdt = Pet: Magic Damage Taken  
 peth   = Pet: Haste  
 pmab   = Pet: Magic Atk. Bonus  
 patt   = Pet: Attack  
 pda    = Pet: Double Attack  
 pacc   = Pet: Accuracy  
 pmacc  = Pet: Magic Accuracy  
 sms    = Summoning Magic Skill  
 pbpd   = Pet: Blood Pact Damage  
 pmdmg  = Pet: Magic Damage  
 cursna = Cursna
