# Data-quality tripwires

- Tickers checked: 2886
- Tickers flagged: 314 (10.9%)

## Failures by check

- **pe_price** (166) — the ratios file's PE disagrees with its own price and the statement EPS
- **eps_shares** (127) — EPS x shares != net income — share-basis mismatch (ADS vs ordinary)
- **income** (41) — net income != pretax - tax (+ discontinued ops, minority interest)
- **balance** (19) — total assets != liabilities + equity (balance sheet does not balance)
- **neg_rev** (3) — negative revenue

## Flagged tickers

| ticker | checks |
|---|---|
| AAUC | income |
| AB | eps_shares |
| ACGL | income |
| AD | balance, pe_price |
| AEG | eps_shares, neg_rev |
| AESI | pe_price |
| AGNC | eps_shares |
| AKO.A | pe_price |
| ALB | income |
| ALH | balance |
| AMBP | eps_shares |
| AMCR | pe_price |
| ANDG | eps_shares |
| APAM | pe_price |
| APPN | eps_shares |
| ARIS | eps_shares |
| ARLO | balance |
| ARLP | pe_price |
| ARMK | pe_price |
| ASIC | balance |
| ASR | pe_price |
| AVAL | eps_shares, pe_price |
| AVEX | eps_shares |
| AVTX | eps_shares |
| BAM | pe_price |
| BANC | income |
| BBAR | eps_shares |
| BBD | eps_shares |
| BBUC | eps_shares, pe_price |
| BDX | pe_price |
| BELFB | eps_shares |
| BH | pe_price |
| BH.A | pe_price |
| BILL | eps_shares |
| BIP | eps_shares |
| BL | pe_price |
| BLFS | eps_shares |
| BLLN | pe_price |
| BMA | pe_price |
| BMNR | eps_shares, income, pe_price |
| BNT | eps_shares |
| BRAI | eps_shares |
| BRK.A | pe_price |
| BRSL | pe_price |
| BSAC | eps_shares |
| BTDR | eps_shares |
| BTG | pe_price |
| BV | income |
| BWLP | pe_price |
| BXSL | pe_price |
| CAI | eps_shares |
| CARG | pe_price |
| CAVA | pe_price |
| CBC | pe_price |
| CBL | income |
| CCC | income |
| CCEC | eps_shares, pe_price |
| CCI | eps_shares |
| CDE | balance |
| CDLR | pe_price |
| CDNL | eps_shares |
| CET | pe_price |
| CHRD | eps_shares |
| CHRN | eps_shares |
| CHWY | eps_shares, pe_price |
| CIB | eps_shares, pe_price |
| CIG | pe_price |
| CLBK | pe_price |
| CMBT | pe_price |
| CMRE | pe_price |
| CNL | eps_shares |
| CNXC | pe_price |
| CRCL | eps_shares |
| CRGY | eps_shares, pe_price |
| CRI | balance |
| CRL | eps_shares |
| CRML | eps_shares |
| CRVS | eps_shares |
| CSTM | balance |
| CSWC | pe_price |
| CVCO | eps_shares |
| CVNA | eps_shares, pe_price |
| CWST | income |
| CX | eps_shares, pe_price |
| DBD | eps_shares |
| DD | pe_price |
| DKNG | eps_shares |
| DMLP | pe_price |
| EC | pe_price |
| ECO | pe_price |
| EDN | income |
| EE | eps_shares |
| ELE | pe_price |
| ELPC | eps_shares |
| ELVR | pe_price |
| EMBJ | pe_price |
| ENR | eps_shares, pe_price |
| EQX | eps_shares |
| ERIC | pe_price |
| ESQ | balance |
| EXR | pe_price |
| EZPW | pe_price |
| FANG | pe_price |
| FE | eps_shares |
| FER | pe_price |
| FERG | eps_shares |
| FIGR | pe_price |
| FLNC | pe_price |
| FLOC | eps_shares |
| FMX | eps_shares, pe_price |
| FSK | pe_price |
| FTRE | eps_shares |
| FWONA | eps_shares |
| GBDC | pe_price |
| GBTG | eps_shares |
| GCMG | eps_shares, pe_price |
| GEF.B | eps_shares |
| GFL | eps_shares |
| GGAL | income, pe_price |
| GGB | eps_shares |
| GLXY | pe_price |
| GNL | income |
| GPGI | balance, eps_shares |
| GRFS | pe_price |
| GSBD | pe_price |
| HAFN | pe_price |
| HASI | income |
| HBAN | income |
| HESM | pe_price |
| HGTY | eps_shares, pe_price |
| HL | income |
| HMY | pe_price |
| HNI | pe_price |
| HON | pe_price |
| HPE | eps_shares |
| HPK | balance |
| HTGC | pe_price |
| ICUI | eps_shares |
| IE | eps_shares |
| IHS | income |
| IMCR | eps_shares |
| INDV | pe_price |
| INFQ | eps_shares |
| ING | pe_price |
| INNV | eps_shares |
| INVX | pe_price |
| IP | income |
| IQMX | eps_shares |
| IRS | income, pe_price |
| IRT | balance |
| JCAP | pe_price |
| KEEL | income |
| KEN | income |
| KNTK | eps_shares, pe_price |
| KRP | pe_price |
| KTOS | eps_shares |
| KYIV | income, pe_price |
| LB | eps_shares, pe_price |
| LEVI | balance |
| LGN | eps_shares |
| LIME | eps_shares |
| LLYVA | eps_shares, pe_price |
| LOMA | pe_price |
| LTGO | eps_shares |
| LTM | pe_price |
| LU | pe_price |
| LUNR | pe_price |
| LUXE | pe_price |
| LYV | eps_shares |
| MARA | eps_shares |
| MBLY | eps_shares |
| MCHB | eps_shares, income, pe_price |
| MDLN | eps_shares |
| MDU | pe_price |
| MFG | pe_price |
| MMYT | pe_price |
| MNR | pe_price |
| MRP | eps_shares |
| MUFG | income, pe_price |
| MUX | eps_shares |
| NAT | pe_price |
| NBR | eps_shares |
| NTRS | income |
| NWG | income |
| NXT | pe_price |
| OCSL | pe_price |
| OKE | pe_price |
| OKTA | eps_shares, pe_price |
| PANW | pe_price |
| PBR | eps_shares, pe_price |
| PBR.A | pe_price |
| PCOR | balance |
| PDFS | income |
| PEN | eps_shares |
| PENG | eps_shares |
| PGEN | eps_shares |
| PNFP | pe_price |
| PPTA | eps_shares |
| PR | pe_price |
| PRCH | income |
| PRI | eps_shares |
| PRMB | eps_shares |
| PRSU | eps_shares |
| PSEC | pe_price |
| PSNY | balance |
| PTC | balance |
| PTEN | pe_price |
| PURR | pe_price |
| PVLA | eps_shares |
| PWP | eps_shares |
| QGEN | pe_price |
| QXO | eps_shares |
| REZI | pe_price |
| RKT | eps_shares |
| RLJ | pe_price |
| RSI | eps_shares |
| RUSHA | pe_price |
| RUSHB | pe_price |
| RYN | income |
| SID | eps_shares |
| SIRI | pe_price |
| SLBT | eps_shares |
| SLSR | eps_shares |
| SMFG | pe_price |
| SMTC | income |
| SNPS | eps_shares |
| SOUN | eps_shares |
| SPB | eps_shares |
| SQM | pe_price |
| SSL | pe_price |
| ST | pe_price |
| STGW | pe_price |
| STM | pe_price |
| STNE | eps_shares, pe_price |
| SUN | pe_price |
| SUZ | income |
| SW | pe_price |
| SYRE | eps_shares |
| TAC | income |
| TAK | eps_shares |
| TALO | balance |
| TECK | eps_shares |
| TGB | income |
| TGS | pe_price |
| TGTX | income |
| TIMB | pe_price |
| TKC | pe_price |
| TKO | eps_shares, pe_price |
| TLN | eps_shares |
| TLV:ACRO | pe_price |
| TLV:ALMA | pe_price |
| TLV:ARF | eps_shares, pe_price |
| TLV:ASHO | pe_price |
| TLV:BLEG | eps_shares |
| TLV:BVC | eps_shares |
| TLV:CILO | pe_price |
| TLV:CMDR | pe_price |
| TLV:DLEKG | pe_price |
| TLV:EFCP | pe_price |
| TLV:ELAD | pe_price |
| TLV:ELAL | pe_price |
| TLV:ELLO | eps_shares |
| TLV:ENOG | pe_price |
| TLV:GAON | pe_price |
| TLV:HRON | pe_price |
| TLV:IBIU | pe_price |
| TLV:ICHO | pe_price |
| TLV:LURO | eps_shares, pe_price |
| TLV:MISH | pe_price |
| TLV:MLRN | eps_shares |
| TLV:MLTH | pe_price |
| TLV:NVPT | pe_price |
| TLV:ORIN | neg_rev, pe_price |
| TLV:POLP | pe_price |
| TLV:PTCH | pe_price |
| TLV:RIMO | pe_price |
| TLV:RTSN | eps_shares |
| TLV:SMSH | eps_shares |
| TLV:TLSY | neg_rev, pe_price |
| TLV:TOEN | balance |
| TLV:TSG | pe_price |
| TLV:WILC | pe_price |
| TMC | eps_shares |
| TPG | eps_shares, pe_price |
| TRIN | pe_price |
| TRIP | income |
| TRMD | pe_price |
| TV | eps_shares |
| TYG | eps_shares |
| UAN | pe_price |
| UHAL | pe_price |
| UHAL.B | pe_price |
| UPWK | eps_shares, pe_price |
| UROY | pe_price |
| UTI | income |
| UWMC | eps_shares, pe_price |
| VALE | pe_price |
| VERX | eps_shares |
| VISN | eps_shares, income, pe_price |
| VNET | eps_shares, pe_price |
| VNOM | pe_price |
| VOYA | balance |
| VSAT | income |
| VTOL | income |
| WF | eps_shares, pe_price |
| WMG | eps_shares |
| WRBY | pe_price |
| WT | balance |
| WTTR | income |
| WULF | eps_shares |
| XPRO | income |
| YPF | income, pe_price |
| ZGN | eps_shares |
| ZIM | pe_price |
