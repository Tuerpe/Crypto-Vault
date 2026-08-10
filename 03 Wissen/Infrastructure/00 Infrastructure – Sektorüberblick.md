---
typ: Wissensbereich
sektor: Infrastructure
stand: 2026-08-10
---

# Infrastructure – Sektorüberblick

> [!abstract] Die Kernaussage in vier Sätzen
> Infrastructure-Token sind die Schaufeln des Kryptomarkts: Oracles, Indexierung, Datenverfügbarkeit, Layer-2-Skalierung, Shared Security. Sie sind **unverzichtbar** – praktisch jede dApp im Markt hängt an mindestens einem dieser Dienste.
> **Und sie sind das schlechteste Investment-Segment im gesamten Vault.** Die sieben recherchierten Token stehen zwischen **-96,7 % und -99,45 %** vom Allzeithoch. Sechs von sieben haben **keinen Wertabschöpfungs-Mechanismus.**
> Der Grund ist strukturell: **Infrastruktur ist ein Rohstoffmarkt.** Wer Datenverfügbarkeit, Indexierung oder Blockspace verkauft, konkurriert in einem Markt, dessen Preise systematisch gegen null tendieren.

---

## Inhalt dieses Bereichs

- **Dieses Dokument** – Segmente, das Rohstoffproblem, Risiken
- [[01 Infrastructure – Warum die Token nicht steigen]] – die strukturelle Analyse
- [[02 Infrastructure – Token-Vergleich]] – alle recherchierten Token in einer Tabelle

**Coin-Dateien im Vault:**
[[Celestia (TIA)]] · [[EigenLayer (EIGEN)]] · [[Pyth Network (PYTH)]] · [[The Graph (GRT)]] · [[Arbitrum (ARB)]] · [[Optimism (OP)]] · [[Walrus (WAL)]]
**Bereits im Vault mit Infrastructure-Bezug:** [[Chainlink (LINK)]] · [[Quant (QNT)]] · [[Jito (JTO)]]

---

## 1. Die Segmente

| Segment | Funktion | Token im Vault |
|---|---|---|
| **Oracles** | Preisdaten und externe Informationen on-chain bringen | [[Chainlink (LINK)]], [[Pyth Network (PYTH)]] |
| **Indexierung** | Blockchain-Daten abfragbar machen | [[The Graph (GRT)]] |
| **Data Availability** | Nachweis, dass Rollup-Daten publiziert wurden | [[Celestia (TIA)]], EigenDA |
| **Shared Security / Restaking** | Sicherheit an neue Dienste verleihen | [[EigenLayer (EIGEN)]] |
| **Layer-2 / Skalierung** | Transaktionen günstiger machen | [[Arbitrum (ARB)]], [[Optimism (OP)]] |
| **Speicher (heiße Daten)** | Programmierbarer Speicher für häufig abgerufene Inhalte | [[Walrus (WAL)]] |
| **Interoperabilität** | Chains und Bankensysteme verbinden | [[Quant (QNT)]], Chainlink CCIP |
| **MEV / Blockbau** | Transaktionsreihenfolge organisieren | [[Jito (JTO)]] |

---

## 2. Das Rohstoffproblem – der Kern des Sektors

> [!danger] Infrastruktur-Preise tendieren gegen null
> Das ist der wichtigste Satz dieses Wissensbereichs. Anders als bei einem Launchpad (Pump.fun), einer Handelsplattform (Hyperliquid) oder einem Zinsmarkt (Pendle) verkaufen Infrastruktur-Protokolle ein **austauschbares Gut**.
>
> **Drei Belege aus dieser Recherche:**
>
> **1. Datenverfügbarkeit:** Celestia und EigenDA liegen **über 90 % unter Ethereum-Blob-Kosten**. Klingt nach Vorteil – ist aber ein Preiskampf in einem Markt, in dem Ethereum mit **EIP-4844** (März 2024) die eigenen Kosten um eine Größenordnung gesenkt hat und weitere Upgrades plant. **Celestias Vorteil schrumpft mit jedem Ethereum-Update.**
>
> **2. Layer-2-Gebühren:** Nach EIP-4844 kosten Transaktionen auf Arbitrum und Optimism nur noch **$0,01–0,30**. Die Nutzer profitieren – die Sequencer-Margen sind entsprechend gefallen.
>
> **3. Der Forma-Fall:** Forma, ein souveräner Rollup auf Celestia, hat die **Abschaltung angekündigt – wegen unhaltbarer Kosten.** Ein Rollup, das genau den Kostenvorteil nutzt, den Celestia verkauft, scheitert trotzdem an den Kosten. Das stellt die Grundthese in Frage.

