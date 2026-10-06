# Asset Library submission - Crisp Quest Free Theme

Paste these into https://godotengine.org/asset-library/asset/submit (log in first). Nothing has been submitted or pushed yet.
The repository URL assumes the GitHub account is `Anipixels` and the repository is named as suggested; adjust if not.

| Field | Value |
|---|---|
| Asset Name (title) | Crisp Quest Free - Fantasy RPG UI Theme |
| Category | Misc |
| Godot version | 4.3 (tested only on 4.7.2 stable (the .NET editor build, run headless on Windows 11); see the note below) |
| Version | 1.0.0 |
| Repository host | GitHub |
| Repository URL | https://github.com/Anipixels/crisp-quest-free-theme |
| Issues URL | https://github.com/Anipixels/crisp-quest-free-theme/issues |
| Download Commit | the full 40-character hash of the commit you pushed (`git rev-parse HEAD`) |
| Icon URL | https://raw.githubusercontent.com/Anipixels/crisp-quest-free-theme/main/icon.png |
| License | CC-BY-4.0 (the form takes one licence; the description says the GDScript is MIT) |
| Suggested repo name | crisp-quest-free-theme |

Preview: type **Image**, image URL and thumbnail URL both
`https://raw.githubusercontent.com/Anipixels/crisp-quest-free-theme/main/screenshot.png`

## Short description

(For the GitHub repository "About" line; the Asset Library form has no short-description field.)

A free carved-wood fantasy RPG UI Theme with 52 PNG pieces: buttons, panels, window, inventory slots, health and mana bars, dialogue box, check box, slider, icons.

## Description (long)

```
A carved-wood fantasy RPG UI Theme with brass corner brackets, with the PNG pieces it is built from.

Set res://addons/crisp_quest_free/crisp_quest_free.tres as your project theme (or on any Control) and these are styled:
- Button (normal, hover, pressed, disabled), OptionButton, CheckBox, ProgressBar (health), HSlider, LineEdit, TextEdit, Panel,
  PanelContainer, HSeparator, ItemList, tooltips, Label.
- Type variations: ButtonSquare, ButtonClose, SlotButton (clickable inventory slot), ProgressBarMana, Slot / SlotHover / SlotSelected /
  SlotRare / SlotEpic, HotbarSlot, WindowPanel, DialogBox, NamePlate, PanelInset, Ribbon, CurrencyPlate, QuestEntry, ListRow, TooltipBox,
  PortraitFrame, LabelTitle, LabelOnAccent, LabelMuted, LabelTooltip.
- A 2x version of the theme for 1080p-and-up / HiDPI layouts.

Also included: 52 PNG pieces at 1x and 2x - 34 Carved Wood pieces, 15 white fantasy icons (sword, shield, potion, key, chest...) and
3 colour icons - and a demo scene: addons/crisp_quest_free/demo/quest_free_demo.tscn

Not covered, because the free sampler has no pieces for them: switch (CheckButton) art, radio buttons, tabs, scroll bars, popup menus,
vertical sliders. No font is bundled. Installs into addons/crisp_quest_free. Written for Godot 4.3+, tested on 4.7.2.

This is the free sampler of Crisp Quest, which has 135 pieces in each of 6 material themes, 184 icons and a full Godot theme per
material: https://anipixels.itch.io/crisp-quest

Licence: images, Theme and scene files CC BY 4.0 (credit "Crisp Quest Free Theme by Anipixels" with the link above); GDScript MIT.
How it was made: every shape is drawn procedurally by code written with an AI assistant (Claude). No AI image generators.
```

## Notes before you submit

- Godot version: the addon is written for 4.3+, but it has only been run on 4.7.2. Choosing "4.3" in the form is a claim that
  it works there. If you would rather claim only what was tested, pick the newest 4.x entry the form offers instead.
- The `.gitattributes` file marks everything except `addons/` as `export-ignore`, so the zip the Asset Library downloads
  contains only `addons/crisp_quest_free/` (with its own README and licence copy).
