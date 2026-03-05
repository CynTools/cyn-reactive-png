# Cyn Reactive PNG

Create reactive PNG avatars for OBS streaming!

A reactive PNG is a layered image that responds to audio input - great for VTuber-style overlays without complex rigging.

## How It Works
1. Create idle and talking PNG states
2. Use OBS Browser Source with our detector script
3. Avatar switches states based on microphone input

## Files
- `idle.png` - Default state (add your own)
- `talking.png` - Active state when speaking (add your own)
- `detector.html` - OBS Browser Source

## Setup
1. Add your idle.png and talking.png images
2. Create Browser Source in OBS
3. Point to detector.html
4. Allow microphone access when prompted

## Support
[Ko-fi](https://ko-fi.com/cyntools)
