---
typ: Wissen
sektor: RWA
stand: 2026-08-10
---

# RWA – Die Wertabschöpfungs-Frage

> [!abstract] Warum dieses Dokument existiert
> Es ist die wichtigste Einzelfrage im gesamten RWA-Sektor, und sie erklärt, warum ein Markt, der um **+263 % im Jahr** wächst, Token hervorbringt, die **-80 bis -95 % vom ATH** stehen.
> **Die Frage lautet: Wer verdient eigentlich an tokenisierten Assets – und kommt davon irgendetwas beim Token an?**

---

## 1. Das Grundproblem in einem Satz

**Ein RWA-Protokoll kann milliardenschwere Assets verwalten, ohne dass ein einziger Cent davon beim Token-Halter ankommt.**

Das klingt banal, ist aber der Unterschied zwischen einer funktionierenden und einer gescheiterten Investmentthese. Konkret:

| Protokoll | Verwaltetes Kapital | Market Cap | Fließt Ertrag an Token-Halter? |
|---|---|---|---|
| **Ondo** | $3,43 Mrd. AUM | $1,68 Mrd. | ❌ **Nein** |
| **Centrifuge** | ~$1,7 Mrd. TVL | $94 Mio. | ❌ **Nein** |
| **Quant** | (nicht offengelegt) | $831 Mio. | ❌ **Nein** – Lizenzmodell mit inverser Preislogik |
| **Plume** | ~$600 Mio. TVL | $22,3 Mio. | ❌ **Nein** |
| **Polymesh** | (kein nennenswerter Markt) | $42,3 Mio. | ❌ **Nein** |
| **MANTRA** | (nicht belegt) | $24,9 Mio. | ❌ **Nein** |
| **Maple** | $4,6 Mrd. AUM | $180,6 Mio. | ✅ **Ja** – 10–30 % des Umsatzes in Rückkäufe |
| **Pendle** | ~$5 Mrd. TVL | $225,8 Mio. | ✅ **Ja** – **80 % des Umsatzes in Rückkäufe** |
| **Chainlink** | $28 Bio. abgesichert | $5,05 Mrd. | ✅ **Ja** – seit 2025 über die Reserve |

**Sechs von neun RWA-relevanten Protokollen haben keinen Mechanismus, der Wert an den Token weiterreicht.**

---

## 2. Warum das bei RWA besonders schwer ist

Bei einem klassischen DeFi-Protokoll ist die Sache einfach: Nutzer zahlen Gebühren, das Protokoll behält einen Anteil, der Anteil kann an Token-Halter fließen. Pump.fun macht das (50 % des Umsatzes in Burns), Hyperliquid macht es (97 % in Rückkäufe), Jito macht es seit JIP-38.

**Bei RWA funktioniert das aus drei Gründen schlechter:**

**1. Der Ertrag gehört jemand anderem.**
Die 4–5 % Rendite aus einer tokenisierten Staatsanleihe gehören dem, der die Anleihe hält – nicht dem Protokoll, das sie tokenisiert hat. Das Protokoll verdient nur eine Verwaltungsgebühr, typischerweise **0,15–0,50 % p. a.** Bei $3,43 Mrd. AUM sind das grob $5–17 Mio. im Jahr. Das ist ein solides Unternehmen, aber es trägt keine Milliardenbewertung.

**2. Die Gebühren sind in Fiat denominiert.**
Ein institutioneller Kunde zahlt 25 Basispunkte auf sein Investment – nicht "0,3 Token". Steigt der Tokenpreis, braucht der Kunde weniger Token für dieselbe Leistung. **Das ist eine inverse Preislogik**, die man bei Quant (Overledger-Lizenzen), Canton (USD-denominierte Netzwerkgebühren) und teilweise XRP (Brückenwährung) findet.

**3. Institutionen wollen keinen volatilen Token halten.**
Ein Vermögensverwalter, der ein Produkt auf einer Chain ausgibt, will die Chain nutzen – nicht ihren Token akkumulieren. Er wird die minimal nötige Menge halten und keinen Cent mehr. **Adoption bedeutet also nicht automatisch Nachfrage.**

---

## 3. Die drei funktionierenden Modelle

Wo es funktioniert, sieht es so aus:

### Modell A: Direkter Revenue-Buyback (das beste)

**Pendle:** 80 % des Protokollumsatzes fließen in Rückkäufe von PENDLE am offenen Markt.
- ~$40 Mio. Jahresumsatz × 80 % = **~$32 Mio. Kaufdruck**
- auf $226 Mio. Market Cap = **~14 % Buyback-Rendite p. a.**
- gegen nur ~2 % Inflation → **netto ~12 % Kaufdruck**

**Maple:** 10–30 % des Monatsumsatzes, gestaffelt nach Umsatzhöhe.
- ~$13,3 Mio. Jahresumsatz × 10–30 % = **$1,3–4,0 Mio.**
- auf $180,6 Mio. Market Cap = **0,7–2,2 %** → richtig konstruiert, aber noch nicht kursrelevant

### Modell B: Gebühren-Abstraktion (funktioniert, aber langsam)

**Chainlink Reserve:** On-Chain- und Enterprise-Umsätze werden automatisch in LINK konvertiert und der Reserve zugeführt.
- ~130.000 LINK/Woche = ~6,8 Mio. LINK/Jahr ≈ $54 Mio.
- auf $5,05 Mrd. Market Cap = **~1 %** → klein, aber **mit +7x Wachstum seit Start**

### Modell C: Gas-Burn (funktioniert nur bei hohem Volumen)

