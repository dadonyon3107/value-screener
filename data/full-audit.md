# Full-universe data audit

- Generated: 2026-09-02
- Tickers audited: **2985**
- **OK: 915** (30.7%)
- **WARN: 41** (1.4%)
- **FAIL: 2029** (68.0%)

A FAIL means the ticker's own numbers contradict each other, so at least one
is wrong. A WARN is a soft issue - stale vintage, or a check that could not run.
An OK means every identity holds and the per-year ratios match the site's page.

## Issues by type

| issue | tickers | meaning |
|---|---|---|
| pe_price | 1963 | the ratios file's PE disagrees with its own price and the statement EPS |
| published pe != stored pe | 197 | latest.json disagrees with the stored CSV |
| eps_shares | 128 | EPS x shares != net income — share-basis mismatch (ADS vs ordinary) |
| income | 42 | net income != pretax - tax (+ discontinued ops, minority interest) |
| balance | 19 | total assets != liabilities + equity (balance sheet does not balance) |
| ratios not page-overlaid | 13 | still on CSV-export values, not the site's page values |
| no statements | 9 | - |
| roa_impossible | 7 | return on assets above 100% - recomputed off a broken export |
| neg_rev | 3 | negative revenue |
| missing cash_flow | 3 | - |

## FAIL tickers (2029)

