## Ecnn sphere

#### Article:   <small><strong>Stable equivariant sampling and reconstruction on the sphere</strong>  <a href=""><img src="https://cdn.simpleicons.org/doi/2dd4bf" alt="DOI" height="14" align="absmiddle"></a>  <a href=""><img src="https://cdn.simpleicons.org/zenodo/2dd4bf" alt="Zenodo" height="14" align="absmiddle"></a>  <a href="https://drive.google.com/drive/folders/1Ax4vdLK6-ELBKNW8qakUzxGspDTEMFnf?usp=drive_link"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Google Drive" height="14" align="absmiddle"></a></small>

This repository implements stable weighted sampling and reconstruction for scalar functions and equivariant feature fields on the unit sphere. Scalar cardinal bases are lifted through Levi-Civita parallel transport with SO(2) representation orders m=0,1,2,3. The completed experiments cover 20 deterministic seeds, multiple center sizes, sampling ratios, and spherical point-set families. Scalar diagnostics include cardinal, local Lagrange, spherical-harmonic, regularized kernel, and moving least-squares methods, together with restricted surface-spline tests. A matched eleven-method benchmark evaluates tangent-field reconstruction on rotational and rotational-exponential targets. Numerical diagnostics assess Marcinkiewicz-Zygmund spectral bounds, reconstruction error, conditioning, noise amplification, localization, Hölder regularity, and parameter sensitivity. Equivariant tests measure gauge covariance, co-rotated SO(3) equivariance, fixed-grid error, and transfer across Fibonacci, icospherical, and equirectangular grids. Paired statistical comparisons, confidence intervals, runtime, and peak resident-memory increments characterize accuracy and computational cost.

#### Dependencies

* Python 3.10.19
* numpy 1.26.4
* scipy 1.12.0
* matplotlib 3.10.8
* PyYAML 6.0.2

#### Bash

```bash
docker compose -f docker/compose.yaml build main
docker compose -f docker/compose.yaml run --rm main
```

#### License (MIT)

* Copyright (c) alancampos-ai
* Code released under the MIT License.
