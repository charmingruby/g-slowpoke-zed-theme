To release a new version, open a PR in the [zed-industries/extensions](https://github.com/zed-industries/extensions) repo with:

1. **Update the submodule** — points the extension entry to the latest commit of your theme repo:
   ```sh
   git submodule update --remote extensions/g-slowpoke-zed-theme
   ```

2. **Sync the version** — in `extensions.toml` (central registry), set the `version` for `g-slowpoke-zed-theme` to the same value as the `version` field in your theme's own `extension.toml` file (e.g. `"0.0.1"`).
