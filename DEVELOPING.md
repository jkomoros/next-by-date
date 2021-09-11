## Installing (development mode)

Open Obsidian. Go to Settings > Community Plugins. Turn off Safe Mode, accepting the scary option in the dialog.

Within your filesytem, navigate to `$VAULT_DIR/.obsidian/plugins/` (creating the plugins directory if it doesn't exist).

`git clone` this repo.

Restart Obsidian and go to Community Plugins and enable `Next File By Date`.

## Publishing a new release

See https://github.com/obsidianmd/obsidian-sample-plugin#releasing-new-releases

- Update manifest.json with new release number
- Add an entry to versions.json with min Obsidian version for this release
- Create a new tag with version number: `git tag 0.1.1`
- Push tags: `git push --tags`