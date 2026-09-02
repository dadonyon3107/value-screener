# Full-universe data audit

- Generated: 2026-09-02
- Tickers audited: **2898**
- **OK: 2443** (84.3%)
- **WARN: 128** (4.4%)
- **FAIL: 327** (11.3%)

A FAIL means the ticker's own numbers contradict each other, so at least one
is wrong. A WARN is a soft issue - stale vintage, or a check that could not run.
An OK means every identity holds and the per-year ratios match the site's page.

## Issues by type

| issue | tickers | meaning |
|---|---|---|
| published pe != stored pe | 186 | latest.json disagrees with the stored CSV |
| pe_price | 174 | the ratios file's PE disagrees with its own price and the statement EPS |
| eps_shares | 127 | EPS x shares != net income — share-basis mismatch (ADS vs ordinary) |
| income | 41 | net income != pretax - tax (+ discontinued ops, minority interest) |
| balance | 19 | total assets != liabilities + equity (balance sheet does not balance) |
| no statements | 9 | - |
| roa_impossible | 7 | return on assets above 100% - recomputed off a broken export |
| neg_rev | 3 | negative revenue |
| missing cash_flow | 3 | - |

## FAIL tickers (327)

| ticker | issues |
|---|---|
| AAUC | income |
| AB | eps_shares |
| ACGL | income |
| AD | balance, pe_price |
| AEG | eps_shares, neg_rev |
| AESI | pe_price |
| AGNC | eps_shares |
| AKO.A | pe_price |
| ALB | income, published pe != stored pe |
| ALH | balance |
| AMBP | eps_shares |
| AMCR | pe_price |
| ANDG | eps_shares |
| APAM | pe_price |
| APMD | roa_impossible, published pe != stored pe |
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
| AZN | pe_price |
| BAM | pe_price |
| BANC | income |
| BBAR | eps_shares |
| BBD | eps_shares, published pe != stored pe |
| BBUC | eps_shares, pe_price |
| BDX | pe_price, published pe != stored pe |
| BELFB | eps_shares, published pe != stored pe |
| BH | pe_price |
| BH.A | pe_price |
| BILL | eps_shares |
| BIP | eps_shares |
| BL | pe_price |
| BLFS | eps_shares |
| BLLN | pe_price |
| BMA | pe_price |
| BMNR | eps_shares, income, pe_price |
| BNT | eps_shares, published pe != stored pe |
| BRAI | eps_shares, roa_impossible |
| BRK.A | pe_price |
| BRSL | pe_price, published pe != stored pe |
| BSAC | eps_shares |
| BTDR | eps_shares |
| BTG | pe_price |
| BV | income |
| BWLP | pe_price |
| BXSL | pe_price |
| CAI | eps_shares |
| CARG | pe_price, published pe != stored pe |
| CAVA | pe_price |
| CBC | pe_price |
| CBL | income |
| CCC | income |
| CCEC | eps_shares, pe_price |
| CCI | eps_shares, published pe != stored pe |
| CDE | balance |
| CDLR | pe_price |
| CDNL | eps_shares |
| CET | pe_price |
| CHRD | eps_shares |
| CHRN | eps_shares |
| CHWY | eps_shares, pe_price |
| CIB | eps_shares, pe_price, published pe != stored pe |
| CIG | pe_price, published pe != stored pe |
| CLBK | pe_price, published pe != stored pe |
| CMBT | pe_price, published pe != stored pe |
| CMRE | pe_price |
| CNL | eps_shares |
| CNXC | pe_price |
| CRCL | eps_shares |
| CRGY | eps_shares, pe_price, published pe != stored pe |
| CRI | balance |
| CRL | eps_shares |
| CRML | eps_shares |
| CRVS | eps_shares |
| CSTM | balance |
| CSWC | pe_price |
| CVCO | eps_shares |
| CVNA | eps_shares, pe_price |
| CWST | income |
| CX | eps_shares, pe_price, published pe != stored pe |
| DBD | eps_shares |
| DD | pe_price, published pe != stored pe |
| DKNG | eps_shares |
| DMLP | pe_price |
| EC | pe_price, published pe != stored pe |
| ECO | pe_price |
| EDN | income |
| EE | eps_shares |
| ELE | pe_price |
| ELPC | eps_shares |
| ELVR | pe_price |
| EMBJ | pe_price, published pe != stored pe |
| ENR | eps_shares, pe_price |
| EQX | eps_shares |
| ERIC | pe_price, published pe != stored pe |
| ESQ | balance |
| EXR | pe_price |
| EZPW | pe_price |
| FANG | pe_price |
| FE | eps_shares |
| FER | pe_price, published pe != stored pe |
| FERG | eps_shares |
| FIGR | pe_price |
| FLNC | pe_price |
| FLOC | eps_shares |
| FMX | eps_shares, pe_price, published pe != stored pe |
| FSK | pe_price |
| FTRE | eps_shares |
| FWONA | eps_shares, published pe != stored pe |
| GBDC | pe_price |
| GBTG | eps_shares |
| GCMG | eps_shares, pe_price |
| GEF.B | eps_shares, published pe != stored pe |
| GFL | eps_shares |
| GGAL | income, pe_price, published pe != stored pe |
| GGB | eps_shares, published pe != stored pe |
| GLXY | pe_price, roa_impossible |
| GNL | income |
| GPGI | balance, eps_shares |
| GRFS | pe_price, published pe != stored pe |
| GSBD | pe_price |
| HAFN | pe_price |
| HASI | income |
| HBAN | income |
| HESM | pe_price |
| HGTY | eps_shares, pe_price, published pe != stored pe |
| HL | income |
| HMY | pe_price |
| HNI | pe_price |
| HON | pe_price |
| HPE | eps_shares |
| HPK | balance |
| HTGC | pe_price |
| ICUI | eps_shares |
| IE | eps_shares |
| IESC | pe_price |
| IHS | income, published pe != stored pe |
| IMCR | eps_shares |
| IMOS | pe_price, published pe != stored pe |
| INDV | pe_price |
| INFQ | eps_shares |
| ING | pe_price |
| INNV | eps_shares |
| INVX | pe_price |
| IP | income |
| IQMX | eps_shares |
| IRS | income, pe_price, published pe != stored pe |
| IRT | balance |
| JCAP | pe_price, published pe != stored pe |
| KEEL | income |
| KEN | income |
| KEP | pe_price, published pe != stored pe |
| KNTK | eps_shares, pe_price |
| KRP | pe_price |
| KT | pe_price, published pe != stored pe |
| KTOS | eps_shares |
| KYIV | income, pe_price |
| LB | eps_shares, pe_price |
| LEVI | balance |
| LGN | eps_shares |
| LIME | eps_shares |
| LLYVA | eps_shares, pe_price |
| LOMA | pe_price, published pe != stored pe |
| LTGO | eps_shares, roa_impossible |
| LTM | pe_price |
| LU | pe_price |
| LUNR | pe_price |
| LUXE | pe_price, published pe != stored pe |
| LYV | eps_shares |
| MARA | eps_shares |
| MBLY | eps_shares |
| MCHB | eps_shares, income, pe_price |
| MDLN | eps_shares |
| MDU | pe_price |
| MFG | pe_price, published pe != stored pe |
| MMYT | pe_price |
| MNR | pe_price |
| MRP | eps_shares |
| MUFG | income, pe_price |
| MUX | eps_shares |
| NAT | pe_price, published pe != stored pe |
| NBR | eps_shares |
| NTES | pe_price |
| NTRS | income |
| NWG | income |
| NXT | pe_price |
| OCSL | pe_price |
| OKE | pe_price |
| OKTA | eps_shares, pe_price |
| PAM | pe_price, published pe != stored pe |
| PANW | pe_price |
| PBR | eps_shares, pe_price, published pe != stored pe |
| PBR.A | pe_price |
| PCOR | balance |
| PDFS | income |
| PEN | eps_shares |
| PENG | eps_shares |
| PGEN | eps_shares |
| PKX | pe_price, published pe != stored pe |
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
| RKT | eps_shares, published pe != stored pe |
| RLJ | pe_price, published pe != stored pe |
| RSI | eps_shares |
| RUSHA | pe_price |
| RUSHB | pe_price |
| RYN | income, published pe != stored pe |
| SID | eps_shares |
| SIG | pe_price |
| SIRI | pe_price |
| SLBT | eps_shares |
| SLSR | eps_shares |
| SMFG | pe_price |
| SMMT | roa_impossible |
| SMTC | income |
| SNPS | eps_shares |
| SOUN | eps_shares |
| SPB | eps_shares |
| SQM | pe_price, published pe != stored pe |
| SSL | pe_price, published pe != stored pe |
| ST | pe_price |
| STGW | pe_price, published pe != stored pe |
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
| TLV:ACRO | pe_price, published pe != stored pe |
| TLV:ALMA | pe_price |
| TLV:ARF | eps_shares, pe_price, published pe != stored pe |
| TLV:ASHO | pe_price, published pe != stored pe |
| TLV:BLEG | eps_shares |
| TLV:BVC | eps_shares, published pe != stored pe |
| TLV:CILO | pe_price, published pe != stored pe |
| TLV:CMDR | pe_price, published pe != stored pe |
| TLV:DLEKG | pe_price, published pe != stored pe |
| TLV:EFCP | pe_price, published pe != stored pe |
| TLV:ELAD | pe_price, published pe != stored pe |
| TLV:ELAL | pe_price |
| TLV:ELLO | eps_shares |
| TLV:ENOG | pe_price |
| TLV:GAON | pe_price, published pe != stored pe |
| TLV:HRON | pe_price, published pe != stored pe |
| TLV:IBIU | pe_price, published pe != stored pe |
| TLV:ICHO | pe_price |
| TLV:LURO | eps_shares, pe_price |
| TLV:MISH | pe_price, published pe != stored pe |
| TLV:MLRN | eps_shares |
| TLV:MLTH | pe_price, published pe != stored pe |
| TLV:NVPT | pe_price |
| TLV:ORIN | neg_rev, pe_price |
| TLV:POLP | pe_price, published pe != stored pe |
| TLV:PTCH | pe_price |
| TLV:RIMO | pe_price |
| TLV:RTSN | eps_shares |
| TLV:SMSH | eps_shares |
| TLV:TLSY | neg_rev, pe_price, published pe != stored pe |
| TLV:TOEN | balance |
| TLV:TSG | pe_price, published pe != stored pe |
| TLV:TURB | roa_impossible |
| TLV:WILC | pe_price |
| TMC | eps_shares |
| TPG | eps_shares, pe_price |
| TRIN | pe_price |
| TRIP | income, published pe != stored pe |
| TRMD | pe_price |
| TV | eps_shares |
| TYG | eps_shares |
| UAN | pe_price |
| UHAL | pe_price, published pe != stored pe |
| UHAL.B | pe_price, published pe != stored pe |
| UPWK | eps_shares, pe_price |
| UROY | pe_price, published pe != stored pe |
| UTI | income |
| UWMC | eps_shares, pe_price |
| VALE | pe_price |
| VERX | eps_shares, published pe != stored pe |
| VISN | eps_shares, income, pe_price |
| VNET | eps_shares, pe_price |
| VNOM | pe_price, published pe != stored pe |
| VOYA | balance |
| VSAT | income |
| VTOL | income |
| WF | eps_shares |
| WINA | roa_impossible |
| WMG | eps_shares |
| WRBY | pe_price |
| WT | balance |
| WTTR | income |
| WULF | eps_shares |
| XPRO | income, published pe != stored pe |
| YPF | income, pe_price |
| ZGN | eps_shares |
| ZIM | pe_price |

