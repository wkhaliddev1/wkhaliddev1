# ASCII avatar

Generated from `https://avatars.githubusercontent.com/u/94002187?s=400&...` by rendering every
candidate back to pixels and optimising until the score stopped improving.

| file | what it is | size |
|---|---|---|
| `ascii-halfblock.txt` | `▀▄█` half blocks — **best likeness**, crisp at GitHub's 12px code font | 100 × 32 |
| `ascii-blocks.txt` | `░▒▓█` shade blocks — softer, more "shaded", fewer rows | 100 × 33 |
| `ascii-classic.txt` | classic ` .:-=+*#%@` ramp — pure ASCII, needs a wide screen | 100 × 41 |
| `preview.png` | all three, rendered at GitHub's exact code-block metrics (12px / 1.45 line-height) | — |

## Use in a GitHub profile README

Create the repo `<your-username>/<your-username>` and put this in `README.md`:

````markdown
```text
<paste the art here>
```
````

Notes:

- Keep the leading spaces — they are the left side of the image.
- 100 columns fits a desktop README; on mobile it scrolls sideways. If that matters,
  ask for a 70-column version.
- The art is drawn with "ink" characters, so it shows as light-on-dark on the dark theme
  and dark-on-white on the light theme (it will look like a negative there). If you want
  one fixed look, upload `preview.png` as an image instead.
