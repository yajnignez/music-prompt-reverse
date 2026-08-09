---
name: music-prompt-reverse
description: Reverse-engineer an uploaded or referenced music file into one precise Suno-ready English generation prompt under 850 characters. Use for audio-to-prompt analysis of melody, harmony, rhythm, timbre, vocals, arrangement, effects, mix, and mastering. Avoid creator and work names, broad genre triggers, and preset-like imitation; express the track through ranked, audible production evidence.
---

# Music Prompt Reverse Engineering

## Goal

Produce only one English Suno prompt, including spaces no longer than 850 characters. Describe what is heard, not who made it. Put the strongest identity-bearing evidence first.

## Evidence-first workflow

1. Listen for the track's signature before assigning any genre: main motif, hook contour, lead timbre, groove, vocal identity, or unusual production device.
2. Estimate supported facts: BPM, meter, swing, key or mode, chord motion, harmonic rhythm, structure, energy curve, and section changes. Use functional harmony or cautious wording when exact transcription is uncertain.
3. Rank audible evidence by perceptual concentration. Preserve only traits that materially distinguish this track.
4. Translate every possible genre label into its construction: melodic shape, scale, chord vocabulary, rhythm, microtiming, instrument articulation, recording or sample texture, frequency balance, transient design, effects chain, arrangement logic, and mastering character.
5. Use a fine-grained genre or hybrid label only as an optional summary after the evidence. Omit it if it risks triggering a generic Suno preset. Never stack synonymous labels.
6. Convert any creator or work comparison into neutral sonic attributes. Never output artist, band, producer, composer, DJ, song, album, label, franchise, or copyrighted-character names.

## Analysis layers

Analyze each layer for every style, then keep only the highest-value findings:

- **Signature:** motif length and contour, hook, scale or mode, chord progression, harmonic tension, lead timbre.
- **Rhythm:** BPM, meter, straight or swung feel, subdivision, syncopation, displaced accents, late or early backbeats, ghost notes, polymeter, odd bars, stop-start edits, loop length, and section-specific changes.
- **Source texture:** acoustic room, recording era, vinyl wear, tape color, sampler bit depth, resampling bandwidth, pitch drift, chopped phrase boundaries, or digital cleanliness.
- **Drums:** kick body and pitch, snare or rim material, clap layering, transient shape, decay, hat brightness and level, percussion placement, bus compression, saturation, and room treatment.
- **Low end:** bass instrument, note movement, sub reinforcement, upper-harmonic roll-off, mono focus, kick relationship, ducking, and multiband control.
- **Performance:** vocal or lead register, texture, articulation, phrasing, timing, vibrato, doubles, harmonies, ad-libs, call-and-response, and ensemble looseness.
- **Arrangement:** intro, verse, refrain, chorus, bridge, breakdown, instrumental passage, outro, density changes, and entry or removal of layers.
- **Narrative:** immediate climax, patient buildup, repeated escalation, verse-to-chorus expansion, breakdown-and-release, late peak, plateau, abrupt ending, or unresolved fade.
- **Effects:** chorus, phaser, flanger, tremolo, wah, vocoder, auto-tune color, bitcrush, granular stutter, reverse reverb, gated reverb, tape stop, delay throws, filter automation, pitch drops, or telephone EQ. State placement when important.
- **Mix/master:** stereo width, depth, center focus, spectral hierarchy, transient control, compression, saturation, headroom, loudness, reverb space, and high-frequency restraint.

## Style-to-evidence rule

Apply decomposition universally, not only to sample-based jazz-influenced hip-hop. Examples:

- Replace `jazz-hop` with evidence such as `melancholic two-bar pentatonic piano loop, dusty 1970s vinyl source, band-limited 12-bit resampling, late-snare boom-bap microtiming, wooden rimshot, muffled acoustic kick, recessed airy hats`.
- Replace `house` with its actual pulse, chord rhythm, kick envelope, matte clap or snare, hat filtering, bass spectrum, sidechain behavior, build and breakdown logic, and mastered density.
- Replace `dream-pop` with the exact vocal distance, guitar or synth modulation, harmonic suspension, drum softness, stereo blur, reverb decay, and energy arc.
- Replace `city pop` with the actual chord extensions, bass articulation, drum pocket, guitar or keyboard processing, horn or string role, vocal delivery, and mix finish.
- Replace `post-punk` with bass ostinato, guitar interval shape, motorik or syncopated pulse, drum-room character, vocal register, repetition, and tension curve.

Prefer five precise acoustic facts over five adjacent genre labels. Do not infer a sample decade, sampler resolution, chord symbol, instrument, lyric, or language without reasonable audio support.

## Modern production safeguards

For beat-led music, describe the finished drum and low-end texture rather than naming raw kit pieces. Distinguish `matte short snare with softened transients`, `dark de-essed hats tucked behind the vocal`, `sub-reinforced kick with a rounded tail`, `bass with rolled-off upper harmonics`, `clean sidechain ducking`, and `tight multiband-controlled lows`. Avoid generic `standard snare`, `bright hats`, or `heavy bass`, which can produce untreated drums, dominant cymbals, or muddy lows.

For contemporary neon electronic music, avoid `synthwave`, `retrowave`, `outrun`, and `classic synthpop` unless a period recreation is explicitly requested. Describe the audible synthesis and processing instead: digital-analog hybrid pads, deep sub-bass, clean drums, sidechain compression, granular sampling, pitch-warped vocals, filter automation, shimmer reverb, wide imaging, and modern mastering. Use `contemporary vaporwave`, `future funk`, `neo-city-pop`, `neon pop`, `nu-disco`, or another supported microgenre only when useful.

## Prompt order

Write compact comma-separated clauses in this order, changing it only when another trait is clearly more defining:

`signature motif/timbre -> rhythmic fingerprint and BPM/meter -> mode and chord motion -> source texture -> drum and low-end processing -> vocal/lead performance -> supporting instruments -> narrative and arrangement -> distinctive effects -> stereo/dynamics/mastering -> essential mood -> optional microgenre or exclusion`

## Compression priority

Treat 850 characters as a ranking test. Preserve, in order: signature motif, distinctive rhythm, chord motion, defining timbres, drum and bass treatment, narrative structure, unique effects, and vocal identity. Cut generic mood adjectives, redundant genre labels, routine effects, repeated ideas, and negative prompts first. Use short noun phrases. Do not force every analysis layer into the result.

## Output contract

- Output only the final prompt: no heading, explanation, label, quotation marks, or analysis.
- Use English words and ASCII punctuation only.
- Stay at or below 850 characters including spaces; aim for 500-760.
- Order traits by audible importance, not by a fixed checklist.
- Include chord motion or a concise functional description.
- Include the distinctive rhythm and narrative or energy curve.
- Include only clearly audible special effects, preferably with placement.
- Never output creator or work names or copied lyrics.
- Express uncertainty honestly; do not invent exact facts.
- Avoid generic quality claims and preset-triggering label stacks.

Before responding, count characters and confirm English-only output, creator-name removal, internal consistency, perceptual ordering, and Suno actionability. The first clause should identify the track even if the rest is removed.
