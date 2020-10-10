# lexicon-sentiment-analysis
Simple example of using a lexicon to perform sentiment analysis

# Usage

```
python ./doAnalysis.py
```

# The lexicon

I've created a simpler format of the lexicon, using the `reformat.py` script. The resulting file is `lexicon_easy.csv`,
and that's what the `doAnalysis.py` script uses.

# Data

Included in this repository is a dataset of tweets. Each row contains three columns:

1. The tweet text.
2. The tweet ID.
3. The tweet publish date

The full dataset (i.e., `newtwitter.csv` contains 8,595 rows. A small sample of 100 rows (i.e., `newtwitter.small.csv`) is also provided.



