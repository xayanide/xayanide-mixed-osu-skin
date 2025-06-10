# xayanide-mixed
My lightweight mixed osu! skin for osu! standard.

## Current state
- Work in progress! See `TODO.md`.

## Previews
Only finished parts are shown.

**Beatmap Selection with Thumbnails**
<img src="https://xayanide.s-ul.eu/fTSabYbg" alt="Beatmap Selection with Thumbnails">

**Beatmap Selection without Thumbnails**
<img src="https://xayanide.s-ul.eu/jWx2eJhI" alt="Beatmap Selection without Thumbnails">

## Variants

## Base variants
- **instafade** - as the name suggests. download this one first, the one I always use all-round. NM, HD, EZ, EZHD, HR, HDHR, DT, DTHD, DTHR, HDDTHR, DTHRFL, HDDTHRFL
- **classic** - non-instafade. an attempt to recreate hitcircle@2x and hitcircleoverlay@2x from its instafade hitcircles. I barely use this at all. Can help with easy mod.

## Optional variants
- **instafade-nc** - same as instafade, but with nightcore sounds for nightcore mod
- **classic-nc** - same as classic, but with nightcore sounds for nightcore mod
- **classic-mapping** - same as classic, but with nightcore and hitsound sample sets for mapping

## Compliance

This osu! skin follows the commonly accepted **osu! community skinning standards**, as compiled and maintained by the osu! community:

