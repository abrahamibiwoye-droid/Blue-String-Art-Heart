# 💙 Electric Blue String Art Heart

A Python animation that draws a glowing electric-blue heart made from intersecting string-art lines, with delicate sparkling particles on a black background.

## Features

- **Electric-blue neon palette:** Bright cyan-blue lines with a soft blue glow.
- **Animated drawing:** The heart is drawn gradually over approximately 32 seconds.
- **Fine sparkles:** Small glowing particles appear around the active drawing point.
- **Replay and exit controls:**
  - Press `R` to restart the animation.
  - Press `Esc` or close the window to exit.
- **Portrait layout:** Uses a 720 × 1280 window, suitable for a mobile-video-style composition.

## Requirements

- Python 3.13 is recommended.
- Pygame 2.5.0 or newer.

## Setup

Open a terminal in the project folder and create a virtual environment:

```bash
python3.13 -m venv .venv
source .venv/bin/activate
```

Install the required package:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Run the animation

```bash
python main.py
```

## Controls

| Key | Action |
| --- | --- |
| `R` | Restart the animation |
| `Esc` | Exit the animation |

## Customization

You can adjust the settings near the top of `main.py`:

- `WIDTH`, `HEIGHT`: Window dimensions.
- `FPS`: Target frames per second.
- `NUM_LINES`: Number of string positions used to draw the heart.
- `TOTAL_TIME`: Time taken to draw the heart.
- `SCALE`: Size of the heart.
- `BLUE_COLOR` and `GLOW_COLOR`: Main line and glow colors.

## Project files

- `main.py` — Animation code.
- `requirements.txt` — Python package dependencies.

## License

No license is specified in this repository. Add a license file if you want to explicitly state how others may use, modify, or distribute this project.
