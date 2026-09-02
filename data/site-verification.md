# Verification against stockanalysis.com

- Tickers sampled: **120** (random, proportional to the universe)
- Values compared: **102,423**
- **Agree with the site: 82,851 (80.89%)**
  - identical: 72,624
  - within 5% (exchange-rate drift / rounding): 10,171
  - native currency, correctly converted by the builder: 6
  - per-share on ADS basis (by decision): 50
- **Genuine mismatches: 19,572 (19.11%)**
- Present one side only: 3,820
- **Tickers with zero genuine mismatches: 0/120**

## By statement

| statement | agree | genuine mismatches | agreement |
|---|---|---|---|
| income_statement | 20,357 | 6,052 | 77.08% |
| balance_sheet | 17,914 | 7,704 | 69.93% |
| cash_flow | 14,503 | 5,598 | 72.15% |
| ratios | 30,077 | 218 | 99.28% |

## Genuine mismatches

| ticker | statement | cells | examples |
|---|---|---|---|
| TLV:OPCE | balance_sheet | 192 | Cash & Equivalents 2025: 2913 vs 913.74; Cash & Equivalents 2024: 962 vs 264.12; Cash & Equivalents 2023: 1007 vs 279.62 |
| JOYY | balance_sheet | 163 | Cash & Equivalents 2025: 396 vs 374.25; Cash & Equivalents 2024: 816 vs 444.76; Cash & Equivalents 2023: 1383 vs 1064 |
| TLV:OPCE | income_statement | 159 | Revenue 2025: 3002 vs 941.66; Revenue 2024: 2779 vs 762.98; Revenue 2023: 2552 vs 708.63 |
| EC | income_statement | 146 | Revenue Growth 2019: 5.41 vs 4.21; Revenue Growth 2018: 21.21 vs 24.26; Revenue Growth 2017: 15.4 vs 13.87 |
| TLV:OPCE | cash_flow | 133 | Net Income 2025: 346 vs 108.53; Net Income 2024: 111 vs 30.48; Net Income 2023: 144 vs 39.99 |
| TLV:ISRA | income_statement | 132 | Revenue 2025: 446 vs 412.47; Revenue 2024: 533 vs 430.41; Revenue 2022: 519 vs 414.2 |
| HHH | income_statement | 132 | Gross Profit 2025: 642 vs 703.33; Gross Profit 2024: 731 vs 790.35; Gross Profit 2023: 455 vs 507.83 |
| EC | balance_sheet | 127 | Accounts Receivable 2025: 4689 vs 4123; Accounts Receivable 2024: 6436 vs 5963; Accounts Receivable 2023: 10496 vs 9868 |
| TXNM | balance_sheet | 123 | Cash & Equivalents 2024: 4 vs 4.5; Cash & Equivalents 2023: 2 vs 2.22; Cash & Equivalents 2022: 32 vs 4.08 |
| TLV:INCR | income_statement | 122 | Cost of Revenue 2025: 80 vs 75.44; Cost of Revenue 2024: 70 vs 64.69; Cost of Revenue 2022: 78 vs 71.23 |
| INDV | income_statement | 121 | Cost of Revenue 2025: 246 vs 198; Cost of Revenue 2024: 231 vs 190; Cost of Revenue 2021: -127 vs 127 |
| NMM | income_statement | 121 | Cost of Revenue 2025: 512 vs 127.76; Cost of Revenue 2024: 509 vs 146.43; Cost of Revenue 2023: 561 vs 160.23 |
| ENOV | income_statement | 119 | Cost of Revenue 2024: 927 vs 857.21; Gross Profit 2024: 1181 vs 1250; Selling, General & Admin 2025: 1070 vs 999.95 |
| PSNY | balance_sheet | 114 | Accounts Receivable 2024: 190 vs 233.09; Other Receivables 2024: 43 vs 188.56; Other Receivables 2023: 153 vs 327.18 |
| STC | balance_sheet | 110 | Other Investments 2025: 5 vs 47.9; Other Investments 2024: 5 vs 41.2; Other Investments 2023: 4 vs 39.02 |
| HR | balance_sheet | 109 | Cash & Equivalents 2020: 115 vs 15.3; Cash & Equivalents 2019: 33 vs 0.66; Cash & Equivalents 2018: 126 vs 8.38 |
| INDV | balance_sheet | 104 | Accounts Receivable 2018: 287 vs 269; Accounts Receivable 2017: 278 vs 257; Accounts Receivable 2016: 227 vs 205 |
| GHM | cash_flow | 104 | Net Income 2024: 5 vs 4.56; Net Income 2023: 0 vs 0.37; Net Income 2021: 2 vs 2.37 |
| TLV:ASHO | income_statement | 104 | Selling, General & Admin 2025: 2 vs 9.73; Selling, General & Admin 2024: 3 vs 9.78; Selling, General & Admin 2023: 2 vs 7.81 |
| MARA | income_statement | 104 | Revenue 2020: 4 vs 4.36; Revenue 2019: 1 vs 1.19; Revenue 2018: 2 vs 1.56 |
| M | balance_sheet | 103 | Other Current Assets 2026: 387 vs 123; Other Current Assets 2025: 385 vs 115; Other Current Assets 2024: 401 vs 125 |
| CCJ | income_statement | 101 | Cost of Revenue 2019: 967 vs 855.38; Cost of Revenue 2018: 1055 vs 901.18; Gross Profit 2021: 138 vs 167.04 |
| CNR | income_statement | 100 | Revenue 2022: 2102 vs 2296; Revenue 2020: 1022 vs 901.82; Cost of Revenue 2022: 949 vs 1132 |
| NBIS | balance_sheet | 99 | Cash Growth 2025: 51.07 vs 54.15; Cash Growth 2022: -21.02 vs -19.82; Cash Growth 2017: 11.65 vs 10.92 |
| PRSU | balance_sheet | 98 | Cash & Equivalents 2023: 53 vs 27.44; Cash Growth 2024: -5.7 vs 81.16; Cash Growth 2023: -11.75 vs -54.06 |
| XPEV | balance_sheet | 97 | Cash & Equivalents 2025: 4268 vs 2578; Cash & Equivalents 2024: 4685 vs 2765; Cash & Equivalents 2023: 4590 vs 3143 |
| TLV:AVRT | income_statement | 97 | Gross Profit 2022: 9 vs 8.33; Gross Profit 2019: 7 vs 6.36; Gross Profit 2016: 10 vs 9.43 |
| TLV:MPP | income_statement | 94 | Revenue 2019: 0 vs 0.38; Revenue 2018: 0 vs 0.16; Revenue Growth 2024: 15.66 vs 18.09 |
| TLV:AVRT | cash_flow | 94 | Net Income 2024: 1 vs 0.9; Net Income 2023: 1 vs 0.49; Net Income 2022: -1 vs -1.44 |
| HR | cash_flow | 93 | Net Income 2019: 31 vs 39.19; Net Income 2018: 218 vs 69.77; Net Income 2017: 66 vs 23.09 |
| GNRC | balance_sheet | 93 | Other Current Assets 2020: 36 vs 1.39; Other Current Assets 2019: 31 vs 0.04; Other Current Assets 2017: 20 vs 0.27 |
| VLO | income_statement | 93 | Revenue 2025: 122687 vs 115939; Revenue 2020: 64912 vs 60115; Revenue 2019: 108324 vs 102729 |
| HHH | cash_flow | 93 | Net Income 2025: 264 vs 123.9; Net Income 2024: 394 vs 197.7; Net Income 2023: -1101 vs -551.77 |
| TLV:OPAL | cash_flow | 92 | Net Income 2025: 14 vs 13.28; Net Income 2018: 8 vs 7.47; Net Income 2016: 5 vs 4.58 |
| ECVT | income_statement | 92 | Gross Profit 2016: 254 vs 283.18; Other Operating Expenses 2025: 27 vs 17.07; Other Operating Expenses 2024: 13 vs 10.34 |
| HR | income_statement | 91 | Property Expenses 2019: 211 vs 181.75; Property Expenses 2018: 221 vs 171.24; Property Expenses 2017: 192 vs 159.43 |
| GRMN | balance_sheet | 91 | Other Current Assets 2025: 485 vs 17.54; Other Current Assets 2024: 378 vs 24.04; Other Current Assets 2023: 335 vs 16.32 |
| PRSU | income_statement | 90 | Cost of Revenue 2025: 261 vs 34.62; Cost of Revenue 2024: 245 vs 31.12; Cost of Revenue 2023: 221 vs 31.9 |
| HURN | balance_sheet | 89 | Cash Growth 2025: 11.85 vs 5.59; Cash Growth 2024: 80.35 vs 25.03; Cash Growth 2023: 2.66 vs -0.73 |
| VLO | cash_flow | 89 | Net Income 2024: 3006 vs 2770; Net Income 2021: 1288 vs 930; Net Income 2020: -1107 vs -1421 |
| MARA | balance_sheet | 88 | Cash & Equivalents 2022: 113 vs 103.71; Cash & Equivalents 2019: 1 vs 0.69; Cash & Equivalents 2018: 3 vs 2.55 |
| HHH | balance_sheet | 88 | Cash & Equivalents 2025: 571 vs 1469; Cash Growth 2025: -4.22 vs 143.18; Cash Growth 2023: 0.49 vs 2.14 |
| GHM | balance_sheet | 87 | Cash & Equivalents 2026: 7 vs 6.58; Accounts Receivable 2026: 34 vs 93.68; Accounts Receivable 2025: 36 vs 74 |
| AU | income_statement | 87 | Revenue Growth 2016: 1.17 vs 5.18; Other Operating Expenses 2025: 336 vs 221; Other Operating Expenses 2024: 86 vs 158 |
| HURN | income_statement | 87 | Revenue 2019: 965 vs 876.76; Revenue 2018: 878 vs 795.13; Revenue 2017: 808 vs 732.57 |
| CPRT | balance_sheet | 86 | Accounts Receivable 2025: 763 vs 188.02; Accounts Receivable 2024: 786 vs 161.12; Accounts Receivable 2023: 702 vs 148.44 |
| ARMK | balance_sheet | 86 | Cash Growth 2025: -4.96 vs -10.59; Cash Growth 2023: 484.94 vs 399.88; Cash Growth 2022: -38.14 vs -23.46 |
| TLV:VRDS | income_statement | 86 | Gross Profit 2025: 97 vs 109.49; Gross Profit 2023: 87 vs 92.67; Selling, General & Admin 2025: 32 vs 71.57 |
| TLV:KEN | income_statement | 86 | Revenue 2016: 1874 vs 324.25; Revenue Growth 2018: -0.54 vs -0.46; Revenue Growth 2017: -80.47 vs 12.78 |
| BRKR | balance_sheet | 85 | Cash Growth 2025: 62.92 vs 53.94; Cash Growth 2022: -39.57 vs -43.79; Cash Growth 2020: 0.52 vs 6.39 |
| FELE | balance_sheet | 84 | Other Long-Term Assets 2025: 16 vs 9.33; Other Long-Term Assets 2024: 19 vs 10.53; Other Long-Term Assets 2023: 15 vs 6.39 |
| SNDX | balance_sheet | 84 | Accounts Receivable 2024: 8 vs 7.6; Other Receivables 2025: 30 vs 32.3; Other Receivables 2024: 4 vs 6.27 |
| AU | balance_sheet | 84 | Accounts Receivable 2025: 426 vs 122; Accounts Receivable 2024: 356 vs 47; Accounts Receivable 2023: 193 vs 25 |
| TLV:ASHO | cash_flow | 84 | Net Income 2024: 9 vs 16; Net Income 2023: 4 vs 10.71; Net Income 2022: 6 vs 5.49 |
| CWT | income_statement | 84 | Other Operating Expenses 2025: 11 vs 50.28; Other Operating Expenses 2024: 36 vs 46.49; Other Operating Expenses 2023: -15 vs 35.08 |
| RYAN | income_statement | 84 | Cost of Revenue 2024: 1591 vs 1479; Cost of Revenue 2023: 1321 vs 1253; Gross Profit 2024: 925 vs 976.96 |
| AXP | balance_sheet | 83 | Long-Term Investments 2025: 1043 vs 2825; Long-Term Investments 2024: 1240 vs 2808; Long-Term Investments 2023: 2186 vs 3555 |
| VLO | balance_sheet | 82 | Accounts Receivable 2025: 9877 vs 9207; Accounts Receivable 2024: 10708 vs 9731; Accounts Receivable 2023: 12525 vs 11038 |
| MYE | cash_flow | 81 | Net Income 2019: 49 vs 24.33; Net Income 2018: -7 vs -3.35; Net Income 2017: -20 vs -9.89 |
| TLV:HOD | balance_sheet | 81 | Cash & Equivalents 2025: 3 vs 2.73; Cash & Equivalents 2023: 5 vs 4.48; Cash & Equivalents 2020: 5 vs 4.54 |

