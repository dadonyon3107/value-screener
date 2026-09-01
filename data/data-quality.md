# Data-quality tripwires

- Tickers checked: 2973
- Tickers flagged: 348 (11.7%)

## Failures by check

- **pe_price** (182) — the ratios file's PE disagrees with its own price and the statement EPS
- **eps_shares** (128) — EPS x shares != net income — share-basis mismatch (ADS vs ordinary)
- **income** (42) — net income != pretax - tax (+ discontinued ops, minority interest)
- **balance** (19) — total assets != liabilities + equity (balance sheet does not balance)
- **neg_rev** (3) — negative revenue

## Flagged tickers

| ticker | checks |
|---|---|
| AAUC | income |
| AB | eps_shares |
| ABEV | pe_price |
| ACGL | income |
| AD | balance |
| AEG | eps_shares, neg_rev, pe_price |
| AFYA | pe_price |
| AGNC | eps_shares |
| AKO.A | pe_price |
| AKO.B | pe_price |
| ALB | income |
| ALH | balance |
| AMBP | eps_shares |
| AMX | pe_price |
| ANDG | eps_shares |
| APPN | eps_shares |
| ARIS | eps_shares |
| ARLO | balance |
| ASIC | balance |
| ASML | pe_price |
| ASR | pe_price |
| ASX | pe_price |
| ATAT | pe_price |
| ATHM | pe_price |
| AVAL | eps_shares |
| AVEX | eps_shares |
| AVTX | eps_shares |
| BABA | pe_price |
| BANC | income |
| BAP | pe_price |
| BBAR | eps_shares, pe_price |
| BBD | eps_shares, pe_price |
| BBUC | eps_shares |
| BBVA | pe_price |
| BCH | pe_price |
| BCS | pe_price |
| BEKE | pe_price |
| BELFB | eps_shares |
| BH.A | pe_price |
| BIDU | pe_price |
| BILI | pe_price |
| BILL | eps_shares |
| BIP | eps_shares |
| BIRK | pe_price |
| BLFS | eps_shares |
| BMA | pe_price |
| BMNR | eps_shares, income |
| BNT | eps_shares |
| BNTX | pe_price |
| BRAI | eps_shares |
| BRBI | pe_price |
| BSAC | eps_shares, pe_price |
| BSBR | pe_price |
| BTDR | eps_shares |
| BTI | pe_price |
| BV | income |
| BZ | pe_price |
| CAI | eps_shares |
| CBL | income |
| CCC | income |
| CCEC | eps_shares |
| CCEP | pe_price |
| CCI | eps_shares |
| CCJ | pe_price |
| CCU | pe_price |
| CDE | balance |
| CDLR | pe_price |
| CDNL | eps_shares |
| CEPU | pe_price |
| CET | pe_price |
| CHA | pe_price |
| CHRD | eps_shares |
| CHRN | eps_shares |
| CHT | pe_price |
| CHWY | eps_shares |
| CIB | eps_shares |
| CIG | pe_price |
| CNL | eps_shares |
| CNQ | pe_price |
| CP | pe_price |
| CPAC | pe_price |
| CRCL | eps_shares |
| CRGY | eps_shares |
| CRI | balance |
| CRL | eps_shares |
| CRML | eps_shares |
| CRVS | eps_shares |
| CSAN | pe_price |
| CSTM | balance |
| CVCO | eps_shares |
| CVNA | eps_shares |
| CWST | income |
| CX | eps_shares |
| CYD | pe_price |
| DAO | pe_price |
| DB | pe_price |
| DBD | eps_shares |
| DKNG | eps_shares |
| DRD | pe_price |
| E | pe_price |
| EC | pe_price |
| EDN | income, pe_price |
| EE | eps_shares |
| ELPC | eps_shares, pe_price |
| EMBJ | pe_price |
| ENR | eps_shares |
| EQX | eps_shares |
| ERIC | pe_price |
| ESQ | balance |
| FE | eps_shares |
| FER | pe_price |
| FERG | eps_shares |
| FLOC | eps_shares |
| FMS | pe_price |
| FMX | eps_shares, pe_price |
| FTRE | eps_shares |
| FWONA | eps_shares |
| GBTG | eps_shares |
| GCMG | eps_shares |
| GDS | pe_price |
| GEF.B | eps_shares |
| GFL | eps_shares |
| GGAL | income, pe_price |
| GGB | eps_shares, pe_price |
| GIB | pe_price |
| GNL | income |
| GPGI | balance, eps_shares |
| GRFS | pe_price |
| GSK | pe_price |
| HASI | income |
| HBAN | income |
| HDB | pe_price |
| HGTY | eps_shares |
| HL | income |
| HLN | pe_price |
| HMC | pe_price |
| HMY | pe_price |
| HPE | eps_shares |
| HPK | balance |
| HSAI | pe_price |
| HTHT | pe_price |
| HUBG | pe_price |
| IBN | pe_price |
| ICUI | eps_shares |
| IE | eps_shares |
| IFS | pe_price |
| IHS | income |
| IMCR | eps_shares |
| IMO | pe_price |
| IMOS | pe_price |
| IMTX | pe_price |
| INFQ | eps_shares |
| INFY | pe_price |
| ING | pe_price |
| INNV | eps_shares |
| INTR | pe_price |
| IP | income |
| IQMX | eps_shares |
| IRS | income, pe_price |
| IRT | balance |
| ITUB | pe_price |
| IX | pe_price |
| JD | pe_price |
| KARO | pe_price |
| KB | pe_price |
| KEEL | income |
| KEN | income |
| KEP | pe_price |
| KNTK | eps_shares |
| KOF | pe_price |
| KSPI | pe_price |
| KT | pe_price |
| KTOS | eps_shares |
| KYIV | income |
| LB | eps_shares |
| LEVI | balance |
| LGN | eps_shares |
| LI | pe_price |
| LIME | eps_shares |
| LKFT | pe_price |
| LLYVA | eps_shares |
| LOMA | pe_price |
| LPL | pe_price |
| LTGO | eps_shares |
| LU | pe_price |
| LYG | pe_price |
| LYV | eps_shares |
| MARA | eps_shares |
| MBLY | eps_shares |
| MCHB | eps_shares, income |
| MDLN | eps_shares |
| MFC | pe_price |
| MFG | pe_price |
| MICC | pe_price |
| MNSO | pe_price |
| MOD | pe_price |
| MQ | pe_price |
| MRP | eps_shares |
| MSGE | pe_price |
| MUFG | income, pe_price |
| MUX | eps_shares |
| NBR | eps_shares |
| NGG | pe_price |
| NMR | pe_price |
| NOK | pe_price |
| NOMD | pe_price |
| NTES | income, pe_price |
| NTRS | income |
| NVO | pe_price |
| NWG | income, pe_price |
| NXE | pe_price |
| OKTA | eps_shares |
| OMAB | pe_price |
| ONON | pe_price |
| PAC | pe_price |
| PAGS | pe_price |
| PBR | eps_shares |
| PBR.A | pe_price |
| PCOR | balance |
| PDD | pe_price |
| PDFS | income |
| PEN | eps_shares |
| PENG | eps_shares |
| PGEN | eps_shares |
| PHI | pe_price |
| PKX | pe_price |
| PNFP | pe_price |
| PPTA | eps_shares |
| PRCH | income |
| PRI | eps_shares |
| PRMB | eps_shares |
| PRSU | eps_shares |
| PSNY | balance |
| PSO | pe_price |
| PTC | balance |
| PVLA | eps_shares |
| PWP | eps_shares |
| QFIN | pe_price |
| QXO | eps_shares |
| RACE | pe_price |
| RCI | pe_price |
| RDY | pe_price |
| RELX | pe_price |
| RKT | eps_shares |
| RLX | pe_price |
| RNW | pe_price |
| RSI | eps_shares |
| RYAAY | pe_price |
| RYN | income |
| SAN | pe_price |
| SAP | pe_price |
| SBS | pe_price |
| SHG | pe_price |
| SID | eps_shares |
| SIFY | pe_price |
| SIM | pe_price |
| SKM | pe_price |
| SLBT | eps_shares |
| SLSR | eps_shares |
| SMFG | pe_price |
| SMTC | income |
| SNPS | eps_shares |
| SNY | pe_price |
| SONY | pe_price |
| SOUN | eps_shares |
| SPB | eps_shares |
| SPOT | pe_price |
| SRAD | pe_price |
| SSL | pe_price |
| STLA | pe_price |
| STNE | eps_shares, pe_price |
| STVN | pe_price |
| SUZ | income, pe_price |
| SYRE | eps_shares |
| TAC | income |
| TAK | eps_shares, pe_price |
| TALO | balance |
| TBBB | pe_price |
| TCOM | pe_price |
| TECK | eps_shares |
| TEO | pe_price |
| TGB | income, pe_price |
| TGS | pe_price |
| TGTX | income |
| TIMB | pe_price |
| TKC | pe_price |
| TKO | eps_shares |
| TLK | pe_price |
| TLN | eps_shares |
| TLV:AMRM | pe_price |
| TLV:ARF | eps_shares |
| TLV:BLEG | eps_shares |
| TLV:BVC | eps_shares |
| TLV:DRSL | pe_price |
| TLV:ELLO | eps_shares, pe_price |
| TLV:ENOG | pe_price |
| TLV:GAON | pe_price |
| TLV:IMCO | eps_shares |
| TLV:LURO | eps_shares |
| TLV:MLRN | eps_shares |
| TLV:MTRD | pe_price |
| TLV:ORIN | neg_rev |
| TLV:RTSN | eps_shares |
| TLV:SLRM | pe_price |
| TLV:SMSH | eps_shares |
| TLV:TLSY | neg_rev |
| TLV:TOEN | balance |
| TLV:WILC | pe_price |
| TM | pe_price |
| TMC | eps_shares |
| TME | pe_price |
| TPG | eps_shares |
| TRIP | income |
| TSAT | pe_price |
| TSM | pe_price |
| TU | pe_price |
| TV | eps_shares |
| TYG | eps_shares |
| UGP | pe_price |
| UL | pe_price |
| UMC | pe_price |
| UPWK | eps_shares |
| UROY | pe_price |
| UTI | income |
| UWMC | eps_shares |
| VALE | pe_price |
| VERX | eps_shares |
| VIPS | pe_price |
| VISN | eps_shares, income |
| VIV | pe_price |
| VNET | eps_shares, pe_price |
| VOD | pe_price |
| VOYA | balance |
| VSAT | income |
| VTOL | income |
| WF | eps_shares |
| WIT | pe_price |
| WMG | eps_shares |
| WPP | pe_price |
| WT | balance |
| WTTR | income |
| WULF | eps_shares |
| XP | pe_price |
| XPRO | income |
| YMM | pe_price |
| YPF | income, pe_price |
| ZGN | eps_shares, pe_price |
| ZTO | pe_price |
