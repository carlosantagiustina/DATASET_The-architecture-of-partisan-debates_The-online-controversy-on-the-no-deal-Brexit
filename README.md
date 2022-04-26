# DATASET - The architecture of partisan debates: The online controversy on the no deal Brexit

This repostiory contains the list of Tweet IDs of the 204 648 causal Tweets identified in the paper titled "The architecture of partisan debates: The online controversy on the no deal Brexit", by Carlo R. M. A. Santagiustina and Massimo Warglien, currently under review at PLOS ONE. <br><br>
Tweets in this dataset can be freely retrieved, with their [IDs](https://github.com/carlosantagiustina/DATASET_The-architecture-of-partisan-debates_The-online-controversy-on-the-no-deal-Brexit/blob/main/causal_nodeal_twitter_data_IDs.txt), using the GET /2/tweets/:id API endpoint (more info at this link: https://developer.twitter.com/en/docs/twitter-api/tweets/lookup/api-reference/get-tweets-id).<br><br>
These Twitter posts were published from the beginning of February 2019 to the beginning of May 2020. <br><br> They were collected with the [DMI-TCAT](https://github.com/digitalmethodsinitiative/dmi-tcat) using the [Twitter Filtered Stream API endpoint V1.1](https://developer.twitter.com/en/docs/twitter-api/tweets/filtered-stream/migrate/standard-to-twitter-api-v2). <br><br>
Our query is based on the following filtering conditions: "no deal" OR no-deal OR nodeal <br><br>
Causal Tweets have been identified from the flitered stream of Tweets using a Regex based causal argument extractor, called ISEED-AEA, which is available at the following link: [https://github.com/carlosantagiustina/ISEED-AEA](https://github.com/carlosantagiustina/ISEED-AEA) <br><br>

For additional information please contact: [Carlo R. M. A. Santagiustina - carlo.santagiustina@unive.it](mailto:carlo.santagiustina@unive.it)

