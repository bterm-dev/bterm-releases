# bterm-releases

Pre-built binaries for [bterm](https://bterm.dev) — the remote-controlled terminal.

This repository only hosts **release artifacts** (no source). Grab the latest
from the [Releases](https://github.com/bterm-dev/bterm-releases/releases) page.

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
