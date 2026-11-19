# antimony-sbml-rs

Pure-Rust Antimony and SBML I/O, copied from
[sys-bio/PathwayDesigner-rs](https://github.com/sys-bio/PathwayDesigner-rs) (`crates/antimony`, `crates/sbml-io`;
upstream commit in `UPSTREAM`) for use in Tellurium Nitro.

- `crates/antimony` (package `antimony-rs`, library `antimony`): read and write Antimony, convert it to SBML L3V2.
- `crates/sbml-io`: read and write SBML Levels 2 and 3 (core, Layout, Render) as plain Rust data.

See each crate's README for usage. Licensed MIT OR Apache-2.0 (crates), original work by Herbert Sauro (`LICENSE`).