| ticker | issues |
|---|---|
| AA | pe_price |
| AAL | pe_price |
| AAMI | pe_price |
| AAP | pe_price, published pe != stored pe |
| AAT | pe_price |
| AAUC | income |
| AB | eps_shares, pe_price |
| ABBV | pe_price |
| ABCB | pe_price |
| ABEV | pe_price |
| ABG | pe_price |
| ABM | pe_price |
| ABNB | pe_price |
| ABR | pe_price |
| ABT | pe_price |
| ACGL | income, pe_price |
| ACI | pe_price, published pe != stored pe |
| ACLS | pe_price |
| ACMR | pe_price |
| ACN | pe_price |
| ACT | pe_price |
| AD | balance, pe_price |
| ADBE | pe_price |
| ADC | pe_price |
| ADI | pe_price |
| ADM | pe_price |
| ADMA | pe_price |
| ADNT | pe_price |
| ADP | pe_price |
| ADT | pe_price |
| ADUS | pe_price |
| AEG | eps_shares, neg_rev, pe_price |
| AEHR | pe_price |
| AEIS | pe_price |
| AEM | pe_price |
| AEO | pe_price |
| AER | pe_price |
| AES | pe_price |
| AESI | pe_price |
| AFL | pe_price |
| AFRM | pe_price |
| AFYA | pe_price |
| AGCO | pe_price |
| AGI | pe_price |
| AGM.A | pe_price, published pe != stored pe |
| AGNC | eps_shares |
| AGO | pe_price |
| AGRO | pe_price, published pe != stored pe |
| AGYS | pe_price |
| AHR | pe_price |
| AIG | pe_price |
| AIN | pe_price |
| AIR | pe_price |
| AIT | pe_price |
| AJG | pe_price |
| AKAM | pe_price |
| AKO.A | pe_price |
| AKO.B | pe_price |
| AKR | pe_price |
| ALAB | pe_price |
| ALB | income, pe_price, published pe != stored pe |
| ALGT | pe_price |
| ALH | balance, pe_price |
| ALK | pe_price |
| ALLE | pe_price |
| ALLY | pe_price |
| ALRM | pe_price |
| ALV | pe_price |
| ALVO | pe_price |
| ALX | pe_price |
| AM | pe_price |
| AMAL | pe_price |
| AMBP | eps_shares |
| AMCR | pe_price |
| AMG | pe_price |
| AMGN | pe_price |
| AMH | pe_price |
| AMKR | pe_price |
| AMLX | pe_price |
| AMN | pe_price |
| AMP | pe_price |
| AMR | pe_price |
| AMRX | pe_price |
| AMRZ | pe_price |
| AMSC | pe_price |
| AMT | pe_price |
| AMTB | pe_price |
| AMX | pe_price |
| AN | pe_price |
| ANDG | eps_shares |
| ANF | pe_price |
| ANIP | pe_price |
| AON | pe_price |
| AOS | pe_price |
| APA | pe_price |
| APAM | pe_price |
| APD | pe_price |
| APH | pe_price |
| APLE | pe_price |
| APO | pe_price |
| APP | pe_price |
| APPF | pe_price |
| APPN | eps_shares, pe_price |
| APTV | pe_price, published pe != stored pe |
| AR | pe_price |
| ARCB | pe_price |
| ARCC | pe_price |
| ARCO | pe_price |
| ARDT | pe_price |
| ARE | pe_price |
| ARES | pe_price |
| ARGX | pe_price |
| ARHS | pe_price |
| ARIS | eps_shares, pe_price |
| ARLO | balance |
| ARLP | pe_price |
| ARM | pe_price |
| ARMK | pe_price |
| AROC | pe_price |
| ARW | pe_price |
| AS | pe_price |
| ASB | pe_price |
| ASIC | balance, pe_price |
| ASM | pe_price |
| ASML | pe_price |
| ASO | pe_price |
| ASR | pe_price |
| ASTH | pe_price |
| ASX | pe_price, published pe != stored pe |
| ATAT | pe_price |
| ATEN | pe_price |
| ATHM | pe_price |
| ATI | pe_price |
| ATLC | pe_price |
| ATO | pe_price |
| ATS | pe_price |
| AU | pe_price, published pe != stored pe |
| AUB | pe_price |
| AUGO | pe_price |
| AUPH | pe_price |
| AVAH | pe_price |
| AVAL | eps_shares, pe_price |
| AVAV | pe_price |
| AVEX | eps_shares |
| AVGO | pe_price |
| AVNT | pe_price |
| AVPT | pe_price |
| AVT | pe_price |
| AVTX | eps_shares |
| AVY | pe_price |
| AX | pe_price |
| AXON | pe_price |
| AXS | pe_price |
| AYA | pe_price |
| AYI | pe_price |
| AZN | pe_price |
| AZO | pe_price |
| AZZ | pe_price |
| B | pe_price |
| BABA | pe_price |
| BAC | pe_price |
| BAH | pe_price |
| BALL | pe_price |
| BAM | pe_price |
| BANC | income, pe_price |
| BANF | pe_price |
| BANR | pe_price |
| BAP | pe_price |
| BAX | pe_price |
| BBAR | eps_shares, pe_price |
| BBD | eps_shares, pe_price, published pe != stored pe |
| BBDO | pe_price |
| BBUC | eps_shares, pe_price |
| BBVA | pe_price |
| BBWI | pe_price |
| BBY | pe_price |
| BC | pe_price |
| BCC | pe_price |
| BCE | pe_price |
| BCH | pe_price |
| BCRX | pe_price |
| BCS | pe_price |
| BDC | pe_price |
| BDX | pe_price, published pe != stored pe |
| BEKE | pe_price |
| BELFA | pe_price |
| BELFB | eps_shares, pe_price, published pe != stored pe |
| BEN | pe_price |
| BF.A | pe_price |
| BF.B | pe_price |
| BFC | pe_price |
| BFH | pe_price |
| BFS | pe_price |
| BFST | pe_price |
| BG | pe_price |
| BGC | pe_price |
| BGSI | pe_price, published pe != stored pe |
| BH | pe_price |
| BH.A | pe_price |
| BHE | pe_price |
| BHF | pe_price |
| BHP | pe_price |
| BHRB | pe_price |
| BIDU | pe_price |
| BILL | eps_shares |
| BIO.B | pe_price |
| BIP | eps_shares, pe_price |
| BIRK | pe_price |
| BJRI | pe_price |
| BKE | pe_price |
| BKH | pe_price |
| BKNG | pe_price |
| BKR | pe_price |
| BKU | pe_price |
| BKV | pe_price |
| BL | pe_price |
| BLBD | pe_price |
| BLDR | pe_price |
| BLFS | eps_shares |
| BLK | pe_price |
| BLKB | pe_price |
| BLLN | pe_price |
| BLX | pe_price |
| BMA | pe_price |
| BMNR | eps_shares, income, pe_price |
| BMO | pe_price |
| BMRN | pe_price |
| BMY | pe_price |
| BN | pe_price |
| BNL | pe_price |
| BNS | pe_price |
| BNT | eps_shares, published pe != stored pe |
| BNTX | pe_price |
| BNY | pe_price |
| BOH | pe_price |
| BOKF | pe_price |
| BORR | pe_price |
| BOW | pe_price |
| BOX | pe_price |
| BP | pe_price |
| BPOP | pe_price |
| BR | pe_price |
| BRAI | eps_shares, roa_impossible |
| BRBI | pe_price, published pe != stored pe |
| BRBR | pe_price |
| BRC | pe_price |
| BRK.A | pe_price |
| BRK.B | pe_price |
| BRKR | pe_price |
| BRO | pe_price |
| BROS | pe_price |
| BRSL | pe_price, published pe != stored pe |
| BRX | pe_price |
| BSAC | eps_shares, pe_price |
| BSBR | pe_price, published pe != stored pe |
| BSM | pe_price |
| BSY | pe_price |
| BTDR | eps_shares |
| BTE | pe_price |
| BTG | pe_price |
| BTI | pe_price |
| BTSG | pe_price |
| BTU | pe_price |
| BUSE | pe_price |
| BV | income, pe_price |
| BVN | pe_price, published pe != stored pe |
| BVS | pe_price |
| BWA | pe_price |
| BWLP | pe_price |
| BX | pe_price |
| BXP | pe_price |
| BXSL | pe_price |
| BY | pe_price |
| BYD | pe_price |
| BZ | pe_price |
| C | pe_price |
| CACC | pe_price |
| CAE | pe_price |
| CAG | pe_price |
| CAI | eps_shares |
| CAKE | pe_price |
| CALM | pe_price |
| CALX | pe_price |
| CALY | pe_price |
| CAMT | pe_price, published pe != stored pe |
| CAR | pe_price |
| CARG | pe_price, published pe != stored pe |
| CART | pe_price |
| CASH | pe_price |
| CAT | pe_price |
| CATY | pe_price |
| CAVA | pe_price |
| CB | pe_price |
| CBC | pe_price |
| CBL | income, pe_price |
| CBOE | pe_price |
| CBRE | pe_price |
| CBRL | pe_price |
| CBSH | pe_price |
| CBT | pe_price |
| CBU | pe_price |
| CBZ | pe_price |
| CC | pe_price |
| CCC | income, pe_price |
| CCEC | eps_shares, pe_price |
| CCEP | pe_price |
| CCI | eps_shares, pe_price, published pe != stored pe |
| CCJ | pe_price |
| CCK | pe_price |
| CCL | pe_price |
| CCS | pe_price |
| CCU | pe_price |
| CDE | balance, pe_price |
| CDLR | pe_price |
| CDNA | pe_price |
| CDNL | eps_shares, pe_price |
| CDP | pe_price |
| CDRE | pe_price |
| CDW | pe_price |
| CECO | pe_price |
| CENT | pe_price |
| CENTA | pe_price |
| CENX | pe_price |
| CEPU | pe_price, published pe != stored pe |
| CET | pe_price |
| CF | pe_price |
| CFFN | pe_price |
| CFG | pe_price |
| CFR | pe_price |
| CGAU | pe_price |
| CHA | pe_price, published pe != stored pe |
| CHCO | pe_price |
| CHD | pe_price |
| CHDN | pe_price |
| CHE | pe_price |
| CHEF | pe_price |
| CHKP | pe_price |
| CHRD | eps_shares, pe_price |
| CHRN | eps_shares |
| CHRW | pe_price |
| CHT | pe_price |
| CHTR | pe_price |
| CHWY | eps_shares, pe_price |
| CI | pe_price |
| CIB | eps_shares, pe_price, published pe != stored pe |
| CIEN | pe_price |
| CIG | pe_price, published pe != stored pe |
| CIGI | pe_price |
| CL | pe_price |
| CLBK | pe_price, published pe != stored pe |
| CLBT | pe_price |
| CLSK | pe_price |
| CLX | pe_price |
| CM | pe_price |
| CMBT | pe_price, published pe != stored pe |
| CMC | pe_price |
| CMCSA | pe_price |
| CME | pe_price |
| CMI | pe_price |
| CMP | pe_price |
| CMPR | pe_price |
| CMRE | pe_price |
| CNC | pe_price |
| CNH | pe_price |
| CNI | pe_price |
| CNK | pe_price |
| CNL | eps_shares |
| CNM | pe_price |
| CNO | pe_price |
| CNOB | pe_price |
| CNQ | pe_price |
| CNR | pe_price |
| CNS | pe_price |
| CNX | pe_price |
| CNXC | pe_price |
| COCO | pe_price |
| COF | pe_price |
| COHR | pe_price |
| COIN | pe_price |
| COKE | pe_price |
| COLB | pe_price |
| COLM | pe_price |
| CON | pe_price |
| COP | pe_price |
| CORT | pe_price |
| COST | pe_price |
| CP | pe_price |
| CPA | pe_price |
| CPAC | pe_price |
| CPAY | pe_price |
| CPB | pe_price |
| CPK | pe_price |
| CPNG | pe_price |
| CPT | pe_price |
| CQP | pe_price |
| CRBG | pe_price |
| CRC | pe_price |
| CRCL | eps_shares |
| CRCT | pe_price |
| CRDO | pe_price |
| CRGY | eps_shares, pe_price, published pe != stored pe |
| CRH | pe_price |
| CRI | balance, pe_price |
| CRK | pe_price |
| CRL | eps_shares |
| CRML | eps_shares |
| CROX | pe_price |
| CRSR | pe_price |
| CRUS | pe_price |
| CRVS | eps_shares |
| CRWD | pe_price, published pe != stored pe |
| CSAN | pe_price |
| CSCO | pe_price |
| CSGP | pe_price |
| CSL | pe_price |
| CSTL | pe_price |
| CSTM | balance, pe_price |
| CSW | pe_price |
| CSWC | pe_price |
| CTBI | pe_price |
| CTRE | pe_price |
| CTRI | pe_price |
| CTS | pe_price |
| CTSH | pe_price |
| CUBE | pe_price |
| CUBI | pe_price |
| CUZ | pe_price |
| CVBF | pe_price |
| CVCO | eps_shares, pe_price |
| CVE | pe_price |
| CVI | pe_price |
| CVLT | pe_price |
| CVNA | eps_shares, pe_price |
| CVS | pe_price |
| CVSA | pe_price |
| CVX | pe_price |
| CWEN | pe_price |
| CWK | pe_price |
| CWST | income, pe_price |
| CX | eps_shares, pe_price, published pe != stored pe |
| CXM | pe_price |
| CXT | pe_price |
| CXW | pe_price |
| CYD | pe_price, published pe != stored pe |
| DAC | pe_price |
| DAL | pe_price |
| DAN | pe_price |
| DAO | pe_price |
| DASH | pe_price |
| DAVE | pe_price |
| DB | pe_price |
| DBD | eps_shares, pe_price |
| DBRG | pe_price |
| DBX | pe_price |
| DCO | pe_price |
| DCOM | pe_price |
| DD | pe_price, published pe != stored pe |
| DDOG | pe_price |
| DDS | pe_price |
| DEA | pe_price |
| DEC | pe_price |
| DECK | pe_price |
| DEI | pe_price |
| DELL | pe_price |
| DEO | pe_price |
| DFH | pe_price |
| DFIN | pe_price |
| DG | pe_price |
| DGII | pe_price |
| DGX | pe_price |
| DHI | pe_price |
| DHT | pe_price |
| DINO | pe_price |
| DIS | pe_price |
| DK | pe_price |
| DKL | pe_price |
| DKNG | eps_shares |
| DKS | pe_price |
| DLB | pe_price |
| DLR | pe_price |
| DLTR | pe_price |
| DLX | pe_price |
| DMC | pe_price |
| DMLP | pe_price |
| DNN | pe_price |
| DOC | pe_price |
| DOCN | pe_price |
| DOCS | pe_price |
| DOCU | pe_price |
| DOLE | pe_price, published pe != stored pe |
| DOO | pe_price |
| DOV | pe_price |
| DOW | pe_price |
| DOX | pe_price |
| DPZ | pe_price |
| DRD | pe_price |
| DRH | pe_price |
| DRI | pe_price |
| DTM | pe_price |
| DUOL | pe_price |
| DV | pe_price |
| DVA | pe_price |
| DVN | pe_price |
| DX | pe_price, published pe != stored pe |
| DXC | pe_price |
| DXCM | pe_price |
| DXPE | pe_price |
| E | pe_price, published pe != stored pe |
| EAT | pe_price |
| EBAY | pe_price |
| EBC | pe_price |
| EC | pe_price, published pe != stored pe |
| ECL | pe_price |
| ECO | pe_price |
| ECPG | pe_price |
| ECVT | pe_price |
| EDN | income, pe_price |
| EDU | pe_price |
| EE | eps_shares, pe_price |
| EEFT | pe_price |
| EFC | pe_price |
| EFOR | pe_price |
| EFSC | pe_price |
| EFXT | pe_price |
| EG | pe_price |
| EGO | pe_price, published pe != stored pe |
| EGP | pe_price |
| EL | pe_price |
| ELE | pe_price |
| ELF | pe_price |
| ELPC | eps_shares, pe_price |
| ELS | pe_price |
| ELVR | pe_price |
| EMBJ | pe_price, published pe != stored pe |
| EMN | pe_price |
| EMR | pe_price |
| ENB | pe_price |
| ENIC | pe_price |
| ENLT | pe_price |
| ENPH | pe_price |
| ENR | eps_shares, pe_price |
| ENS | pe_price |
| ENSG | pe_price |
| ENVA | pe_price |
| EOG | pe_price |
| EPAM | pe_price |
| EPC | pe_price |
| EPD | pe_price |
| EPR | pe_price |
| EPRT | pe_price |
| EQBK | pe_price |
| EQH | pe_price |
| EQIX | pe_price |
| EQNR | pe_price, published pe != stored pe |
| EQT | pe_price |
| EQX | eps_shares, pe_price |
| ERIC | pe_price, published pe != stored pe |
| ERIE | pe_price |
| ERO | pe_price |
| ES | pe_price |
| ESBA | pe_price |
| ESI | pe_price |
| ESLT | pe_price |
| ESNT | pe_price |
| ESQ | balance, pe_price |
| ESRT | pe_price |
| ESS | pe_price |
| ESTC | pe_price |
| ET | pe_price |
| ETN | pe_price |
| ETOR | pe_price |
| ETSY | pe_price, published pe != stored pe |
| EVR | pe_price |
| EWBC | pe_price |
| EXEL | pe_price |
| EXK | pe_price |
| EXLS | pe_price |
| EXP | pe_price |
| EXPE | pe_price |
| EXR | pe_price |
| EXTR | pe_price |
| EZPW | pe_price |
| F | pe_price |
| FANG | pe_price |
| FAST | pe_price |
| FBIN | pe_price |
| FBK | pe_price |
| FBNC | pe_price |
| FBP | pe_price |
| FCF | pe_price |
| FCN | pe_price |
| FCNCA | pe_price |
| FCPT | pe_price |
| FCX | pe_price |
| FDX | pe_price |
| FE | eps_shares |
| FER | pe_price, published pe != stored pe |
| FERG | eps_shares, pe_price |
| FFBC | pe_price |
| FFIN | pe_price |
| FFIV | pe_price |
| FG | pe_price |
| FHB | pe_price |
| FHI | pe_price |
| FHN | pe_price |
| FIBK | pe_price |
| FICO | pe_price |
| FIGR | pe_price |
| FIGS | pe_price |
| FISV | pe_price |
| FITB | pe_price |
| FIVN | pe_price |
| FIZZ | pe_price |
| FLEX | pe_price |
| FLNC | pe_price |
| FLNG | pe_price |
| FLO | pe_price, published pe != stored pe |
| FLOC | eps_shares, pe_price |
| FLR | pe_price |
| FLS | pe_price |
| FLYW | pe_price |
| FMBH | pe_price |
| FMC | pe_price |
| FMS | pe_price |
| FMX | eps_shares, pe_price, published pe != stored pe |
| FNB | pe_price |
| FORTY | pe_price |
| FOUR | pe_price |
| FOX | pe_price |
| FOXA | pe_price |
| FR | pe_price |
| FRME | pe_price |
| FRO | pe_price, published pe != stored pe |
| FRPT | pe_price |
| FRSH | pe_price |
| FRT | pe_price |
| FSBC | pe_price |
| FSK | pe_price |
| FTAI | pe_price |
| FTDR | pe_price |
| FTI | pe_price |
| FTNT | pe_price |
| FTRE | eps_shares |
| FTV | pe_price |
| FULT | pe_price |
| FUTU | pe_price |
| FWONA | eps_shares, pe_price, published pe != stored pe |
| G | pe_price |
| GABC | pe_price |
| GAP | pe_price |
| GATX | pe_price |
| GBCI | pe_price |
| GBDC | pe_price |
| GBTG | eps_shares, pe_price |
| GCMG | eps_shares, pe_price |
| GCT | pe_price |
| GD | pe_price |
| GDDY | pe_price |
| GDRX | pe_price, published pe != stored pe |
| GDS | pe_price |
| GE | pe_price |
| GEF | pe_price, published pe != stored pe |
| GEF.B | eps_shares, pe_price, published pe != stored pe |
| GEL | pe_price |
| GEN | pe_price |
| GEO | pe_price |
| GFF | pe_price |
| GFI | pe_price, published pe != stored pe |
| GFL | eps_shares, pe_price |
| GGAL | income, pe_price, published pe != stored pe |
| GGB | eps_shares, pe_price, published pe != stored pe |
| GIB | pe_price |
| GIC | pe_price |
| GIII | pe_price |
| GIL | pe_price, published pe != stored pe |
| GILD | pe_price |
| GIS | pe_price |
| GL | pe_price |
| GLBE | pe_price |
| GLNG | pe_price, published pe != stored pe |
| GLOB | pe_price |
| GLP | pe_price |
| GLPI | pe_price |
| GLW | pe_price |
| GLXY | pe_price, roa_impossible |
| GM | pe_price |
| GMAB | pe_price |
| GME | pe_price |
| GMED | pe_price |
| GNK | pe_price |
| GNL | income |
| GNTX | pe_price |
| GNW | pe_price |
| GOLD | pe_price |
| GOLF | pe_price |
| GPC | pe_price |
| GPGI | balance, eps_shares, pe_price |
| GPI | pe_price |
| GPK | pe_price |
| GPN | pe_price |
| GPOR | pe_price |
| GRAB | pe_price |
| GRC | pe_price |
| GRFS | pe_price, published pe != stored pe |
| GRMN | pe_price |
| GRND | pe_price |
| GS | pe_price |
| GSBD | pe_price |
| GSHD | pe_price |
| GSK | pe_price |
| GSL | pe_price |
| GTES | pe_price |
| GTM | pe_price |
| GTX | pe_price |
| GTY | pe_price |
| GVA | pe_price |
| GWRE | pe_price |
| H | pe_price |
| HAE | pe_price |
| HAFN | pe_price, published pe != stored pe |
| HAL | pe_price |
| HALO | pe_price |
| HAS | pe_price |
| HASI | income, pe_price |
| HAYW | pe_price |
| HBAN | income, pe_price |
| HBM | pe_price |
| HBT | pe_price |
| HCA | pe_price |
| HCC | pe_price |
| HCI | pe_price |
| HCM | pe_price |
| HCSG | pe_price |
| HD | pe_price |
| HDB | pe_price |
| HEI | pe_price |
| HEI.A | pe_price |
| HESM | pe_price |
| HFWA | pe_price |
| HG | pe_price |
| HGTY | eps_shares, pe_price, published pe != stored pe |
| HGV | pe_price |
| HHH | pe_price |
| HIG | pe_price |
| HII | pe_price |
| HIMS | pe_price |
| HIMX | pe_price |
| HIW | pe_price |
| HL | income, pe_price |
| HLI | pe_price |
| HLIO | pe_price |
| HLIT | pe_price |
| HLMN | pe_price |
| HLN | pe_price |
| HLNE | pe_price |
| HLT | pe_price |
| HMC | pe_price |
| HMN | pe_price |
| HMY | pe_price |
| HNI | pe_price |
| HOG | pe_price |
| HOMB | pe_price |
| HON | pe_price |
| HOOD | pe_price |
| HOPE | pe_price |
| HP | pe_price |
| HPE | eps_shares, pe_price |
| HPK | balance, pe_price |
| HPQ | pe_price |
| HQY | pe_price |
| HRB | pe_price |
| HRI | pe_price |
| HRL | pe_price |
| HRMY | pe_price |
| HSAI | pe_price |
| HSBC | pe_price |
| HSIC | pe_price |
| HST | pe_price |
| HSY | pe_price |
| HTGC | pe_price |
| HTH | pe_price |
| HTHT | pe_price |
| HUBB | pe_price |
| HUBG | pe_price |
| HUN | pe_price |
| HURN | pe_price |
| HUT | pe_price |
| HWC | pe_price |
| HZO | pe_price, published pe != stored pe |
| IAG | pe_price |
| IART | pe_price |
| IBKR | pe_price |
| IBM | pe_price |
| IBN | pe_price |
| IBOC | pe_price |
| IBP | pe_price |
| ICE | pe_price |
| ICL | pe_price |
| ICLR | pe_price, published pe != stored pe |
| ICUI | eps_shares |
| IDCC | pe_price |
| IE | eps_shares |
| IESC | pe_price |
| IEX | pe_price |
| IFF | pe_price |
| IFS | pe_price |
| IHG | pe_price |
| IHS | income, published pe != stored pe |
| IIPR | pe_price |
| ILMN | pe_price |
| IMAX | pe_price |
| IMC | roa_impossible |
| IMCR | eps_shares |
| IMKTA | pe_price |
| IMO | pe_price |
| IMOS | pe_price, published pe != stored pe |
| IMTX | pe_price |
| INBX | pe_price |
| INCY | pe_price |
| INDB | pe_price |
| INDV | pe_price |
| INFQ | eps_shares |
| INFY | pe_price |
| ING | pe_price |
| INGM | pe_price |
| INGR | pe_price |
| INNV | eps_shares |
| INOD | pe_price |
| INSP | pe_price |
| INSW | pe_price |
| INTR | pe_price |
| INVA | pe_price |
| INVH | pe_price |
| INVX | pe_price |
| IOSP | pe_price |
| IP | income, pe_price |
| IPAR | pe_price |
| IQMX | eps_shares |
| IQV | pe_price |
| IRDM | pe_price |
| IREN | pe_price |
| IRM | pe_price |
| IRMD | pe_price |
| IRS | income, pe_price, published pe != stored pe |
| IRT | balance, pe_price |
| ISRG | pe_price |
| IT | pe_price |
| ITGR | pe_price |
| ITRI | pe_price |
| ITRN | pe_price |
| ITT | pe_price |
| ITUB | pe_price |
| ITW | pe_price |
| IVT | pe_price |
| IVZ | pe_price |
| IX | pe_price |
| J | pe_price |
| JAZZ | pe_price |
| JBHT | pe_price |
| JBL | pe_price |
| JBS | pe_price |
| JCAP | pe_price, published pe != stored pe |
| JCI | pe_price, published pe != stored pe |
| JD | pe_price |
| JEF | pe_price |
| JHX | pe_price |
| JJSF | pe_price |
| JKHY | pe_price |
| JLL | pe_price |
| JOE | pe_price |
| JOYY | pe_price |
| JPM | pe_price |
| JXN | pe_price |
| KALU | pe_price |
| KARO | pe_price |
| KB | pe_price |
| KBH | pe_price |
| KD | pe_price |
| KDP | pe_price |
| KEEL | income |
| KEN | income, pe_price |
| KEP | pe_price, published pe != stored pe |
| KEX | pe_price |
| KEY | pe_price |
| KFY | pe_price |
| KGC | pe_price |
| KGS | pe_price |
| KHC | pe_price |
| KIM | pe_price |
| KKR | pe_price |
| KLIC | pe_price |
| KMB | pe_price |
| KMI | pe_price |
| KMPR | pe_price |
| KMT | pe_price |
| KMX | pe_price |
| KN | pe_price |
| KNSA | pe_price |
| KNTK | eps_shares, pe_price |
| KNX | pe_price |
| KO | pe_price |
| KOF | pe_price |
| KOS | pe_price |
| KR | pe_price |
| KRC | pe_price |
| KRG | pe_price |
| KRO | pe_price |
| KRP | pe_price |
| KRYS | pe_price |
| KSPI | pe_price |
| KSS | pe_price |
| KT | pe_price, published pe != stored pe |
| KTOS | eps_shares |
| KVUE | pe_price |
| KWR | pe_price |
| KYIV | income, pe_price |
| L | pe_price |
| LAD | pe_price |
| LAMR | pe_price |
| LAUR | pe_price |
| LAZ | pe_price |
| LB | eps_shares, pe_price |
| LBTYA | pe_price |
| LBTYB | pe_price |
| LBTYK | pe_price |
| LCII | pe_price |
| LDOS | pe_price |
| LEA | pe_price |
| LEN | pe_price |
| LEN.B | pe_price |
| LEU | pe_price |
| LEVI | balance, pe_price |
| LFST | pe_price |
| LFUS | pe_price |
| LGN | eps_shares |
| LGND | pe_price |
| LHX | pe_price |
| LI | pe_price |
| LIF | pe_price |
| LIME | eps_shares |
| LKFN | pe_price |
| LKFT | pe_price |
| LKQ | pe_price |
| LLYVA | eps_shares, pe_price |
| LMT | pe_price |
| LNN | pe_price |
| LNTH | pe_price |
| LOAR | pe_price |
| LOGI | pe_price |
| LOMA | pe_price, published pe != stored pe |
| LOW | pe_price |
| LPG | pe_price |
| LPX | pe_price |
| LQDT | pe_price |
| LRN | pe_price |
| LSCC | pe_price |
| LSTR | pe_price |
| LTC | pe_price |
| LTGO | eps_shares, roa_impossible |
| LTH | pe_price |
| LTM | pe_price |
| LU | pe_price |
| LULU | pe_price |
| LUNR | pe_price |
| LUV | pe_price |
| LUXE | pe_price, published pe != stored pe |
| LVS | pe_price |
| LW | pe_price |
| LXP | pe_price |
| LYB | pe_price |
| LYFT | pe_price |
| LYG | pe_price |
| LYV | eps_shares |
| LZ | pe_price |
| LZB | pe_price |
| M | pe_price |
| MAA | pe_price |
| MAIN | pe_price |
| MAN | pe_price |
| MARA | eps_shares, pe_price |
| MAS | pe_price |
| MAT | pe_price |
| MATX | pe_price |
| MBC | pe_price |
| MBIN | pe_price |
| MBLY | eps_shares |
| MBWM | pe_price |
| MC | pe_price |
| MCB | pe_price |
| MCBS | pe_price |
| MCD | pe_price |
| MCHB | eps_shares, income, pe_price |
| MCHP | pe_price |
| MDA | pe_price |
| MDLN | eps_shares |
| MDLZ | pe_price |
| MDT | pe_price |
| MDU | pe_price |
| MEDP | pe_price |
| MEOH | pe_price |
| MET | pe_price |
| META | pe_price |
| MFC | pe_price |
| MFG | pe_price |
| MGA | pe_price |
| MGM | pe_price |
| MGNI | pe_price |
| MGRC | pe_price |
| MGRT | pe_price, published pe != stored pe |
| MGY | pe_price |
| MH | pe_price |
| MHO | pe_price |
| MIDD | pe_price |
| MIR | pe_price, published pe != stored pe |
| MKC | pe_price |
| MKC.V | pe_price |
| MKTX | pe_price |
| MLCO | pe_price |
| MLI | pe_price |
| MMS | pe_price |
| MMYT | pe_price |
| MNDY | pe_price |
| MNKD | pe_price |
| MNR | pe_price |
| MNSO | pe_price, published pe != stored pe |
| MNST | pe_price |
| MO | pe_price |
| MOD | pe_price |
| MOH | pe_price |
| MOS | pe_price |
| MP | pe_price |
| MPC | pe_price |
| MPLX | pe_price |
| MQ | pe_price |
| MRK | pe_price |
| MRP | eps_shares, pe_price |
| MRSH | pe_price |
| MRTN | pe_price |
| MRVL | pe_price |
| MRX | pe_price |
| MS | pe_price |
| MSA | pe_price |
| MSCI | pe_price |
| MSDL | pe_price |
| MSGE | pe_price |
| MSM | pe_price |
| MSTR | pe_price |
| MT | pe_price, published pe != stored pe |
| MTB | pe_price |
| MTCH | pe_price |
| MTDR | pe_price |
| MTG | pe_price |
| MTH | pe_price |
| MTN | pe_price |
| MTSI | pe_price |
| MUFG | income, pe_price |
| MUR | pe_price |
| MUSA | pe_price |
| MUX | eps_shares, pe_price |
| MWA | pe_price |
| MYE | pe_price |
| MYRG | pe_price |
| MZTI | pe_price |
| NAT | pe_price, published pe != stored pe |
| NATL | pe_price |
| NBHC | pe_price |
| NBIS | pe_price |
| NBIX | pe_price |
| NBN | pe_price, published pe != stored pe |
| NBR | eps_shares, pe_price |
| NBTB | pe_price |
| NCLH | pe_price |
| NCNO | pe_price |
| NDAQ | pe_price |
| NDSN | pe_price |
| NE | pe_price |
| NESR | pe_price |
| NEU | pe_price |
| NFLX | pe_price |
| NGG | pe_price |
| NHC | pe_price |
| NHI | pe_price |
| NI | pe_price |
| NIC | pe_price |
| NICE | pe_price |
| NKE | pe_price |
| NLY | pe_price |
| NMIH | pe_price |
| NMR | pe_price |
| NMRK | pe_price |
| NNN | pe_price |
| NOC | pe_price |
| NOG | pe_price |
| NOK | pe_price |
| NOMD | pe_price |
| NOV | pe_price |
| NOVT | pe_price |
| NPK | pe_price |
| NPKI | pe_price |
| NRG | pe_price |
| NRP | pe_price |
| NSC | pe_price |
| NSIT | pe_price |
| NSP | pe_price |
| NSSC | pe_price |
| NTB | pe_price |
| NTES | income, pe_price |
| NTNX | pe_price, published pe != stored pe |
| NTR | pe_price |
| NTRS | income, pe_price |
| NTST | pe_price |
| NU | pe_price |
| NUTX | pe_price |
| NVAX | pe_price |
| NVGS | pe_price |
| NVMI | pe_price |
| NVO | pe_price |
| NVR | pe_price |
| NVS | pe_price |
| NVST | pe_price |
| NWBI | pe_price |
| NWG | income, pe_price |
| NWN | pe_price |
| NWPX | pe_price |
| NWS | pe_price |
| NWSA | pe_price |
| NXPI | pe_price |
| NXST | pe_price |
| NXT | pe_price |
| NYAX | pe_price |
| NYT | pe_price |
| O | pe_price |
| OBDC | pe_price |
| OBK | pe_price |
| OC | pe_price |
| OCFC | pe_price, published pe != stored pe |
| OCSL | pe_price |
| ODC | pe_price |
| OFG | pe_price |
| OGC | pe_price |
| OGE | pe_price |
| OGN | pe_price |
| OHI | pe_price |
| OKE | pe_price |
| OKTA | eps_shares, pe_price |
| OLED | pe_price |
| OLN | pe_price |
| OMAB | pe_price |
| OMC | pe_price, published pe != stored pe |
| OMCL | pe_price |
| ON | pe_price |
| ONB | pe_price |
| ONC | pe_price, published pe != stored pe |
| ONON | pe_price |
| OPCH | pe_price |
| OPLN | pe_price |
| OPRA | pe_price |
| OPY | pe_price |
| OR | pe_price |
| ORI | pe_price |
| ORLY | pe_price |
| OSBC | pe_price |
| OSCR | pe_price, published pe != stored pe |
| OSIS | pe_price |
| OSK | pe_price |
| OTEX | pe_price |
| OTF | pe_price |
| OTIS | pe_price |
| OTTR | pe_price |
| OUT | pe_price |
| OVV | pe_price |
| OWL | pe_price |
| OXY | pe_price, published pe != stored pe |
| OZK | pe_price, published pe != stored pe |
| P | pe_price |
| PAA | pe_price |
| PAAS | pe_price |
| PAC | pe_price |
| PACS | pe_price |
| PAG | pe_price |
| PAGP | pe_price, published pe != stored pe |
| PAGS | pe_price |
| PAHC | pe_price |
| PAM | pe_price, published pe != stored pe |
| PANW | pe_price |
| PARR | pe_price |
| PATK | pe_price |
| PAX | pe_price |
| PAY | pe_price |
| PAYO | pe_price |
| PAYP | pe_price |
| PAYX | pe_price |
| PB | pe_price |
| PBA | pe_price |
| PBF | pe_price |
| PBH | pe_price |
| PBI | pe_price |
| PBR | eps_shares, pe_price, published pe != stored pe |
| PBR.A | pe_price |
| PCAR | pe_price |
| PCOR | balance |
| PCRX | pe_price |
| PCTY | pe_price |
| PDD | pe_price |
| PDFS | income, pe_price |
| PDS | pe_price |
| PEBO | pe_price |
| PECO | pe_price |
| PEGA | pe_price |
| PEN | eps_shares |
| PENG | eps_shares, pe_price |
| PEP | pe_price |
| PFBC | pe_price |
| PFE | pe_price |
| PFG | pe_price |
| PFS | pe_price |
| PFSI | pe_price |
| PG | pe_price |
| PGEN | eps_shares |
| PGNY | pe_price |
| PGY | pe_price |
| PHI | pe_price |
| PHIN | pe_price |
| PI | pe_price |
| PII | pe_price |
| PINS | pe_price, published pe != stored pe |
| PIPR | pe_price |
| PJT | pe_price, published pe != stored pe |
| PK | pe_price |
| PKG | pe_price |
| PKX | pe_price, published pe != stored pe |
| PLD | pe_price |
| PLGO | pe_price |
| PLMR | pe_price |
| PLNT | pe_price |
| PLTR | pe_price |
| PLXS | pe_price |
| PM | pe_price |
| PNC | pe_price |
| PNFP | pe_price |
| PNR | pe_price |
| PNTG | pe_price |
| PNW | pe_price |
| PODD | pe_price |
| POOL | pe_price |
| POR | pe_price |
| POST | pe_price |
| POWI | pe_price |
| PPC | pe_price |
| PPG | pe_price |
| PPLI | pe_price |
| PPTA | eps_shares |
| PR | pe_price |
| PRCH | income |
| PRG | pe_price |
| PRGS | pe_price |
| PRI | eps_shares, pe_price |
| PRK | pe_price |
| PRKS | pe_price |
| PRLB | pe_price |
| PRM | pe_price |
| PRMB | eps_shares |
| PRSU | eps_shares, pe_price |
| PRVA | pe_price |
| PSA | pe_price |
| PSEC | pe_price |
| PSMT | pe_price |
| PSN | pe_price |
| PSNY | balance |
| PSO | pe_price |
| PSX | pe_price |
| PTC | balance |
| PTCT | pe_price |
| PTEN | pe_price |
| PTGX | pe_price, published pe != stored pe |
| PTON | pe_price |
| PUK | pe_price |
| PUMP | pe_price |
| PURR | pe_price |
| PVH | pe_price |
| PVLA | eps_shares |
| PWP | eps_shares, pe_price |
| PWR | pe_price |
| PYPL | pe_price |
| QCOM | pe_price |
| QFIN | pe_price |
| QGEN | pe_price |
| QLYS | pe_price |
| QNST | pe_price |
| QRVO | pe_price |
| QSR | pe_price |
| QTWO | pe_price |
| QXO | eps_shares |
| RACE | pe_price |
| RAMP | pe_price |
| RBA | pe_price |
| RBC | pe_price |
| RBCAA | pe_price |
| RCI | pe_price |
| RCL | pe_price |
| RDDT | pe_price |
| RDN | pe_price |
| RDNT | pe_price |
| RDVT | pe_price |
| RDWR | pe_price |
| RDY | pe_price, published pe != stored pe |
| REG | pe_price |
| REGN | pe_price |
| RELX | pe_price |
| RELY | pe_price |
| RES | pe_price |
| REXR | pe_price |
| REYN | pe_price |
| REZI | pe_price |
| RF | pe_price |
| RGLD | pe_price |
| RH | pe_price |
| RHI | pe_price |
| RHP | pe_price |
| RIO | pe_price |
| RIOT | pe_price |
| RITM | pe_price |
| RJF | pe_price |
| RKT | eps_shares, pe_price, published pe != stored pe |
| RL | pe_price |
| RLJ | pe_price, published pe != stored pe |
| RLX | pe_price |
| RMBS | pe_price |
| RNG | pe_price |
| RNR | pe_price |
| RNST | pe_price |
| RNW | pe_price |
| ROIV | pe_price |
| ROK | pe_price |
| ROL | pe_price |
| ROST | pe_price |
| RPM | pe_price |
| RPRX | pe_price |
| RRC | pe_price |
| RRR | pe_price |
| RSG | pe_price |
| RSI | eps_shares, pe_price |
| RTO | pe_price, published pe != stored pe |
| RTX | pe_price |
| RUN | pe_price |
| RUSHA | pe_price |
| RUSHB | pe_price |
| RVLV | pe_price |
| RVTY | pe_price |
| RXO | pe_price |
| RY | pe_price |
| RYAAY | pe_price |
| RYAN | pe_price |
| RYN | income, pe_price, published pe != stored pe |
| RYZ | pe_price |
| SAFE | pe_price |
| SAIC | pe_price |
| SAM | pe_price |
| SAN | pe_price, published pe != stored pe |
| SANM | pe_price |
| SAP | pe_price |
| SARO | pe_price |
| SBAC | pe_price |
| SBCF | pe_price |
| SBET | pe_price |
| SBGI | pe_price |
| SBH | pe_price |
| SBLK | pe_price |
| SBRA | pe_price |
| SBS | pe_price, published pe != stored pe |
| SBUX | pe_price |
| SCCO | pe_price |
| SCHW | pe_price |
| SCL | pe_price |
| SCSC | pe_price |
| SDGR | pe_price |
| SDRL | pe_price, published pe != stored pe |
| SE | pe_price |
| SEB | pe_price |
| SEI | pe_price |
| SEIC | pe_price |
| SENEA | pe_price |
| SENEB | pe_price |
| SEZL | pe_price |
| SF | pe_price |
| SFBS | pe_price |
| SFD | pe_price |
| SFL | pe_price |
| SFNC | pe_price |
| SGHC | pe_price |
| SHAK | pe_price |
| SHC | pe_price |
| SHEL | pe_price, published pe != stored pe |
| SHG | pe_price |
| SHLS | pe_price |
| SHO | pe_price |
| SHOO | pe_price |
| SHOP | pe_price |
| SID | eps_shares |
| SIFY | pe_price |
| SIG | pe_price |
| SIM | pe_price, published pe != stored pe |
| SIMO | pe_price, published pe != stored pe |
| SIRI | pe_price |
| SJM | pe_price |
| SKM | pe_price, published pe != stored pe |
| SKT | pe_price |
| SKWD | pe_price |
| SKY | pe_price |
| SKYW | pe_price |
| SLB | pe_price |
| SLBT | eps_shares |
| SLDE | pe_price |
| SLG | pe_price |
| SLGN | pe_price |
| SLM | pe_price |
| SLSR | eps_shares, pe_price |
| SLVM | pe_price |
| SM | pe_price |
| SMCI | pe_price, published pe != stored pe |
| SMFG | pe_price |
| SMG | pe_price |
| SMMT | roa_impossible |
| SMTC | income |
| SNA | pe_price |
| SNDK | pe_price |
| SNDR | pe_price |
| SNEX | pe_price |
| SNN | pe_price |
| SNPS | eps_shares, pe_price |
| SNY | pe_price |
| SOBO | pe_price |
| SOFI | pe_price |
| SOMN | pe_price |
| SON | pe_price |
| SONY | pe_price |
| SOUN | eps_shares |
| SPB | eps_shares, pe_price |
| SPG | pe_price |
| SPGI | pe_price |
| SPH | pe_price |
| SPHR | pe_price |
| SPNT | pe_price |
| SPOT | pe_price |
| SPXC | pe_price |
| SQM | pe_price, published pe != stored pe |
| SR | pe_price |
| SRAD | pe_price |
| SRCE | pe_price |
| SRPT | pe_price |
| SSB | pe_price |
| SSL | pe_price, published pe != stored pe |
| SSNC | pe_price |
| SSRM | pe_price |
| ST | pe_price |
| STAG | pe_price |
| STBA | pe_price |
| STC | pe_price |
| STEP | pe_price |
| STGW | pe_price, published pe != stored pe |
| STLA | pe_price |
| STM | pe_price |
| STN | pe_price |
| STNE | eps_shares, pe_price |
| STNG | pe_price |
| STRA | pe_price |
| STT | pe_price |
| STVN | pe_price |
| STWD | pe_price |
| STX | pe_price |
| STZ | pe_price |
| SU | pe_price |
| SUI | pe_price |
| SUN | pe_price |
| SUNB | pe_price |
| SUPN | pe_price |
| SUZ | income, pe_price |
| SVM | pe_price, published pe != stored pe |
| SVV | pe_price |
| SW | pe_price |
| SWK | pe_price |
| SWKS | pe_price |
| SXT | pe_price |
| SYBT | pe_price |
| SYF | pe_price |
| SYRE | eps_shares |
| SYY | pe_price |
| T | pe_price |
| TAC | income |
| TAK | eps_shares, pe_price |
| TAL | pe_price |
| TALO | balance, pe_price |
| TAP | pe_price |
| TAP.A | pe_price |
| TBBK | pe_price |
| TBLA | pe_price |
| TCBK | pe_price |
| TCOM | pe_price |
| TD | pe_price |
| TDC | pe_price |
| TDG | pe_price |
| TDY | pe_price |
| TECK | eps_shares, pe_price |
| TEL | pe_price |
| TEN | pe_price, published pe != stored pe |
| TEO | pe_price |
| TER | pe_price |
| TFC | pe_price |
| TFII | pe_price |
| TFIN | pe_price |
| TFPM | pe_price |
| TFSL | pe_price |
| TGB | income, pe_price |
| TGLS | pe_price |
| TGS | pe_price |
| TGT | pe_price |
| TGTX | income, pe_price |
| TH | pe_price |
| THC | pe_price |
| THG | pe_price |
| THO | pe_price |
| TIGO | pe_price |
| TIMB | pe_price |
| TK | pe_price |
| TKC | pe_price |
| TKO | eps_shares, pe_price |
| TKR | pe_price |
| TLK | pe_price |
| TLN | eps_shares, pe_price |
| TLV:ABRA | pe_price |
| TLV:ACCL | pe_price |
| TLV:ACKR | pe_price, published pe != stored pe |
| TLV:ACRO | pe_price, published pe != stored pe |
| TLV:ADGR | pe_price |
| TLV:AFHL | pe_price |
| TLV:AFPR | pe_price |
| TLV:AFRE | pe_price |
| TLV:ALBA | pe_price |
| TLV:ALHE | pe_price |
| TLV:ALLT | pe_price |
| TLV:ALMA | pe_price |
| TLV:ALMY | pe_price, published pe != stored pe |
| TLV:ALTF | pe_price |
| TLV:ALUMA | pe_price |
| TLV:AMD | pe_price |
| TLV:AMOT | pe_price |
| TLV:AMPA | pe_price, published pe != stored pe |
| TLV:AMRK | pe_price |
| TLV:AMRM | pe_price, ratios not page-overlaid |
| TLV:ANLT | pe_price |
| TLV:ARAN | pe_price, published pe != stored pe |
| TLV:ARD | pe_price |
| TLV:ARF | eps_shares, pe_price, published pe != stored pe |
| TLV:ARGO | pe_price |
| TLV:ARIN | pe_price |
| TLV:ARYT | pe_price, published pe != stored pe |
| TLV:ASGR | pe_price, published pe != stored pe |
| TLV:ASHG | pe_price, published pe != stored pe |
| TLV:ASHO | pe_price, published pe != stored pe |
| TLV:ATRY | pe_price |
| TLV:AUDC | pe_price |
| TLV:AURA | pe_price |
| TLV:AVGL | pe_price |
| TLV:AVIA | pe_price |
| TLV:AVIV | pe_price, published pe != stored pe |
| TLV:AVRT | pe_price |
| TLV:AZRG | pe_price |
| TLV:AZRM | pe_price |
| TLV:BEZQ | pe_price |
| TLV:BIG | pe_price |
| TLV:BIRM | pe_price, published pe != stored pe |
| TLV:BKFR | pe_price, published pe != stored pe |
| TLV:BKRY | pe_price |
| TLV:BLEG | eps_shares |
| TLV:BLGO | pe_price, published pe != stored pe |
| TLV:BLSR | pe_price, published pe != stored pe |
| TLV:BOTI | pe_price |
| TLV:BRAN | pe_price |
| TLV:BRIH | pe_price, published pe != stored pe |
| TLV:BRMG | pe_price |
| TLV:BRND | pe_price |
| TLV:BSEN | pe_price |
| TLV:BVC | eps_shares, published pe != stored pe |
| TLV:BWAY | pe_price |
| TLV:CAMT | pe_price |
| TLV:CAST | pe_price |
| TLV:CDEV | pe_price |
| TLV:CEL | pe_price |
| TLV:CILO | pe_price, published pe != stored pe |
| TLV:CISY | pe_price |
| TLV:CMDR | pe_price, published pe != stored pe |
| TLV:CNGL | pe_price, published pe != stored pe |
| TLV:CRML | pe_price |
| TLV:CRSM | pe_price |
| TLV:CRSR | pe_price |
| TLV:DANE | pe_price |
| TLV:DELG | pe_price, published pe != stored pe |
| TLV:DIMRI | pe_price |
| TLV:DIPL | pe_price |
| TLV:DLEA | pe_price |
| TLV:DLEKG | pe_price |
| TLV:DLPR | pe_price |
| TLV:DLTI | pe_price |
| TLV:DNYA | pe_price |
| TLV:DRAL | pe_price |
| TLV:DRSL | pe_price, ratios not page-overlaid |
| TLV:DSCT | pe_price |
| TLV:DUNI | pe_price |
| TLV:ECP | pe_price |
| TLV:EFCP | pe_price, published pe != stored pe |
| TLV:ELAD | pe_price, published pe != stored pe |
| TLV:ELAL | pe_price |
| TLV:ELCO | pe_price, published pe != stored pe |
| TLV:ELLO | eps_shares, pe_price |
| TLV:ELMR | pe_price, published pe != stored pe |
| TLV:ELTR | pe_price |
| TLV:EMDV | pe_price |
| TLV:ENLT | pe_price |
| TLV:ENOG | pe_price |
| TLV:EQTL | pe_price |
| TLV:ESLT | pe_price |
| TLV:ETGA | pe_price |
| TLV:EXPO | pe_price |
| TLV:FBRT | pe_price |
| TLV:FIBI | pe_price |
| TLV:FIBIH | pe_price |
| TLV:FORTY | pe_price |
| TLV:FOX | pe_price |
| TLV:FRDN | pe_price |
| TLV:GAGR | pe_price |
| TLV:GAON | pe_price, published pe != stored pe |
| TLV:GCT | pe_price |
| TLV:GILT | pe_price |
| TLV:GKL | pe_price, published pe != stored pe |
| TLV:GLRS | pe_price |
| TLV:GLTL | pe_price, published pe != stored pe |
| TLV:GNRS | pe_price, published pe != stored pe |
| TLV:GOHO | pe_price |
| TLV:GOLD | pe_price |
| TLV:GOLF | pe_price |
| TLV:GOSS | pe_price, published pe != stored pe |
| TLV:GRIN | pe_price |
| TLV:GSFI | pe_price |
| TLV:GVYM | pe_price |
| TLV:HAMAT | pe_price, published pe != stored pe |
| TLV:HGG | pe_price |
| TLV:HGGE | pe_price |
| TLV:HIPR | pe_price |
| TLV:HLAN | pe_price |
| TLV:HLMS | pe_price |
| TLV:HRON | pe_price, published pe != stored pe |
| TLV:IBI | pe_price |
| TLV:IBIU | pe_price, published pe != stored pe |
| TLV:ICHO | pe_price |
| TLV:ICL | pe_price |
| TLV:ICON | pe_price |
| TLV:ILCO | pe_price |
| TLV:ILDC | pe_price |
| TLV:ILDR | pe_price |
| TLV:ILX | pe_price |
| TLV:IMCO | eps_shares, pe_price |
| TLV:INRM | pe_price |
| TLV:INTR | pe_price |
| TLV:ISCN | pe_price, published pe != stored pe |
| TLV:ISHI | pe_price |
| TLV:ISHO | pe_price |
| TLV:ISI | pe_price |
| TLV:ISRA | pe_price |
| TLV:ISRG | pe_price |
| TLV:ISRO | pe_price |
| TLV:ISRS | pe_price |
| TLV:ISTA | pe_price |
| TLV:JBNK | pe_price |
| TLV:KAFR | pe_price |
| TLV:KARE | pe_price |
| TLV:KLIL | pe_price |
| TLV:KMDA | pe_price |
| TLV:KNFM | pe_price |
| TLV:KRDI | pe_price |
| TLV:KRUR | pe_price, published pe != stored pe |
| TLV:KSTN | pe_price |
| TLV:LAHAV | pe_price |
| TLV:LAPD | pe_price |
| TLV:LBTL | pe_price |
| TLV:LEVI | pe_price |
| TLV:LSCO | pe_price |
| TLV:LUDN | pe_price |
| TLV:LUMI | pe_price |
| TLV:LURO | eps_shares, pe_price |
| TLV:LUZN | pe_price |
| TLV:MAXO | pe_price |
| TLV:MCLL | pe_price |
| TLV:MDPR | pe_price, published pe != stored pe |
| TLV:MDTR | pe_price |
| TLV:MGDO | pe_price, published pe != stored pe |
| TLV:MGOR | pe_price |
| TLV:MGRT | pe_price, published pe != stored pe |
| TLV:MISH | pe_price, published pe != stored pe |
| TLV:MLRN | eps_shares |
| TLV:MLSR | pe_price |
| TLV:MLTH | pe_price, published pe != stored pe |
| TLV:MNIN | pe_price |
| TLV:MNRT | pe_price |
| TLV:MPP | pe_price |
| TLV:MRG | pe_price, published pe != stored pe |
| TLV:MRIN | pe_price |
| TLV:MSLA | pe_price |
| TLV:MTAV | pe_price |
| TLV:MTRD | pe_price, ratios not page-overlaid |
| TLV:MTRN | pe_price |
| TLV:MTRX | pe_price |
| TLV:MVNE | pe_price |
| TLV:MZTF | pe_price |
| TLV:NFTA | pe_price |
| TLV:NICE | pe_price |
| TLV:NTGR | pe_price |
| TLV:NTML | pe_price |
| TLV:NTO | pe_price |
| TLV:NVLG | pe_price |
| TLV:NVMI | pe_price |
| TLV:NVPT | pe_price |
| TLV:NWMD | pe_price |
| TLV:NXSN | pe_price |
| TLV:NXTM | pe_price |
| TLV:ONE | pe_price |
| TLV:ORAD | pe_price |
| TLV:ORIN | neg_rev, pe_price |
| TLV:ORL | pe_price |
| TLV:ORMP | pe_price |
| TLV:ORON | pe_price |
| TLV:OVRS | pe_price |
| TLV:PAYT | pe_price |
| TLV:PAZ | pe_price |
| TLV:PCBT | pe_price |
| TLV:PERI | pe_price |
| TLV:PLRM | pe_price |
| TLV:PLSN | pe_price |
| TLV:PMNT | pe_price |
| TLV:POLI | pe_price |
| TLV:POLP | pe_price, published pe != stored pe |
| TLV:PRMG | pe_price, published pe != stored pe |
| TLV:PRSK | pe_price |
| TLV:PRTC | pe_price |
| TLV:PTBL | pe_price, published pe != stored pe |
| TLV:PTCH | pe_price |
| TLV:PTNR | pe_price |
| TLV:QLTU | pe_price |
| TLV:QNCO | pe_price, published pe != stored pe |
| TLV:RANI | pe_price |
| TLV:RATI | pe_price |
| TLV:RAVD | pe_price |
| TLV:REKA | pe_price |
| TLV:RGAS | pe_price, published pe != stored pe |
| TLV:RIMO | pe_price |
| TLV:RIT1 | pe_price |
| TLV:RLCO | pe_price |
| TLV:RMLI | pe_price |
| TLV:RMN | pe_price |
| TLV:RMON | pe_price |
| TLV:ROTS | pe_price |
| TLV:RPAC | pe_price |
| TLV:RSEL | pe_price, published pe != stored pe |
| TLV:RTLS | pe_price |
| TLV:RTSN | eps_shares, pe_price |
| TLV:RVL | pe_price |
| TLV:SAE | pe_price |
| TLV:SANO1 | pe_price |
| TLV:SCC | pe_price |
| TLV:SCOP | pe_price |
| TLV:SHAN | pe_price |
| TLV:SHGR | pe_price |
| TLV:SHNP | pe_price, published pe != stored pe |
| TLV:SHOM | pe_price |
| TLV:SHVA | pe_price |
| TLV:SKBN | pe_price, published pe != stored pe |
| TLV:SLARL | pe_price |
| TLV:SLRM | pe_price, published pe != stored pe |
| TLV:SMNR | pe_price |
| TLV:SMSH | eps_shares, ratios not page-overlaid |
| TLV:SMT | pe_price |
| TLV:SNCM | pe_price |
| TLV:SOFW | pe_price |
| TLV:SPEN | pe_price |
| TLV:SPNTC | pe_price |
| TLV:SRFT | pe_price, published pe != stored pe |
| TLV:STG | pe_price |
| TLV:STRS | pe_price |
| TLV:TATT | pe_price |
| TLV:TAYA | pe_price, published pe != stored pe |
| TLV:TDRN | pe_price |
| TLV:TFRLF | pe_price, published pe != stored pe |
| TLV:TGI | pe_price |
| TLV:TIGBUR | pe_price |
| TLV:TLSY | neg_rev, pe_price |
| TLV:TMRP | pe_price |
| TLV:TOEN | balance, pe_price |
| TLV:TOPG | pe_price |
| TLV:TPGM | pe_price |
| TLV:TRPZ | pe_price |
| TLV:TRX | pe_price |
| TLV:TSG | pe_price, published pe != stored pe |
| TLV:TTAM | pe_price |
| TLV:TURB | roa_impossible |
| TLV:UMH | pe_price |
| TLV:UNIT | pe_price |
| TLV:VCTR | pe_price |
| TLV:VILR | pe_price |
| TLV:VTNA | pe_price |
| TLV:WILC | pe_price, ratios not page-overlaid |
| TLV:YBOX | pe_price |
| TLV:YHNF | pe_price |
| TLV:ZNKL | pe_price |
| TLX | pe_price |
| TM | pe_price |
| TMC | eps_shares |
| TMDX | pe_price |
| TME | pe_price |
| TMP | pe_price |
| TNC | pe_price |
| TNET | pe_price |
| TNK | pe_price |
| TNL | pe_price |
| TOL | pe_price |
| TOP | pe_price |
| TOST | pe_price |
| TOWN | pe_price, published pe != stored pe |
| TPB | pe_price |
| TPG | eps_shares, pe_price |
| TPL | pe_price |
| TPR | pe_price |
| TRGP | pe_price |
| TRI | pe_price |
| TRIN | pe_price |
| TRIP | income, pe_price, published pe != stored pe |
| TRMD | pe_price |
| TRMK | pe_price |
| TRN | pe_price |
| TRNO | pe_price |
| TROW | pe_price |
| TRP | pe_price |
| TS | pe_price |
| TSAT | pe_price |
| TSCO | pe_price |
| TSLA | pe_price |
| TSLX | pe_price |
| TSM | pe_price |
| TSN | pe_price |
| TTAM | pe_price |
| TTC | pe_price |
| TTD | pe_price |
| TTE | pe_price |
| TTI | pe_price, published pe != stored pe |
| TTMI | pe_price |
| TU | pe_price |
| TUYA | pe_price |
| TV | eps_shares |
| TWFG | pe_price |
| TWLO | pe_price |
| TX | pe_price |
| TXN | pe_price |
| TXNM | pe_price |
| TXRH | pe_price |
| TXT | pe_price |
| TYG | eps_shares, pe_price |
| UAA | pe_price |
| UAN | pe_price |
| UBER | pe_price |
| UBS | pe_price, published pe != stored pe |
| UBSI | pe_price |
| UCB | pe_price |
| UDR | pe_price |
| UE | pe_price |
| UFCS | pe_price |
| UFPI | pe_price |
| UGI | pe_price |
| UGP | pe_price, published pe != stored pe |
| UHAL | pe_price, published pe != stored pe |
| UHAL.B | pe_price, published pe != stored pe |
| UHS | pe_price |
| UL | pe_price |
| ULS | pe_price |
| ULTA | pe_price |
| UMBF | pe_price |
| UMC | pe_price |
| UMH | pe_price |
| UNFI | pe_price |
| UNIT | pe_price, published pe != stored pe |
| UNM | pe_price |
| UNP | pe_price |
| UPBD | pe_price |
| UPS | pe_price |
| UPST | pe_price |
| UPWK | eps_shares, pe_price |
| URBN | pe_price, published pe != stored pe |
| UROY | pe_price, published pe != stored pe |
| USAC | pe_price |
| USB | pe_price |
| USFD | pe_price |
| USPH | pe_price |
| UTHR | pe_price |
| UTI | income, pe_price |
| UTZ | pe_price |
| UVE | pe_price |
| UVSP | pe_price |
| UVV | pe_price |
| UWMC | eps_shares, pe_price |
| V | pe_price |
| VAC | pe_price |
| VAL | pe_price |
| VALE | pe_price |
| VCEL | pe_price |
| VCTR | pe_price |
| VCYT | pe_price |
| VECO | pe_price |
| VEON | pe_price, published pe != stored pe |
| VERX | eps_shares, pe_price, published pe != stored pe |
| VG | pe_price |
| VIAV | pe_price |
| VICI | pe_price |
| VICR | pe_price |
| VIK | pe_price |
| VIPS | pe_price |
| VIRT | pe_price |
| VISN | eps_shares, income, pe_price |
| VIST | pe_price |
| VIV | pe_price, published pe != stored pe |
| VLO | pe_price |
| VLY | pe_price |
| VMET | pe_price |
| VMRK | pe_price, published pe != stored pe |
| VNET | eps_shares, pe_price |
| VNO | pe_price |
| VNOM | pe_price, published pe != stored pe |
| VOD | pe_price |
| VOYA | balance, pe_price |
| VRT | pe_price |
| VRTS | pe_price |
| VSAT | income |
| VSEC | pe_price |
| VSH | pe_price |
| VST | pe_price |
| VSXY | pe_price |
| VTMX | pe_price |
| VTOL | income, pe_price |
| VTR | pe_price |
| VTRS | pe_price |
| VVV | pe_price |
| VZ | pe_price |
| WABC | pe_price |
| WAFD | pe_price |
| WAL | pe_price |
| WAY | pe_price |
| WB | pe_price |
| WDC | pe_price |
| WDFC | pe_price |
| WDS | pe_price |
| WELL | pe_price |
| WEN | pe_price |
| WERN | pe_price |
| WES | pe_price |
| WEX | pe_price |
| WF | eps_shares, pe_price |
| WFC | pe_price |
| WHR | pe_price |
| WINA | pe_price, roa_impossible |
| WIT | pe_price |
| WIX | pe_price |
| WKC | pe_price |
| WLDN | pe_price |
| WLFC | pe_price |
| WLK | pe_price |
| WLY | pe_price |
| WLYB | pe_price |
| WM | pe_price |
| WMB | pe_price |
| WMG | eps_shares, pe_price |
| WMK | pe_price |
| WMT | pe_price |
| WOLF | pe_price |
| WOR | pe_price |
| WPC | pe_price |
| WPM | pe_price |
| WPP | pe_price |
| WRBY | pe_price |
| WS | pe_price |
| WSBC | pe_price |
| WSC | pe_price |
| WSE | pe_price, published pe != stored pe |
| WSFS | pe_price |
| WSM | pe_price |
| WSO | pe_price |
| WSO.B | pe_price |
| WT | balance, pe_price |
| WTFC | pe_price |
| WTTR | income, pe_price |
| WTW | pe_price |
| WU | pe_price |
| WULF | eps_shares |
| WWD | pe_price |
| WWW | pe_price |
| WY | pe_price |
| WYNN | pe_price |
| XEL | pe_price |
| XERS | pe_price |
| XHR | pe_price |
| XOM | pe_price |
| XP | pe_price |
| XPO | pe_price |
| XPRO | income, published pe != stored pe |
| XYL | pe_price |
| XYZ | pe_price |
| XZO | pe_price |
| YELP | pe_price |
| YETI | pe_price |
| YMM | pe_price |
| YOU | pe_price |
| YPF | income, pe_price |
| YUM | pe_price |
| YUMC | pe_price |
| Z | pe_price |
| ZD | pe_price |
| ZG | pe_price |
| ZGN | eps_shares, pe_price |
| ZIM | pe_price |
| ZION | pe_price |
| ZM | pe_price |
| ZTO | pe_price |
| ZTS | pe_price |
| ZWS | pe_price |

