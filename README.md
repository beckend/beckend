# Linken Quy Dinh

Rust and systems engineer. I contribute upstream to Rust, storage, and developer-tooling
projects, and ship small CLI and library tools of my own.

## Upstream contributions

Across the GitHub search API the account `beckend` has authored **62 pull requests**:
**33 merged** upstream, **7 open**, and 22 closed without merging. The open set includes
3 pull requests to upstream projects; the remaining 4 are opened against my own forks.
Every entry below is a pull request I authored to a project I do not maintain, grouped by
target project. Merged status was verified against the REST API at the time of writing.

### Rust

- [smol-rs/event-listener#114](https://github.com/smol-rs/event-listener/pull/114) —
  `add method total_listeners() when feature std` (merged 2024-01-25)
- [fjall-rs/fjall#67](https://github.com/fjall-rs/fjall/pull/67) —
  `Feature: Config::temporary` (merged 2024-07-19)
- [SeaQL/sea-query#550](https://github.com/SeaQL/sea-query/pull/550) —
  `add Cow<str> conversion to Value` (merged 2022-12-15)
- [FyroxEngine/Fyrox#128](https://github.com/FyroxEngine/Fyrox/pull/128) —
  `WASM start game by user interaction to enable sound` (merged 2021-06-23)

### Systems, filesystems and platform

- [lalinsky/zio#608](https://github.com/lalinsky/zio/pull/608) —
  `fix: pass real environment to Threaded io for process spawning` (merged 2026-07-24)
- [al8n/fs4#24](https://github.com/al8n/fs4/pull/24) —
  `feature: add support for crate fs_err` (merged 2024-07-27)
- [blazzy/podman-rest-client#7](https://github.com/blazzy/podman-rest-client/pull/7) —
  `Fix: Config::guess() Linux Unix socket path.` (merged 2024-07-23)
- [emersion/xdg-desktop-portal-wlr#235](https://github.com/emersion/xdg-desktop-portal-wlr/pull/235) —
  `add Hyprland to wlr.portal` (merged 2022-09-11)

### Rust web stack

- [maxcountryman/tower-sessions#19](https://github.com/maxcountryman/tower-sessions/pull/19) —
  `README: production notes, db(s) cleaning` (merged 2023-10-01)
- [maxcountryman/axum-login#31](https://github.com/maxcountryman/axum-login/pull/31) —
  `expose sqlx_store::SqlxStore` (merged 2022-12-09)

### Terminal and desktop

- [wezterm/wezterm#7366](https://github.com/wezterm/wezterm/pull/7366) —
  `Fix: config max_fps` (merged 2025-11-11)
- [AvengeMedia/DankMaterialShell#2042](https://github.com/AvengeMedia/DankMaterialShell/pull/2042) —
  `fix(wallpaper): fix multi-monitor cycling not working` (merged 2026-03-20)
- [AvengeMedia/DankMaterialShell#1169](https://github.com/AvengeMedia/DankMaterialShell/pull/1169) —
  `add seconds to wallpaper cycling` (merged 2025-12-27)

### Go

- [gookit/config#51](https://github.com/gookit/config/pull/51) —
  `option ParseEnv add support for nested keys` (merged 2021-05-18)

### TypeScript and JavaScript

Earlier contributions to the TypeScript and JavaScript ecosystem, all merged:

- [DefinitelyTyped/DefinitelyTyped#11899](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/11899),
  [#11935](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/11935),
  [#11612](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/11612),
  [#11614](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/11614)
- [tajo/ladle#126](https://github.com/tajo/ladle/pull/126),
  [#111](https://github.com/tajo/ladle/pull/111)
- [algolia/faux-jax#23](https://github.com/algolia/faux-jax/pull/23),
  [#22](https://github.com/algolia/faux-jax/pull/22)
- [jurassiscripts/velociraptor#43](https://github.com/jurassiscripts/velociraptor/pull/43)
- [staylor/react-helmet-async#63](https://github.com/staylor/react-helmet-async/pull/63)
- [kulshekhar/ts-jest#1135](https://github.com/kulshekhar/ts-jest/pull/1135)
- [cssinjs/css-vendor#108](https://github.com/cssinjs/css-vendor/pull/108)
- [ctrlplusb/react-sizeme#167](https://github.com/ctrlplusb/react-sizeme/pull/167)
- [googleapis/gaxios#26](https://github.com/googleapis/gaxios/pull/26)
- [restify/node-restify#1568](https://github.com/restify/node-restify/pull/1568)
- [roylee0704/react-flexbox-grid#136](https://github.com/roylee0704/react-flexbox-grid/pull/136)
- [mfellner/koa-router-rx#6](https://github.com/mfellner/koa-router-rx/pull/6)
- [react-toolbox/react-toolbox#1141](https://github.com/react-toolbox/react-toolbox/pull/1141)
- [redux-observable/redux-observable#139](https://github.com/redux-observable/redux-observable/pull/139)

### Open upstream pull requests

- [containerd/containerd#13571](https://github.com/containerd/containerd/pull/13571) —
  `remotes/docker: activity-based timeout for blob transfers`
- [niri-wm/niri#3838](https://github.com/niri-wm/niri/pull/3838) —
  `feat(animations): add border color crossfade and gradient angle rotation`
- [wefoxplatform/rustainers#65](https://github.com/wefoxplatform/rustainers/pull/65) —
  `fix: nerdctl 2.2`

## Projects

- [email-validate-rs](https://github.com/beckend/email-validate-rs) — a multithreaded Rust
  CLI for email deliverability checks, published to crates.io as
  [`email-validate`](https://crates.io/crates/email-validate) (v0.1.12).
- [fjall-fs-performance](https://github.com/beckend/fjall-fs-performance) — disk
  persistence benchmarks for `fjall` and `redb`.
- [go-config](https://github.com/beckend/go-config) — ordered, environment-substituted
  config file loading into a validated Go struct.