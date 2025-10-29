# Audio Samples for Metro Maker Generative Music

This directory contains audio samples used by the generative music system.

## Requirements

All samples should be:

- **C Major Pentatonic** scale (C-D-E-G-A)
- **120 BPM** (or 60 BPM for calm variations)
- **4/4 time signature**
- **WAV format** for best performance
- **Mono or Stereo** 16-bit, 44.1kHz

## Sample Types

### achievement.wav

- One-shot sound for achievements
- Short (0.5-2 seconds)
- Bright, celebratory tone

### pentatonic_loop.wav

- Melodic loop in C major pentatonic
- 4, 8, or 16 bars
- Can be layered with other elements

### drums_light.wav

- Light percussion loop
- Subtle rhythm for moderate activity
- 8-16 bars

### drums_heavy.wav

- Heavier percussion loop
- Driving rhythm for high activity
- 16-32 bars

### ambient_texture.wav

- Ambient pad or texture
- Long, evolving sound
- Supports passenger density atmosphere

## Usage

The generative music system will:

- Dynamically adjust tempo between 60-120 BPM
- Fade samples in/out smoothly
- Loop samples for specified bar counts
- Layer multiple samples based on game state
