# bterm-releases

Pre-built binaries for [bterm](https://bterm.dev) — the remote-controlled terminal.

> ⚠️ **bterm is proprietary, closed-source software.**
> This repository hosts only the compiled **release artifacts** — it contains
> **no source code**. The "Source code (zip)" / "Source code (tar.gz)" archives
> that GitHub automatically attaches to every release are generated from this
> repository and contain only this README — **not** bterm's source.

Grab the latest build from the
[Releases](https://github.com/bterm-dev/bterm-releases/releases) page.

## Install

**macOS (Homebrew):**
```sh
brew install bterm-dev/bterm/bterm
```

**Manual (any platform):** download the tarball for your platform from the
latest release, verify with `SHA256SUMS`, and copy the binaries into your
`PATH`:

```sh
tar -xzf bterm-<version>-<target>.tar.gz
sudo install -m755 bterm-<version>-<target>/* /usr/local/bin/
```

## Get started

```sh
bterm login --relay https://relay.bterm.dev   # link this machine (one-time URL)
bterm daemon                                  # start the terminal daemon
```

Then manage your terminals from anywhere at [app.bterm.dev](https://app.bterm.dev).

## License

© 2026 bterm. All rights reserved.

bterm is proprietary software. The binaries distributed here are licensed for
use under the [bterm Terms of Service](https://bterm.dev/terms). No source code
is provided or implied, and no rights to copy, modify, decompile,
reverse-engineer or redistribute are granted except as expressly permitted by
the Terms or by applicable law.
