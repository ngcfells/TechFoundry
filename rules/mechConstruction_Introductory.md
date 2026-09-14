# Tech Foundry - Introductory Mech Construction Rules

> **System Layer:** Client-Side Browser Operations  
> **Status:** Draft under review  
> **Applicability:** Browser-Based Mech Chassis Validation & Legacy File Importers, eventually 

---

## 1. Browser Execution Framework
To ensure absolute workflow privacy, accessibility, and zero local environmental dependencies, all parsing, construction mapping, and mathematical validation rules must operate **strictly within the browser**.
- **Browser-Native Processing:** Execution logic, code parsing, and file conversions must run in-browser via client-side scripts, utilizing local web APIs instead of a local Command Line Interface (CLI) or installed on local machine apps.
- **Interface Error Handling:** Execution warnings, file errors, and processing logs are piped directly into client-side UI log popups and display panels.

---

## 2. BattleMech Allowed Tonnages and Associated Classes
BattleMechs have certain classes they are assigned to by weight.
  ### Light
  - 20 Tons
  - 25 Tons
  - 30 Tons
  - 35 Tons

  ### Medium
  - 40 Tons
  - 45 Tons
  - 50 Tons
  - 55 Tons

  ### Heavy
  - 60 Tons
  - 65 Tons
  - 70 Tons
  - 75 Tons

  ### Assault
  - 80 Tons
  - 85 Tons
  - 90 Tons
  - 95 Tons
  - 100 Tons

## 2. Engine & Mobility Speed Metrics
- **Base Engine Rating** The Engine rating needed for a particular chassis is dependent upon the weight of the chassis and walking speed desired. A **20 Ton** machine, like a _Locust_ desiring to walk at the canon rating of **8** means it needs and Engine rating of **160**
- **Core Velocity Ratio:** An Engine Walk profile rating of **5** automatically iterates and maps to an Engine Run profile rating of **8** via the client-side calculator.
- **Locomotive Type Support:** In Introductory Level rules, only bipeds are allowed.
-**Standard Engine Weights:**
  **| Rating | Weight in Tons |**
  |--------|----------------|
  |**10**|0.5|
  |**15**|0.5|
  |**20**|0.5|
  |**25**|0.5|
  |**30**|0.5|
  |**35**|0.5|
  |**40**|1.0|
  |**45**|1.0|
  |**50**|1.5|
  |**55**|1.5|
  |**60**|1.5|
  |**65**|2.0|
  |**70**|2.0|
  |**75**|2.0|
  |**80**|2.5|
  |**85**|2.5|
  |**90**|3.0|
  |**95**|3.0|
  |**100**|3.0|
  |**105**|3.5|
  |**110**|3.5|
  |**115**|4.0|
  |**120**|4.0|
  |**125**|4.0|
  |**130**|4.5|
  |**135**|4.5|
  |**140**|5.0|
  |**145**|5.0|
  |**150**|5.5|
  |**155**|5.5|
  |**160**|6.0|
  |**165**|6.0|
  |**170**|6.0|
  |**175**|7.0|
  |**180**|7.0|
  |**185**|7.5|
  |**190**|7.5|
  |**195**|8.0|
  |**200**|8.5|
  |**205**|8.5|
  |**210**|9.0|
  |**215**|9.5|
  |**220**|10.0|
  |**225**|10.0|
  |**230**|10.5|
  |**235**|11.0|
  |**240**|11.5|
  |**245**|12.0|
  |**250**|12.5|
  |**255**|13.0|
  |**260**|13.5|
  |**265**|14.0|
  |**270**|14.5|
  |**275**|15.5|
  |**280**|16.0|
  |**285**|16.5|
  |**290**|17.5|
  |**295**|18.0|
  |**300**|19.0|
  |**305**|19.5|
  |**310**|20.5|
  |**315**|21.5|
  |**320**|22.5|
  |**325**|23.5|
  |**330**|24.5|
  |**335**|25.5|
  |**340**|27.0|
  |**345**|38.5|
  |**350**|29.5|
  |**355**|31.5|
  |**360**|33.0|
  |**365**|34.5|
  |**370**|36.5|
  |**375**|38.5|
  |**380**|41.0|
  |**385**|43.5|
  |**390**|46.0|
  |**395**|49.0|
  |**400**|52.5|

---

## 3. Structural Material Science
- **Internal Structure** In the Introductory Level, only standard Internal Structure is allowed. To determine the weight of this, you take the tonnage of the Mech and divide by 10. So our _Locust_ weighing 20 tons has an internal structure weight of 2.0 tons.
  |Mech Tonnage|Structure Tonnage|Center Torso Boxes|Left/Right Torso Boxes|Arm Boxes|Leg Boxes|Max Armor Factor|
  |-----|-----|-----|-----|------|------|------|------|
  |20|2.0|6|5|3|4|69|
  |25|2.5|8|6|4|6|89|
  |30|3.0|10|7|5|7|105|
  |35|3.5|11|8|6|8|119|
  |40|4.0|12|10|6|10|137|
  |45|4.5|14|11|7|11|153|
  |50|5.0|16|12|8|12|169|
  |55|5.5|18|||||
  |60|6.0|20|||||
  |65|6.5|21|||||
  |70|7.0|22|||||
  |75|7.5|23|||||
  |80|8.0|25|||||
  |85|8.5|27|||||
  |90|9.0|29|||||
  |95|9.5|30|||||
  |100|10.0|31|||||
- **Cockpit** Only the Standard Cockpit is available in this level of play. It takes a flat 3.0 tons.
- **Gyroscopic Support** Gyroscopes are required equipment to keep the Mech upright. They weigh **Engine rating** / 100 round up to nearest 1/2 ton.
- **Jump Jets** Jump Jets, if equipped vary in weight by class.
  |Class|Mech Tonnage Range|Jump Jet Weight per Jump Movement Point|
  |-----|-----|-----|
  |Class I|20 - 55|0.5 ton|
  |Class II|60 - 85|1 ton|
  |Class III|90 - 100| 2 tons|

---

## 4. Custom Equipment Isolation Rules
To allow smooth homebrew injection into browser workspaces (like custom weapon mapping or half-ton ammo arrays):
- **Non-Destructive Overrides:** Homebrew equipment configurations must be held in isolated, sandboxed object structures. 
- **Validation Shielding:** Base code schemas are protected from hard alterations, ensuring browser sessions remain clean.
