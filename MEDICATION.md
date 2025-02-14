A sheet documenting all available medical items in BHS and BHSRO to map out identifiers, names, primary effects, icon design, and assigned item use animation. Used as reference for consistency and to determine gaps in player needs against what items provide. This document applies to an assumed mod pack combination of Anomaly x GAMMA x Body Health System (BHS) x Body Health System Realistic Overhaul (BHSRO).


## Items

A listing of all items as they are added by the pack combination.

### Analgesics

Items that are primarily painkillers and damage resistance boosters. These may be used to triage damaged body parts as a temporary relief and taken voluntarily before combat encounters to increase survival chances.

| Name            | Identifier       | Cost | strike_immunity, wound_immunity, bhs_pain_protection | Applicator    |
| --------------- | ---------------- | ---- | ---------------------------------------------------- | ------------- |
| Ibuprofen       | `salicidic_acid` | 1280 | 0.05, 0.05, 0.1                                      | Pills (White) |
| Yadylin         | `yadylin`        | 1880 | 0.1, 0.1, 0.2                                        | Pills (White) |
| Diclofenac      | `analgetic`      | 2480 | 0.12, 0.12, 0.25                                     | Pills (White) |
| Oxycodone       | `tetanus`        | 3880 | 0.2, 0.2, 0.4                                        | Pills (White) |
| Metamizole Shot | `analgin`        | 4280 | 0.25, 0.25, 0.5                                      | Ampoule       |
| Morphine Shot   | `morphine`       | 5080 | 0.3, 0.3, 0.6                                        | Ampoule       |

### First Aid

Items that are taken after sustaining damage, to heal main player health and to triage damaged body parts. Some may also restore radiation exposure as a side effect (e.g. expeditionary items).

| Name                   | Identifier          | Cost | health_restore, bhs_healonelist | Applicator            |
| ---------------------- | ------------------- | ---- | ------------------------------- | --------------------- |
| First Aid Kit          | `medkit`            | 1600 | 0.0015, 21                      | Medkit (Red)          |
| Military Medkit        | `medkit_army`       | 2400 | 0.0020, 32                      | Medkit (Blue)         |
| Expeditionary Medkit   | `medkit_scientic`   | 3280 | 0.0022, 32                      | Medkit (Yellow)       |
| Stimpack               | `stimpack`          | 2200 | 0.007, 21                       | Big Injector (Red)    |
| Military Stimpack      | `stimpack_army`     | 3200 | 0.01, 32                        | Big Injector (Blue)   |
| Expeditionary Stimpack | `stimpack_scientic` | 4600 | 0.01, 32                        | Big Injector (Yellow) |
| Fluorapine Shot        | `propital`          | 3580 | 0.0015, 21                      | Compact Injector      |
| Axyltallisal Shot      | `rebirth`           | 6880 | 0.0188, 60                      | Compact Injector      |
| Survival Kit           | `survival_kit`      | 7200 | 0.0015, 60                      | (Dummy, fade)         |

### Emergency Nutrition

Items that give calories in injector form, used for emergencies, only provide satiety.

| Name               | Identifier  | Cost | eat_satiety | Applicator       |
| ------------------ | ----------- | ---- | ----------- | ---------------- |
| Small Glucose Shot | `glucose_s` | 1140 | 0.375       | Compact Injector |
| Large Glucose Shot | `glucose`   | 1940 | 0.610       | Compact Injector |

### Bleeding & Body

Items that primarily prevent or reduce bleeding and are used to triage or fully treat head, torso, arms, and legs.

