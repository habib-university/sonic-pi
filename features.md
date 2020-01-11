# Getter/setter
- set, get
# Iteration
- live_loop
- 18.times
# Scope
- do, end
# Built-in Functions
- use_bpm
- use_octave
# Syntax
- :
# Effects 
- with_fx, :pan, reverb, :panslicer
## Effect Options
- room:1
- mix:0.3
- phase:0.125
# Samples
- sample
- :drum_heavy_kick, :drum_snare_hard, :drum_cymbal_closed, :drum_cymbal_pedal
## Sample Options
- amp:5, 
# Synth
- use_synth :fm
- use_synth :pnoise
- :piano
# Playback and Options
- sleep
- play :c2
- attack
- release
- sustain
# Chords
- chord(:c2 :major7)
- chord(:a2 :minor)
- chord(:c3, :major7, num_octaves: 2)
# Randomization
- choose(chord(:c3, :major7, num_octaves: 2))

--------

# Features in Tracks

|                                            | Ditty                               | Easy                                   | Medium        | Hard |
| ---                                        | -----                               | ----                                   | ------        | ---- |
| Built-in Functions                         | sleep                               | "use\_bpm, live\_loop,                 |               |      |
| with\_fx, use\_synth"                      | "chords, sync, cue,                 |                                        |               |      |
| use\_octave, define"                       | range, ring (step, inclusive, tick) |                                        |               |      |
| Effect Options                             |                                     | room, mix, amp, pan                    |               |      |
| Effects                                    |                                     | reverb, pan                            |               |      |
| Getter/setter                              |                                     |                                        | get, set      |      |
| Iteration                                  |                                     | .times                                 | live\_loop    |      |
| Playback                                   | play                                |                                        |               |      |
| Playback Options                           |                                     | "attack, release, sustain, amp,        |               |      |
| cutoff"                                    |                                     |                                        |               |      |
| Randomization                              |                                     |                                        | .choose, rand |      |
| Rings                                      |                                     |                                        |               | ring |
| Sample Options                             |                                     | amp                                    |               |      |
| Samples                                    |                                     | "drum\_heavy\_kick, drum\_snare\_hard, |               |      |
| drum\_cymbal\_closed, drum\_cymbal\_pedal" |                                     | bass\_drop\_c                          |               |      |
| Scope                                      |                                     | do, end                                |               |      |
| Synth                                      |                                     | fm, blade, pnoise                      |               |      |
|                                            | (tutorial example)                  |                                        |               |      |
|                                            | (common melody)                     |                                        |               |      |
