<p align="center">
  <img src="https://img.shields.io/badge/INTERACTIVE_FICTION-CIPHER_VEIL-101010?style=for-the-badge&labelColor=050508&color=00FF41" alt="Cipher Veil"/>
  <img src="https://img.shields.io/badge/HTML_CSS_JS-BROWSER_GAME-101010?style=for-the-badge&logo=javascript&logoColor=00FF41" alt="Browser game"/>
</p>

# Cipher Veil · La Última Bruja del Nexo

<p align="center">
  <a href="https://tzayadet.github.io/Cipher-Veil/"><strong>LIVE DEMO ↗</strong></a> ·
  <a href="https://github.com/tzayadet/Cipher-Veil"><strong>SOURCE CODE</strong></a>
</p>

[![Static validation](https://github.com/tzayadet/Cipher-Veil/actions/workflows/quality.yml/badge.svg)](https://github.com/tzayadet/Cipher-Veil/actions/workflows/quality.yml) · [![GitHub Pages](https://github.com/tzayadet/Cipher-Veil/actions/workflows/jekyll-gh-pages.yml/badge.svg)](https://github.com/tzayadet/Cipher-Veil/actions/workflows/jekyll-gh-pages.yml)

An interactive dark-fantasy and science-fiction narrative. The first volume follows a branching story where player choices affect attributes, traits and possible endings.

<p align="center">
  
</p>

## Experience

- Interactive prologue and chapters.
- Branching decisions with consequences.
- Attributes and traits that change according to choices.
- Typewriter-style dialogue.
- Routes and endings conditioned by game state.
- Original visual interface and dark-fantasy setting.

## Play

Open the [live experience](https://tzayadet.github.io/Cipher-Veil/) or run `index.html` locally in a modern browser. No installation, backend or database is required.

The decorative typeface is loaded from Google Fonts, so that visual element requires an internet connection.

## Technology

HTML5, CSS3, JavaScript and Google Fonts.

## Scope and limitations

A single-player narrative prototype. It does not include account synchronisation or a server-side save system. Progress is not shared across devices.

## Validation

The quality workflow checks the inline JavaScript syntax, rejects remote JavaScript dependencies and detects duplicate HTML IDs:

```bash
python scripts/validate_site.py
```

Requires Python 3.11+ and Node.js 22+.

## Deployment

Static site published through GitHub Pages.

## License

See [LICENSE](LICENSE) for the repository's licensing terms.
