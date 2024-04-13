A sheet documenting all available medical items in BHS and BHSRO to map out identifiers, names, primary effects, icon design, and assigned item use animation. Used as reference for consistency and to determine gaps in player needs against what items provide. This document applies to an assumed mod pack combination of Anomaly x GAMMA x Body Health System (BHS) x Body Health System Realistic Overhaul (BHSRO).

## Items

A listing of all items as they are added by the pack combination.

### Analgesics

Items that are primarily painkillers and damage resistance boosters. These may be used to triage damaged body parts as a temporary relief and taken voluntarily before combat encounters to increase survival chances.

> Todo: Too many painkillers, middle part can be repurposed.

| Name            | Identifier       | Cost | boost_strike_immunity, boost_wound_immunity, bhs_painkillerlist |
| --------------- | ---------------- | ---- | --------------------------------------------------------------- |
| Paracetamol     | `analgin`        | 2500 | 0, 0, 2                                                         |
| Ibuprofen       | `akvatab`        | 2500 | 0, 0, 4                                                         |
| Hydrocodone     | `tetanus`        | 1940 | 0, 0, 4                                                         |
| Yadylin         | `yadylin`        | 985  | 0, 0, 5                                                         |
| Diclofenac      | `analgetic`      | 1100 | 0.05, 0.05, 5                                                   |
| Metamizole Shot | `salicidic_acid` | 1600 | 0.075, 0.075, 6                                                 |
| Morphine Shot   | `morphine`       | 2000 | 0.1, 0.1, 7                                                     |

### First Aid

Items that are taken after sustaining damage, to heal main player health and to triage damaged body parts. Some may also restore radiation exposure as a side effect (e.g. expeditionary items).

| Name                   | Identifier        | Cost  | boost_health_restore, bhs_healonelist |
| ---------------------- | ----------------- | ----- | ------------------------------------- |
| Fluorapine Shot        | `propital`        | 4000  | 0.0015, 21                            |
| Axyltallisal           | `rebirth`         | 12000 | 0.0188, 60                            |
| First Aid Kit          | `medkit`          | 2500  | 0.0015, 21                            |
| Military Medkit        | `medkit_army`     | 4500  | 0.0025, 32                            |
| Expeditionary Medkit   | `medkit_scientic` | 6500  | 0.0025, 32                            |
| Stimpack               | `stimpack`        | 3000  | 0.007, 21                             |
| Military Stimpack      | `stimpack`        | 5000  | 0.01, 32                              |
| Expeditionary Stimpack | `stimpack`        | 6000  | 0.01, 32                              |
| Survival Kit           | `survival_kit`    | 7500  | 0.0015, 60                            |

### Bleeding & Body

Items that primarily prevent or reduce bleeding and are used to triage or fully treat head, torso, arms, and legs.

| Name                 | Identifier       | Cost | boost_bleeding_restore, bhs_* |
| -------------------- | ---------------- | ---- | ----------------------------- |
| Bandage              | `bandage`        | 1000 | 0.016, none                   |
| Vinca                | `drug_coagulant` | 5000 | 0.00042, 11 (healone)         |
| Tourniquet           | `jgut`           | 1750 | 0.04, none                    |
| Synthetic Splint     | `splint`         | 600  | 0, 1 (splint)                 |
| SAM Splint           | `alu_splint`     | 1500 | 0, 1 (splint)                 |
| Surgical Field Kit   | `cms`            | 8000 | 0, 1 (surgery)                |
| Surgical Instruments | `surginst`       | 800  | 0, 1 (surgery)                |

### Stimulants

Items that are taken before or during combat for primarily increased carry weight, painkilling, damage resistance, and stamina-enhancing effects. Some items may also boost other resistances or provide minor health restoration.

| Name                        | Identifier     | Cost | boost_power_restore, boost_max_weight, boost_strike_immunity |
| --------------------------- | -------------- | ---- | ------------------------------------------------------------ |
| Caffeine Tablets            | `caffeine`     | 2550 | 0.0008, 2.653, 0                                             |
| Hercules                    | `drug_booster` | 1750 | 0.0028, 6.123, 0                                             |
| Cocaine                     | `cocaine`      | 3500 | 0.00442, 12.645, 0                                           |
| Epinephrine Shot            | `adrenalin`    | 6520 | 0.00629, 22.294, 0                                           |
| SJ-I Combat Stimulant Shot  | `etg`          | 4500 | 0.00642, 25, 0                                               |
| SJ-V Combat Stimulant Shot  | `sj1`          | 4000 | 0.00442, 20, 0.15                                            |
| SJ-IX Combat Stimulant Shot | `sj6`          | 5500 | 0.00842, 30, 0.2                                             |

### Radiation

Items that primarily give radiation resistance or remove radiation exposure.

| Name                 | Identifier            | Cost | boost_radiation_protection, boost_radiation_restore |
| -------------------- | --------------------- | ---- | --------------------------------------------------- |
| Chlortetracycline    | `antibio_chlor`       | 521  | 0.00035, 0                                          |
| Sulfadimethoxine     | `antibio_sulfad`      | 933  | 0.0005, 0                                           |
| Radioprotectant      | `drug_radioprotector` | 1250 | 0.001, 0                                            |
| Cystamine            | `antirad_cystamine`   | 1950 | 0.0018, 0                                           |
| Potassium Iodide     | `antirad_kalium`      | 2340 | 0, 0.0012                                           |
| Anti-Radiation Drugs | `antirad`             | 2700 | 0, 0.008                                            |

### Toxicity

Items that primarily give resistance to toxic anomalies (acid). Toxicity damage is directly applied as health damage, so no restoration property exists.

| Name              | Identifier       | Cost | boost_chemburn_protection |
| ----------------- | ---------------- | ---- | ------------------------- |
| Antidote          | `drug_antidot`   | 3360 | 0.0038                    |
| Chlortetracycline | `antibio_chlor`  | 521  | 0.009                     |
| Sulfadimethoxine  | `antibio_sulfad` | 933  | 0.0025                    |

### Electric Shock

There are no items that give resistance to electric shock damage.

### Psy

Items that give resistance to psychic damage (e.g. psy fields, psy anomalies, psy-based creatures like poltergheists and controllers). Some of these medications may be referred to as antipsychotics in the overhaul; *Psy Block* may become *Clozapine*.

| Name           | Identifier           | Cost | boost_telepat_protection |
| -------------- | -------------------- | ---- | ------------------------ |
| Cannabis Joint | `joint`              | 380  | 0.02                     |
| Marijuana      | `marijuana`          | 1040 | 0.03                     |
| Etperazine     | `antiemetic`         | 678  | 0.041                    |
| Psy Block      | `drug_psy_blockade`  | 4450 | 0.075                    |
| Diazepam       | `drug_sleepingpills` | 4200 | 0.025                    |

### Miscellaneous

…