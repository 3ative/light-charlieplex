# light-charlieplex
🐉 ESPHome-ing Charlieplexed LED of the "_LED Whimpers_" Lashes - 6 LEDs, 3 GPIOs, Custom Patterns Infinite Possibilities!

#### Parts List:
- 3 x 330Ω 1/4 Watt Resistors
- LED False Eyelashes: [AliExpress](https://s.click.aliexpress.com/e/_c3HGj8K3)

#### *Code-y Bits*
- ESPHome Code: [light-charlieplex.yaml](https://github.com/3ative/light-charlieplex/blob/main/light-charlieplex.yaml)

#### ✨ Features
- 6 LEDs from 3 pins - Because maths is beautiful
- 4 Pre-programmed patterns - Forward, Reverse, KnightRider, and Random
- Adjustable speed - From "sleepy" to "caffeinated"
- Easy to customize - Just edit the Patterns and Names in the ``substitutions:`` section!

#### Example Patterns:
```yaml
# Twinkle
sequence: "1, 0, 0, 3, 0, 0, 5, 0, 0, 2, 0, 0, 4, 0, 0, 6, 0, 0"

# Pairs
sequence: "1, 2, 0, 3, 4, 0, 5, 6, 0"

# Build up
sequence: "1, 1, 2, 1, 2, 3, 1, 2, 3, 4, 1, 2, 3, 4, 5, 1, 2, 3, 4, 5, 6"

# Heartbeat
sequence: "1, 1, 0, 1, 1, 0, 0, 0, 0, 0"
```
Note: Remember to adjust the ``length_n: "X"`` with the number of steps

---
#### YouTube tutorial: [Ultimate Fan Project v4.0](https://youtu.be/jFA75R_Z6gE)
---

#### 🤝 Found this useful, want to say 'Thanks', and support my efforts. CHEERS🍺
| Buy me a Coffee | PATREON |
|-----------------|---------|
| [![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-donate-yellow.svg?style=flat-square&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/3ative) | [![Patreon](https://img.shields.io/badge/Patreon-support-red.svg?style=flat-square&logo=patreon)](https://www.patreon.com/3ative) |
---
