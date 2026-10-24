# TheOne

A modern Obsidian theme with light and dark modes, coordinated color palettes, rounded surfaces, and expressive headings. Designed for both Reading view and Live Preview.

## Features

- **19 color presets**, each with light and dark variants, plus a Custom option.
- Gradient titles and subtle section decorations, with options for simpler headings.
- Optional animated heading underlines and a border around the whole note.
- Soft, translucent highlights and inline code that composes with bold and italic text.
- A clean Properties card with understated labels and palette-aware tags.
- Compact footnotes with wrapping links and small return arrows.
- Contained Mermaid diagrams with horizontal scrolling when needed.
- Styled callouts, tables, task lists, navigation, and command menus.
- Reduced-motion support for animation and print adjustments for diagrams and note frames.

## Installation

Requires Obsidian **1.5.0 or newer**, as declared in `manifest.json`.

1. Download `theme.css` and `manifest.json` from this repository.
2. Create a `TheOne` folder inside your vault's `.obsidian/themes/` directory.
3. Place both files in that folder:

   ```text
   Your vault/
   └── .obsidian/
       └── themes/
           └── TheOne/
               ├── manifest.json
               └── theme.css
   ```

4. In Obsidian, open **Settings → Appearance** and select **TheOne** as your theme. Reload Obsidian if it does not appear yet.

The theme works without additional plugins. Install the optional **Style Settings** community plugin to access its customization controls.

## Color palettes

Open **Settings → Style Settings → TheOne → Color palette → Palette** to select a preset. Each preset coordinates the note and sidebar surfaces, accents, internal links, and highlights. Switch between Obsidian's light and dark modes to use its matching variant.

| Palette | Colors |
| --- | --- |
| Iris | Indigo and lavender |
| Ocean | Teal and sea glass |
| Forest | Sage and moss |
| Rose | Rosewood and blush |
| Ember | Terracotta and warm paper |
| Cobalt | Royal blue and ink |
| Frost | Arctic blue and cool mist |
| Plum | Aubergine and lilac |
| Sakura | Cherry blossom and porcelain |
| Amber | Honey and charcoal |
| Coffee | Mocha and parchment |
| Lagoon | Turquoise and deep blue |
| Graphite | Silver and soft charcoal |
| Glacier | Ice blue and polar white |
| Midnight | Electric blue and deep navy |
| Steel | Slate blue and brushed silver |
| Mint | Frosted mint and pine shadow |
| Periwinkle | Blue violet and moonlight |
| Aurora | Glacial teal and violet |

Select **Custom** to use the accent, wikilink, and highlight sliders. Presets override those sliders; switching back to Custom restores your slider choices. External links retain a separate cyan color.

## Style Settings

| Section | Controls |
| --- | --- |
| Color palette | Preset selection or Custom colors |
| Layout | Content width (400–1400 px), base font size (14–22 px), optional whole-note frame |
| Text | Justified paragraphs with automatic hyphenation |
| Accent Color | Custom accent hue, saturation, and lightness |
| Links | Custom wikilink hue, saturation, and lightness |
| Highlights | Custom highlight hue, saturation, lightness, and tint intensity |
| Headings | Animated hover underline, simplified H1, simplified H2–H4 |
| Emphasis | Plain bold and italic colors |
| Shape | Sharper corners |
| Callouts | Flatter callout appearance |

**Frame the whole note** and **Animated heading underline** are off by default. The underline appears on heading hover or focus within a heading in Reading view and Live Preview. With reduced motion enabled in your operating system, it appears without the sweep animation.

Automatic hyphenation depends on the document language reported by Obsidian. The selected font must also support the characters in your notes.

## Customization and troubleshooting

The theme lives in a single `theme.css` file. Its `@settings` block defines the controls exposed by Style Settings. `manifest.json` contains the theme name and compatibility metadata.

If a change does not appear, switch to another theme and back, or reload Obsidian. If styling looks inconsistent, temporarily disable CSS snippets or other appearance plugins to identify overlapping rules. Choose Custom before adjusting individual color sliders.

After updating the theme, check a note in both Reading view and Live Preview, especially if you use custom snippets or plugins that add their own interfaces.
