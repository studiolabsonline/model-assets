# Adding a model

Every model here backs a public claim, so provenance is a requirement rather than a nicety.

## Checklist

- [ ] The upstream license permits **commercial use** and **derivatives**. Both, explicitly.
- [ ] You have read the license **at the source**, not a directory label or a third-party
      re-host. A re-hosted file relabeled by someone downstream is the exact failure that
      cost us a published asset once already.
- [ ] The full chain from original author to the file you have is **establishable**. If you
      cannot write a correct attribution because a link in the chain is unknown, stop. An
      unknowable chain is a reason to pick a different model, not to guess.
- [ ] `source/` holds unmodified upstream bytes with original filenames.
- [ ] `source/UPSTREAM.md` records where it came from, **the retrieval date**, and the
      license as of that date.
- [ ] The root `README.md` model table has a row for it.

## What this repository does not assert

Nothing here claims a particular tool produced a file. If a caption or README would need to
say "exported by X" to make its point, that claim has to be earned separately.
