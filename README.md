## Demo: Sentiment Analysis for a Pizzeria, with Cognitive Services, Synapse and Power BI

This is a demo series, showcasing how to perform sentiment analysis, text translation and key phrase extraction using Cognitive Services on Power BI Pro and Azure Synapse. The end result is a Power BI report that can be used by the pizzeria owner to understand why its sales change, based on the customer feedback and the sentiment it indicates.

A sample text file containing mock customer feedback should be upldated to Azure Data Lake. Then a Synapse notebook is used to translate Greek comments into English and perform sentiment analysis. The output table in ADL is then used as input for the Power BI report. Extra transformations involve calling a key phrase extraction cognitive service within and setting up incremental refresh, within Power BI Pro. This 1st stage output is then used to create the report.

There are also explanatory videos on youtube, going through the various stages of the demo:

1. [Intro](https://youtu.be/Mxh8_FWL8r8) in English - briefly showing the report.


Disclaimer: Please note that the contents of this repo and my comments in the videos are provided as is without warranty, and represent my own views and not necessarily the views of my employer or Microsoft.
