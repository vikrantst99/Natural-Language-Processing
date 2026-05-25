Dataset: messy_real_movies_nlp_550.csv
Rows: 550
Base source: TMDB 5000 Movie Dataset. Movies/credits were merged using movie id.
Important: title, description, genre, actors, directors, release dates, ratings and vote counts are based on real TMDB metadata.
The review column is a derived review-summary text generated from real vote_average and vote_count, not raw user review text.
Intentional irregularities added: missing values, inconsistent casing, noisy punctuation, mixed separators, date format variation, numeric values as text, and duplicate-ish rows.
Use this for NLP preprocessing: text cleaning, tokenization, stop-word handling, vectorization, feature extraction, classification/topic modeling experiments.
