# Borozdov Phosphor

A theme from the Borozdov collection. Two faces — dark **Charcoal**, a midnight code
editor, and light **Chalk**, the same editor on white. Charcoal surfaces, hairline edges,
pill controls and one phosphor-green pulse for what you run.

![Borozdov Phosphor in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/phosphor/main/screenshots/dark.png)

![Borozdov Phosphor in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/phosphor/main/screenshots/light.png)

## Principles

- **Grayscale, rationed green.** The page is charcoal and snow; every green pixel earns
  its place as a link, the caret, a checked task, a toggle or the main button.
- **Borders, not shadows.** Surfaces sit one step above the canvas behind a hairline
  edge; nothing floats.
- **Regular-weight headlines.** The platform's sans, tracked a hair tight; 500 is the
  loudest voice, so headings whisper and size does the work.
- **Monospace where it counts.** JetBrains Mono for code, tags, table headers, property
  names and the status bar.
- **Pills and panels.** Buttons and tags are pills; callouts and embeds get 16px corners.

## Features

- Dark and light modes, following Settings → Appearance → Base color scheme
- Callouts as panels with the title in the type's colour; the default callout is green
- Code in a charcoal panel with a hairline; tables as query results with monospace headers
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces; the link green is deepened on Chalk
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Console**. Install Borozdov Console under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Phosphor** under Style Settings → Borozdov Console → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/phosphor/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Phosphor/`, then choose Borozdov Phosphor under
Settings → Appearance → Themes.

## Font

JetBrains Mono (© 2020 The JetBrains Mono Project Authors) is embedded in `theme.css` as
base64 WOFF2 under the SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt).
Weights 400–600, Latin and Cyrillic, for code, tags and metadata only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: тёмный «Уголь» — полуночный редактор
кода, и светлый «Мел» — тот же редактор на белом. Угольные поверхности, тонкие грани, кнопки
и теги в виде пилюль, моноширинный JetBrains Mono для кода и метаданных и один
фосфорно-зелёный импульс для того, что вы запускаете. В каталоге тема живёт вариантом Borozdov Console: установите Borozdov Console и плагин Style Settings, затем выберите Phosphor в Style Settings → Borozdov Console → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