**Die Konsequenz:** In einem Rohstoffmarkt gewinnt, wer die niedrigsten Kosten hat – nicht, wer den besten Token hat. **Und der günstigste Anbieter ist oft derjenige ohne Token**, weil er keinen Preis stützen muss.

---

## 3. Das Base-Problem – der schärfste Befund

> [!important] Der erfolgreichste Layer-2 hat keinen Token
> **Base** (Coinbase) läuft auf dem **OP Stack**, hat direkten Zugang zu Coinbases Nutzerbasis – und **keinen eigenen Token.**
>
> Das ist für die gesamte L2-Kategorie ein existenzielles Argument:
> - Coinbase muss keinen Token-Preis stützen
> - Coinbase kann Gebühren beliebig senken, um Marktanteile zu gewinnen
> - Coinbase braucht keine Token-Emission, um Nutzer anzulocken
>
> **Wenn der erfolgreichste Rollup beweist, dass man für einen Layer-2 keinen Token braucht, ist das ein strukturelles Problem für ARB und OP** – unabhängig davon, wie gut ihre Technologie ist.
>
> Besonders bitter für Optimism: **Base zahlt einen Umsatzanteil an die Optimism Collective** – aber an OP-Halter fließt davon nichts.

---

## 4. Die Wertabschöpfung im Sektor

| Token | Mechanismus | Wirksamkeit |
|---|---|---|
| **[[Chainlink (LINK)]]** | **Reserve (Payment Abstraction)** seit 08/2025 | ✅ ~130.000 LINK/Woche, **+7x seit Start** |
| **[[Jito (JTO)]]** | **JIP-38** seit 07/2026: 100 % des DAO-Anteils aus JTX | ⚠️ hängt an einer vier Wochen alten Plattform |
| **[[The Graph (GRT)]]** | Query-Gebühren-Burn (~1 %) gegen ~3 % Inflation | ⚠️ Netto-Effekt unklar, keine Zahlen |
| **[[Celestia (TIA)]]** | ❌ keiner | ~8 % Inflation, keine Obergrenze |
| **[[EigenLayer (EIGEN)]]** | ❌ keiner | keine Obergrenze, **MC/FDV 14 %** |
| **[[Pyth Network (PYTH)]]** | ❌ keiner | – |
| **[[Arbitrum (ARB)]]** | ❌ keiner – Sequencer-Erlöse gehen an die Foundation | – |
| **[[Optimism (OP)]]** | ❌ keiner – Superchain-Erlöse gehen an die Collective | plus laufende Förderausschüttungen |
| **[[Walrus (WAL)]]** | ❌ keiner | **MC/FDV 25 %** |
| **[[Quant (QNT)]]** | ❌ Lizenzmodell mit **inverser Preislogik** | P/S ~277x |

**Nur Chainlink hat einen nachweislich funktionierenden Mechanismus.** Und genau Chainlink ist der einzige Infrastructure-Token, den ich in diesem Vault zum Kauf empfohlen habe.

➡️ Ausführlich: [[01 Infrastructure – Warum die Token nicht steigen]]

---

## 5. Die Tokenomics sind im Sektor besonders schlecht

| Token | MC/FDV |
|---|---|
| The Graph | 88,5 % ⭐ |
| Arbitrum | 66 % |
| Celestia | 57 % ⚠️ |
| Optimism | 53 % ⚠️ |
| Pyth | 36 % ❌ |
| **Walrus** | **25 %** ❌ |
| **EigenLayer** | **14 %** ❌❌ |

**Vier von sieben liegen unter 57 %.** EigenLayer hat mit ~14 % den schlechtesten Wert im gesamten Vault, Walrus mit 25 % den drittschlechtesten.

Dazu haben **Celestia, EigenLayer und (teilweise) The Graph keine harte Supply-Obergrenze** – sie inflationieren über Staking-Rewards.

---

## 6. Was für den Sektor spricht

Damit das Bild fair bleibt – es gibt echte Stärken:

