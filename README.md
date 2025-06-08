# xayanide-mixed
My lightweight mixed osu! skin for osu! standard.

## Current state
- In progress...
- Check `todo.md`

## Previews
Only finished parts are shown.

**Beatmap Selection with Thumbnails**
<img src="https://xayanide.s-ul.eu/fTSabYbg" alt="Beatmap Selection with Thumbnails">

**Beatmap Selection without Thumbnails**
<img src="https://xayanide.s-ul.eu/jWx2eJhI" alt="Beatmap Selection without Thumbnails">

## Variants
- **instafade** - download this one first, the one I always use all-round. NM, HD, EZ, EZHD, HR, HDHR, DT, DTHD, DTHR, HDDTHR
- **instafade-nc** - same as instafade, but with nightcore sounds for nightcore mod
- **classic** - non-instafade, an attempt to recreate the instafade hitcircles. I barely use this at all. Can help with easy mod.
- **classic-nightcore** - same as classic, but with nightcore sounds for nightcore mod
- **classic-mapping** - same as classic, but with nightcore and hit sound samples for mapping

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

## Hitsounds
You can replace them with hitsounds you prefer, but I suggest first trying the **Argon Pro hitsound pack** from osu!lazer. These are the official hitsounds made by the osu! team, and they follow their own recommended standards which likely ensures higher and more consistent quality (e.g. no leading delays, recommended volume levels, clean mastering) compared to third-party hitsounds from community-made skins, they sound good too imo.

To test them, I recommend duplicating your current mixed skin and swapping only the hitsounds, so you can compare them without losing your original setup.

You can find the hitsounds here (from the osu-resources repo):
GitHub Directory:
https://github.com/ppy/osu-resources/tree/master/osu.Game.Resources/Samples/Gameplay/ArgonPro

These hitsounds are licensed, see the license section for details:
https://github.com/ppy/osu-resources?tab=readme-ov-file#licence

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

With Speakers Properties open, go to each specified tab then go to:

**Spatial Sound -> Spatial sound format**
- Select `Off`.

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
- **instafade**: After hitcircle combo 9, the hitcircle numbers overlaps with each other
- **instafade**: On a certain combo, some hitcircles will appear to have a visible small box or dot on its center
> [!NOTE]
> This will not be worked on. This is a known issue to all osu! skins that have instantly fading hitcircles.

## osu! skin License, Credits, Acknowledgements
Each variant of my mixed osu! skin has a credits-licenses.txt. See that file for more details

## Contributing
Anything meaningful would be great! Make sure the checks are passing, and there are no reasons to deny your pull request.

## Other Remarks
This osu! skin used to be stuck at skin.ini version 2.0 due to outdated `star`, `play-warningarrow` and `menu-button-background` osu! skin elements. Now, it supports `2.6` and newer versions! For more information about skin.ini versions, see https://osu.ppy.sh/wiki/en/Skinning/skin.ini#versions

### Disclaimer
This osu! skin neither guarantees a drastic increase in performance nor does it instantly make you a better player in osu! standard.
