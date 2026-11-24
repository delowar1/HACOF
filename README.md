# HACOF reproducibility package - submission edition

This anonymous peer-review artefact is aligned byte-for-byte with the manuscript source package.
The exact manuscript source and PDF are included under `paper/`. Major numerical claims are mapped
to evidence in `data/CLAIMS_REGISTRY.csv`, and `data/DATA_COVERAGE.csv` distinguishes raw-supported
results from historical summary-only results.

Run:
```bash
python -m pip install -r analysis/requirements.txt
make validate
make stats
make figures
make sources
```

No public repository URL or DOI is asserted in this review package. The ZIP supplied with the
journal submission is the reviewer-facing artefact. No identifiable patient data or private MSP keys are included.

`SHA256SUMS.txt` contains one entry for every other file in the archive and intentionally does not hash itself.