- [osu! - Skinnable Files - Detailed List Google Spreadsheet - RockRoller](https://docs.google.com/spreadsheets/d/1bhnV-CQRMy3Z0npQd9XSoTdkYxz0ew5e648S00qkJZ8)
- [Skinnable Files List - Haskorion](https://osu.ppy.sh/community/forums/topics/186787)

> [!TIP]
> These resources are unofficial but widely respected within the osu! skinning community. The spreadsheet is maintained by RockRoller and is based on extensive research across stable versions of osu!

Additionally, this osu! skin:

- References certain sizes and layout alignments of elements from the **official osu! default skin** on the Stable release stream.
- May include text (such as labels or names) derived from the osu! default skin.

These are meant to maintain familiarity and predictability for players used to osu!'s native UI and gameplay cues.

## Hitsounds and Compliance

## Official Hitsounds

You can replace the hitsounds in this osu! skin with ones you prefer, but I recommend first trying the **Argon Pro hitsound pack** from osu!lazer. These are official hitsounds made by the osu! team and follow their own internal standards ensuring consistent quality such as:

- Clean mastering
- No leading delays
- Reasonable and balanced volume levels

Compared to many community-made hitsound sets, these are more likely to meet technical standards by default, though some community-made sets also sound great in practice.

To experiment safely, I recommend duplicating your current skin and swapping only the hitsounds, so you can A/B test without losing your original configuration.

You can find the Argon Pro hitsounds here (from the `osu-resources` repository):

https://github.com/ppy/osu-resources/tree/master/osu.Game.Resources/Samples/Gameplay/ArgonPro

> [!NOTE]
> These hitsounds are under a specific license. Please see the full terms here:  
> https://github.com/ppy/osu-resources?tab=readme-ov-file#licence

### Unofficial Hitsounds

You might also enjoy the hitsounds from the following osu! skin:

- **The hitsounds that come with my mixed osu! skin**

- **Signaturka Tournament v1.0**  
https://skins.osuck.net/skins/3630

> [!WARNING]
> While community-made hitsounds can sound great, I can't personally guarantee that they follow technical standards (e.g., clean mastering, no unintended delay, optimal volume balancing). Use your own judgment and always test for audio quality and sync in-game.

## Prerequisites
- [osu! stable](https://osu.ppy.sh/home/download) (or [osu! lazer](https://github.com/ppy/osu))

## Download and Installation

1. Download the `.osk` file at releases: https://github.com/xayanide/xayanide-mixed-osu-skin/releases
2. Once downloaded. Open the `.osk` file.

> [!TIP]
> You can also drag the `.osk` file into osu!'s `Skins` folder or move the folder from the `.osk` file to the `Skins` folder.
> In-depth: https://skinship.xyz/guides/installing_skins

## Usage
1. With osu! open. Open Options menu. Shortcut is `CTRL + O`.
2. Navigate to `Skin` category, navigate to the `Skin` section.
3. At `Current skin`, select the osu! skin.

### Recommended osu! settings for this osu! skin
These settings are from osu! stable, the options should be similar to osu! lazer.

|Setting Category|Setting Section|Option|Recommended State|
| :--- | :--- | :--- | :---: |
| Graphics | Detail settings | All | off |
| Gameplay | General | Background dim | 100% |
| | | Always show key overlay | on |
| | Song select | Show thumbnails | off |
| Audio | Volume | Master | <=100% (depends on audio device) |
| | | Effect | <=60% (depends on audio device) |
| | | Ignore beatmap hitsounds | on |
| Skin | Skin | Ignore all beatmap skins | on |
| | | Use skin's sound samples | on |
| | | Always use skin cursor | on |
| | | Automatic cursor size | off |
| | | Use combo colour as tint for slider ball | off |

### Recommended operating system settings for this osu! skin
These settings are from Windows 10.

With `Speakers` Properties open, go to each specified tab then go to:

**Advanced -> Default Format**
- Select `16 bit, 44100 Hz (CD Quality)` or `16 bit, 48000 Hz (DVD Quality)`, higher than that is unnecessary and adds overhead, 24-bit is useful for recording/mixing, not for playback.
> Sources: https://learn.microsoft.com/en-us/windows/win32/coreaudio/wasapi, pro audio software (DAWs, low-latency applications) and hardware forums

**Spatial Sound -> Spatial sound format**
- Select `Off`.

**Enhancements**
- Tick or check the `Disable all sound effects` box.

## osu! skin Feature Overview
- **instafade**: [Instantly fading hitcircles](https://skinship.xyz/guides/insta_fade_hc)
- **instafade**:  Hitcircle colored between red and orange
- **instafade**: One white combo color only
- Obvious ranking letters
- Increased distinction on song selection menu
- Skin.ini version 2.7
- No redundant visual elements (e.g., anime girl on score screen, aesthetics on song selection)
- No slider follow circle
- No slider end circle
- No cursor expand
- No menu click sounds
- No key press sounds
- No button click sounds
- No sound when the cursor hovers over menus, keys and buttons
- No sound applause sound
- No sound when game is paused
- No spinner background
- No background when game is paused
- No combo bursts
- Yellow cursor
- Yellow cursor trail
- Default smoke trail
- Spinner approach circle
- Spinner small dot at the middle
- Default slider tick sounds
- Default in-game leaderboard font
- Thin follow points
- Numbers on hitcircles
- Health bar with similar length and thickness to osu! Default skin's health bar
- Small score and combo number elements (downscaled from osu! default skin's elements)

## Known Issues
- **instafade**: After hitcircle combo 9, the hitcircle numbers overlap with each other.
> [!NOTE]
> This will not be worked on. This is a known issue to all osu! skins that have instantly fading hitcircles.

## osu! skin License, Credits, Acknowledgements
Each variant of my mixed osu! skin has a credits-licenses.txt. See that file for more details.

## Contributing
Anything meaningful would be great! Make sure the checks are passing, and there are no reasons to deny your pull request.

## Other Remarks
This osu! skin used to be stuck at skin.ini version 2.0 due to outdated `star`, `play-warningarrow` and `menu-button-background` osu! skin elements. Now, it supports `2.6` and newer versions! For more information about skin.ini versions, see https://osu.ppy.sh/wiki/en/Skinning/skin.ini#versions

### Disclaimer
This osu! skin neither guarantees a drastic increase in performance nor does it instantly make you a better player in osu! standard.
