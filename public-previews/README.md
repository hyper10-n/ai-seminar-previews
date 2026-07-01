# Public Previews

Files under this directory are intended to be externally public through GitHub Pages.

Use unlisted preview IDs:

```text
public-previews/<35+ random chars>/index.html
```

Create a new preview directory:

```bash
make preview-new
```

Put generated HTML and related assets under that preview directory, preferably under `content/`.

Refresh the preview landing page:

```bash
make preview-index ID=<preview-id>
```

Build the GitHub Pages artifact locally:

```bash
make preview-build
```

Publish to the public previews repository:

```bash
make preview-publish ID=<preview-id>
```

The root `public-previews/index.html` intentionally does not list preview IDs.
