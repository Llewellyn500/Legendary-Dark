# Publishing Legendary Dark to Zed

Legendary Dark is structured as a Zed theme extension:

```text
Legendary-Dark/
  zed/
    extension.toml
    LICENSE.md
    themes/
      legendary-dark.json
```

The public Zed extension ID is:

```toml
legendary-dark
```

Zed extension IDs cannot be changed after publishing, so keep this value stable.

## Local test

1. Open Zed.
2. Open the command palette.
3. Run `zed: install dev extension`.
4. Select the `zed/` folder inside this repository.
5. Open the theme selector and choose `Legendary Dark`.

## Registry submission

Zed publishes community extensions through pull requests to `zed-industries/extensions`.

From a fork of `https://github.com/zed-industries/extensions`, run:

```sh
git submodule add https://github.com/Llewellyn500/Legendary-Dark.git extensions/legendary-dark
git add extensions/legendary-dark
```

Add this entry to the top-level `extensions.toml`:

```toml
[legendary-dark]
submodule = "extensions/legendary-dark"
path = "zed"
version = "5.0.1"
```

Then run:

```sh
pnpm sort-extensions
```

Open a pull request to `zed-industries/extensions`. After the PR is merged, Zed will package the extension and publish it to the Extension Gallery.
