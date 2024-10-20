Banana Plug to USB-C (Power Only) Adapter

Based on the `USB4125-GF-A` 6 position surface mount connector.

## Version 3: DFP Fix
Version 2 had placements for pull-down resistors. As the DFP, this board should have pull-up resistors. Turns out, most UFP devices don't care so v2 works fine in most cases.

### Status
2024-OCT-20: V3 has not been tested yet.

## DFP Pull-Up Values
| DFP Advertisement | R Pull-Up to 4.75 - 5.5 V | R Pull-Up to 3.3 ±5%
| :--- | :---: | :---: |
| **Default USB PWR** | 56 kΩ ± 20% | 36 kΩ ± 20% |
| **1.5 A at 5 V** | 22 kΩ ± 5%  | 12 kΩ ± 5% |
| **3.0 A at 5V** | 10 kΩ ± 5% | 4.7 kΩ ± 5% |

[Values from Infineon KB Article](https://community.infineon.com/t5/Knowledge-Base-Articles/USB-Type-C-connector-Rp-Rd-and-Ra-termination-resistors/ta-p/253544)

## Discuss on Discord
Join the [AddOhms/Baldengineer Discord](https://discord.gg/Q3xzyuWqm6) to discuss this project