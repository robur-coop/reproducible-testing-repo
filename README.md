# Reproducible testing opam repository

This opam repository contains some simple opam packages which do not require the OCaml compiler, mainly for testing the reproducibility tooling for opam.

- [`env`](packages/env.0.0.0) captures the environment variables in a file which is installed,
- [`fail-random`](packages/fail-random.0.0.0) is a non-reproducible package which captures output from `/dev/random` into a file,
- [`fail-timestamp`](packages/fail-timestamp.0.0.0) is a non-reproducible package which records the current timestamp,
- [`nothing`](packages/nothing.0.0.0) installs nothing,
- [`ocaml`](packages/ocaml.0.0.0) is an empty package to avoid bootstrapping an OCaml compiler,
- [`something`](packages/something.0.0.0) installs a single file,
- [`timestamp`](packages/timestamp.0.0.0) respects `SOURCE_DATE_EPOCH` and records a timestamp.
