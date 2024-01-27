# mcdle-public

Public Repo of MCdle. Post issues here or on discord!

## Translations

This repo contains the translations of MCdle. I will keep english and german up to date, everything else is community based, so feel free to contribute! Pull requests are welcome, for new languages, fixes or updates!

| Language               | Up to date | Official |
| ---------------------- | ---------- | -------- |
| English (US) (default) | ✅         | ✅       |
| English (UK)           | ✅         | ✅       |
| German                 | ✅         | ✅       |
| French                 | ✅         | ❌       |
| Spanish                | ❌         | ❌       |

### How to contribute to the translations

Optionally but recommended - join the MCdle [discord server](https://discord.gg/3rDDPcFd4f) and open a Post in the #translations forum channel to let me know what you are working on. There we can discuss any questions you might have and you might even get some translation help from others!

1. Fork this repo
2. Create a new branch
3. Open the `generateTranslations.js` script. By default it will generate an english version, so please modify the variables at the top in the Configuration section - there are comments to help you. In particularly change the `target_language` to help you translate the mob/block/items.
4. Run the code either in the browser console (`F12` or `Ctrl/Cmd+Shift+I`) or in the terminal (`node generateTranslations.js`).
5. Copy the output and paste it into the corresponding language file in the `translations` folder.
6. Make your translation changes and look for any _[TODO]_ messages in the file.
7. Commit your changes and open a pull request.

## Asset modifications

Any commit that modifies the assets will be marked with emojis accordingly.
| Emoji | Meaning |
| ----- | ------- |
| 🌍 | Language files |
| 🖼️ | Images |
Currently images do not have translations, but there might be translation options in the future.
