# Mobile smoke report — 2026-07-15

Live build: https://blue-cloud-787.higgsfield.gg/

## Touch and Garage
- 390x844 portrait: all five vehicle choices visible; Legend Plate touch selection changed status to EQUIPPED.
- 667x375 landscape: two-column Garage layout; all five choices visible; Legend Plate clears the bottom action buttons.
- Pointer coordinates are normalized from the rendered canvas rectangle and pointer capture/cancel is handled.

## Audio
- First trusted browser click changed the Web Audio context state from suspended to running.
- Audio resume is attempted on every direct gesture and after foreground/focus return while Sound is enabled.
- Theme MP3 loaded successfully.

## Result card
- Generated PNG: image/png, 920,539 bytes, filename icewear-vezzo-rop4-result.png.
- Mobile PNG file sharing capability returned true.
- Mobile path invokes native file sharing first, with object-URL download fallback.

## Performance and stability
- FPS sample: 60 average.
- Frame time: 16.67 ms average; 16.8 ms maximum sample.
- Canvas compositor surfaces: 1.
- Runtime console errors: 0.
