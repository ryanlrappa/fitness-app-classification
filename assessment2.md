### PersonaGraph Text Classification Case Study (60 minutes)

This is a challenge from [PersonaGraph](http://www.personagraph.com/). They use this challenge for prospective hires to test their abilities.

The data can be found in the `data/` folder.

* `train.txt` contains 2820 text descriptions of Android apps
* `labels.txt` contains a corresponding list of label data (ones and zeros indicating if they are fitness apps or not). Note that the first half are all positive cases (1) and the second half are all negative (0).

Your task is to build a model to classify the data. You should use whatever libraries you find helpful (sklearn, nltk, etc.)

You should submit two files located in the `submissions/` folder:

* `personagraph.py` containing your code
* `personagraph.txt` (or markdown if you prefer) containing your analysis

Here are some questions to consider and make sure you answer in your analysis.

1. What models and featurization techniques (stemming vs lemming, tf-idf vs bag of words, etc.) did you compare?

2. What validation and testing methodology did you use?

3. Which model did you choose and why?
