# Labels Mapping — SCADA-MV-IDS

This file documents the label columns used in **SCADA-MV-IDS**.

---

## 1) `classe` — Binary label
| Value | Meaning         | Count |
|------:|-----------------|------:|
| 0     | Normal          | 22067 |
| 1     | Attack (any)    | 23988 |

---

## 2) `classe_atk` — Multiclass label (string)
The `classe_atk` column contains **string** labels.  
For name mapping to the paper terminology, see: `attacks_mapping.md`.

| Label (dataset)              | Count |
|-----------------------------|------:|
| normal                      | 22067 |
| AcunetixScadaAuthhm         |  6168 |
| AcunetixAutenticado         |  5764 |
| ArachniRodouporh            |  2346 |
| AcunetixDefaultWire         |  1862 |
| AcunetixDefaultXX           |  1203 |
| AcunetixScadaBRDefault      |  1100 |
| SmodDosWriteAllRegisters    |   977 |
| SmodDosWriteAllcoins        |   967 |
| SmodGetFunc                 |   860 |
| SmodScannerUID              |   673 |
| ModFuzzer                   |   601 |
| NexposeExaustiveNoFW        |   431 |
| NexposeFull                 |   396 |
| NessusDefault               |   314 |
| Nmap                        |   203 |
| PLCScan                     |   123 |

