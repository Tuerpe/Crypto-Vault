---
typ: Wissen
sektor: Infrastructure
stand: 2026-08-10
---

# Infrastructure – Warum die Token nicht steigen

> [!abstract] Die Frage
> Praktisch jede Anwendung im Kryptomarkt hängt an Oracles, Indexierung, Datenverfügbarkeit oder Layer-2-Skalierung. Die Nutzung ist unbestritten und wächst.
> **Warum stehen dann alle sieben recherchierten Infrastructure-Token zwischen -96,7 % und -99,45 % vom Allzeithoch?**
> Die Antwort besteht aus drei strukturellen Gründen – und sie gelten alle gleichzeitig.

---

## Grund 1: Infrastruktur ist ein Rohstoffmarkt

**Ein Launchpad hat einen Netzwerkeffekt.** Pump.fun hat 75 % Marktanteil, weil dort die Liquidität ist. Ein Konkurrent muss nicht nur billiger sein, sondern auch die Nutzer mitbringen.

**Ein Zinsmarkt hat einen Liquiditätsvorteil.** Pendle hat 50–60 % Marktanteil, weil tiefe Pools bessere Preise bedeuten – das verstärkt sich selbst.

**Eine Datenverfügbarkeits-Schicht hat nichts davon.** Ein Rollup wechselt die DA-Schicht, wenn eine andere billiger ist. Es gibt keinen Wechselaufwand, keine Liquidität, keine Nutzerbindung. Das Produkt ist austauschbar.

**Die Folge: Preiskampf ohne Boden.**

| Beleg | Zahl |
|---|---|
| Celestia und EigenDA vs. Ethereum-Blobs | **über 90 % günstiger** |
| Ethereum nach EIP-4844 (März 2024) | L1-Datenkosten **um eine Größenordnung gefallen** |
| Transaktionskosten auf Arbitrum/Optimism 2026 | **$0,01–0,30** |
| Celestias Blob-Gebühren p. a. (geschätzt) | **~$820.000** |

> [!danger] Celestia ist das Musterbeispiel
> Celestia verkauft günstige Datenverfügbarkeit. Aber:
> - **Ethereum senkt die eigenen Blob-Kosten** mit jedem Upgrade – der Vorteil schrumpft
> - **EigenDA** bietet dasselbe, besichert durch restaked ETH
> - **Avail** und **NEAR DA** konkurrieren ebenfalls
>
> **Und trotzdem hat Forma**, ein Rollup auf Celestia, die **Abschaltung wegen unhaltbarer Kosten** angekündigt. Wenn ein Kunde, der den Kostenvorteil nutzt, trotzdem an den Kosten scheitert, liegt der Engpass woanders – bei der Nachfrage, nicht beim Preis.
>
> **Bei ~$820.000 Jahresumsatz und $201,7 Mio. Market Cap ergibt das ein P/S von ~246x.**

---

## Grund 2: Der Token ist vom Geschäft getrennt

Das ist dasselbe Muster wie im RWA-Sektor – aber hier noch ausgeprägter.

| Token | Wer verdient? | Bekommt der Token-Halter etwas? |
|---|---|---|
| **[[Arbitrum (ARB)]]** | Arbitrum Foundation (Sequencer-Erlöse) | ❌ nein |
| **[[Optimism (OP)]]** | Optimism Collective (inkl. Base-Anteil) | ❌ nein |
| **[[The Graph (GRT)]]** | Indexer (Query-Gebühren) | ⚠️ nur ~1 % Burn gegen ~3 % Inflation |
| **[[Celestia (TIA)]]** | Validatoren | ❌ nein, dazu ~8 % Inflation |
| **[[EigenLayer (EIGEN)]]** | Restaker und AVS-Betreiber | ❌ nein |
| **[[Pyth Network (PYTH)]]** | Datenlieferanten | ❌ nein |
| **[[Quant (QNT)]]** | Quant Network (Lizenzen) | ❌ **inverse Preislogik** |
| **[[Chainlink (LINK)]]** | Node-Betreiber – **aber seit 2025 auch die Reserve** | ✅ **ja, über die Reserve** |

**Acht von neun Infrastructure-Token im Vault haben keinen Wertabschöpfungs-Mechanismus.**

> [!important] Der Chainlink-Beweis
> Chainlink war von 2019 bis 2025 der Musterfall dieses Problems: **Der abgesicherte Wert stieg in die Billionen, der Kurs machte zwei Zyklen lang kein neues Hoch.** Node-Betreiber verdienten die Gebühren, LINK-Halter nichts – und Chainlink Labs verkaufte laufend Treasury-Token.
>
> **Seit August 2025 gibt es die Reserve:** Umsätze werden automatisch in LINK konvertiert und dem Umlauf entzogen. Die Zuflüsse sind noch klein (~1 % der MC p. a.), **wachsen aber mit +7x seit Start.**
>
> **Chainlink ist damit der einzige Infrastructure-Token im Vault, bei dem die Trennung von Geschäft und Token aufgehoben wurde.** Das ist der Grund, warum er im Portfolio ist und die anderen nicht.

