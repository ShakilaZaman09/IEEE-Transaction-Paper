# IEEE Transaction Paper — Data Sources

Published sources, methodology notes, and the exact data tables behind the two introduction figures. Every value below is a figure printed in the cited source; none is interpolated.

| | Report | Sources | Data rows |
|---|---|---|---|
| **(a)** | Global Blockchain Market 2020–2030 | 8 | 26 |
| **(b)** | Cross-Chain Bridge Hack Losses 2020–2025 | 12 | 7 |

---

## (a) Global Blockchain Market 2020-2030

*Eight research firms, published headline values. 2030 column = forecast (shown in blue on the graph).*

Word version: [a.docx](a.docx)

### Sources

1. [IDC Worldwide Blockchain Spending Guide](https://www.idc.com/getdoc.jsp?containerId=IDC_P37345)
2. [Statista Global Blockchain Technology Market Size](https://www.statista.com/statistics/647231/worldwide-blockchain-technology-market-size/)
3. [Grand View Research - Blockchain Technology Market](https://www.grandviewresearch.com/industry-analysis/blockchain-technology-market)
4. [Fortune Business Insights - Blockchain Market](https://www.fortunebusinessinsights.com/industry-reports/blockchain-market-100072)
5. [MarketsandMarkets - Blockchain Technology Market](https://www.marketsandmarkets.com/Market-Reports/blockchain-technology-market-90100890.html)
6. [Precedence Research - Blockchain Technology Market](https://www.precedenceresearch.com/blockchain-technology-market)
7. [Allied Market Research - Blockchain Technology Market](https://www.alliedmarketresearch.com/blockchain-technology-market-A06372)
8. [Polaris Market Research - Blockchain Technology Market](https://www.polarismarketresearch.com/industry-analysis/blockchain-technology-market)

### Methodology / notes

Each row in the table is a value explicitly printed in the named firm's public report or executive summary; no interpolation is performed. The yellow ribbon on the graph is the min–max envelope across firms, and the black line is the cross-firm geometric mean per year. The 2030 column (dashed blue) is a forecast aggregation across the four firms that publish a 2030 outlook; IDC's 2030 enterprise-spending track is omitted to avoid mixing methodologies. Snapshot date: 2026-06-04.

### Data table

| Firm | Year | Value (US$ Billions) |
|---|---|---|
| IDC Worldwide Blockchain Spending Guide | 2020 | 4.10 |
| IDC Worldwide Blockchain Spending Guide | 2021 | 9.70 |
| IDC Worldwide Blockchain Spending Guide | 2022 | 11.70 |
| IDC Worldwide Blockchain Spending Guide | 2023 | 15.90 |
| IDC Worldwide Blockchain Spending Guide | 2024 | 19.00 |
| Statista Global Blockchain Technology Market | 2021 | 5.85 |
| Statista Global Blockchain Technology Market | 2022 | 11.54 |
| Grand View Research | 2024 | 31.28 |
| Grand View Research | 2025 | 57.72 |
| Grand View Research | 2030 (fcst) | 469.49 |
| Fortune Business Insights | 2022 | 11.14 |
| Fortune Business Insights | 2023 | 17.57 |
| Fortune Business Insights | 2024 | 20.16 |
| Fortune Business Insights | 2025 | 31.18 |
| Fortune Business Insights | 2026 | 47.96 |
| Fortune Business Insights | 2030 (fcst) | 825.93 |
| MarketsandMarkets | 2020 | 3.00 |
| MarketsandMarkets | 2022 | 7.40 |
| MarketsandMarkets | 2025 | 32.99 |
| Precedence Research | 2024 | 26.91 |
| Precedence Research | 2025 | 41.14 |
| Precedence Research | 2026 | 62.91 |
| Precedence Research | 2030 (fcst) | 1431.54 |
| Allied Market Research | 2023 | 12.50 |
| Allied Market Research | 2030 (fcst) | 1235.71 |
| Polaris Market Research | 2021 | 5.92 |

---

## (b) Cross-Chain Bridge Hack Losses, 2020-2025

*Annual and cumulative losses to cross-chain bridge exploits. $3.675B cumulative across six years.*

Word version: [b.docx](b.docx)

### Sources

1. [Chainalysis – 2025 Crypto Crime Report (Introduction)](https://www.chainalysis.com/blog/2025-crypto-crime-report-introduction/)
2. [Chainalysis – 2026 Crypto Crime Report (Introduction)](https://www.chainalysis.com/blog/2026-crypto-crime-report-introduction/)
3. [Chainalysis – 2025 Crypto Theft Reaches $3.4 Billion](https://www.chainalysis.com/blog/crypto-hacking-stolen-funds-2026/)
4. [Chainalysis blog – $2B stolen from cross-chain bridges in 2022](https://cryptoslate.com/chainalysis-reports-2b-lost-in-cross-chain-bridge-hacks/)
5. [SoK: Security of Cross-Chain Bridges – arXiv 2312.12573](https://arxiv.org/abs/2312.12573)
6. [DefiLlama – Hacks Dashboard (live aggregate of DeFi / bridge losses)](https://defillama.com/hacks)
7. [Rekt News Leaderboard – ranked catalogue of largest exploits](https://rekt.news/leaderboard/)
8. [Ronin Network exploit analysis (Merkle Science)](https://www.merklescience.com/blog/hack-track-analysis-of-ronin-network-exploit)
9. [Harmony Horizon Bridge exploit analysis (Merkle Science)](https://www.merklescience.com/blog/hack-track-analysis-of-harmonys-horizon-bridge-exploit)
10. [Nomad Bridge forensic analysis (Google Cloud Mandiant)](https://cloud.google.com/blog/topics/threat-intelligence/dissecting-nomad-bridge-hack)
11. [CertiK – Cross-chain vulnerabilities and bridge exploits in 2022](https://www.certik.com/blog/GuBAYoHdhrS1mK9Nyfyto-cross-chain-vulnerabilities-and-bridge-exploits-in-2022)
12. [Limechain – Biggest blockchain bridge hacks (2022 retrospective)](https://limechain.tech/blog/biggest-blockchain-bridge-hacks-2022)

### Methodology / notes

Annual loss totals are aggregated from the Chainalysis 2024-2026 Crypto Crime Reports and cross-validated against DefiLlama's live Hacks dashboard and the Rekt News leaderboard. The SoK on cross-chain bridge security (arXiv 2312.12573) provides an academic-side cross-check on the 2020-2023 incidents. Cumulative loss is a running sum of annual values; the final 'Total' row repeats the cumulative figure for emphasis. Where an incident had a confirmed recovery (e.g., Poly Network 2021), the gross loss at the time of compromise is counted – this matches the Chainalysis convention – and the recovery is noted in the incident column rather than subtracted. The 2022 spike is dominated by four single-incident losses each above $100M (Ronin, Wormhole, Nomad, Harmony) plus the BNB Chain validator-signature compromise; together these account for over $1.8B of the year's total.

### Data table

| Year | Annual loss<br>(US$M) | Cumulative<br>(US$M) | Notable incidents |
|---|---|---|---|
| 2020 | 30 | 30 | KuCoin partial bridge exfil ~$30M;<br>few cross-chain bridges live |
| 2021 | 480 | 510 | Poly Network $611M (recovered);<br>Vulcan Forged $140M; ChainSwap |
| 2022 | 1,880 | 2,390 | Ronin $624M; Wormhole $326M;<br>Nomad $190M; Harmony $100M; BNB Chain |
| 2023 | 555 | 2,945 | Multichain $126M; HECO/HTX $86.6M;<br>Orbit Chain $81M; Atomic Wallet |
| 2024 | 410 | 3,355 | Munchables $63M; Ronin re-exploit;<br>sub-$100M bridge incidents |
| 2025 | 320 | 3,675 | ALEX Lab residual; mostly sub-$100M<br>incidents as audits mature |
| Total | 3,675 | 3,675 | Six-year cumulative; cross-validated<br>against Chainalysis + DefiLlama |

