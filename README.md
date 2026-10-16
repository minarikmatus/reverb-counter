# reverb-counter
This is repository for a page to calculate reverb times in live music mixing.

The calculator is a static GitHub Pages-compatible page with no build step. It uses
`beat duration = 60 / BPM`, then calculates `reverb time = decay time - predelay`.
Decay can be set to a quarter note, half note, one 3/4 bar, or one 4/4 bar.
Predelay can be set from a quarter note down to a 1/64 note. Tap tempo averages
recent taps and clamps the result to 40-300 BPM.

These tempo-synced values are starting points for a mix rather than acoustic
measurements; adjust them by ear for the venue, source, and desired density.