## Why the three financial statements disagree (ratios do not)

The app stores the site's **CSV download** for income statement, balance sheet and cash flow, but the site's **rendered page** is a different dataset. The ratios statement already uses the page (overlay) and agrees at 99.3%. Differences found in the sample, by cause:

1. **Row definitions** — the page breaks out sub-rows the download lumps together (GRMN Other Current Assets: 485 download vs 17.5 page + a separate Prepaid Expenses row); the page's Total Debt includes leases, the download's does not (GRMN 196 vs 165). Largest source; mostly rows the app does not use.
2. **Foreign filers** — the page converts each year at that year's exchange rate, the download uses one rate (EC, JOYY, XPEV). Israeli (TLV) stocks are stored in shekels while the page shows dollars, so every cell differs by the exchange rate.
3. **Different versions of the same year** — the page and the download carry different figures for recent years (VLO SG&A 2023: 998 vs 898; Revenue 2025: 122,687 vs 115,939).
4. **Rounding** — the download rounds to whole millions (TXNM cash 4 vs 4.5).
5. **Download errors** — HHH cash-flow Net Income is exactly double the page for every year; TXNM's 2022 column holds its subsidiary's balance sheet (Total Assets 2,747 vs 9,257).

Fix that removes 1, 3, 4 and 5: overlay the page onto the three statements, as already done for ratios (ADR share basis kept by the existing guard).
