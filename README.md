# endmin.moe Internationalization (i18n)

This repository contains translation files for [endmin.moe](https://endmin.moe).

## Supported Languages

- 🇺🇸 English (en) - Default
- 🇧🇷 Portuguese (br)
- 🇩🇪 German (de)
- 🇫🇷 French (fr)
- 🇮🇩 Indonesian (id)
- 🇮🇹 Italian (it)
- 🇯🇵 Japanese (ja)
- 🇰🇷 Korean (ko)
- 🇲🇽 Spanish (mx)
- 🇷🇺 Russian (ru)
- 🇹🇭 Thai (th)
- 🇻🇳 Vietnamese (vn)
- 🇨🇳 Simplified Chinese (zh-cn)
- 🇹🇼 Traditional Chinese (zh-tw)

## File Structure

Each language has its own JSON file in the repository:

```
├── en.json       # English (base language)
├── br.json       # Portuguese
├── de.json       # German
├── fr.json       # French
├── id.json       # Indonesian
├── it.json       # Italian
├── ja.json       # Japanese
├── ko.json       # Korean
├── mx.json       # Spanish
├── ru.json       # Russian
├── th.json       # Thai
├── vn.json       # Vietnamese
├── zh-cn.json    # Simplified Chinese
└── zh-tw.json    # Traditional Chinese
```

## Contributing

We welcome contributions to improve translations!

### How to Contribute

1. Fork this repository
2. Create a new branch for your changes
3. Edit the appropriate language file(s)
4. Ensure JSON is valid and properly formatted
5. Submit a pull request with a clear description of your changes

### Adding a New Language

To add support for a new language:

1. Create a new JSON file named with the appropriate language code (e.g., `pl.json` for Polish)
2. Copy the structure from `en.json` as a template
3. Translate all strings to the new language
4. Update this README with the new language
5. Submit a pull request
