# Data-quality tripwires

- Tickers checked: 2890
- Tickers flagged: 185 (6.4%)

## Failures by check

- **pe_price** (155) — the ratios file's PE disagrees with its own price and the statement EPS
- **eps_shares** (32) — EPS x shares != net income — share-basis mismatch (ADS vs ordinary)
- **income** (9) — net income != pretax - tax (+ discontinued ops, minority interest)

## Flagged tickers

| ticker | checks |
|---|---|
| ABEV | pe_price |
| ACA | income |
| AD | pe_price |
| AESI | pe_price |
| AKO.A | pe_price |
| AKO.B | pe_price |
| AMCR | pe_price |
| ANDG | eps_shares |
| APAM | pe_price |
| ARLP | pe_price |
| ARMK | pe_price |
| ASR | pe_price |
| AVAL | pe_price |
| AVEX | eps_shares |
| AVTX | eps_shares |
| BAM | pe_price |
| BBAR | pe_price |
| BBDO | pe_price |
| BCH | pe_price |
| BCS | pe_price |
| BDX | pe_price |
| BH | pe_price |
| BH.A | pe_price |
| BILL | eps_shares |
| BL | pe_price |
| BLLN | pe_price |
| BMA | pe_price |
| BMNR | pe_price |
| BP | pe_price |
| BRSL | pe_price |
| BSAC | pe_price |
| BTDR | eps_shares |
| BTG | pe_price |
| BWLP | pe_price |
| BXSL | pe_price |
| CARG | eps_shares, pe_price |
| CAVA | pe_price |
| CBC | pe_price |
| CBRS | eps_shares |
| CCEC | pe_price |
| CDLR | pe_price |
| CERT | income |
| CIB | pe_price |
| CMBT | pe_price |
| CMRE | pe_price |
| CNX | eps_shares |
| CNXC | pe_price |
| CRGY | pe_price |
| CRVS | eps_shares |
| CSAN | pe_price |
| CSWC | pe_price |
| CVNA | eps_shares, pe_price |
| DBD | pe_price |
| DD | pe_price |
| DKNG | eps_shares |
| DMLP | pe_price |
| E | pe_price |
| EC | pe_price |
| ECO | pe_price |
| EE | eps_shares |
| ELE | pe_price |
| ELVR | pe_price |
| EQPT | eps_shares |
| EROK | income |
| EXR | pe_price |
| EZPW | pe_price |
| FANG | pe_price |
| FIG | eps_shares |
| FIGR | pe_price |
| FLNC | pe_price |
| FLOC | eps_shares |
| FMS | pe_price |
| FMX | pe_price |
| FSK | pe_price |
| GBDC | pe_price |
| GBTG | eps_shares |
| GCMG | eps_shares, pe_price |
| GGAL | pe_price |
| GLXY | eps_shares, pe_price |
| GMAB | pe_price |
| GRFS | pe_price |
| GSBD | pe_price |
| HAFN | pe_price |
| HAWK | eps_shares |
| HDB | pe_price |
| HESM | pe_price |
| HGTY | eps_shares, pe_price |
| HMC | pe_price |
| HNI | pe_price |
| HON | pe_price |
| HSBC | pe_price |
| HTGC | pe_price |
| HUT | pe_price |
| IBN | pe_price |
| IFF | income |
| INVX | pe_price |
| IRS | pe_price |
| JCAP | pe_price |
| KNTK | pe_price |
| KRP | pe_price |
| KYIV | pe_price |
| LB | pe_price |
| LBTYA | pe_price |
| LBTYK | pe_price |
| LIF | pe_price |
| LOMA | pe_price |
| LU | pe_price |
| LUNR | pe_price |
| LUXE | pe_price |
| LYG | pe_price |
| MDLN | eps_shares |
| MDU | pe_price |
| MFG | pe_price |
| MMYT | pe_price |
| MNR | pe_price |
| NAT | pe_price |
| NWG | pe_price |
| NXT | pe_price |
| OCSL | pe_price |
| OKE | pe_price |
| OKTA | eps_shares, pe_price |
| PBR | pe_price |
| PBR.A | pe_price |
| PR | pe_price |
| PSEC | pe_price |
| PTEN | pe_price |
| PURR | pe_price |
| PWP | eps_shares |
| REZI | pe_price |
| RKT | eps_shares |
| RLJ | pe_price |
| RSI | eps_shares |
| RYAAY | pe_price |
| SHEL | pe_price |
| SKM | pe_price |
| SMFG | pe_price |
| SSRM | income |
| STGW | pe_price |
| SUN | pe_price |
| SW | pe_price |
| TAK | pe_price |
| TEO | pe_price |
| TIMB | pe_price |
| TKC | pe_price |
| TKO | eps_shares, pe_price |
| TLK | pe_price |
| TLV:ARYT | pe_price |
| TLV:BRIH | pe_price |
| TLV:BWAY | pe_price |
| TLV:CILO | pe_price |
| TLV:CNGL | pe_price |
| TLV:DLEKG | pe_price |
| TLV:ELAL | pe_price |
| TLV:ELLO | income |
| TLV:HAMAT | income |
| TLV:HRON | pe_price |
| TLV:IBIU | pe_price |
| TLV:ISCD | eps_shares |
| TLV:ISRG | pe_price |
| TLV:MLTH | pe_price |
| TLV:NVPT | pe_price |
| TLV:ORL | pe_price |
| TLV:PTCH | pe_price |
| TLV:SMSH | eps_shares |
| TLV:SPGS | income |
| TPG | eps_shares, pe_price |
| TRIN | pe_price |
| TRIP | income |
| TRMD | pe_price |
| TSM | pe_price |
| UAN | pe_price |
| UPWK | eps_shares, pe_price |
| UWMC | eps_shares, pe_price |
| VALE | pe_price |
| VISN | pe_price |
| VNET | eps_shares, pe_price |
| VNOM | pe_price |
| VOD | pe_price |
| VTMX | pe_price |
| WF | pe_price |
| WOLF | pe_price |
| WPP | pe_price |
| WRBY | pe_price |
| YPF | pe_price |
| ZIM | pe_price |
