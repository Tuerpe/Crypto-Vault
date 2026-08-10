---
coin: Pyth Network
ticker: PYTH
status: Recherchiert
kategorie: Infrastructure / Oracle
recherche_stand: 2026-08-10
sektor: Infrastructure
---

# Pyth Network (PYTH)

> [!abstract] Kurzfazit
> **Der einzige ernsthafte Herausforderer von Chainlink – mit einer besseren Datenquelle und schlechteren Tokenomics.** Pyth liefert Preisdaten direkt von den **Erzeugern** (Börsen, Market Maker, Handelsfirmen wie Jane Street, Jump, Wintermute, CBOE) statt über Node-Betreiber, die Daten von APIs abgreifen. Das ist strukturell die sauberere Architektur – und deutlich schneller (Sub-Sekunden-Updates statt fester Aktualisierungsintervalle).
> Aber: **MC/FDV nur ~36 %**, **-97,3 % vom ATH**, und wie bei Chainlink vor der Reserve gibt es **keinen belegten Wertabschöpfungs-Mechanismus**.
> **10x-Bewertung: mittel.**

---

## 0. Kennzahlen auf einen Blick

| Kennzahl | Wert | Quelle/Stand |
|---|---|---|
| Preis | ~$0,030858 | Coinpaprika, 09.06.2026 |
| **Market Cap** | **~$111,9 Mio.** | **Rank #227** |
| Circulating Supply | ~3,63 Mrd. PYTH | |
| Total / Max Supply | 10,0 Mrd. PYTH (fix) | |
| **MC/FDV** | **~36 %** ⚠️ | |
| FDV | ~$309 Mio. | |
| ATH | $1,1509 (16.03.2024) | |
| Abstand zum ATH | **-97,3 %** | |
| **Beta zu BTC** | **1,69** ⭐ | oberes Drittel |
| 24h-Volumen | ~$6,00 Mio. | ok (5,4 % der MC) |
| 7-Tage-Performance | **-21,1 %** ⚠️ | zum Erhebungszeitpunkt |

**Was 10x konkret bedeuten würde:** $0,30858 → bei ~5 Mrd. Circulating (2027) eine **Market Cap von ~$1,54 Mrd.**, FDV **$3,09 Mrd.**

---

## 1. Fundamentaldaten

**Use Case / Problem**
Oracles bringen Preisdaten on-chain. Chainlink macht das über ein Netzwerk unabhängiger Node-Betreiber, die Daten von APIs beziehen und aggregieren.

**Pyth macht es anders – und das ist der Kern der These:** Die Daten kommen **direkt von den Institutionen, die sie erzeugen**. Market Maker, Handelsfirmen und Börsen publizieren ihre eigenen Preisdaten direkt ins Netzwerk. Zu den Datenlieferanten zählen Namen wie **Jane Street, Jump Trading, Wintermute, CBOE, Binance, OKX**.

**Die technischen Vorteile:**
- **Erstanbieter-Daten** statt aggregierter API-Abfragen – weniger Zwischenschichten, weniger Manipulationsfläche
- **Pull-Modell:** Anwendungen fordern Preise bei Bedarf ab, statt dass permanent Updates on-chain geschrieben werden. Das ist deutlich billiger
- **Sub-Sekunden-Latenz** – wichtig für Perpetual-DEXs und Liquidationen
- **Konfidenzintervalle:** Pyth liefert nicht nur einen Preis, sondern auch eine Unsicherheitsspanne

**Marktposition:** Pyth ist der **Standard-Oracle im Solana-Ökosystem** und hat sich von dort auf zahlreiche weitere Chains ausgebreitet.

**Kategorie / Narrativ**
Infrastructure / Oracle. Pyth ist der direkte Wettbewerber zu Chainlink – und das ist im Portfolio-Kontext wichtig, weil du **Chainlink bereits mit 14 % hältst.**

---

## 2. Tokenomics ⚠️

| | |
|---|---|
| Circulating | ~3,63 Mrd. PYTH |
| Total / Max | 10,0 Mrd. PYTH (fix) |
| **MC/FDV** | **~36 %** |

**Positiv:** Harte Obergrenze bei 10 Mrd.

**Negativ:** Nur 36 % im Umlauf – 6,4 Mrd. PYTH stehen noch aus. Das ist schlechter als Chainlink (~65 %), Celestia (57 %) oder The Graph (88,5 %), aber besser als EigenLayer (14 %).

> [!warning] Die Wertabschöpfungs-Frage
> **In der Recherche ließ sich kein belegter Buyback- oder Fee-Sharing-Mechanismus für PYTH finden.** Der Token dient primär der Governance und der Steuerung der Datenlieferanten-Vergütung.
>
> Das ist **exakt das Problem, das Chainlink von 2019 bis 2025 hatte** – und das dort erst mit der Reserve gelöst wurde. Chainlink hat inzwischen einen funktionierenden Mechanismus (~130.000 LINK/Woche, +7x seit Start). **Pyth hat ihn nicht.**
>
> Im direkten Vergleich ist das ein erheblicher struktureller Nachteil.

---

## 3. Team & Adoption

- **Pyth Data Association**, initiiert aus dem Solana-Umfeld, Mainnet 2021, Token-Launch November 2023.
- **Datenlieferanten:** über 100 Institutionen, darunter einige der größten Handelsfirmen der Welt. **Das ist die eigentliche Stärke** – diese Namen liefern nicht bei Chainlink.
- **Multichain:** über 50 Blockchains.
- **Anwendungsfälle:** Perpetual-DEXs (die niedrige Latenz brauchen), Lending-Protokolle, Optionen.