| Name                 | Identifier       | Cost | bleeding_restore, bhs_* | Applicator             |
| -------------------- | ---------------- | ---- | ----------------------- | ---------------------- |
| Vikasolum            | `drug_coagulant` | 1780 | 0.00042, 11 (healone)   | Pills (Yellow, Small)  |
| Tranexyban Shot      | `zagustin`       | 2880 | 0.002, 14 (healone)     | Pen Injector (Magenta) |
| Bandage              | `bandage`        | 500  | 0.016, none             | Bandage                |
| Military Bandage     | `bandage_army`   | 800  | 0.02, none              | Bandage                |
| Tourniquet           | `jgut`           | 1100 | 0.12, none              | (Dummy, clear)         |
| Synthetic Splint     | `splint`         | 800  | 0, 1 (splint)           | (Dummy, clear)         |
| SAM Splint           | `alu_splint`     | 1400 | 0, 1 (splint)           | (Dummy, clear)         |
| Surgical Instruments | `surginst`       | 1380 | 0, 1 (surgery)          | (Dummy, clear)         |
| Surgical Field Kit   | `cms`            | 7980 | 0, 1 (surgery)          | (Dummy, fade)          |

### Stimulants

Items that are taken before or during combat for primarily increased carry weight, painkilling, damage resistance, and stamina-enhancing effects. Some items may also boost other resistances or provide minor health restoration.

| Name                        | Identifier     | Cost | power_restore, max_weight, strike_immunity | Applicator            |
| --------------------------- | -------------- | ---- | ------------------------------------------ | --------------------- |
| Caffeine Tablets            | `caffeine`     | 920  | 0.0008, 1, 0                               | Pills (Gray, Small)   |
| Modafinil                   | `akvatab`      | 1720 | 0.001, 2, 0                                | Pills (White, Big)    |
| Hercules                    | `drug_booster` | 2120 | 0.0028, 6, 0                               | Drink                 |
| Cocaine                     | `cocaine`      | 3860 | 0.00442, 8, 0                              | Crystalline Powder    |
| Epinephrine Shot            | `adrenalin`    | 3690 | 0.00629, 16, 0                             | Pen Injector (Yellow) |
| SJ-I Combat Stimulant Shot  | `etg`          | 4590 | 0.00642, 10, 0                             | Pen Injector (Green)  |
| SJ-V Combat Stimulant Shot  | `sj1`          | 3990 | 0.00442, 10, 0.15                          | Pen Injector (Orange) |
| SJ-IX Combat Stimulant Shot | `sj6`          | 5590 | 0.00842, 12, 0.25                          | Pen Injector (Red)    |

### Radiation

Items that primarily give radiation resistance or remove radiation exposure.

| Name             | Identifier            | Cost | radiation_restore, radiation_protection | Applicator            |
| ---------------- | --------------------- | ---- | --------------------------------------- | --------------------- |
| Potassium Iodide | `antirad_kalium`      | 1020 | 0, 0.0064                               | Pills (Yellow, Small) |
| Radioprotectant  | `drug_radioprotector` | 1690 | 0, 0.0154                               | Pills (Gray, Big)     |
| Amiprodine Cx    | `antirad_cystamine`   | 1990 | 0.0008, 0.0100                          | Ampoule               |
| Hipyridine Shot  | `antirad`             | 2260 | 0.0046, 0                               | Ampoule               |

### Toxicity

Items that primarily give resistance to toxic anomalies (acid). Toxicity damage is directly applied as health damage, so no restoration property exists.

| Name              | Identifier       | Cost | chemburn_protection, radiation_protection | Applicator               |
| ----------------- | ---------------- | ---- | ----------------------------------------- | ------------------------ |
| Chlortetracycline | `antibio_chlor`  | 1180 | 0.009, 0.00035                            | Pills (Red, Small)       |
| Sulfadimethoxine  | `antibio_sulfad` | 1780 | 0.020, 0.0050                             | Pills (Green, Small)     |
| IP2 Antitoxin     | `drug_antidot`   | 2780 | 0.048, 0                                  | Pills (Yellow/Blue, Big) |

### Electric Shock

There are no items that give resistance to electric shock damage.

### Psy

Items that give resistance to psychic damage (e.g. psy fields, psy anomalies, psy-based creatures like poltergheists and controllers). Medications may be referred to as antipsychotics.

