# Music Prompt Reverse

Reverse-engineer an audio track into a precise Suno-ready music-generation prompt.

## What It Does

The skill converts audible evidence into one compact English prompt. It analyzes:

- Signature motifs, hooks, scales, modes, and chord motion
- BPM, meter, swing, syncopation, microtiming, and unusual rhythmic fingerprints
- Instrument materials, vocal delivery, arrangement, and energy curve
- Drum transients, hat brightness, sub-bass shape, sidechain, compression, and spectral balance
- Sampling texture, modulation, reverb, delay, distortion, and other distinctive effects

Broad genre names are optional summaries. The prompt prioritizes concrete sonic details to reduce generic or trigger-driven Suno results. Creator, song, album, and other identifiable names are never used as style references.

## Output Contract

- English only
- Maximum 850 characters, including spaces
- One prompt only, with no explanation or heading
- Highest-concentration musical elements appear first
- Chord motion, rhythmic identity, narrative structure, and audible effects are included when supported

## Installation

Copy the `music-prompt-reverse` folder into your Codex skills directory, then upload or reference an audio file and ask for a reverse-engineered Suno prompt.

## Example

`Reverse-engineer this audio into a Suno prompt.`
