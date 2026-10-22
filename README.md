# Glyph theme template

Start a theme for [Glyph](https://glyph.my) here. Click **Use this template** → **Create a new repository**, then:

1. **Edit `glyph-plugin.json`.** Give it its own `id` (lowercase, dashes: `midnight-coral`), a `name`, your `author` name and your colours. Every field is explained in the [manifest reference](https://docs.glyph.my/plugins/manifest).
2. **Try it in Glyph before you publish.** Copy `glyph-plugin.json` into `<Glyph data folder>/plugins/<your id>/`, then press **Settings › Plugins › Plugins folder › Reload**. See [Test your plugin](https://docs.glyph.my/plugins/testing).
3. **Publish it.** Add the topic `glyph-plugin` to this repository (the gear next to **About** on the repo page). Within the hour your theme shows up under **Community** in Glyph and on [glyph.my/plugins](https://glyph.my/plugins).
4. **Optional: get listed.** Open a pull request on [glyphmusic/plugins](https://github.com/glyphmusic/plugins) so your theme appears under **Listed**. See [Publish](https://docs.glyph.my/plugins/publishing).

The **Validate** workflow checks `glyph-plugin.json` on every push with the same rules Glyph uses. If it fails, its log names the problem.

## Ship an update

Change the colours, raise `version` (`1.0.0` → `1.1.0`) and push. Glyph installs the new version for everyone who has your theme, unless they turned automatic updates off.

## Share it

Link to `https://glyph.my/plugins/<your id>`. That page shows your theme with its colours and has an **Install in Glyph** button.

## More

- [How plugins work](https://docs.glyph.my/plugins/how-it-works): what Glyph does from the GitHub topic to the colours on screen
- [Designing a theme](https://docs.glyph.my/plugins/themes): where each colour shows up, and what makes a theme readable
- [Troubleshooting](https://docs.glyph.my/plugins/troubleshooting): my theme does not show up

Replace this README with your own once you are done. Keep a screenshot in it: people like to see a theme before they install it.

## License

The template is MIT. Pick any license you like for your theme and put it in `license` and `LICENSE`.
