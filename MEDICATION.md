A sheet documenting all available medical items in BHS and BHSRO to map out identifiers, names, primary effects, icon design, and assigned item use animation. Used as reference for consistency and to determine gaps in player needs against what items provide. This document applies to an assumed mod pack combination of Anomaly x GAMMA x Body Health System (BHS) x Body Health System Realistic Overhaul (BHSRO).

## Items

A listing of all items as they are added by the pack combination.

### Analgesics

Items that are primarily painkillers and damage resistance boosters. These may be used to triage damaged body parts as a temporary relief and taken voluntarily before combat encounters to increase survival chances.

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
| Military Bandage     | `bandage_army`   | 800  | 0.02, none                    |
| Tourniquet           | `jgut`           | 1200 | 0.12, none                    |
| Vinca                | `drug_coagulant` | 1880 | 0.00042, 11 (healone)         |
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
| Hercules                    | `drug_booster` | 3480 | 0.0028, 6, 0                                                 |
| Cocaine                     | `cocaine`      | 3860 | 0.00442, 8, 0                                                |
| Epinephrine Shot            | `adrenalin`    | 6520 | 0.00629, 16, 0                                               |
| SJ-I Combat Stimulant Shot  | `etg`          | 4580 | 0.00642, 10, 0                                               |
| SJ-V Combat Stimulant Shot  | `sj1`          | 3880 | 0.00442, 10, 0.15                                            |
| SJ-IX Combat Stimulant Shot | `sj6`          | 5580 | 0.00842, 12, 0.25                                            |

### Radiation

Items that primarily give radiation resistance or remove radiation exposure.

| Name                 | Identifier            | Cost | boost_radiation_restore, boost_radiation_protection |
| -------------------- | --------------------- | ---- | --------------------------------------------------- |
| Potassium Iodide     | `antirad_kalium`      | 1280 | 0, 0.0024                                           |
| Cystamine            | `antirad_cystamine`   | 1680 | 0.0008, 0.0100                                      |
| Radioprotectant      | `drug_radioprotector` | 1880 | 0, 0.0160                                           |
| Anti-Radiation Drugs | `antirad`             | 2260 | 0.0046, 0                                           |

### Toxicity

Items that primarily give resistance to toxic anomalies (acid). Toxicity damage is directly applied as health damage, so no restoration property exists. All toxicity items were changed to pill form.

| Name              | Identifier       | Cost | boost_chemburn_protection, boost_radiation_protection |
| ----------------- | ---------------- | ---- | ----------------------------------------------------- |
| Chlortetracycline | `antibio_chlor`  | 880  | 0.009, 0.00035                                        |
| Sulfadimethoxine  | `antibio_sulfad` | 1280 | 0.020, 0.0088                                         |
| Antidote          | `drug_antidot`   | 2280 | 0.048, 0                                              |

### Electric Shock

There are no items that give resistance to electric shock damage.

### Psy

Items that give resistance to psychic damage (e.g. psy fields, psy anomalies, psy-based creatures like poltergheists and controllers). Some of these medications may be referred to as antipsychotics in the overhaul; *Psy Block* may become *Clozapine*.

| Name           | Identifier           | Cost | boost_telepat_protection, eat_sleepiness |
| -------------- | -------------------- | ---- | ---------------------------------------- |
| Cannabis Joint | `joint`              | 680  | 0.02, 0.17                               |
| Marijuana      | `marijuana`          | 1180 | 0.03, 0.22                               |
| Etperazine     | `antiemetic`         | 2480 | 0.04, 0.05                               |
| Psy Block      | `drug_psy_blockade`  | 3680 | 0.075, 0.046                             |
| Diazepam       | `drug_sleepingpills` | 2080 | 0.025, 2.25                              |
