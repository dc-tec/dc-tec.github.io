# OpenBao Operator documentation continuity

This user site redirects old OpenBao Operator documentation URLs to `https://docs.kubebao.org/`.
The old paths live under `openbao-operator/`. GitHub Pages publishes the `main` branch at `/`.

The frozen source is the operator repository's `gh-pages` commit `719664fb17b3efe1af8161f1425ec0727fc3e446`.
The 856 HTML pages use browser redirects. JavaScript preserves query strings and fragments;
each page also provides a visible link and a no-script refresh. These are not HTTP 301 redirects.
All 2,132 non-HTML files remain byte-for-byte unchanged, including historical edge and nightly
manifests, metadata, checksums, and signature bundles. These channel files are frozen historical artifacts.

The custom 404 page forwards unknown `/openbao-operator/` paths and retains HTTP 404.
It does not redirect unrelated project paths. Preserve machine-readable files at their original paths.
Do not add a custom domain to this user site or recreate the old operator repository name.

If the destination becomes unavailable, restore the frozen mirror from the earlier site commit.
