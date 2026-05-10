# whatcable has moved to **[usbeehive](https://github.com/abrauchli/usbeehive)** 🐝

This crate was previously published on crates.io as
[`whatcable`](https://crates.io/crates/whatcable). To avoid collisions with the
[original WhatCable repo](https://github.com/darrylmorley/whatcable) by Darryl
Morley, the project has been renamed.

Big thanks to Darryl for the original work!

## Original Project

[WhatCable (macOS)](https://github.com/darrylmorley/whatcable) by Darryl
Morley — the macOS menu-bar app this Rust port is derived from.

## New home

- **crates.io:** [`usbeehive`](https://crates.io/crates/usbeehive)
- **GitHub:** <https://github.com/abrauchli/usbeehive>
- **Install:** `cargo install usbeehive`

The full git history is preserved at the new repo. This repository is
archived and read-only.

## What changed

| Old (`whatcable` 0.4.x) | New (`usbeehive` 0.5.x) |
| --- | --- |
| Crate `whatcable` | Crate `usbeehive` |
| CLI `whatcable` | CLI `usbeehive` |
| Daemon `whatcabled` | Daemon `usbeehived` |
| D-Bus `org.whatcable.Devices1` | D-Bus `org.usbeehive.Devices1` |
| `github.com/abrauchli/whatcable` | `github.com/abrauchli/usbeehive` |

The library API is otherwise unchanged from `whatcable 0.4.0` plus the
new D-Bus daemon. See the
[`usbeehive` CHANGELOG](https://github.com/abrauchli/usbeehive/blob/master/CHANGELOG.md)
for full migration notes.

## Credits

usbeehive (and `whatcable` before it) is a Linux port of
[WhatCable](https://github.com/darrylmorley/whatcable) — a macOS menu-bar
app by [Darryl Morley](https://github.com/darrylmorley). The Rust rewrite
was forked from
[Zetaphor/whatcable-linux](https://github.com/Zetaphor/whatcable-linux).

## License

[MIT](LICENSE)
