# Feature-Aligned Speech Watermarking Demo

Official implementation for "Feature-Aligned Speech Watermarking for Robustness to Reconstruction Distortions" (ICME 2026).

This repository contains an interactive web demo for comparing different audio watermarking methods, released for double-blind review.

## Overview

This demo provides a comprehensive comparison of 6 different audio watermarking approaches:
- **Ours**: Feature-aligned speech watermarking method
- **WavMark**: Baseline watermarking method
- **AudioSeal**: Audio watermarking with robustness
- **TimbreWM**: Timbre-based watermarking
- **VoiceMark**: Voice-specific watermarking
- **WMCodec**: Codec-based watermarking

## Datasets

The demo includes audio samples from three benchmark datasets:
- **LibriSpeech**: Clean speech recordings
- **LJSpeech**: Single-speaker TTS dataset
- **VCTK**: Multi-speaker corpus

## Features

- 🎵 **Interactive Audio Playback**: Click to listen to original and watermarked audio
- 📊 **Side-by-Side Comparison**: Compare different watermarking methods horizontally
- 🎯 **Professional Layout**: Clean, academic-style presentation
- 📱 **Responsive Design**: Works on different screen sizes

## File Structure

```
├── index.html          # Main demo page
├── data/
│   ├── data.js        # Audio file metadata and paths
│   └── demo/          # Audio files organized by dataset and method
│       ├── librispeech/
│       ├── ljspeech/
│       └── vctk/
├── imgs/              # Images and diagrams
└── .github/           # GitHub Pages configuration
```

## How to View the Demo

1. **Online Demo**: Visit the [GitHub Pages deployment](https://anonymouswatermark.github.io/icme2026_wm/)
2. **Local Viewing**: Open `index.html` in a modern web browser

## Audio Organization

Each dataset contains:
- `gt/`: Original audio files
- Method folders: Watermarked audio files for each approach

## Technical Details

- **Frontend**: HTML5, CSS3, JavaScript, Vue.js
- **Audio**: WAV format, native HTML5 audio player
- **Styling**: Custom CSS with professional academic appearance

## Citation

If you find this work useful, please cite:

```bibtex
@article{anonymous2026feature,
  title={Feature-Aligned Speech Watermarking for Robustness to Reconstruction Distortions},
  author={Anonymous},
  journal={ICME},
  year={2026}
}
```

## License

For double-blind review only; redistribution is not permitted.
