
# WA Predictors

## Data locations in s3 bucket

| Rasters | Tiles | Notes |
|------|----------------|--------|
|`dsm-wa/dsm-wa-gpu/covariates/`|`dsm-wa/dsm-wa-gpu/tiles_wa_500_fast_tiler/` | 2026 Current covariate set. Includes **FathomDEM**. |
|`covariates/` | `dsm-wa/dsm-wa-gpu/tiles_wa_new_500` | 2025 Used for **RVG v1 models** and early soil DSM products. Includes **FABDEM**. |
| `karen-nimbus/WA_state_covs/` | `dsm-wa/dsm-wa-gpu/tiles_wa_500` | 2024 and earlier. Legacy covariate set, primarily based on **SLGA** predictors with some WA updates. Older covariate development files here.  |

**Note:** 2025 Relief predictors were based on **FABDEM**, while current production Relief covariates use **FathomDEM**.

