In our paper [Robust Benchmarking for Clinical Entity Extraction](http://arxiv.org/abs/2007.16127), we find that current performance of clinical entity extraction systems is still brittle, and that further work needs to be conducted. As part of this we developed a new schema, outlined in the paper, and below we provide instructions on how to access the proof-of-concept dataset we constructed. 

## MIMIC Access
For this dataset, we annotated notes from the [MIMIC Critical Care Database](https://mimic.physionet.org/). The dataset has been made publicly available, subject to completing the relevant trainings. See detailed instructions on gaining MIMIC access [here](https: /mimic.physionet.org/gettingstarted/access/). 

## Connecting MIMIC to Google Cloud
To ensure we only allow access to those users who have completed MIMIC credentialing, we are storing the dataset in a Google Cloud bucket only accessible by users who have MIMIC access. To connect your Google Cloud account to your Physionet account, follow the step-by-step instructions available [here](https://mimic.physionet.org/gettingstarted/cloud/). 

## Dataset
Once you have gained MIMIC access and connected to Google Cloud, you should be able to access the dataset at [this link](https://console.cloud.google.com/storage/browser/mimic_nlp_annotations). 

This version of the dataset has been collated from the two annotators, and we wanted to provide it for exploration. We plan to release a more thorough version with more fleshed out synonyms later in 2020. To be contacted when this is released, please fill out [this Google form](https://forms.gle/svNwWntkyqAHFFq37) with your email, and we will get in touch!

If you have any questions, please contact Monica Agrawal at magrawal [at] mit [dot] edu
