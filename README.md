A lightweight, dependency-free alternative to `torchdata.nodes`, following the same compositing idea.

No loading/saving of states (for now), to avoid memory issues. Support `set_epoch()` instead, to continue training from
a given epoch.

See `tests` for usage examples.