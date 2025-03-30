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
