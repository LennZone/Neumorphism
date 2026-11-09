# Contributing

Thanks for your interest in improving Neumorphism. Bug reports, ideas and pull requests are all welcome.

## Reporting a bug

Please [open an issue](https://github.com/LennZone/Neumorphism/issues/new/choose) and include:

- your Obsidian version and platform (Windows, macOS, Linux, Android, iOS)
- light or dark mode
- a screenshot of the problem
- other themes, snippets or plugins that change the look (for example Style Settings), if any

## Suggesting a change

For larger changes, please open an issue first so we can talk about the idea before you spend time on it. The theme follows a few strict design rules, and not every good idea fits them.

## Design rules

Every change should keep these rules intact:

- **One material**: every surface is shaped from the same base color. New colors are only used as accents.
- **Raised means "can be pressed"**, inset means "pressed, active or input".
- **Light comes from the top left**, so highlights sit top left and shadows bottom right.
- **Readable**: body text keeps at least 7:1 contrast, accent and callout colors at least 4.5:1.

## Working on the theme

The whole theme lives in `theme.css`. The table of contents at the top of the file lists its sections.

1. Fork the repository and clone it.
2. Link or copy the folder into a test vault at `.obsidian/themes/Neumorphism`.
3. Select the theme under Settings, Appearance, Themes.
4. After saving `theme.css`, reload the theme (switch to another theme and back, or run "Reload app without saving").

Before opening a pull request, please check:

- light and dark mode
- desktop and, if you can, mobile
- that the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) options still work, if you touched a token
- that new values use the existing tokens (`--nm-*`) instead of hard coded colors or shadows

## Pull requests

- Keep a pull request focused on one change.
- Add before and after screenshots for visual changes.
- Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages, for example `fix: align tab bar icons` or `feat: add option for flat sidebars`.

## License

By contributing, you agree that your contributions are licensed under the [MIT License](LICENSE).
