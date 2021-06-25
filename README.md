# Crypto Trading Bot

## General Information
Dieses Projekt enthält einen Trading Bot für Kryptowährungen der basierend auf verschiedener Trading Faktoren eine Kauf- oder Verkaufsentscheidung fällt. Es handelt sich um keinen Trading Bot, der Fast-Trading betreibt.

## Trading Faktoren
Die Trading Faktoren umfassen folgende Parameter:

- **Sentiment Analysis Twitter**: Zeigt an, inwiefern ein Tweet Bullish/Bearish/Neutral sind
- **Sentiment Analysis News**: Zeigt an, inwiefern die News Bullish/Bearish/Neutral sind
- **RSI**: RSI steht für relative Stärke Index. Er ist ein wichtiges Instrument in der technischen Analyse, da er die Dynamik eines Assets bestimmt und beurteilt, ob sich dieses in einem überkauften oder überverkauften Bereich befindet
- **MACD**: Der MACD berechnet die Differenz zweier Exponentieller Gleitender Durchschnitte (EMA) und stellt diese in Form einer Linie dar. Meistens hat der MACD eine zusätzliche Signallinie (Trigger). Mithilfe des MACD Indikator lassen sich Trendrichtung, stärke, sowie verschiedene Kauf- und Verkaufssignale definieren
- **Score**: Der User kann die Gewichtungen der einzelnen Paramter wählen. Ab einem Score von 80 wird eine Buy Order ausgeführt


## Programmiersprache und Technologie 

Das Script wurde durch folgende Programmiersprache umgesetzt:
Python


## Requirements
Verwende npm zum installieren der Packages
-	**requests**
-	**os**
-	**json**
-	**langdetect**
-	**csv**
-	**ernie**
-	**numpy**
-	**urllib.request**
-	**bs4**
-	**re**
-	**pandas**
-	**datetime**



## Verwendung
1.	Packages installieren
2.	Twitter API Zugang beantragen und BEARER Token in das Script einfügen
3.	Binance Account eröffnen und API's erstellen und im Script einbetten
4.	Script ausführen

## Weiteres
Bei Fragen zur Ausführung melden