## WARN tickers (128)

| ticker | issues |
|---|---|
| AAP | published pe != stored pe |
| ACI | published pe != stored pe |
| ACM | published pe != stored pe |
| ADBT | published pe != stored pe |
| AERO | published pe != stored pe |
| AGM.A | published pe != stored pe |
| AGRO | published pe != stored pe |
| AIIR | no statements |
| ALGM | published pe != stored pe |
| ALM | published pe != stored pe |
| APTV | published pe != stored pe |
| ASA | missing cash_flow |
| ASX | published pe != stored pe |
| AU | published pe != stored pe |
| AXTI | published pe != stored pe |
| BB | published pe != stored pe |
| BGSI | published pe != stored pe |
| BSBR | published pe != stored pe |
| BST | no statements |
| BTSG | published pe != stored pe |
| BTX | no statements |
| BVN | published pe != stored pe |
| BXDC | no statements |
| CAMT | published pe != stored pe |
| CEPU | published pe != stored pe |
| CHA | published pe != stored pe |
| CIG.C | published pe != stored pe |
| CPRI | published pe != stored pe |
| CRWD | published pe != stored pe |
| DOLE | published pe != stored pe |
| DSL | no statements |
| DX | published pe != stored pe |
| E | published pe != stored pe |
| EQNR | published pe != stored pe |
| ESE | published pe != stored pe |
| ETSY | published pe != stored pe |
| FLO | published pe != stored pe |
| FRO | published pe != stored pe |
| FSUN | published pe != stored pe |
| FTV | published pe != stored pe |
| FWONK | published pe != stored pe |
| GDRX | published pe != stored pe |
| GEF | published pe != stored pe |
| GFI | published pe != stored pe |
| GIL | published pe != stored pe |
| GLNG | published pe != stored pe |
| HZO | published pe != stored pe |
| ICLR | published pe != stored pe |
| JCI | published pe != stored pe |
| KEYS | published pe != stored pe |
| MGRT | published pe != stored pe |
| MIR | published pe != stored pe |
| MLM | published pe != stored pe |
| MNSO | published pe != stored pe |
| MT | published pe != stored pe |
| NBN | published pe != stored pe |
| NTNX | published pe != stored pe |
| OCFC | published pe != stored pe |
| OMC | published pe != stored pe |
| ONC | published pe != stored pe |
| OSCR | published pe != stored pe |
| OXY | published pe != stored pe |
| OZK | published pe != stored pe |
| PAGP | published pe != stored pe |
| PBT | missing cash_flow |
| PINS | published pe != stored pe |
| PJT | published pe != stored pe |
| PSUS | no statements |
| PTGX | published pe != stored pe |
| RDY | published pe != stored pe |
| RTO | published pe != stored pe |
| SA | published pe != stored pe |
| SAN | published pe != stored pe |
| SBR | missing cash_flow |
| SBS | published pe != stored pe |
| SDRL | published pe != stored pe |
| SHEL | published pe != stored pe |
| SIM | published pe != stored pe |
| SIMO | published pe != stored pe |
| SKM | published pe != stored pe |
| SMCI | published pe != stored pe |
| SVM | published pe != stored pe |
| TEN | published pe != stored pe |
| TLV:ACKR | published pe != stored pe |
| TLV:ALMY | published pe != stored pe |
| TLV:ALRPR | published pe != stored pe |
| TLV:ARYT | published pe != stored pe |
| TLV:ASGR | published pe != stored pe |
| TLV:ASHG | published pe != stored pe |
| TLV:BKFR | published pe != stored pe |
| TLV:BLGO | published pe != stored pe |
| TLV:BLSR | published pe != stored pe |
| TLV:BRIH | published pe != stored pe |
| TLV:BRKT | no statements |
| TLV:CNGL | published pe != stored pe |
| TLV:DISI | published pe != stored pe |
| TLV:DLAS | no statements |
| TLV:ELCO | published pe != stored pe |
| TLV:ELMR | published pe != stored pe |
| TLV:ELRN | no statements |
| TLV:GNRS | published pe != stored pe |
| TLV:GOSS | published pe != stored pe |
| TLV:HAMAT | published pe != stored pe |
| TLV:ISCD | published pe != stored pe |
| TLV:ISCN | published pe != stored pe |
| TLV:KRUR | published pe != stored pe |
| TLV:LUZN | published pe != stored pe |
| TLV:MGDO | published pe != stored pe |
| TLV:MGRT | published pe != stored pe |
| TLV:NXSN | published pe != stored pe |
| TLV:OPCE | published pe != stored pe |
| TLV:PTBL | published pe != stored pe |
| TLV:RGAS | published pe != stored pe |
| TLV:SKBN | published pe != stored pe |
| TLV:SPGS | published pe != stored pe |
| TLV:WESR | published pe != stored pe |
| TOWN | published pe != stored pe |
| TRS | published pe != stored pe |
| UBS | published pe != stored pe |
| UGP | published pe != stored pe |
| UNIT | published pe != stored pe |
| URBN | published pe != stored pe |
| VEON | published pe != stored pe |
| VIV | published pe != stored pe |
| VMRK | published pe != stored pe |
| VYX | published pe != stored pe |
| WAT | published pe != stored pe |
| WSE | published pe != stored pe |