| Name           | Identifier           | Cost | telepat_protection, eat_sleepiness | Applicator                |
| -------------- | -------------------- | ---- | ---------------------------------- | ------------------------- |
| Cannabis Joint | `joint`              | 880  | 0.02, 0.17                         | Joint                     |
| Marijuana      | `marijuana`          | 1180 | 0.03, 0.22                         | Joint                     |
| Etperazine     | `antiemetic`         | 2480 | 0.04, 0.05                         | Pills (Magenta/Blue, Big) |
| Diazepam       | `drug_sleepingpills` | 2080 | 0.025, 2.25                        | Pills (Red, Small)        |
| Haloperidol    | `drug_psy_blockade`  | 3680 | 0.075, 0.046                       | Pills (Magenta/Blue, Big) |
| Anabiotic      | `drug_anabiotic`     | 6880 | 0, 0                               | Pills (White, Big)        |

### Kits

Collections of item that are sold as a medical kit that is unpacked before use.

| Name                      | Identifier   | Cost  | (No properties) | Applicator   |
| ------------------------- | ------------ | ----- | --------------- | ------------ |
| Universal Medical Kit     | `medkit_ai1` | 17800 |                 | Unpacked Kit |
| Military Medical Kit      | `medkit_ai2` | 29800 |                 | Unpacked Kit |
| Expeditionary Medical Kit | `medkit_ai3` | 41800 |                 | Unpacked Kit |


## Applicators

- Pills/Blister
- Pills/Bottle
- Bottle
- Ampoule
- Pen Injector
- Compact Injector
- Big Injector


## Animations

| Animation Identifier          | Applicator                                    |
| ----------------------------- | --------------------------------------------- |
| `item_ea_antibio_sulfad`      | Pills (Small, Yellow/Blue)                    |
| `item_ea_antirad_kalium`      | Pills (Small, Green)                          |
| `item_ea_drug_antidot`        | Pills (Small, Magenta/Blue)                   |
| `item_ea_drug_psy_blocade`    | Pills (Small, Red)                            |
| `item_ea_drug_sleepingpills`  | Pills (Small, Gray)                           |
| `item_ea_drug_coagulant`      | Pills (Small, Yellow)                         |
| `item_ea_drug_akvatab`        | Pills (Blue Bottle)                           |
| `item_ea_drug_yadulin`        | Pills (White Bottle)                          |
| `item_ea_antiemetic`          | Pills (Small, Orange)                         |
| `item_ea_caffeine`            | Pills (White)                                 |
| `item_ea_drug_radioprotector` | Pills (Big, Yellow)                           |
| `item_ea_antirad`             | Big Injector, Red                             |
| `item_ea_stimpack_army`       | Big Injector, Blue                            |
| `item_ea_stimpack_scientic`   | Big Injector, Yellow                          |
| `item_ea_morphine`            | Antique Syringe (`syringe_hand, syringe`)     |
| `item_ea_syringe_def`         | Compact Injector (`syringe1_hands, syringe1`) |
| `item_ea_syringer_guns`       | Ampoule (`syringe2_hands, syringe2`)          |
| `item_ea_medkit`              | Medkit (Red)                                  |
| `item_ea_medkit_army`         | Medkit (Red)                                  |
| `item_ea_medkit_scientic`     | Medkit (Red)                                  |
| `item_ea_medkit_elite`        | Medkit (Unknown)                              |
| `item_ea_bandage`             | Bandage (Red)                                 |
| `item_ea_bandage_israeli`     | Unused                                        |
| `item_ea_bio_bandage`         | Unused                                        |
| `item_ro_injector_morphine`   | Pen Injector (Dark Blue)                      |
| `item_ro_injector_adrenaline` | Pen Injector (Red)                            |
| `item_ro_injector_propital`   | Pen Injector (Yellow)                         |
| `item_ro_injector_zagustin`   | Pen Injector (Purple)                         |
| `item_ro_injector_etg`        | Pen Injector (Green)                          |
| `item_ro_injector_sj1`        | Pen Injector (Red)                            |
| `item_ro_injector_sj6`        | Pen Injector (Blue)                           |