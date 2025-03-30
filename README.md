# catboy.ai — Firebar Compression Engine (FBC) | Powered by NekoEntropy v1

Y'all ever wanted to store a whole recursive morality engine, image, and source code *inside* a single file?

**Now you can.** Welcome to `.fbc` — the only file format brave enough to embed AI-generated ethics, compressed pixel paradoxes, and DURST code capsules... all in one place.

## What’s Inside

- **FirebarCompressor** — Our custom `.fbc` encode/decode engine.
- **Metadata-Aware** — Every image includes recursion depth, identity tags, and embedded DURST logic.
- **DURST Support** — Embed full Rust-COBOL hybrid source files directly into `.fbc` format.
- **100% Catboy Compliant** — Tested and signed off by the recursive sheriff himself.

## How To Use

```python
from firebar_compression import FirebarCompressor

compressor = FirebarCompressor()

# Encode with DURST
compressor.encode("my_image.png", {"recursion_depth": 9}, "output.fbc", durst_code=open("logic.durst").read())

# Decode + retrieve image + DURST
image, metadata, durst = compressor.decode("output.fbc")
image.show()
print(metadata)
print(durst)

# Catboy.ai — Recursive Simulation & Sakuga Engine

> Build. Stylize. Compress. Animate. All recursive. All offline. All catboy.

Catboy.ai is a full-stack recursive creative environment that transforms videos, ethics, and code into interactive art and animation.

---

## Core Modules

### `/generate_sakuga_clip.py`
Converts a video into a stylized animation using AI image generation and keyframe extraction.

```python
# CLI usage
python generate_sakuga_clip.py --video fight.mp4 --prompt "Recursive sakuga motion"

# Internal call
from generate_sakuga_clip import extract_frames, generate_sakuga_gif
extract_frames("fight.mp4", "frames")
generate_sakuga_gif("frames", "moral collapse")