# arcaverborum.org

Deploy-only repository. GitHub Pages here serves the **latest schema-letter
release** of [arcaverborum/arcaverborum](https://github.com/arcaverborum/arcaverborum)
at <https://arcaverborum.org>.

Nothing is edited here. The workflow downloads the release's sealed site
bundle (`arcaverborum-<release>-site.tar.gz`, explorer code and data built
from the same commit), checks it against the release's `SHA256SUMS`, and
deploys it. It runs hourly and on demand; the deployed release identifier is
published at `/RELEASE`.

The current `master` is served by [arcaverborum/live](https://github.com/arcaverborum/live)
at <https://live.arcaverborum.org>.
