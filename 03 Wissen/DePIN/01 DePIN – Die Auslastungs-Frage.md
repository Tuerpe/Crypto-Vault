---
typ: Wissen
sektor: DePIN
stand: 2026-08-10
---

# DePIN – Die Auslastungs-Frage

> [!abstract] Warum dieses Dokument existiert
> Im RWA-Sektor lautet die entscheidende Frage: **Fließt der Ertrag an den Token?**
> Im DePIN-Sektor kommt eine Frage davor: **Wird die Infrastruktur überhaupt genutzt?**
> Das klingt banal, ist aber die Kennzahl, die im DePIN-Bereich am systematischsten verschleiert wird – und diejenige, die echte Netzwerke von leeren Hüllen trennt.

---

## 1. Der Trick mit der "Kapazität"

Jedes DePIN-Projekt kommuniziert eine große Zahl. Fast immer ist es die **bereitgestellte Kapazität**, nicht die **genutzte**:

- "327.000 registrierte GPUs"
- "Millionen von Hotspots"
- "Exabytes an Speicherkapazität"

Diese Zahlen sind einfach zu erzeugen: Man zahlt Token-Anreize, und Menschen schließen Hardware an. **Sie sagen nichts darüber aus, ob jemand dafür bezahlt.**

Die relevante Frage lautet: **Wie viel Prozent der bereitgestellten Kapazität wird von zahlenden Kunden tatsächlich genutzt?**

---

## 2. Die Auslastung im direkten Vergleich

| Projekt | Bereitgestellt | Tatsächlich genutzt | **Auslastung** |
|---|---|---|---|
| **[[Filecoin (FIL)]]** | – | – | **~32 %** ⭐ |
| **[[Akash Network (AKT)]]** | 334 GPUs verfügbar | **Ø 84 GPUs** | 33,7 % – **aber auf lächerlich kleiner Basis** |
| **[[io.net (IO)]]** | **327.000 GPUs registriert** | **6.720 aktiv** | **~2 %** ❌ |
| **[[Aethir (ATH)]]** | 440.000+ Container | on-chain verifiziert | keine Prozentzahl, aber $166 Mio. ARR ⚠️ |

> [!danger] Der Akash-Fall zeigt, warum Prozentzahlen allein nicht reichen
> Akash meldet **33,7 % Auslastung** – auf den ersten Blick ein guter Wert, vergleichbar mit Filecoin.
> **Aber die absolute Basis ist Ø 84 genutzte GPUs.** Ein einzelner mittelgroßer AI-Cluster hat mehr. 33,7 % von fast nichts ist immer noch fast nichts.
>
> **Regel:** Immer beide Zahlen prüfen – die Auslastungsquote **und** die absolute Menge.

> [!danger] Der io.net-Fall zeigt, wie die Zahl verschleiert wird
> io.net kommuniziert **327.000 registrierte GPUs**. Das ist die Zahl, die in Präsentationen steht.
> Der tägliche Durchschnitt **verifizierter, aktiver** GPUs lag bei **6.720**. Das sind **2 %.**
> Erschwerend: Die verifizierte Zahl **fiel um 11,1 % im Quartal**, während das Unternehmen **steigende Umsätze** meldete. Diese Divergenz ist ein Warnsignal.

---

## 3. Die vier Prüffragen für jedes DePIN-Projekt

**1. Wie hoch ist die Auslastung – und wie groß ist die absolute Basis?**
Unter 10 % ist das Netzwerk eine Hülle. Über 30 % ist es ein Geschäft. Aber immer die absolute Zahl danebenlegen.

**2. Sind die Zahlen extern verifiziert oder selbstberichtet?**
Aethirs Zahlen sind on-chain abgeglichen, io.nets sind es nicht. Messari-Reports (Helium, Akash, Livepeer) sind belastbarer als Projekt-Blogposts.

**3. Wer bezahlt – Kunden oder das Protokoll selbst?**
Viele DePIN-Netzwerke subventionieren die eigene Nachfrage über Anreizprogramme. Bei Helium tauchte in der Recherche genau diese Unterscheidung auf: **$24 Mio. Umsatz im Januar 2026** vs. **$11 Mio. annualisiert, wenn man den "diskretionären Subscriber-Revenue-Burn" herausrechnet.** Der zweite Wert ist der ehrliche.

**4. Wächst die Anbieterzahl oder schrumpft sie?**
Das ist der Frühindikator für die Todesspirale. **Akash: 58 aktive Provider – historischer Tiefstand.** Wenn Anbieter gehen, ist der Anreiz gebrochen.

