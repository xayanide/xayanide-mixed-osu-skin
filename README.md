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

### Base variants
- **instafade** - as the name suggests. download this one first, the one I always use all-round. NM, HD, EZ, EZHD, HR, HDHR, DT, DTHD, DTHR, HDDTHR, DTHRFL, HDDTHRFL
- **classic** - non-instafade. an attempt to recreate hitcircle@2x and hitcircleoverlay@2x from its instafade hitcircles. I barely use this at all. Can help with easy mod.

### Optional variants
- **instafade-nc** - same as instafade, but with nightcore sounds for nightcore mod
- **classic-nc** - same as classic, but with nightcore sounds for nightcore mod
- **classic-mapping** - same as classic, but with nightcore and hitsound sample sets for mapping

## Compliance

This osu! skin follows the commonly accepted **osu! community skinning standards**, as compiled and maintained by the osu! community:

- [osu! - Skinnable Files - Detailed List Google Spreadsheet - RockRoller](https://docs.google.com/spreadsheets/d/1bhnV-CQRMy3Z0npQd9XSoTdkYxz0ew5e648S00qkJZ8)
- [Skinnable Files List - Haskorion](https://osu.ppy.sh/community/forums/topics/186787)

> [!TIP]
> These resources are unofficial but widely respected within the osu! skinning community. The spreadsheet is maintained by [RockRoller](https://osu.ppy.sh/users/8388854) and is based on extensive research across stable versions of osu!

Additionally, this osu! skin:

- References certain sizes and layout alignments of elements from the **official osu! default skin** on the Stable release stream.
- May include text (such as labels or names) derived from the osu! default skin.

These are meant to maintain familiarity and predictability for players used to osu!'s native UI and gameplay cues.

## Hitsounds and Compliance

### Official Hitsounds

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

|Setting Category|Category Section|Option|Recommended State|
| :--- | :--- | :--- | :---: |
| Graphics | Detail settings | * (all) | off |
| | Main Menu | Snow | off |
| | | Parallax | off |
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

To adjust advanced audio settings, it's often best to use the classic Sound control panel instead of the newer Windows Settings UI. There are many methods, I'll just write the simplest methods.

### Method 1: Using Run
1. Press `Windows key/Super key/Meta key + R` to open the Run dialog.
2. Type the following and press Enter:
```shell
mmsys.cpl
```

### Method 2: From the Taskbar
1. Right-click the **volume icon** in the system tray.
2. Select **"Sounds"** (or **"Open Sound settings"**).
> [!TIP]
> If the modern settings UI opens, click **"Sound Control Panel"** under the *Related settings* section.

1. Moving on, go to the `Playback` tab.
2. Select your active output device (e.g. Speakers or Headphones), then click **Properties**.
3. With `Properties` window open. Navigate to the specified tab and sections and apply the following settings:

|Tab|Section|Option|Recommended State|
| :--- | :--- | :--- | :---: |
| Advanced (Ignore this row entirely on Windows 11) | Default Format | | `16 bit, 44100 Hz (CD Quality)` or `16 bit, 48000 Hz (DVD Quality)` |
| | Signal Enhancements | Enable audio enhancements | off |
| Enhancements | | Disable all sound effects | on |
| Spatial Sound | Spatial sound format | | off |

> [!NOTE]
> Higher than `16 bit, 44100 Hz (CD Quality)` or `16 bit, 48000 Hz (DVD Quality)` is unnecessary and can add overhead, 24-bit is useful for recording/mixing, not for playback.
> 
> Sources:
> - https://learn.microsoft.com/en-us/windows/win32/coreaudio/wasapi
> - pro audio software (DAWs, low-latency applications)
> - hardware forums
> - articles

## osu! skin Feature Overview

### Metadata
- Skin.ini version 2.7

### Visual

- **instafade**: [instantly fading hitcircles](https://skinship.xyz/guides/insta_fade_hc)
- **instafade**: hitcircle is colored between red and orange
- **instafade**: one combo color only, white
- More obvious ranking letters
- Increased distinction on beatmap selection
- No redundant visual elements (e.g., anime girl on score screen, aesthetics on beatmap selection)
- No slider follow circle
- No slider end circle
- No cursor expand
- No spinner background
- Transparent score screen background
- Transparent pause background
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

### Auditory

- No menu click sounds
- No key press (typing) sounds
- No button click sounds
- No nightcore sounds
- No applause sound
- No paused sound
- No menu hover, key and button sounds

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
