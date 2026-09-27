# AMASS

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FAMASS-181717?logo=github)](https://github.com/biometric-community/AMASS)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://amass.is.tue.mpg.de/)

**AMASS** — tbiom catalog packaging for `amass` (pose3d; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/AMASS
- **Upstream source**: https://amass.is.tue.mpg.de/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `amass` |
| Category | `pose3d` |
| Access | `register` |
| Upstream homepage | https://amass.is.tue.mpg.de/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Archive of Motion Capture as Surface Shapes (SMPL); register at MPI.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/AMASS.git
cd AMASS
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_amass.sh
```

Place licensed archives under `projects/datasets/amass/` (gitignored).

## Dataset structure

```text
AMASS/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://amass.is.tue.mpg.de/
- Packaging: https://github.com/biometric-community/AMASS/issues
