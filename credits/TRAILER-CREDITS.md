# Sources and notices

Game footage, fighter/stage art, portraits, branding, bitmap fonts, game sounds
and voices come from this project's existing assets. Existing guest-character
depictions remain the supplied game's content. No new voice cloning was used.

## Motion recipes

Opening and closing code is adapted from Vincentwei1021's
[video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft), revision
`42f922fe076f6428814d10f6184caf22a8b2adc2`, under Apache License 2.0.
The license is preserved in `licenses/video-shotcraft-APACHE-2.0.txt`.

- `demos/rhythm/trailer-grammar-moves/TrailerBumper.tsx`
- `demos/outro/outro-group-photo-launch/OutroGroupPhotoLaunch.tsx`

Changes: 60-fps timing conversion, game branding and type, gameplay teases,
nine fighter portraits, cabinet composition, fixed final hold and game copy.
Exact recipe/variant records and reference hashes are in
`shotcraft-references.json`. Gallery previews are review references only;
they do not appear in the finished trailer.

## Score and voices

The score derives from `assets/audio/production_05/music/battle_breakbeat_0.ogg`.
The existing game manifest identifies it as original ElevenLabs-generated music
for this project. Its 64-beat, 27.52-second loop is repeated and adjusted with
FFmpeg's pitch-preserving tempo filter to 140.28169 BPM, then reduced in volume
and faded at the boundaries. `asset-receipt.json` records the exact ratio and
hashes. Existing provider/account terms continue to apply.

The title announcement is from the existing production pack. "Engage" is from
the existing `announcer_20261116` pack. Fight efforts, reactions, signatures and
assist announcements are recorded directly from the current game.

## Editorial impacts

Both files are high-quality MP3 previews, not uploader lossless originals.
Hashes, metadata, exact license URLs and measured energy peaks are preserved in
`public/audio/sfx/audio-manifest.json`.

| Sound | Author | License | Use |
|---|---|---|---|
| [Sound Design Elements Impact SFX PS 070](https://freesound.org/people/AudioPapkin/sounds/812736/) | AudioPapkin | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) | Opening reveal at frame 66, gain 0.36 |
| [PLASMA IMPACT ONE](https://freesound.org/people/johnjohnfm/sounds/804681/) | johnjohnfm | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) | Closing stamp, gain 0.42; energy apex aligned to frame 2494 |

Source files are preserved without destructive edits. Playback timing, duration
and gains are authored in `src/timeline.ts`. Measurements and download metadata
are not described as listening conclusions.