- **Die höchsten Betas im Vault außerhalb von Centrifuge:** EigenLayer 1,92, Celestia 1,78, Walrus 1,72, Optimism 1,69, Pyth 1,69. Für einen Bullrun ist das mechanisch attraktiv
- **Gute Liquidität:** Celestia 8,4 %, EigenLayer 9,7 %, Optimism 7,4 % Tagesvolumen relativ zur MC – deutlich besser als bei den meisten DePIN- oder RWA-Werten
- **Extreme Drawdowns:** -96,7 % bis -99,45 %. Bei mehreren Werten liegt ein 10x deutlich unter dem alten ATH-Niveau (The Graph 42 %, Celestia 78 %)
- **Unbestrittene Notwendigkeit:** Ohne Oracles, Indexierung und Skalierung funktioniert der Markt nicht

---

## 7. Einordnung für ein 10x-Portfolio

**Die ehrliche Zusammenfassung:** Infrastructure ist der Sektor mit der höchsten Notwendigkeit und der schlechtesten Investorenökonomie.

| Rang | Token | Einordnung |
|---|---|---|
| 🥇 | **[[Chainlink (LINK)]]** *(bereits im Portfolio)* | Der einzige mit funktionierendem Buyback. ETFs live, chain-agnostisch. **Bleibt die Infrastructure-Position** |
| 🥈 | **[[Pyth Network (PYTH)]]** | Bessere Datenarchitektur als LINK, **Beta 1,69**, kleinere MC → mehr Hebel. *Aber kein Fee-Sharing.* **Nur als Teiltausch gegen LINK** → 0–3 % |
| 🥉 | **[[The Graph (GRT)]]** | **MC/FDV 88,5 %**, 10x = nur 42 % des alten Peaks. *Aber Beta 1,33 und keine Umsatzzahlen* → 0–3 % |
| 4 | **[[Celestia (TIA)]]** | **Beta 1,78**, beste Liquidität. *Aber P/S ~246x, keine Obergrenze, Ethereum drückt den Preis* → 0–3 % |
| 5 | **[[Arbitrum (ARB)]]** | Größter L2, gute Liquidität. *Aber reiner Governance-Token, Base-Problem* → 0–3 % |
| 6 | **[[EigenLayer (EIGEN)]]** | **Beta 1,92** (zweithöchster im Vault). *Aber MC/FDV 14 % zerstört den Vorteil* → 0–2 % |
| 7 | **[[Optimism (OP)]]** | Klügere Strategie als ARB. *Aber Base beweist, dass L2s keinen Token brauchen* → 0–2 % |
| 8 | **[[Walrus (WAL)]]** | Mysten-Labs-Team, moderne Technik. *Aber MC/FDV 25 %, keine Zahlen, Doppelwette auf Sui* → 0–2 % |

**Meine Empfehlung: Keine zusätzliche Infrastructure-Position.** Chainlink deckt den Sektor bereits ab – mit dem einzigen funktionierenden Wertabschöpfungs-Mechanismus. Wer mehr Hebel will, tauscht einen Teil LINK gegen PYTH; wer mehr Beta will, nimmt eine kleine Celestia-Position.

➡️ Detaillierter Vergleich: [[02 Infrastructure – Token-Vergleich]]

---

## Quellen

- [BlockEden – Celestia's Competitive Edge in Data Availability: A Deep Dive](https://blockeden.xyz/blog/2026/01/16/celestia-blob-economics-data-availability-rollup-costs/)
- [VaasBlock – Ethereum L2 Economics 2026: Arbitrum, Base, Optimism Revenue](https://www.vaasblock.com/news/ethereum-l2-economics-revenue-arbitrum-base-optimism-2026/)
- [Everstake – Arbitrum vs Optimism vs Base: Which Ethereum L2 Wins in 2026?](https://everstake.one/resources/blog/arbitrum-vs-optimism-vs-base)
- [The Block – 2026 Layer 2 Outlook](https://www.theblock.co/post/383329/2026-layer-2-outlook)
- [Eco – Arbitrum vs Optimism 2026: Fees, TVL, Ecosystem](https://eco.com/support/en/articles/15183711-arbitrum-vs-optimism-2026-fees-tvl-ecosystem)
- [Ryder – Ethereum L2s in 2026: Arbitrum vs Optimism vs Base vs zkSync](https://ryder.id/blogs/post/ethereum-l2s-in-2026-arbitrum-vs-optimism-vs-base-vs-zksync)
