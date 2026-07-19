# BangPro • Gunshot / Impulse Analyzer

A clean, ad-free web-based real-time audio analyzer built with Web Audio API + FFT. Designed for detecting and logging loud impulsive sounds (claps, shouts, gunshots, etc.).

![Demo Screenshot](https://user-images.githubusercontent.com/38884937/xxx/bangpro-screenshot.png)  
*(Replace with a screenshot of the app if you want)*

## Features

- Real-time dB meter with analog gauge
- Live waveform and FFT frequency spectrum
- Adjustable impulse detection threshold (slider)
- Smart classification of impulses:
  - 🔫 **Gunshot** (very loud broadband)
  - 👏 **Clap / Snap**
  - 🗣️ **Shout / Voice**
  - ⚡ **Generic Impulse**
- Impulse logging table with timestamps
- Fully client-side — works offline after first load
- No ads, no tracking, privacy-friendly

## How to Use

1. Visit: https://glargod.github.io/bangpro/
2. Click **Start Microphone**
3. Allow microphone access
4. Make loud sharp sounds (claps, snaps, etc.)
5. Adjust the **Threshold** slider as needed

## Files

- `index.html` — Complete single-file webapp

## Tech Stack

- HTML5 + CSS
- JavaScript (Web Audio API)
- Canvas for visualizations

## Future Improvements

- CSV export for logs
- Spectrogram view
- Peak duration measurement
- Mobile PWA support
- Calibration tool

## License

MIT License — feel free to fork and modify.

---

**Made by Glargod** • Retired Navy tech exploring sound, consciousness & more.
