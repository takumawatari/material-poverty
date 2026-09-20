# Global assessment of material poverty and inequality

This repository contains data supporting the study “Global assessment of material poverty and inequality”.

Source stock data: [MaterialCities](https://doi.org/10.5281/zenodo.22306604).

## Columns and units

| Column or suffix | Description |
| --- | --- |
| `ADM0_NAME`, `ADM1_NAME`, `ADM2_NAME` | Country and administrative-area names |
| `GID_1`, `GID_2` | GADM administrative-area identifiers |
| `ADM2_area_sq_km` | Administrative-area land area, in km² |
| `GFA` | Gross floor area, in m² |
| `population` | Population, in people |
| `concrete_cap`, `steel_cap` | Residential material stocks, in t/capita |
| `_abs_poor`, `_rel_poor` | Absolute or relative poverty classification (`True` or `False`) |
| `_abs_gap_t`, `_rel_gap_t` | Additional material needed to reach the corresponding threshold, in tonnes |
| `both_`, `either_` | Poverty in both materials (AND) or at least one material (OR) |
| `both_abs_or_rel_poor` | Both materials qualify as poor under the absolute or relative test |
| `either_abs_or_rel_poor` | At least one material qualifies as poor under the absolute or relative test |

## Citation
If you find this repository useful for your work, please cite the associated paper below.
> Watari, T. et al. (xxxx) Global assessment of material poverty and inequality.

If you want to use material stock data, please cite the MaterialCities paper below.
> Fishman, T. et al. (xxxx) MaterialCities dataset: mapping buildings' material stocks and floor area of the world's 1.8 million settlements by structures and functions.