---

## Grund 3: Der beste Konkurrent hat oft gar keinen Token

Das ist der Befund, der mich in dieser Recherche am meisten überzeugt hat.

**Base (Coinbase)** ist der erfolgreichste Layer-2 im OP-Stack-Ökosystem – **und hat keinen eigenen Token.**

Was das bedeutet:
- Coinbase muss keinen Token-Preis stützen
- Coinbase kann Gebühren beliebig senken, um Marktanteile zu gewinnen
- Coinbase braucht keine Token-Emission, um Nutzer anzuziehen
- Coinbase hat direkten Zugang zu Millionen verifizierter Nutzer

**Ein Konkurrent ohne Token-Kostenstruktur schlägt in einem Rohstoffmarkt fast immer einen Konkurrenten mit Token.** Der Token ist in dieser Konstellation kein Vorteil, sondern eine Belastung.

Dasselbe gilt in anderen Segmenten:
- **Alchemy und QuickNode** konkurrieren mit The Graph – ohne Token
- **AWS, Cloudflare R2** konkurrieren mit Walrus und Filecoin – ohne Token
- **Ethereum selbst** konkurriert mit Celestia – und senkt die Preise aus eigenem Interesse

---

## Was daraus folgt – die Prüfliste

Für jeden Infrastructure-Token:

- [ ] **Gibt es einen Buyback- oder Burn-Mechanismus?** Wenn nein: Wie soll der Token je steigen?
- [ ] **Ist das Produkt austauschbar?** Datenverfügbarkeit, Blockspace und Indexierung sind Rohstoffe. Oracles mit institutionellen Datenquellen (Pyth) oder Compliance-Integration (Chainlink ACE) weniger
- [ ] **Gibt es einen tokenlosen Konkurrenten?** Base, Alchemy, AWS – wenn ja, ist der Preiskampf strukturell verloren
- [ ] **Wie hoch ist MC/FDV?** Im Sektor besonders schlecht: EigenLayer 14 %, Walrus 25 %, Pyth 36 %
- [ ] **Gibt es eine Supply-Obergrenze?** Celestia und EigenLayer haben keine
- [ ] **Wächst der Umsatz schneller als die Konkurrenz die Preise senkt?**

---

## Die Ausnahme, die die Regel bestätigt

**[[Jito (JTO)]]** ist der einzige Infrastructure-nahe Token neben Chainlink, der 2026 einen Mechanismus eingeführt hat: **JIP-38** leitet 100 % des DAO-Anteils der JTX-Umsätze in Rückkäufe und Burns.

Bezeichnend ist, was Jito **nicht** getan hat: Die bestehenden $9,3 Mio. MEV- und Staking-Umsätze fließen weiterhin in Wachstumsanreize, **nicht** an Token-Halter. Der Buyback speist sich allein aus einer vier Wochen alten Handelsplattform.

**Selbst dort, wo Wertabschöpfung eingeführt wird, geschieht es zögerlich** – weil Infrastruktur-Protokolle im Wettbewerb stehen und jeder Euro, der an Token-Halter geht, im Preiskampf fehlt.

**Das ist die eigentliche Erkenntnis: Der Preiskampf im Rohstoffmarkt und die Wertabschöpfung an den Token stehen im direkten Zielkonflikt.**

---

## Fazit

Infrastructure ist der Sektor, in dem die Diskrepanz zwischen **Notwendigkeit** und **Investierbarkeit** am größten ist.

**Für ein 10x-Portfolio bedeutet das:**
1. **Chainlink bleibt die Infrastructure-Position** – der einzige mit funktionierender Wertabschöpfung
2. **Alles andere höchstens als Beta-Spiel** – Celestia (1,78) und EigenLayer (1,92) haben hohe Betas, aber schlechte Tokenomics
3. **L2-Token (ARB, OP) meiden** – das Base-Problem ist strukturell unlösbar
4. **Der Trigger bei allen anderen:** ein Governance-Beschluss zu Fee-Sharing. Bei Chainlink hat genau das die These gedreht

---

## Verwandte Dokumente

- [[00 Infrastructure – Sektorüberblick]]
- [[02 Infrastructure – Token-Vergleich]]
- [[01 RWA – Die Wertabschöpfungs-Frage]] – dieselbe Analyse für den RWA-Sektor
- [[01 DePIN – Die Auslastungs-Frage]] – die vorgelagerte Frage im DePIN-Bereich
