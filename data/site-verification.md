# Verification against stockanalysis.com

- Tickers sampled: **91**
- Values compared: **63,261**
- **Matching the site: 40,382 (63.83%)**
- Mismatched: 22,879
- Per-share rows on the ADS basis (expected, see header): 69
- Present one side only: 3,326

## By statement

| statement | matched | mismatched | match rate |
|---|---|---|---|
| income_statement | 9,876 | 7,418 | 57.11% |
| balance_sheet | 7,018 | 9,187 | 43.31% |
| cash_flow | 5,465 | 5,789 | 48.56% |
| ratios | 18,023 | 485 | 97.38% |

## Tickers with mismatches

| ticker | statement | cells | examples |
|---|---|---|---|
| INFY | balance_sheet | 269 | Cash & Equivalents 2026-03-31: stored 222010.0 vs site 2341.0; Cash & Equivalents 2025-03-31: stored 244525.0 vs site 2861.0; Cash & Equivalents 2024-03-31: stored 147806.0 vs site 1773.0; Cash & Equivalents 2023-03-31: stored 121710.0 vs site 1481.0 |
| TLV:SCOP | balance_sheet | 211 | Cash & Equivalents 2025-12-31: stored 142.0 vs site 139.9; Cash & Equivalents 2024-12-31: stored 79.0 vs site 77.55; Cash & Equivalents 2023-12-31: stored 97.0 vs site 95.74; Cash & Equivalents 2022-12-31: stored 151.0 vs site 148.43 |
| TLV:BEZQ | balance_sheet | 205 | Cash & Equivalents 2025-12-31: stored 216.0 vs site 212.6; Cash & Equivalents 2024-12-31: stored 263.0 vs site 259.22; Cash & Equivalents 2023-12-31: stored 189.0 vs site 186.15; Cash & Equivalents 2022-12-31: stored 249.0 vs site 245.0 |
| TLV:HAMAT | balance_sheet | 200 | Cash & Equivalents 2025-12-31: stored 9.0 vs site 8.47; Cash & Equivalents 2024-12-31: stored 4.0 vs site 4.09; Cash & Equivalents 2023-12-31: stored 11.0 vs site 10.83; Cash & Equivalents 2022-12-31: stored 18.0 vs site 17.28 |
| INFY | income_statement | 199 | Revenue 2026-03-31: stored 1884462.0 vs site 20158.0; Revenue 2025-03-31: stored 1647573.0 vs site 19277.0; Revenue 2024-03-31: stored 1547422.0 vs site 18562.0; Revenue 2023-03-31: stored 1496676.0 vs site 18212.0 |
| TLV:AVIV | balance_sheet | 198 | Cash & Equivalents 2024-12-31: stored 17.0 vs site 16.44; Cash & Equivalents 2023-12-31: stored 3.0 vs site 2.86; Cash & Equivalents 2020-12-31: stored 6.0 vs site 6.23; Cash & Equivalents 2019-12-31: stored 8.0 vs site 7.89 |
| TLV:ISTA | balance_sheet | 194 | Cash & Equivalents 2025-12-31: stored 61.0 vs site 59.72; Cash & Equivalents 2024-12-31: stored 12.0 vs site 12.28; Cash & Equivalents 2021-12-31: stored 31.0 vs site 30.18; Cash & Equivalents 2017-12-31: stored 14.0 vs site 13.4 |
| TLV:SRFT | balance_sheet | 192 | Cash & Equivalents 2025-12-31: stored 17.0 vs site 16.43; Cash & Equivalents 2024-12-31: stored 11.0 vs site 10.36; Cash & Equivalents 2023-12-31: stored 22.0 vs site 21.62; Cash & Equivalents 2022-12-31: stored 46.0 vs site 45.18 |
| INFY | cash_flow | 192 | Net Income 2026-03-31: stored 294740.0 vs site 3313.0; Net Income 2025-03-31: stored 270251.0 vs site 3158.0; Net Income 2024-03-31: stored 264184.0 vs site 3167.0; Net Income 2023-03-31: stored 245145.0 vs site 2981.0 |
| TLV:ORON | balance_sheet | 185 | Cash & Equivalents 2025-12-31: stored 51.0 vs site 44.26; Cash & Equivalents 2024-12-31: stored 35.0 vs site 34.04; Cash & Equivalents 2023-12-31: stored 36.0 vs site 35.24; Cash & Equivalents 2022-12-31: stored 39.0 vs site 38.52 |
| TLV:TAYA | balance_sheet | 185 | Cash & Equivalents 2025-12-31: stored 6.0 vs site 6.37; Cash & Equivalents 2023-12-31: stored 3.0 vs site 2.82; Cash & Equivalents 2022-12-31: stored 9.0 vs site 8.55; Cash & Equivalents 2021-12-31: stored 8.0 vs site 8.12 |
| TLV:BEZQ | income_statement | 183 | Revenue 2025-12-31: stored 2924.0 vs site 2877.0; Revenue 2024-12-31: stored 2985.0 vs site 2937.0; Revenue 2023-12-31: stored 3058.0 vs site 3010.0; Revenue 2022-12-31: stored 3034.0 vs site 2971.0 |
| TLV:BRMG | balance_sheet | 182 | Cash & Equivalents 2025-12-31: stored 3.0 vs site 2.73; Cash & Equivalents 2024-12-31: stored 3.0 vs site 2.92; Cash & Equivalents 2023-12-31: stored 5.0 vs site 4.66; Cash & Equivalents 2022-12-31: stored 3.0 vs site 2.63 |
| TLV:SANO1 | balance_sheet | 181 | Cash & Equivalents 2025-12-31: stored 99.0 vs site 97.4; Cash & Equivalents 2024-12-31: stored 121.0 vs site 118.63; Cash & Equivalents 2023-12-31: stored 176.0 vs site 172.87; Cash & Equivalents 2022-12-31: stored 110.0 vs site 108.28 |
| TLV:ORON | income_statement | 175 | Revenue 2025-12-31: stored 686.0 vs site 675.23; Revenue 2024-12-31: stored 625.0 vs site 615.01; Revenue 2023-12-31: stored 510.0 vs site 502.15; Revenue 2022-12-31: stored 406.0 vs site 186.84 |
| TLV:BRND | balance_sheet | 173 | Cash & Equivalents 2025-12-31: stored 23.0 vs site 18.36; Cash & Equivalents 2023-12-31: stored 7.0 vs site 6.54; Cash & Equivalents 2022-12-31: stored 4.0 vs site 4.27; Cash & Equivalents 2021-12-31: stored 5.0 vs site 5.28 |
| TLV:ORAD | balance_sheet | 170 | Cash & Equivalents 2025-12-31: stored 1.0 vs site 0.9; Cash & Equivalents 2024-12-31: stored 1.0 vs site 1.39; Cash & Equivalents 2023-12-31: stored 1.0 vs site 1.15; Cash & Equivalents 2022-12-31: stored 2.0 vs site 2.33 |
| TLV:ACCL | balance_sheet | 168 | Cash & Equivalents 2024-12-31: stored 8.0 vs site 7.65; Cash & Equivalents 2023-12-31: stored 3.0 vs site 3.43; Cash & Equivalents 2022-12-31: stored 7.0 vs site 6.76; Cash & Equivalents 2021-12-31: stored 10.0 vs site 9.64 |
| AEG | income_statement | 166 | Revenue Growth 2025-12-31: stored -1.25 vs site -5.09; Revenue Growth 2024-12-31: stored 2.73 vs site -0.66; Revenue Growth 2023-12-31: stored -12.03 vs site -9.48; Revenue Growth 2022-12-31: stored -68.12 vs site -69.28 |
| TLV:DIPL | balance_sheet | 160 | Cash & Equivalents 2024-12-31: stored 26.0 vs site 25.66; Cash & Equivalents 2023-12-31: stored 27.0 vs site 26.32; Cash & Equivalents 2022-12-31: stored 35.0 vs site 34.04; Cash & Equivalents 2021-12-31: stored 25.0 vs site 24.6 |
| TLV:SCOP | income_statement | 159 | Revenue 2025-12-31: stored 696.0 vs site 684.48; Revenue 2024-12-31: stored 606.0 vs site 596.41; Revenue 2023-12-31: stored 550.0 vs site 541.51; Revenue 2022-12-31: stored 553.0 vs site 544.62 |
| TLV:ISTA | income_statement | 159 | Revenue 2025-12-31: stored 197.0 vs site 194.03; Revenue 2024-12-31: stored 140.0 vs site 138.02; Revenue 2023-12-31: stored 136.0 vs site 134.29; Revenue 2022-12-31: stored 125.0 vs site 122.65 |
| TLV:KLIL | balance_sheet | 158 | Cash & Equivalents 2025-12-31: stored 23.0 vs site 22.68; Cash & Equivalents 2023-12-31: stored 20.0 vs site 19.64; Cash & Equivalents 2021-12-31: stored 17.0 vs site 16.76; Cash & Equivalents 2020-12-31: stored 30.0 vs site 29.38 |
| TLV:MGOR | balance_sheet | 157 | Property, Plant & Equipment 2025-12-31: stored 2.0 vs site 2228.0; Property, Plant & Equipment 2024-12-31: stored 2.0 vs site 1786.0; Property, Plant & Equipment 2023-12-31: stored 1499.0 vs site 1476.0; Property, Plant & Equipment 2022-12-31: stored 14.0 vs site 1188.0 |
| TLV:ACRO | income_statement | 157 | Revenue 2025-12-31: stored 205.0 vs site 217.04; Revenue 2023-12-31: stored 302.0 vs site 298.4; Revenue 2022-12-31: stored 291.0 vs site 306.01; Revenue 2021-12-31: stored 161.0 vs site 177.52 |
| TLV:ACCL | income_statement | 156 | Revenue 2025-12-31: stored 150.0 vs site 147.68; Revenue 2024-12-31: stored 121.0 vs site 119.49; Revenue 2023-12-31: stored 92.0 vs site 90.74; Revenue 2022-12-31: stored 70.0 vs site 68.87 |
| TLV:DIPL | income_statement | 155 | Revenue 2025-12-31: stored 1261.0 vs site 1241.0; Revenue 2024-12-31: stored 1195.0 vs site 1176.0; Revenue 2023-12-31: stored 1133.0 vs site 1115.0; Revenue 2022-12-31: stored 977.0 vs site 961.81 |
| TLV:ELWS | balance_sheet | 153 | Cash & Equivalents 2025-12-31: stored 8.0 vs site 7.45; Cash & Equivalents 2023-12-31: stored 18.0 vs site 17.8; Cash & Equivalents 2022-12-31: stored 23.0 vs site 22.35; Cash & Equivalents 2021-12-31: stored 42.0 vs site 41.13 |
| IP | income_statement | 152 | Gross Profit 2024-12-31: stored 4438.0 vs site 4515.0; Selling, General & Admin 2025-12-31: stored 4260.0 vs site 3828.0; Selling, General & Admin 2024-12-31: stored 3002.0 vs site 2713.0; Selling, General & Admin 2023-12-31: stored 2624.0 vs site 2551.0 |
| TLV:ARPT | balance_sheet | 151 | Property, Plant & Equipment 2025-12-31: stored 106.0 vs site 26.41; Property, Plant & Equipment 2023-12-31: stored 28.0 vs site 27.49; Property, Plant & Equipment 2022-12-31: stored 24.0 vs site 23.23; Property, Plant & Equipment 2021-12-31: stored 23.0 vs site 22.53 |
| TLV:SANO1 | income_statement | 149 | Revenue 2025-12-31: stored 753.0 vs site 740.53; Revenue 2024-12-31: stored 764.0 vs site 751.84; Revenue 2023-12-31: stored 715.0 vs site 704.07; Revenue 2022-12-31: stored 643.0 vs site 632.37 |
| TLV:SHVA | balance_sheet | 149 | Cash & Equivalents 2025-12-31: stored 5.0 vs site 5.14; Cash & Equivalents 2024-12-31: stored 15.0 vs site 14.56; Cash & Equivalents 2023-12-31: stored 6.0 vs site 5.9; Cash & Equivalents 2022-12-31: stored 13.0 vs site 12.54 |
| TLV:ACRO | balance_sheet | 148 | Cash & Equivalents 2025-12-31: stored 173.0 vs site 168.22; Cash & Equivalents 2024-12-31: stored 144.0 vs site 142.05; Cash & Equivalents 2023-12-31: stored 156.0 vs site 153.72; Cash & Equivalents 2022-12-31: stored 153.0 vs site 150.35 |
| TLV:SRFT | income_statement | 146 | Revenue 2025-12-31: stored 137.0 vs site 135.16; Revenue 2024-12-31: stored 162.0 vs site 159.19; Revenue 2023-12-31: stored 100.0 vs site 97.45; Revenue 2022-12-31: stored 158.0 vs site 155.24 |
| AN | balance_sheet | 146 | Accounts Receivable 2025-12-31: stored 948.0 vs site 424.0; Accounts Receivable 2024-12-31: stored 1066.0 vs site 452.7; Accounts Receivable 2023-12-31: stored 1040.0 vs site 434.7; Accounts Receivable 2022-12-31: stored 859.0 vs site 357.0 |
| TLV:LUMI | balance_sheet | 145 | Cash & Equivalents 2025-12-31: stored 44317.0 vs site 49055.0; Cash & Equivalents 2024-12-31: stored 52355.0 vs site 48461.0; Cash & Equivalents 2023-12-31: stored 34428.0 vs site 33880.0; Cash & Equivalents 2022-12-31: stored 60691.0 vs site 59724.0 |
| E | income_statement | 144 | Revenue Growth 2019-12-31: stored -7.66 vs site -7.32; Revenue Growth 2018-12-31: stored 8.4 vs site 12.99; Revenue Growth 2016-12-31: stored -22.91 vs site -21.59; Cost of Revenue 2019-12-31: stored 69561.0 vs site 58383.0 |
| TLV:HAMAT | income_statement | 143 | Revenue 2025-12-31: stored 321.0 vs site 315.47; Revenue 2024-12-31: stored 298.0 vs site 293.29; Revenue 2023-12-31: stored 325.0 vs site 319.84; Revenue 2022-12-31: stored 357.0 vs site 351.49 |
| INDV | income_statement | 143 | Cost of Revenue 2025-12-31: stored 246.0 vs site 198.0; Cost of Revenue 2024-12-31: stored 231.0 vs site 190.0; Cost of Revenue 2021-12-31: stored -127.0 vs site 127.0; Cost of Revenue 2020-12-31: stored -97.0 vs site 92.0 |
| TLV:BRMG | income_statement | 142 | Revenue 2025-12-31: stored 145.0 vs site 142.38; Revenue 2024-12-31: stored 135.0 vs site 133.17; Revenue 2023-12-31: stored 156.0 vs site 153.07; Revenue 2022-12-31: stored 174.0 vs site 170.8 |
| TLV:ELAL | income_statement | 141 | Revenue 2025-12-31: stored 3763.0 vs site 3476.0; Revenue Growth 2025-12-31: stored 9.64 vs site 1.28; Cost of Revenue 2025-12-31: stored 2400.0 vs site 2191.0; Cost of Revenue 2024-12-31: stored 2469.0 vs site 1996.0 |
| TLV:AYAL | income_statement | 140 | Revenue Growth 2025-12-31: stored 26.84 vs site 9.13; Revenue Growth 2024-12-31: stored 19.32 vs site 59.18; Revenue Growth 2023-12-31: stored 55.79 vs site 59.82; Revenue Growth 2021-12-31: stored 26.68 vs site 24.41 |
| TLV:ICON | income_statement | 140 | Revenue 2025-12-31: stored 544.0 vs site 535.33; Revenue 2024-12-31: stored 537.0 vs site 528.14; Revenue 2023-12-31: stored 485.0 vs site 477.46; Revenue 2022-12-31: stored 511.0 vs site 502.87 |
| TLV:FIBIH | balance_sheet | 139 | Cash & Equivalents 2025-12-31: stored 26382.0 vs site 27489.0; Cash & Equivalents 2024-12-31: stored 25932.0 vs site 25431.0; Cash & Equivalents 2023-12-31: stored 23140.0 vs site 22339.0; Cash & Equivalents 2022-12-31: stored 19197.0 vs site 18327.0 |
| TLV:AYAL | balance_sheet | 139 | Cash & Equivalents 2025-12-31: stored 284.0 vs site 153.49; Cash & Equivalents 2024-12-31: stored 251.0 vs site 206.71; Cash & Equivalents 2023-12-31: stored 138.0 vs site 179.52; Cash & Equivalents 2022-12-31: stored 245.0 vs site 151.28 |
| TLV:BEZQ | cash_flow | 138 | Net Income 2025-12-31: stored 476.0 vs site 468.51; Net Income 2024-12-31: stored 360.0 vs site 354.44; Net Income 2023-12-31: stored 399.0 vs site 393.12; Net Income 2022-12-31: stored 336.0 vs site 330.63 |
| JHX | balance_sheet | 137 | Cash & Equivalents 2026-03-31: stored 344.0 vs site 269.2; Cash & Equivalents 2025-03-31: stored 606.0 vs site 562.7; Cash & Equivalents 2024-03-31: stored 416.0 vs site 365.0; Cash & Equivalents 2023-03-31: stored 186.0 vs site 113.0 |
| APPS | balance_sheet | 137 | Cash & Equivalents 2025-03-31: stored 40.0 vs site 39.39; Cash & Equivalents 2024-03-31: stored 34.0 vs site 33.61; Cash & Equivalents 2022-03-31: stored 0.0 vs site 126.77; Cash & Equivalents 2021-03-31: stored 0.0 vs site 30.78 |
| TLV:ORAD | income_statement | 136 | Revenue 2025-12-31: stored 68.0 vs site 66.96; Revenue 2024-12-31: stored 61.0 vs site 60.25; Revenue 2022-12-31: stored 57.0 vs site 56.11; Revenue 2020-12-31: stored 49.0 vs site 48.22 |
| TLV:FIBIH | cash_flow | 134 | Net Income 2025-12-31: stored 366.0 vs site 360.06; Net Income 2024-12-31: stored 384.0 vs site 377.91; Net Income 2023-12-31: stored 352.0 vs site 346.17; Net Income 2022-12-31: stored 269.0 vs site 569.35 |
| TLV:KLIL | income_statement | 134 | Revenue 2025-12-31: stored 128.0 vs site 126.16; Revenue 2024-12-31: stored 105.0 vs site 103.71; Revenue 2023-12-31: stored 126.0 vs site 124.21; Revenue 2022-12-31: stored 153.0 vs site 150.1 |
| NVR | balance_sheet | 131 | Cash & Equivalents 2025-12-31: stored 1916.0 vs site 1884.0; Cash & Equivalents 2024-12-31: stored 2611.0 vs site 2561.0; Cash & Equivalents 2023-12-31: stored 3163.0 vs site 3126.0; Cash & Equivalents 2020-12-31: stored 2778.0 vs site 2715.0 |
| TK | balance_sheet | 130 | Cash Growth 2019-12-31: stored -16.72 vs site -17.22; Cash Growth 2018-12-31: stored -4.78 vs site -4.19; Accounts Receivable 2025-12-31: stored 83.0 vs site 135.17; Accounts Receivable 2024-12-31: stored 83.0 vs site 140.92 |
| PBT | balance_sheet | 130 | Cash & Equivalents 2025-12-31: stored 2.0 vs site 1.72; Cash & Equivalents 2024-12-31: stored 2.0 vs site 2.12; Cash & Equivalents 2022-12-31: stored 3.0 vs site 2.86; Cash & Equivalents 2021-12-31: stored 2.0 vs site 2.25 |
| CNR | income_statement | 129 | Revenue 2022-12-31: stored 2102.0 vs site 2296.0; Revenue 2020-12-31: stored 1022.0 vs site 901.82; Revenue 2019-12-31: stored 1431.0 vs site 1410.0; Revenue 2017-12-31: stored 1412.0 vs site 1366.0 |
| TLV:LUMI | cash_flow | 128 | Net Income 2025-12-31: stored 3448.0 vs site 3393.0; Net Income 2024-12-31: stored 3292.0 vs site 3240.0; Net Income 2023-12-31: stored 2361.0 vs site 2323.0; Net Income 2022-12-31: stored 2590.0 vs site 2549.0 |
| QLYS | balance_sheet | 128 | Cash Growth 2024-12-31: stored -10.69 vs site -10.37; Cash Growth 2023-12-31: stored 32.9 vs site 32.44; Other Current Assets 2025-12-31: stored 41.0 vs site 8.71; Other Current Assets 2024-12-31: stored 40.0 vs site 7.29 |
| TLV:BVGG | income_statement | 127 | Revenue 2025-12-31: stored 37.0 vs site 36.25; Revenue 2024-12-31: stored 48.0 vs site 45.1; Revenue 2023-12-31: stored 44.0 vs site 42.43; Revenue 2022-12-31: stored 91.0 vs site 89.89 |
| TLV:BRND | income_statement | 127 | Revenue 2025-12-31: stored 290.0 vs site 285.25; Revenue 2024-12-31: stored 120.0 vs site 118.0; Revenue 2023-12-31: stored 98.0 vs site 96.33; Revenue 2022-12-31: stored 96.0 vs site 94.17 |
| TLV:ISTA | cash_flow | 127 | Net Income 2025-12-31: stored 63.0 vs site 62.12; Net Income 2024-12-31: stored 33.0 vs site 32.16; Net Income 2023-12-31: stored 43.0 vs site 42.06; Net Income 2022-12-31: stored 72.0 vs site 70.96 |
