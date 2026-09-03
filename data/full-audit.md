# Full-universe data audit

- Generated: 2026-09-03
- Tickers audited: **2904**
- **OK: 2542** (87.5%)
- **WARN: 145** (5.0%)
- **FAIL: 217** (7.5%)

A FAIL means the ticker's own numbers contradict each other, so at least one
is wrong. A WARN is a soft issue - stale vintage, or a check that could not run.
An OK means every identity holds and the per-year ratios match the site's page.

## Issues by type

| issue | tickers | meaning |
|---|---|---|
| pe_price | 182 | the ratios file's PE disagrees with its own price and the statement EPS |
| published pe != stored pe | 177 | latest.json disagrees with the stored CSV |
| eps_shares | 32 | EPS x shares != net income — share-basis mismatch (ADS vs ordinary) |
| no statements | 11 | - |
| income | 9 | net income != pretax - tax (+ discontinued ops, minority interest) |
| roa_impossible | 6 | return on assets above 100% - recomputed off a broken export |
| missing cash_flow | 3 | - |

## FAIL tickers (217)

| ticker | issues |
|---|---|
| ABEV | pe_price |
| ACA | income |
| AD | pe_price |
| AESI | pe_price |
| AKO.A | pe_price |
| AKO.B | pe_price |
| AMCR | pe_price |
| AMX | pe_price |
| ANDG | eps_shares |
| APAM | pe_price |
| ARLP | pe_price |
| ARMK | pe_price |
| ASR | pe_price |
| ASX | pe_price, published pe != stored pe |
| AVAL | pe_price |
| AVEX | eps_shares |
| AVTX | eps_shares |
| BAM | pe_price |
| BBAR | pe_price |
| BBDO | pe_price |
| BCH | pe_price |
| BCS | pe_price |
| BDX | pe_price, published pe != stored pe |
| BH | pe_price |
| BH.A | pe_price |
| BHP | pe_price |
| BILL | eps_shares |
| BL | pe_price |
| BLLN | pe_price |
| BMA | pe_price |
| BMNR | pe_price |
| BP | pe_price |
| BRAI | roa_impossible |
| BRSL | pe_price, published pe != stored pe |
| BSAC | pe_price |
| BTDR | eps_shares |
| BTG | pe_price |
| BWLP | pe_price |
| BXSL | pe_price |
| CARG | eps_shares, pe_price, published pe != stored pe |
| CAVA | pe_price |
| CBC | pe_price |
| CBRS | eps_shares |
| CCEC | pe_price |
| CCU | pe_price |
| CDLR | pe_price |
| CERT | income |
| CHT | pe_price |
| CIB | pe_price, published pe != stored pe |
| CMBT | pe_price, published pe != stored pe |
| CMRE | pe_price |
| CNX | eps_shares |
| CNXC | pe_price |
| CPAC | pe_price |
| CRGY | pe_price, published pe != stored pe |
| CRVS | eps_shares |
| CSAN | pe_price |
| CSWC | pe_price |
| CVNA | eps_shares, pe_price |
| CX | pe_price, published pe != stored pe |
| DBD | pe_price |
| DD | pe_price, published pe != stored pe |
| DEO | pe_price |
| DKNG | eps_shares |
| DMLP | pe_price |
| E | pe_price, published pe != stored pe |
| EC | pe_price, published pe != stored pe |
| ECO | pe_price |
| EE | eps_shares |
| ELE | pe_price |
| ELVR | pe_price |
| EMBJ | pe_price, published pe != stored pe |
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
| FMX | pe_price, published pe != stored pe |
| FSK | pe_price |
| GBDC | pe_price |
| GBTG | eps_shares |
| GCMG | eps_shares, pe_price |
| GGAL | pe_price, published pe != stored pe |
| GLXY | eps_shares, pe_price, roa_impossible |
| GMAB | pe_price |
| GRFS | pe_price, published pe != stored pe |
| GSBD | pe_price |
| GSK | pe_price |
| HAFN | pe_price, published pe != stored pe |
| HAWK | eps_shares |
| HCM | pe_price |
| HDB | pe_price |
| HESM | pe_price |
| HGTY | eps_shares, pe_price, published pe != stored pe |
| HLN | pe_price |
| HMC | pe_price |
| HNI | pe_price |
| HON | pe_price |
| HSBC | pe_price |
| HTGC | pe_price |
| HUT | pe_price |
| IBN | pe_price |
| IFF | income |
| IMOS | pe_price, published pe != stored pe |
| INVX | pe_price |
| IRS | pe_price, published pe != stored pe |
| JCAP | pe_price, published pe != stored pe |
| KEP | pe_price |
| KNTK | pe_price |
| KRP | pe_price |
| KT | pe_price, published pe != stored pe |
| KYIV | pe_price |
| LB | pe_price |
| LBTYA | pe_price |
| LBTYK | pe_price |
| LIF | pe_price |
| LOMA | pe_price, published pe != stored pe |
| LPL | pe_price |
| LTGO | roa_impossible |
| LU | pe_price |
| LUNR | pe_price |
| LUXE | pe_price, published pe != stored pe |
| LYG | pe_price |
| MDLN | eps_shares |
| MDU | pe_price |
| MFG | pe_price, published pe != stored pe |
| MMYT | pe_price |
| MNR | pe_price |
| NAT | pe_price, published pe != stored pe |
| NTES | pe_price |
| NWG | pe_price |
| NXT | pe_price |
| OCSL | pe_price |
| OKE | pe_price |
| OKTA | eps_shares, pe_price |
| OMAB | pe_price |
| PAC | pe_price |
| PBR | pe_price, published pe != stored pe |
| PBR.A | pe_price |
| PKX | pe_price, published pe != stored pe |
| PR | pe_price |
| PSEC | pe_price |
| PTEN | pe_price |
| PURR | pe_price |
| PWP | eps_shares |
| REZI | pe_price |
| RKT | eps_shares, published pe != stored pe |
| RLJ | pe_price, published pe != stored pe |
| RSI | eps_shares |
| RTO | pe_price, published pe != stored pe |
| RYAAY | pe_price |
| SHEL | pe_price, published pe != stored pe |
| SKM | pe_price, published pe != stored pe |
| SMFG | pe_price |
| SMMT | roa_impossible |
| SNN | pe_price |
| SNY | pe_price |
| SSRM | income |
| STGW | pe_price, published pe != stored pe |
| SUN | pe_price |
| SW | pe_price |
| TAK | pe_price |
| TEO | pe_price |
| TIMB | pe_price |
| TKC | pe_price |
| TKO | eps_shares, pe_price |
| TLK | pe_price |
| TLV:ARYT | pe_price, published pe != stored pe |
| TLV:BRIH | pe_price, published pe != stored pe |
| TLV:BWAY | pe_price |
| TLV:CILO | pe_price, published pe != stored pe |
| TLV:CNGL | pe_price, published pe != stored pe |
| TLV:DLEKG | pe_price |
| TLV:ELAL | pe_price |
| TLV:ELLO | income |
| TLV:HAMAT | income, published pe != stored pe |
| TLV:HRON | pe_price, published pe != stored pe |
| TLV:IBIU | pe_price, published pe != stored pe |
| TLV:ISCD | eps_shares, published pe != stored pe |
| TLV:ISRG | pe_price |
| TLV:MLTH | pe_price, published pe != stored pe |
| TLV:NVPT | pe_price |
| TLV:ORL | pe_price |
| TLV:PTCH | pe_price |
| TLV:SMSH | eps_shares |
| TLV:SPGS | income, published pe != stored pe |
| TLV:TURB | roa_impossible |
| TM | pe_price |
| TPG | eps_shares, pe_price |
| TRIN | pe_price |
| TRIP | income, published pe != stored pe |
| TRMD | pe_price |
| TS | pe_price |
| TSM | pe_price |
| UAN | pe_price |
| UMC | pe_price |
| UPWK | eps_shares, pe_price |
| UWMC | eps_shares, pe_price |
| VALE | pe_price |
| VISN | pe_price |
| VIV | pe_price, published pe != stored pe |
| VNET | eps_shares, pe_price |
| VNOM | pe_price, published pe != stored pe |
| VOD | pe_price |
| VTMX | pe_price |
| WF | pe_price |
| WINA | roa_impossible |
| WOLF | pe_price |
| WPP | pe_price |
| WRBY | pe_price |
| YPF | pe_price |
| ZIM | pe_price |

