# POGO Studios Archive — Media Companion Repository

This repository contains the canonical media files referenced by the [POGO Studios Archive](https://github.com/POGO-XYZ/POGO-ARCHIVE) — the public, permanent record of physical artworks created by POGO Studios.

Each image here corresponds to a specific archived work, identified by its POGO ID. Filenames match that ID exactly (e.g. `POGO-2024-PO-A.PNG`), so any record in the primary archive can be traced directly to its image with no ambiguity.


## Why this repository exists separately

The POGO Studios Archive deliberately separates verification data from presentation. The primary archive holds the structural record of a work — its ID, its metadata, its cryptographic proofs. This repository holds what that work looks like.

That separation matters because each serves a different purpose. The primary archive is built to remain small, stable, and permanent. This repository is allowed to grow, and its media can be reorganized, re-hosted, or mirrored elsewhere over time without ever affecting the integrity of the verified record itself.


## How images are verified

Each work's SHA-256 hash is computed from the exact original file stored here, as it existed at the time of documentation - recorded in its corresponding entry in the primary archive. That hash is a cryptographic fingerprint, so if a reference image file is ever altered, copied incorrectly, or corrupted, the fingerprint changes, and the hash will no longer match - a discrepancy evident to anyone checking. This means the image itself doesn't need to live in a single permanent location to remain verifiable. What matters is that whatever copy exists, it can still be confirmed against its recorded hash.


## Structure

```
2024/
2025/
2026/
```

Each folder contains the media files for works archived that year, mirroring the archive's own yearly structure.


## License

Licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Share and adapt freely with credit to POGO Studios.


## Related

- [POGO Studios Archive](https://github.com/POGO-XYZ/POGO-ARCHIVE) — the primary record
- [pogostudios.xyz](https://www.pogostudios.xyz) — studio and collection access