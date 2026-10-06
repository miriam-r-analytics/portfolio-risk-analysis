# Portfolio Risk Analysis (Python Project)

Ein Python-Projekt zur Analyse von Risiken und Erträgen im Portfolio.

## Projektbeschreibung
In diesem Projekt wird gezeigt, wie man historische Finanzdaten mit Python auswertet und ein Portfolio aus Aktien (SPY) und Gold (GLD) zusammenstellt. Ziel war es, das beste Verhältnis aus Rendite und Risiko zu finden sowie den maximalen Verlust im Vergleich zum S&P 500 zu reduzieren.

## Hauptfunktionen
* **Datenbezug:** Automatischer Download von historischen Kursen über `yfinance`.
* **Portfolio-Optimierung:** Berechnung der optimalen Verteilung (ca. 42% SPY / 58% GLD) mit `scipy.optimize`.
* **Kennzahlen:** Auswertung von Schwankungsbreite (Volatilität), Rendite-Risiko-Verhältnis und maximalem Verlust.
* **Verwendete Tools:** Python, Pandas, NumPy, SciPy, Matplotlib.

## Ergebnisse im Überblick
| Kennzahl | Optimiertes Portfolio | S&P 500 Benchmark |
| :--- | :---: | :---: |
| **Erwartete Rendite** | **15,53%** | 12,18% |
| **Schwankung (Risiko)** | **13,95%** | 17,19% |
| **Rendite-Risiko-Verhältnis** | **1,11** | 0,71 |
| **Maximaler Verlust (Drawdown)** | **-17,95%** | -24,50% |

## Fazit
Durch die Kombination von Aktien und Gold konnte das Gesamtrisiko des Portfolios gesenkt werden. Das Portfolio liefert bei geringerer Schwankung eine bessere Ertragslage als der reine S&P 500.
