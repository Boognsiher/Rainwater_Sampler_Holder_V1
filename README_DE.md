# Rainwater_Sampler_Holder_V1 – Halterung für Trichter & Probefläschchen

Ein 3D-druckbarer Halter zur Befestigung eines Trichters und eines Probefläschchens für die automatische Regenwassersammlung. Mit integrierter Füllstandsskala (10–60 mm) am Guckloch.

![Regenwassersammler Halterung](./preview.png)
<!-- Ersetze preview.png durch deinen eigenen Screenshot -->

---

## Inhalt dieses Repositories

| Datei | Beschreibung |
|---|---|
| `Regenwassersammler.f3d` | Fusion 360 Quelldatei (Parameterbaum erhalten) |
| `Regenwassersammler.step` | STEP-Export für alle anderen CAD-Programme |
| `README_DE.md` | Diese Datei (Deutsch) |
| `README_EN.md` | Englische Version |

---

## Komponenten (38 Körper)

Die Datei ist in folgende Gruppen unterteilt:

### Rechts (2 Untergruppen)
| Körper | Gruppe | Beschreibung |
|---|---|---|
| Körper21 | – | Rechte Hälfte des Halters |
| Körper3–20 | TextR (18 Körper) | Füllstandsskala rechts – je ein Zeichen pro Körper |

### Links (2 Untergruppen)
| Körper | Gruppe | Beschreibung |
|---|---|---|
| Körper2 | – | Linke Hälfte des Halters |
| Körper22–39 | TextL (18 Körper) | Füllstandsskala links – je ein Zeichen pro Körper |

### Verschluss
| Körper | Beschreibung |
|---|---|
| Körper1 | Verschlusselement für das Fläschchen |

> **Hinweis zur Füllstandsskala:** Die Zeichen der Skala (TextR / TextL) sind als einzelne Körper modelliert – jeder Körper entspricht einem einzelnen Zeichen (z. B. «0», «1», «2», «-» usw.). Damit sie in einer Kontrastfarbe gedruckt werden können, ist ein **Automatic Material System (AMS)** oder ein vergleichbares Mehrfarb-System erforderlich (z. B. Bambu AMS, Prusa MMU). Ein manueller Filamentwechsel pro Zeichen ist technisch möglich, aber sehr aufwändig.

---

## Benötigte Kaufteile

### Probefläschchen
- **Produkt:** VWR Gewindefläschchen ND18
- **Link:** [vwr.com – EU7061890](https://www.vwr.com/ch/de/product/EU7061890/vwr-gewindeflschchennd18)

### Trichter
- Standardtrichter mit einem Halsdurchmesser von 16–18 mm (passend für das ND18-Fläschchen)

### Schrauben & Muttern

| Anzahl | Schraube | Mutter | Hinweis |
|---|---|---|---|
| 5× | M3 oder M4 × 25 mm | M3 / M4 | M4 empfohlen – sitzt fester, aber engeres Einführen |
| 2× | M3 oder M4 × 15 mm | M3 / M4 | M4 empfohlen – sitzt fester, aber engeres Einführen |
| 1× | M5 × 35 mm | M5 | – |

### Weiteres Zubehör

| Anzahl | Teil | Beschreibung |
|---|---|---|
| 1× | Gummizug | 3–5 mm Durchmesser |
| 2× | Rohrschelle oder Kabelbinder | Zur Befestigung der Halterung |

---

## 3D-Druckdateien

Druckfertige Dateien (STL / 3MF) mit Druckeinstellungen sind auf MakerWorld verfügbar:

> 🔗 **MakerWorld:** [Rainwater_Sampler_Holder_V1](https://makerworld.com/de/models/2576738-rainwater_sampler_holder_v1#profileId-2841437)

---

## Technische Angaben

| Parameter | Wert |
|---|---|
| Maßeinheit | mm |
| Erstellt mit | Autodesk Fusion 360 |
| CAD-Formate | `.f3d` (nativ), `.step` (kompatibel) |
| Koordinatenursprung | Unterkante Halterungsfuss |

---

## Verwendung der CAD-Dateien

### Mit Fusion 360
Öffne die `.f3d` Datei direkt – der vollständige Parameterbaum und die Modellhistorie bleiben erhalten.

### Mit anderen CAD-Programmen
*(SolidWorks, FreeCAD, Rhino, CATIA, Creo u. a.)*  
Importiere die `.step` Datei. Geometrie und Baugruppenstruktur sind vollständig erhalten. Modellhistorie und Parameter werden dabei nicht übertragen.

---

## Lizenz

Dieses Projekt steht unter der **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** Lizenz.

- ✅ Nutzen, anpassen und weitergeben erlaubt
- ✅ Namensnennung des Erstellers erforderlich
- ❌ Kommerzielle Nutzung nicht gestattet

🔗 [Lizenztext (englisch)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## Kontakt & Mitwirken

**Erstellt von:** Roman Thurnherr  
**Fragen & Verbesserungsvorschläge:** gerne als GitHub Issue oder Pull Request

---

*Letzte Aktualisierung: März 2026*
