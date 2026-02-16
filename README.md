# Datalift Scoop Bucket

## What is Scoop?

A command-line installer for Windows, see more at <https://scoop.sh>

## What is a Bucket?

A bucket is a collection of app manifests that describe how to install a program. This is a third-party bucket providing installable packages for Datalift products and tools on Windows.

See more at <https://github.com/ScoopInstaller/Scoop/wiki/Buckets>

## How do I install packages from here?

```pwsh
scoop bucket add datalift https://github.com/DataliftHQ/scoop-bucket
scoop install datalift/<name>
```

## What packages are available?

With the following commands, you can install the latest generally available (GA) version of each product:

```pwsh
scoop install datalift/admiral
```

Prereleases (including alphas, betas, and release candidates) will not be available in this bucket.
