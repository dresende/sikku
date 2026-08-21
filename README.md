# Sikku

A one-line logic puzzle. Draw a single unbroken line from **1** to the last
number, touching the numbers in order, filling every open cell. Three rules,
150 hand-picked levels across six chapters, and a last chapter where the line
you find is the only one that works.

Fifty levels free. One payment for the rest. No ads, no account.

**App Store:** coming soon
**Website & support:** https://dresende.github.io/sikku/
**Privacy policy:** https://dresende.github.io/sikku/privacy.html

This repository hosts Sikku's public website (GitHub Pages). It is plain
hand-written HTML with no build step and no dependencies.

The board in the hero is playable: it is level 14 of First Light, drawn as SVG
and driven by a port of the app's own rules. Only that one level's checkpoints
are inlined — never paste in `levels.json` or `tools/levelgen/thread-prototype.html`,
because both carry all 150 levels and a view-source would give the game away.

The palette mirrors `Shared/Theme.swift` in the (private) app repo, and the
rules, banner strings and haptic weights mirror `GuideSheet.swift`,
`PuzzleScreen.swift` and `Feedback.swift`. If any of those change, update
`index.html` to match.

Questions or feedback: [dresende@thinkdigital.pt](mailto:dresende@thinkdigital.pt)
