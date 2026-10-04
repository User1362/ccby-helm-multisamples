# ccby-helm-multisamples

176 multisampled synthesizer instruments, rendered from the **factory patches of the Helm synthesizer** (Matt Tytel), as FLAC files with ready-to-use SFZ mappings.

Each folder under a category contains one instrument: a `.sfz` file and five 24-bit/48 kHz stereo FLAC samples (one every octave, about 4 s held + 1.5 s release tail, velocity 100). The SFZ files map each sample to a key range around its root note and carry a per-region `volume` so that all instruments sit at a similar level. Any SFZ player (sfizz, sforzando, ...) can load them. Sustained patches have no loop points; use your sampler's loop tools if you need endless sustain.

## License and attribution (CC BY 4.0 — attribution required)

These recordings are **adaptations of CC BY 4.0 patches** and are licensed under the **Creative Commons Attribution 4.0 International License** (see `LICENSE`, https://creativecommons.org/licenses/by/4.0/). If you use or share them you must credit the patch authors, link to the license, and indicate changes. Every patch file declares: "Patch (c) by <author>. This patch is licensed under a Creative Commons Attribution 4.0 International License." `SOURCES.md` lists, for every instrument, the creator, the copyright notice, the license, a link to the original patch, and the change made.

**Changes made:** each original Helm patch was played through the Helm synthesizer (version 0.9.0, GPL-3.0, https://tytel.org/helm/) and recorded as notes at five pitches; the recordings were normalized in level and encoded as FLAC with an SFZ mapping. No other modification of the patch's sound was made.

Patch authors: Cris Owl Alvarez (88), Matt Tytel (31), SF (25), Mikolis (17), Ones & Zeros (14), Sf (1).

The audio was rendered with Helm 0.9.0. Under the GNU GPL FAQ ("GPLOutput"), the copyright status of a program's output inherits that of its input unless substantial parts of the output are copied from the program itself; Helm's source repository contains no audio, sample or wavetable files. No warranty of any kind.

## What is not included

Percussion, SFX and arpeggiator patches, patches that Helm does not load completely, and the five factory patches that are licensed under the GPL rather than CC BY.

## Categories

- Bass: 46
- Chip: 8
- Harsh: 3
- Keys: 42
- Lead: 37
- Pad: 40

See `SOURCES.md` for the full list with credits.
