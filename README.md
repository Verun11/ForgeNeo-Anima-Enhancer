# SD WebUI Forge - Anima Detail Enhancer

This is a port of the [ComfyUI-Anima-Enhancer](https://github.com/AdamNizol/ComfyUI-Anima-Enhancer/) extension for **Stable Diffusion WebUI Forge**. **ported using AI and uploaded using AI** All credits go to the original creator/s

## Features
- Enhances fine detail and structural coherence on Anima models.
- Optional built-in Spectrum acceleration to speed up generation.
- Supports custom block selection during denoising.
- Operates directly via the `Forge` backend ModelPatcher.

## Installation
1. Place this entire folder (`sd-webui-forge-anima-enhancer`) into your `stable-diffusion-webui-forge/extensions/` directory.
2. Restart your Forge web interface.
3. The extension will appear as "Anima Detail Enhancer" in an accordion under the generation settings directly in `txt2img` or `img2img`.

## Recommended starting settings
For many Anima tests, a strong starting point is:
- **Block Indices**: `3,4,5`
- **Denoise Start Pct**: `0.50`
- **Denoise End Pct**: `1.00`

If using Spectrum, a good starting point is:
- **Enable Spectrum**: `checked`
- **Spectrum w**: `0.20-0.30`
- **Spectrum m**: `8-16`
- **Spectrum lam**: `0.5`
- **Spectrum Warmup Steps**: `6`
- **Spectrum Window Size**: `2`
- **Spectrum Flex Window**: `0`