---

## 4. Die Todesspirale erkennen

Die Reihenfolge ist immer gleich:

```
Token fällt → Anbieter-Erträge decken Strom und Hardware nicht mehr
→ Anbieter gehen offline → Kapazität sinkt → Netzwerk wird unattraktiver
→ Kunden gehen → Token fällt weiter
```

**Die Frühwarnsignale, in dieser Reihenfolge:**

| Signal | Beispiel im Vault |
|---|---|
| 1. Anbieterzahl sinkt | **Akash: 58 Provider, Allzeittief** |
| 2. Genutzte Kapazität sinkt | **Akash: Ø GPU-Nutzung -57,4 % QoQ** |
| 3. Umsatz sinkt | **Akash: Netzwerkgebühren -44 % QoQ** |
| 4. Handelsvolumen versiegt | **Hivemapper: $77.836/Tag = 0,8 % der MC** |
| 5. Beta fällt unter ~1,2 | **Hivemapper: 1,05 · Helium: 1,15** |

> [!important] Punkt 5 ist der unterschätzte Indikator
> **Ein Micro Cap mit niedrigem Beta ist ein Warnsignal.** Normalerweise haben kleine Coins hohe Betas, weil sie spekulativ gehandelt werden: Grass 1,74, Peaq 1,73, Akash 1,67.
>
> **Hivemapper liegt bei 1,05 – bei $9,5 Mio. Market Cap.** Das bedeutet: Es gibt keine spekulative Nachfrage mehr. Der Coin wird schlicht nicht mehr gehandelt.
>
> **Helium liegt bei 1,15** – trotz echter Konzernkunden. Auch das ist ein Signal, dass der Markt das Interesse verloren hat, unabhängig von den Fundamentaldaten.

---

## 5. Die Rangfolge nach belegter Nutzung

| Rang | Projekt | Belegte Nutzung | Qualität des Belegs |
|---|---|---|---|
| 🥇 | **Aethir** | 440.000+ Container, 94 Länder, $166 Mio. ARR | **on-chain verifiziert** ⚠️ Zahl trotzdem prüfen |
| 🥈 | **Grass** | $17 Mio. → $18 Mio. im H1 2026, 8,5 Mio. Nutzer | berichtete Umsätze |
| 🥉 | **Helium** | 1,6 Mio. tägliche Nutzer, 9.839 TB Offload, AT&T/Telefónica | **Messari-verifiziert** |
| 4 | **Filecoin** | ~32 % Auslastung, 100+ Teams auf FOC | teilweise belegt |
| 5 | **Render** | 24,3 Mio. Frames 2025 (+156 %) | berichtet |
| 6 | **Livepeer** | 134,4 Mio. Minuten (+71,9 % QoQ) | **Messari-verifiziert**, aber Umsatz nur ~$1 Mio. |
| 7 | **Akash** | **Ø 84 GPUs, 58 Provider** | Messari – und die Zahlen sind schlecht |
| 8 | **io.net** | **6.720 von 327.000 = 2 %** | selbstberichtet, nicht abgeglichen |
| 9 | **Arweave** | **keine Zahlen gefunden** | – |
| 10 | **Peaq** | **keine Zahlen gefunden** | – |
| 11 | **Hivemapper** | **keine 2026er-Zahlen gefunden** | – |

---

## 6. Praktische Checkliste

Für jedes neue DePIN-Projekt:

- [ ] **Auslastung in Prozent** – unter 10 % ist das Netzwerk leer
- [ ] **Absolute genutzte Kapazität** – 33 % von 250 GPUs ist irrelevant
- [ ] **Extern verifiziert?** Messari, DefiLlama, on-chain – oder nur Projekt-Blog?
- [ ] **Zahlen echte Kunden, oder subventioniert das Protokoll die Nachfrage?**
- [ ] **Anbieterzahl: steigend oder fallend?**
- [ ] **Beta:** unter 1,2 bei einem Micro Cap = der Markt hat aufgegeben
- [ ] **Vol/MC:** unter 1 % = faktisch illiquide
- [ ] **Inflation vs. Burn** – deckt der Burn die Emission? (Akash: nur ~8 %)

---

## Verwandte Dokumente

- [[00 DePIN – Sektorüberblick]]
- [[02 DePIN – Token-Vergleich]]
- [[01 RWA – Die Wertabschöpfungs-Frage]] – die zweite Prüfebene, sektorübergreifend gültig
