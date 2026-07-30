# GeoProspect Model Release Policy

## Stage 0

No trained model artefact, checkpoint, score, ranked target, prospectivity raster or predictive-performance claim may be published.

## Future release prerequisites

A future model release must have:

1. Explicit authorisation from the central `Lukeyone/geoprospect` repository.
2. A completed model card.
3. Versioned and checksum-identified training/evaluation inputs.
4. A spatially separated evaluation design and leakage controls.
5. Reproducible code and environment references.
6. Licence and attribution clearance for every distributed artefact.
7. Documented limitations, exploration bias and prohibited uses.
8. Integrity checksums and a deprecation/rollback path.

## Blocked release conditions

Release is prohibited when evidence is incomplete, a mandatory gate is unresolved, licensing is ambiguous, performance claims are not reproducible, or the artefact could be mistaken for drilling or investment advice.
