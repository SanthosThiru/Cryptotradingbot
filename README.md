# Crypto Trading Bot
![alt text](https://images.unsplash.com/photo-1614787296891-d1b2b1aced36?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1350&q=80)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hgjudzojmvlB47dCXP02JB73kPKe3H1g?usp=sharing)

## Präsentation 
[Trading Bot Abschlusspräsentation.pdf](https://github.com/SanthosThiru/Cryptotradingbot/files/6817049/Trading.Bot.Abschlussprasentation.pdf)


## General Information
Dieses Projekt enthält einen Trading Bot für Kryptowährungen der basierend auf verschiedener Trading Faktoren eine Kauf- oder Verkaufsentscheidung fällt. Es handelt sich um keinen Trading Bot, der Fast-Trading betreibt.

## Datensatz
Entweder Tweet Stream erzeugen und abspeichern. Dort händisch die Sentiments labeln. Alternativ Datensatz aus dem Github Repo nutzen. 


## Trading Faktoren
Die Trading Faktoren umfassen folgende Parameter:

- **Sentiment Analysis Twitter**: Zeigt an, inwiefern ein Tweet Bullish/Bearish/Neutral sind. 
- **Sentiment Analysis News**: Zeigt an, inwiefern die News Bullish/Bearish/Neutral sind
- **RSI**: RSI steht für relative Stärke Index. Er ist ein wichtiges Instrument in der technischen Analyse, da er die Dynamik eines Assets bestimmt und beurteilt, ob sich dieses in einem überkauften oder überverkauften Bereich befindet
- **MACD**: Der MACD berechnet die Differenz zweier Exponentieller Gleitender Durchschnitte (EMA) und stellt diese in Form einer Linie dar. Meistens hat der MACD eine zusätzliche Signallinie (Trigger). Mithilfe des MACD Indikator lassen sich Trendrichtung, stärke, sowie verschiedene Kauf- und Verkaufssignale definieren
- **Score**: Der User kann die Gewichtungen der einzelnen Paramter wählen. Ab einem Score von 80 wird eine Buy Order ausgeführt

## Sentiment Analysis Twitter
Hierzu wurde ein Pretrained Model verwendet (BERT Uncased). Weitere Informationen sind hier zu finden --> https://github.com/labteral/ernie. Accuracy +95%

## Sentiment Analysis News
Hierzu wurde https://pypi.org/project/pysentiment/ implementiert

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


## Ausführung
1.	Jupyter Notebook installieren oder den Code über die oben genannten Verknüpfung auf Google Colab ausführen
2.	Das Model befindet sich unter folgendem Ordner und sollte vor der Ausführung in Colab runtergeladen und in der Drive gesichert werden.
--> https://drive.google.com/drive/folders/1ol0QOybtzeNlYHWc7sM7RxAGDiEfhpc4?usp=sharing
4.	TradingBot2 Code kopieren und in ein eigenes Notebook einfügen
5.	Packages installieren, die unter Requirements genannt wurden
6.	Twitter API Zugang beantragen und BEARER Token in das Script einfügen
7.	Binance Account eröffnen und API's erstellen und im Script einbetten
8.	Trading Parameter eingeben (Wieviel Profit?)
9.	Script ausführen 

## Weiteres
Bei Fragen zur Ausführung melden
