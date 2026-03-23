# Vonk — VCV Rack Modules Website

A static website listing all VCV Rack modules released under the **Vonk** brand by Grant Pieterse. Built with plain HTML and CSS — no frameworks, no build step.

## Modules

| Module | Type | Repo |
|--------|------|------|
| Avalanche | Granular Delay | [grant-pie/avalanche](https://github.com/grant-pie/avalanche) |
| BitBoy | Oscillator | [grant-pie/BitBoy](https://github.com/grant-pie/BitBoy) |
| MotherFuzzer | Distortion | [grant-pie/MotherFuzzer](https://github.com/grant-pie/MotherFuzzer) |
| SubGate8 | Gate Sequencer | [grant-pie/SubGate8](https://github.com/grant-pie/SubGate8) |
| Barrage | Burst Sequencer | [grant-pie/Barrage](https://github.com/grant-pie/Barrage) |
| Tenuto | Utility | [grant-pie/Tenuto](https://github.com/grant-pie/Tenuto) |
| SubGate16 | Gate Sequencer | [grant-pie/SubGate16](https://github.com/grant-pie/SubGate16) |
| Riddim | Drum Sequencer | [grant-pie/Riddim](https://github.com/grant-pie/Riddim) |
| Scatter | Burst Generator | [grant-pie/scatter](https://github.com/grant-pie/scatter) |

## Project Structure

```
vonk/
├── index.html        # Single-page site
├── assets/
│   ├── avalanche.jpg
│   ├── bitboy.jpg
│   ├── motherfuzzer.jpg
│   └── subgate8.jpg
└── README.md
```

## Running Locally

No build step required. Open `index.html` directly in a browser:

```bash
# Option 1 — open directly
open index.html

# Option 2 — serve with any static file server
npx serve .
```

## Adding a New Module

1. Add a `.jpg` image to `assets/`
2. Copy an existing card block in `index.html` and update the module name, type badge, description, feature tags, I/O items, and GitHub link

## License

Proprietary — © Grant Pieterse / Vonk
