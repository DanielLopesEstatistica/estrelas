<sub>**Datas:** pasta 17/05/2023 · código 17/05/2023 (`sdss_ddr14.csv`)</sub>

# Estrelas e objetos SDSS

Diagrama HR com amostra de **6 classes** e clusterização em levantamento **SDSS**.

## O que o código faz

`Estrelas.Rmd`:

1. **`6 class csv.csv`**: diagrama temperatura–luminosidade (cor/classe espectral).
2. **`sdss_ddr14.csv`**: scatter `u-g` vs log(redshift); **k-means** (k=3) comparado a `class` (Quasar/Galaxy/Star).

## Dados

| Arquivo | Descrição |
|---------|-----------|
| `6 class csv.csv` | Estrelas modelo por classe |
| `sdss_ddr14.csv` | Recorte SDSS DR14 (grande; fotometria + classificação) |

## Como rodar

Knit `Estrelas.Rmd` (`tidyverse`).