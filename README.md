# gold_silver_copper

<p align="center">
  Rust developer building terminal rendering tools, language tooling, roguelikes, and strange runtime systems.
</p>

<p align="center">
  <code>Rust</code> • <code>ratatui</code> • <code>Bevy</code> • <code>WASM</code> • <code>no_std</code> • <code>NLP</code>
</p>

<p align="center">
  <a href="https://grift.rs">Website</a>
  ·
  <a href="https://github.com/gold-silver-copper">Profile</a>
  ·
  <a href="https://github.com/gold-silver-copper?tab=repositories">All repositories</a>
</p>

I mostly build in Rust, usually somewhere in the overlap between terminal UI, software rendering, procedural text generation, embedded-friendly interpreters, and game-adjacent experiments.

## Ratatui and Terminal Rendering

- [`egui_ratatui`](https://github.com/gold-silver-copper/egui_ratatui): runs full Ratatui interfaces inside `egui`, so terminal-style apps can ship as native GUI apps or WASM browser apps.
- [`soft_ratatui`](https://github.com/gold-silver-copper/soft_ratatui): a fast software renderer for Ratatui with no GPU requirement, multiple font backends, and portable pixel output.
- [`bevy_ratatui`](https://github.com/ratatui/bevy_ratatui): upstream Ratatui + Bevy ecosystem work.
- [`bracket_ratatui`](https://github.com/gold-silver-copper/bracket_ratatui): `bracket-lib` meets `ratatui`.
- [`gold-silver-copper.github.io`](https://github.com/gold-silver-copper/gold-silver-copper.github.io): live browser demos for terminal UI experiments.

## NLP and Language Tooling

- [`english`](https://github.com/gold-silver-copper/english): a compact, fast English inflection library for procedural text generation.
- [`botanical-latin`](https://github.com/gold-silver-copper/botanical-latin): a decliner / conjugator / inflector for classical and botanical Latin.
- [`chinese`](https://github.com/gold-silver-copper/chinese): Chinese language tooling and experiments.
- [`interslavic-rs`](https://github.com/gold-silver-copper/interslavic-rs): Rust work around Interslavic language tooling.
- [`ruthenian`](https://github.com/gold-silver-copper/ruthenian): Ruthenian language and NLP experiments.
- [`to_fraktur`](https://github.com/gold-silver-copper/to_fraktur): a tiny zero-dependency Rust library that converts ASCII text into Fraktur Unicode.

## Runtime and Language Design

- [`grift`](https://github.com/gold-silver-copper/grift): a `no_std`, `no_alloc`, `no_unsafe` Lisp for bare-metal devices with first-class operatives, first-class environments, and tail-call optimization.
- [`grift.rs`](https://grift.rs): the project site with examples and documentation.

## Games and Interactive Experiments

- [`Textual-Multiplayer-Roguelike`](https://github.com/gold-silver-copper/Textual-Multiplayer-Roguelike): a multiplayer roguelike experiment built with Textual TUI and Socket.IO.
- [`octopus`](https://github.com/gold-silver-copper/octopus), [`mud`](https://github.com/gold-silver-copper/mud), [`fps`](https://github.com/gold-silver-copper/fps), [`graphgame`](https://github.com/gold-silver-copper/graphgame): game, simulation, and interface experiments.

## What You Will Find Here

- Rust-first projects with a bias toward performance, portability, and unusual interfaces.
- Terminal UI work that escapes the terminal and shows up in browsers, game engines, and software renderers.
- Language tooling for English, Latin, Slavic languages, and procedural text generation.
