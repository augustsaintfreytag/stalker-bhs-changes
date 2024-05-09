A sheet documenting all available medical items in BHS and BHSRO to map out identifiers, names, primary effects, icon design, and assigned item use animation. Used as reference for consistency and to determine gaps in player needs against what items provide. This document applies to an assumed mod pack combination of Anomaly x GAMMA x Body Health System (BHS) x Body Health System Realistic Overhaul (BHSRO).

## Items

A listing of all items as they are added by the pack combination.

### Analgesics

Items that are primarily painkillers and damage resistance boosters. These may be used to triage damaged body parts as a temporary relief and taken voluntarily before combat encounters to increase survival chances.

> Todo: Too many painkillers, middle part can be repurposed.

| Name            | Identifier       | Cost | boost_strike_immunity, boost_wound_immunity, bhs_painkillerlist |
| --------------- | ---------------- | ---- | --------------------------------------------------------------- |
| Ibuprofen       | `salicidic_acid` | 1680 | 0.02, 0.02, 2                                                   |
| Yadylin         | `yadylin`        | 1880 | 0.05, 0.05, 5                                                   |
| Diclofenac      | `analgetic`      | 2680 | 0.05, 0.05, 5                                                   |
| Oxycodone       | `tetanus`        | 3880 | 0.06, 0.06, 6                                                   |
| Metamizole Shot | `analgin`        | 4280 | 0.1, 0.1, 10                                                    |
| Morphine Shot   | `morphine`       | 5080 | 0.15, 0.15, 15                                                  |

### First Aid

Items that are taken after sustaining damage, to heal main player health and to triage damaged body parts. Some may also restore radiation exposure as a side effect (e.g. expeditionary items).

| Name                   | Identifier          | Cost  | boost_health_restore, bhs_healonelist |
| ---------------------- | ------------------- | ----- | ------------------------------------- |
| First Aid Kit          | `medkit`            | 1800  | 0.0015, 21                            |
| Military Medkit        | `medkit_army`       | 2800  | 0.0025, 32                            |
| Expeditionary Medkit   | `medkit_scientic`   | 4200  | 0.0025, 32                            |
| Stimpack               | `stimpack`          | 2200  | 0.007, 21                             |
| Military Stimpack      | `stimpack_army`     | 3200  | 0.01, 32                              |
| Expeditionary Stimpack | `stimpack_scientic` | 4600  | 0.01, 32                              |
| Fluorapine Shot        | `propital`          | 3580  | 0.0015, 21 (Purpose unknown)          |
| Survival Kit           | `survival_kit`      | 7200  | 0.0015, 60                            |
| Axyltallisal           | `rebirth`           | 12000 | 0.0188, 60                            |

### Bleeding & Body

Items that primarily prevent or reduce bleeding and are used to triage or fully treat head, torso, arms, and legs.

| Name                 | Identifier       | Cost | boost_bleeding_restore, bhs_* |
| -------------------- | ---------------- | ---- | ----------------------------- |
| Bandage              | `bandage`        | 600  | 0.016, none                   |
| Tourniquet           | `jgut`           | 1200 | 0.04, none                    |
| Vinca                | `drug_coagulant` | 2480 | 0.00042, 11 (healone)         |
| Synthetic Splint     | `splint`         | 800  | 0, 1 (splint)                 |
| SAM Splint           | `alu_splint`     | 1400 | 0, 1 (splint)                 |
| Surgical Field Kit   | `cms`            | 8000 | 0, 1 (surgery)                |
| Surgical Instruments | `surginst`       | 1180 | 0, 1 (surgery)                |

### Stimulants

Items that are taken before or during combat for primarily increased carry weight, painkilling, damage resistance, and stamina-enhancing effects. Some items may also boost other resistances or provide minor health restoration.

| Name                        | Identifier     | Cost | boost_power_restore, boost_max_weight, boost_strike_immunity |
| --------------------------- | -------------- | ---- | ------------------------------------------------------------ |
| Caffeine Tablets            | `caffeine`     | 1480 | 0.0008, 1, 0                                                 |
| Modafinil                   | `akvatab`      | 2280 | 0.001, 2, 0                                                  |
| Hercules                    | `drug_booster` | 3480 | 0.0028, 6.5, 0                                               |
| Cocaine                     | `cocaine`      | 3500 | 0.00442, 12, 0                                               |
| Epinephrine Shot            | `adrenalin`    | 6520 | 0.00629, 22, 0                                               |
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