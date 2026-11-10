# Contributing to the episode archive

## Layout convention

- `contributors/<handle>/` holds one directory per published episode.
- Episode directories are named `ep-<nnn>-<slug>`.
- A contributor directory may also contain **reserved structural directories**:
  `kit`, `templates`, `_shared`, and `archive-index`.
  These hold reusable production material and indexes. They are *never*
  published episodes and must never be catalogued.
- Resource folders nested inside an episode (for example `assets/`) belong to
  that episode and are not separate episodes.
- Some contributors keep `manifest.yml`, a plain list of their episode
  directory names. Where present, the manifest is authoritative for that
  contributor.

## Contributor names

The catalog records contributors by display name, not by their folder handle. See `CONTRIBUTORS.json` for the canonical mapping.

## Published counts

`reports/quarterly.md` carries the authoritative number of episodes published to date.
