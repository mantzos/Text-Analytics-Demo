## Demo: Text Analytics for a Pizzeria
### using Cognitive Services within Azure Synapse and Power BI Pro

This is a demo series, showcasing how to perform sentiment analysis, text translation and key phrase extraction using [Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) on [Power BI Pro](https://powerbi.microsoft.com/en-us/) and [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/). The end result is a Power BI report, used by the pizzeria owner to understand why sales change, based on the customer feedback and the sentiment it indicates.

A [sample text file](https://github.com/mantzos/Text-Analytics-Demo/blob/main/files/synapse_comments_tab.txt), containing mock customer feedback should be upldated to Azure Data Lake. Then a [Synapse notebook](https://github.com/mantzos/Text-Analytics-Demo/blob/main/Spark%20notebook%20v.1.ipynb) is used to translate Greek comments into English and perform sentiment analysis. The output parquet file is then used as input for the Power BI report. Extra transformations involve calling a key phrase extraction cognitive service and setting up incremental refresh, within Power BI Pro. This [1st stage output](https://github.com/mantzos/Text-Analytics-Demo/blob/main/files/Data%20ready.pbix) is then used to create the [final report](https://github.com/mantzos/Text-Analytics-Demo/blob/main/files/Report%20Ready.pbix).

There are also explanatory videos on youtube, going through the various stages of the demo:

1. [Intro](https://youtu.be/36Lekgu0iaU) - briefly showing the report and providing context.
2. [Visualization](https://www.youtube.com/watch?v=GE56zs8xR2E) - focusing on the work required to create the visuals of the report, given the dataset.


Disclaimer: Please note that the contents of this repo and my comments in the videos are provided as is without warranty, and represent my own views and not necessarily the views of my employer or Microsoft.
