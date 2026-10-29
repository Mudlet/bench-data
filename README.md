# bench-data

Large inputs for Mudlet's benchmarks, kept out of the main repository. Each dataset is a release asset; the
benchmark that uses it pins the SHA-256.

| Release | Asset | Used by |
|---|---|---|
| `svof-1` | `SvofBench.mpackage` | [`test/svof-replay`](https://github.com/Mudlet/Mudlet/tree/development/test/svof-replay) |

`SvofBench.mpackage` is a replayed Achaea session with the svof curing system and its settings. Lines svof
does not react to are filler and names are stand-ins; see the benchmark's README for how it was built.
