# JavascriptStroboscopicTuner

A javascript based stroboscopic instrument tuner

[▶️ Run Demo](https://trevorpeacock.github.io/JavascriptStroboscopicTuner/strobe.html)

Notes:
 * Uses your computer microphone. Disables echo cancellation and noise suppression (these tend to filter out tones)
 * Currently only tunes to A=440
 * Performs noticeably better in Edge/Chromium/Chrome.
 * Uses a crude zero-crossing pitch detection (with averaging and frequency limiting). Could be improved.
 * Doesn't work on mobile browsers

To use:
 * Play an "A" on your instrument. As you get close, you will notice dots lining up on the semi-circular display.
 * If you are sharp, dots will be rotating clockwise, if you are flat, dots will rotate counter-clockwise.
 * Adjust pitch until dots are stationary

Stroboscope can also be used for tuning pure intervals. Eg, playing a +2 cent E while tuning to A will produce three groups of dots. Placing a -14 cent C# will produce 5 groups of dots.

