# essential-eda-methods

Goal of EDA: Quickly understand the structure, quality, and relationships in your dataset to guide cleaning, feature engineering, and modeling.


# 1. Quick Peek at the Data
What: View a small slice to sanity-check columns and values.
Typical ops: df.head(), df.tail(), df.sample(k)
Why: Confirms load worked, spots obvious issues (weird encodings, wrong delimiters).
