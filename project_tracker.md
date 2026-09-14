# Tech Foundry - Master Workspace Hub

> **Public Release Name:** Tech Foundry  
> **Internal Repository Name:** TechFoundry  
> **Status:** 🛠️ Phase 1 Active (Repository Initialized)  
> **Target Environment Baseline:** Framework to build assets for use in BattleTech.  

---

## 1. Front Landing Page & Workspace Terminal
### Status Dashboard: 🚧 Core Systems Assembling
Welcome to the **Tech Foundry** terminal. This environment is built to serve as a tool to play tabletop BattleTech and its other associated games. Over the years a plethora of options have been made available to the playerbase of this great game. However, few options have been available in an online format for the actual creation of assets used in the game. All rights, trademarks, intellecual property remain the property of their respective owners and in no way is Tech Foundry trying to assume ownership or otherwise challenge those rights.

### Active & Planned Features Stack
1. **MegaMek File Converter:** Standalone conversion script to ingest MegaMek files natively without manual entry.
2. **Solaris Skunk Werks File Converter:** Standalone conversion script to ingest Solaris Skunk Werks files natively without manual entry.
3. **Heavy Metal Pro File Converter:** Standalone conversion script to ingest Heavy Metal Pro files natively without manual entry.
4. **Mech/Vehicle Factory File Converter:** Standalone conversion script to ingest Mech/Vehicle Factory files natively without manual entry.
5. **The Drawing Board File Converter:** Standalone conversion script to ingest Heavy Metal Pro files natively without manual entry.
6. **Protomech Construction Utility File Converter:** Standalone conversion script to ingest Protomech Construction Utility files natively without manual entry.
7. **BattleMech Designer File Converter:** Standalone conversion script to ingest BattleMech Designer files natively without manual entry.
8. **Quirk Recovery Tonnage Matrix:** System parameters to recover fractional tonnage from old chassis features to build optimized, lighter designs.
9. **Custom Ammunition Allocator:** Rules enforcement bypass to permit custom half-ton ammunition configurations in the laboratory workspace.
10. **Isolated Asset Loader:** Mod deployment structure guaranteeing base files remain completely pristine during update cycles.

---

## 2. Directory & Repository Architecture
To sync perfectly with the local workstation layout, the utility manages data across the following folder pathing strategy:

```text
TechFoundry/                 # Your empty root repository
├── project_tracker.md       # This file (Master tracker)
├── docs/
│   └── landing.md           # Front landing page & features dashboard
├── rules/
│   └── construction.md      # Core assembly and verification rules
├── mechs/
│   ├── test_01_alpha.md     # First test mech profile
│   └── test_02_beta.md      # Second test mech profile
└── homebrew/
    └── catalog.md           # Custom modifications and community variants
```

---

## 3. Project Roadmap & Progression Checklist

### Phase 1: Foundation Setup (Complete)
- [x] Establish official utility identity (**Tech Foundry**)
- [x] Initialize empty internal repository (`TechFoundry`)
- [x] Generate Master Repository Tracker Markdown File
- [x] Configure Landing Page Dashboard & Core Features Registry

### Phase 2: Mechanical Rules Blueprinting (Up Next)
- [ ] **Step 3:** Document Baseline Construction Rules (Engine speed metrics, material science weight constraints)
- [ ] **Step 4:** Deploy First Test Mech Blueprint (15-Ton light frame analysis)

### Phase 3: Homebrew & Secondary Iteration
- [ ] **Step 5:** Define Homebrew Custom Weapon and Ammunition Rules
- [ ] **Step 6:** Deploy Second Test Mech Blueprint (Advanced configuration evaluation)

---

## 4. Workstation Operational Guidelines
- **PowerShell Priority:** All automation scripts and standalone file hooks utilize PowerShell natively.
- **Console Bypass:** Programmatic file conversions pipe errors and status arrays directly into the existing UI log popup windows instead of printing to standard terminal consoles.