> [!warning] Belegsituation
> **Es ließen sich keine belastbaren 2026er-Zahlen zu Umsatz, abgesichertem Wert (TVS) oder Abfragevolumen finden.** Bei Chainlink habe ich $28 Bio. TVS und ~$75 Mio. Jahresgebühren belegen können – bei Pyth fehlen vergleichbare Zahlen.

---

## 4. Marktdaten & Risiken

- **ATH:** $1,1509 (16.03.2024) – **früh im Zyklus**, wie Kaspa, Render, Celestia und Pendle
- **Aktuell:** -97,3 %
- **⭐ Beta 1,69** – oberes Drittel im Vault, deutlich besser als Chainlink (1,59)
- **Liquidität:** $6,00 Mio./24h = 5,4 % der MC – solide
- **-21,1 % in sieben Tagen** zum Erhebungszeitpunkt – hohe Volatilität

**Risiken:**
- **Kein belegter Wertabschöpfungs-Mechanismus** – Hauptrisiko, dasselbe wie bei Chainlink vor 2025
- **MC/FDV 36 %** – 64 % Überhang
- **Konkurrenz Chainlink:** Chainlink hat ETFs, die Reserve, ACE, CCIP, JPMorgan und einen zehnfach größeren Marktwert. Pyth hat die bessere Datenarchitektur, aber Chainlink hat den Netzwerkeffekt und die institutionellen Beziehungen
- **Keine veröffentlichten Umsatzzahlen**
- **Abhängigkeit von Solana-Ökosystem** – ein erheblicher Teil des Volumens
- **ATH früh im Zyklus**

---

## 5. Verfügbarkeit & Steuer

| Plattform | Status |
|---|---|
| Coinbase / Binance / Bybit / OKX | ✅ gelistet |
| Trade Republic / Smartbroker+ | ❌ eher ausgeschlossen |
| Wallets | Phantom, Solflare, Ledger (Solana) |

**Steuerlich:** § 23 EStG, nach >1 Jahr steuerfrei. PYTH-Staking (Oracle Integrity Staking) liefert Rewards → **sonstige Einkünfte (§ 22 Nr. 3 EStG)**. Für reines Halten: sauberer Fall.

---

## 6. Eigene Szenarien (Horizont 2027/28)

Annahme: ~5 Mrd. PYTH zirkulierend Ende 2027.

| Szenario | Preis | Market Cap | Faktor | Bedingung |
|---|---|---|---|---|
| **Bear** | $0,010 – $0,018 | $50–90 Mio. | **-68 % bis -42 %** | Chainlink zementiert die Marktführerschaft, Freischaltungen drücken, kein Fee-Sharing |
| **Base** | $0,085 – $0,130 | $425–650 Mio. | **2,8x – 4,2x** | Alt-Zyklus mit Beta 1,69, Marktanteil wächst weiter |
| **Bull** | $0,270 – $0,380 | $1,35–1,90 Mrd. | **8,8x – 12,3x** | **Fee-Sharing eingeführt** + veröffentlichte Umsatzzahlen + Marktanteilsgewinne gegen Chainlink außerhalb von Solana |

> [!important] Fazit für dein 10x-Portfolio
> **Empfehlung: 0–3 % – und wenn, dann als bewusster Tausch gegen einen Teil von Chainlink.**
>
> Dafür: **bessere Datenarchitektur als Chainlink** (Erstanbieter statt API-Aggregation), erstklassige Datenlieferanten (Jane Street, Jump, CBOE), Sub-Sekunden-Latenz, **Beta 1,69** (besser als LINK 1,59), harte Supply-Obergrenze, deutlich kleinere Market Cap → mehr Hebel.
> Dagegen: **kein Fee-Sharing** (Chainlink hat es seit 2025), **MC/FDV 36 %**, keine veröffentlichten Umsatzzahlen, ATH früh im Zyklus.
>
> **Der Portfolio-Punkt:** Du hältst Chainlink mit 14 %. Pyth ist derselbe Sektor mit derselben These – nur kleiner, mit mehr Hebel und ohne Buyback. **Beide zusammen wären eine Doppelposition auf Oracles.**
>
> Wenn du mehr Hebel im Oracle-Bereich willst: 3 % PYTH gegen 3 % weniger LINK. Wenn du Wertabschöpfung höher gewichtest: bei Chainlink bleiben.
> **Der eine Trigger, der das ändern würde:** Ein Governance-Beschluss zu PYTH-Buybacks aus Protokollgebühren.

---

## Offene Punkte / To-Do

- [ ] **⚠️ Hausaufgabe:** Umsatz-, TVS- und Abfragevolumen-Zahlen für Pyth suchen (Vergleichbasis zu Chainlinks $28 Bio. TVS und $75 Mio. Gebühren)
- [ ] **Tracker 1:** Gibt es Governance-Vorschläge zu Fee-Sharing oder Buybacks?
- [ ] **Tracker 2:** Marktanteil vs. Chainlink außerhalb des Solana-Ökosystems
- [ ] **Tracker 3:** Unlock-Kalender für die ausstehenden 64 %
- [ ] Entscheidung: PYTH als Teiltausch gegen LINK, oder gar nicht?

---

## Quellen

- [Coinpaprika – PYTH Ticker](https://api.coinpaprika.com/v1/tickers/pyth-pyth-network)
- [KuCoin – DePIN Crypto Sector 2026: How Decentralized Physical Infrastructure Surpassed Oracles](https://www.kucoin.com/blog/en-depin-crypto-sector-2026-how-decentralized-physical-infrastructure-surpassed-oracles)