**Aptos:** Gasgebühren ×10 mit 100 % Burn seit April 2026. Bei ~10 Mio. Transaktionen täglich kann das netto deflationär werden.
**Canton:** Burn-Mint-Equilibrium – aber die Gebühren sind USD-denominiert, und es müssten ~$375 Mio. Jahresgebühren anfallen, damit Burn = Mint. Das ist derzeit nicht der Fall.

---

## 4. Der Chainlink-Präzedenzfall – die wichtigste Lehre

Chainlink ist das Lehrbeispiel, weil man dort **beide Phasen** beobachten kann:

**2019–2025: Adoption ohne Wertabschöpfung.**
Chainlink wurde in dieser Zeit zum Standard-Oracle für praktisch das gesamte DeFi-Ökosystem. Der abgesicherte Wert stieg in die Billionen. **Der Kurs machte trotzdem zwei Zyklen in Folge kein neues Hoch.** Grund: Node-Betreiber verdienten die Gebühren, LINK-Halter nichts – und Chainlink Labs verkaufte laufend Treasury-Token zur Finanzierung.

**Ab August 2025: die Reserve.**
Erstmals fließen Umsätze zurück in den Token. Das Unternehmen wandelt sich vom Netto-Verkäufer zum Netto-Käufer. Die Zuflüsse sind noch klein (~1 % der MC p. a.), **wachsen aber mit 7x seit Start.**

> [!important] Die Lehre für alle anderen RWA-Token
> **Sechs Jahre lang war Chainlink fundamental erfolgreich und als Investment enttäuschend.** Genau in dieser Phase befinden sich heute Ondo, Centrifuge, Quant, Plume und Polymesh.
>
> **Die Frage ist nicht, ob diese Protokolle erfolgreich sind. Die Frage ist, ob und wann sie einen Buyback-Mechanismus einführen.**
>
> Wer heute Ondo oder Centrifuge kauft, wettet darauf, dass die jeweilige Governance denselben Schritt geht wie Chainlink 2025, Pendle mit sPENDLE, Maple und Jito mit JIP-38. **Das ist eine plausible Wette – aber sie sollte bewusst getroffen werden, nicht versehentlich.**

---

## 5. Die praktische Checkliste

Für jeden neuen RWA-Token, den du prüfst:

- [ ] **Gibt es einen Buyback- oder Burn-Mechanismus?** Wenn nein: Wie soll der Token jemals steigen, außer durch Spekulation?
- [ ] **Wie hoch ist die Buyback-Rendite in Prozent der Market Cap?** Unter 2 % ist symbolisch, über 10 % ist relevant.
- [ ] **Sind die Gebühren in Fiat oder in Token denominiert?** Fiat-denominiert = inverse Preislogik = struktureller Nachteil.
- [ ] **Wie hoch ist die Inflation?** Ein 5-%-Buyback bei 9 % Inflation ist netto negativ.
- [ ] **Gibt es überhaupt veröffentlichte Umsatzzahlen?** Wenn nein, kann man nicht rechnen – dann ist es eine Narrativ-Wette (Quant, Plume, MANTRA, Polymesh).
- [ ] **MC/AUM oder MC/TVL im Vergleich zur Peer Group?** Ondo 0,49 vs. Centrifuge 0,055 – solche Lücken sind entweder Chance oder berechtigte Abwertung.

---

## 6. Die Rangfolge nach Wertabschöpfung

| Rang | Token | Mechanismus | Buyback-Rendite p. a. |
|---|---|---|---|
| 🥇 | **Pendle** | 80 % des Umsatzes → Rückkauf | **~14 %** |
| 🥈 | **Maple** | 10–30 % gestaffelt | ~0,7–2,2 % (skaliert mit Erfolg) |
| 🥉 | **Chainlink** | Reserve (Payment Abstraction) | ~1 %, aber +7x Wachstum |
| 4 | Aptos | 100 % Gas-Burn | potenziell deflationär |
| — | Canton | Burn-Mint, aber USD-denominiert | derzeit unwirksam |
| ❌ | **Ondo** | keiner | 0 % |
| ❌ | **Centrifuge** | keiner | 0 % |
| ❌ | **Quant** | Lizenz mit inverser Logik | 0 % |
| ❌ | **Plume** | keiner | 0 % |
| ❌ | **Polymesh** | keiner, dazu Inflation | negativ |
| ❌ | **MANTRA** | keiner | 0 % |

---

## 7. Fazit

**Der RWA-Sektor wächst real und schnell. Die meisten RWA-Token partizipieren daran nicht.**

Für ein Portfolio, das Vervielfachung sucht, folgt daraus eine klare Priorisierung:

1. **Token mit funktionierendem Buyback zuerst** – Pendle deutlich vor allen anderen
2. **Token mit sehr großer Bewertungslücke als Spekulation auf einen künftigen Mechanismus** – Centrifuge (MC/TVL 0,055) ist hier der interessanteste Fall
3. **Token ohne Mechanismus und ohne Bewertungslücke meiden** – das trifft Ondo, Quant, Plume, Polymesh und MANTRA

**Der eine Trigger, auf den man bei allen Kandidaten ohne Mechanismus achten muss:** ein Governance-Vorschlag zu Fee-Sharing oder Buybacks. Bei Chainlink hat genau dieser Schritt die These gedreht.

---

## Verwandte Dokumente

- [[00 RWA – Sektorüberblick]]
- [[02 RWA – Emittenten und Plattformen]]
- [[03 RWA – Token-Vergleich]]