## WARN tickers (145)

| ticker | issues |
|---|---|
| AAP | published pe != stored pe |
| ACI | published pe != stored pe |
| AERO | published pe != stored pe |
| AGM.A | published pe != stored pe |
| AGRO | published pe != stored pe |
| AIIR | no statements |
| ALB | published pe != stored pe |
| ALGM | published pe != stored pe |
| ALM | published pe != stored pe |
| APTV | published pe != stored pe |
| APXT | no statements |
| ASA | missing cash_flow |
| AU | published pe != stored pe |
| AXTI | published pe != stored pe |
| BBD | published pe != stored pe |
| BELFB | published pe != stored pe |
| BGSI | published pe != stored pe |
| BNT | published pe != stored pe |
| BSBR | published pe != stored pe |
| BST | no statements |
| BTX | no statements |
| BVN | published pe != stored pe |
| BXDC | no statements |
| CCC | published pe != stored pe |
| CCI | published pe != stored pe |
| CEPU | published pe != stored pe |
| CHA | published pe != stored pe |
| CIG | published pe != stored pe |
| CIG.C | published pe != stored pe |
| CLBK | published pe != stored pe |
| CPRI | published pe != stored pe |
| CRDO | published pe != stored pe |
| CRWD | published pe != stored pe |
| CYD | published pe != stored pe |
| DELL | published pe != stored pe |
| DOLE | published pe != stored pe |
| DSL | no statements |
| DX | published pe != stored pe |
| EDN | published pe != stored pe |
| EGO | published pe != stored pe |
| EQNR | published pe != stored pe |
| ERIC | published pe != stored pe |
| ETSY | published pe != stored pe |
| FER | published pe != stored pe |
| FLO | published pe != stored pe |
| FRO | published pe != stored pe |
| FSUN | published pe != stored pe |
| FWONA | published pe != stored pe |
| GDRX | published pe != stored pe |
| GEF | published pe != stored pe |
| GEF.B | published pe != stored pe |
| GFI | published pe != stored pe |
| GGB | published pe != stored pe |
| GIII | published pe != stored pe |
| GIL | published pe != stored pe |
| GLNG | published pe != stored pe |
| HZO | published pe != stored pe |
| ICLR | published pe != stored pe |
| IHS | published pe != stored pe |
| JCI | published pe != stored pe |
| KEYS | published pe != stored pe |
| MGRT | published pe != stored pe |
| MQ | published pe != stored pe |
| MT | published pe != stored pe |
| NBN | published pe != stored pe |
| NTNX | published pe != stored pe |
| OCFC | published pe != stored pe |
| OMC | published pe != stored pe |
| ONC | published pe != stored pe |
| OSCR | published pe != stored pe |
| OXY | published pe != stored pe |
| OZK | published pe != stored pe |
| PAM | published pe != stored pe |
| PANW | published pe != stored pe |
| PBT | missing cash_flow |
| PINS | published pe != stored pe |
| PJT | published pe != stored pe |
| PSQL | no statements |
| PSUS | no statements |
| PTGX | published pe != stored pe |
| RDY | published pe != stored pe |
| REX | published pe != stored pe |
| RYN | published pe != stored pe |
| SA | published pe != stored pe |
| SBR | missing cash_flow |
| SBS | published pe != stored pe |
| SDRL | published pe != stored pe |
| SIM | published pe != stored pe |
| SIMO | published pe != stored pe |
| SKHY | published pe != stored pe |
| SQM | published pe != stored pe |
| SSL | published pe != stored pe |
| SVM | published pe != stored pe |
| TEN | published pe != stored pe |
| TEX | published pe != stored pe |
| TLV:ACKR | published pe != stored pe |
| TLV:ACRO | published pe != stored pe |
| TLV:ALMY | published pe != stored pe |
| TLV:ALRPR | published pe != stored pe |
| TLV:AMPA | published pe != stored pe |
| TLV:ARF | published pe != stored pe |
| TLV:ASGR | published pe != stored pe |
| TLV:ASHO | published pe != stored pe |
| TLV:BKFR | published pe != stored pe |
| TLV:BLGO | published pe != stored pe |
| TLV:BRKT | no statements |
| TLV:CMDR | published pe != stored pe |
| TLV:DISI | published pe != stored pe |
| TLV:DLAS | no statements |
| TLV:EFCP | published pe != stored pe |
| TLV:ELAD | published pe != stored pe |
| TLV:ELCO | published pe != stored pe |
| TLV:ELRN | no statements |
| TLV:GAON | published pe != stored pe |
| TLV:GNRS | published pe != stored pe |
| TLV:GOSS | published pe != stored pe |
| TLV:HGG | published pe != stored pe |
| TLV:ISCN | published pe != stored pe |
| TLV:KRUR | published pe != stored pe |
| TLV:LUZN | published pe != stored pe |
| TLV:MGDO | published pe != stored pe |
| TLV:MGRT | published pe != stored pe |
| TLV:MISH | published pe != stored pe |
| TLV:OPCE | published pe != stored pe |
| TLV:POLP | published pe != stored pe |
| TLV:PTBL | published pe != stored pe |
| TLV:RGAS | published pe != stored pe |
| TLV:SKBN | published pe != stored pe |
| TLV:SRFT | published pe != stored pe |
| TLV:TLSY | published pe != stored pe |
| TLV:TSG | published pe != stored pe |
| TLV:WESR | published pe != stored pe |
| TOWN | published pe != stored pe |
| UBS | published pe != stored pe |
| UGP | published pe != stored pe |
| UHAL | published pe != stored pe |
| UHAL.B | published pe != stored pe |
| UNIT | published pe != stored pe |
| URBN | published pe != stored pe |
| VEON | published pe != stored pe |
| VERX | published pe != stored pe |
| VMRK | published pe != stored pe |
| WAT | published pe != stored pe |
| WSE | published pe != stored pe |
| XPRO | published pe != stored pe |