## WARN tickers (41)

| ticker | issues |
|---|---|
| ADBT | published pe != stored pe |
| AERO | published pe != stored pe |
| AIIR | no statements |
| ALGM | published pe != stored pe |
| ALM | published pe != stored pe |
| ASA | missing cash_flow |
| AXTI | published pe != stored pe |
| BST | no statements |
| BTX | no statements |
| BXDC | no statements |
| CIG.C | published pe != stored pe |
| CPRI | published pe != stored pe |
| DSL | no statements |
| FOIL | ratios not page-overlaid |
| FSUN | published pe != stored pe |
| FWONK | published pe != stored pe |
| JMKE | ratios not page-overlaid |
| KEYS | published pe != stored pe |
| PBT | missing cash_flow |
| PSUS | no statements |
| SA | published pe != stored pe |
| SBR | missing cash_flow |
| TLV:ALRPR | published pe != stored pe |
| TLV:AMAL | ratios not page-overlaid |
| TLV:AVGD | published pe != stored pe |
| TLV:BRKT | no statements |
| TLV:DISI | published pe != stored pe |
| TLV:DLAS | no statements |
| TLV:ELRN | no statements |
| TLV:ISCD | published pe != stored pe |
| TLV:MNRV | ratios not page-overlaid |
| TLV:OPCE | published pe != stored pe |
| TLV:POLY | published pe != stored pe |
| TLV:RENT | ratios not page-overlaid |
| TLV:RPOL | ratios not page-overlaid |
| TLV:SARN | ratios not page-overlaid |
| TLV:SPGS | published pe != stored pe |
| TLV:TDHR | ratios not page-overlaid |
| TLV:WESR | published pe != stored pe |
| TRS | published pe != stored pe |
| WAT | published pe != stored pe |
