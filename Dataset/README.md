# Dataset preprocessing

This project employs a combined dataset from two different sources of ASAG data.
1. 'expand.txt'
2. 'mohler_joined.csv'

Sources for both files can be found in the preprocessing notebook 'ASAG_EDA_Dataset_processing.ipynb'

This was performed to obtain a large enough dataset with varied samples.

Further, the scoring criteria was modified from the original 0 to 5 points (0.5 increment) scale.
The modifications include:
1. Rounding the points to the nearest integer (to facilitate a more manageable number of classes)
2. Mapping a string score descriptor to support the LLM's innate ability to penalize natural language text over integer scores

The map is as follows:

| Score | Description |
|-------|-------------|
| 0     | Incorrect   |
| 1     | Poor        |
| 2     | Fair        |
| 3     | Adequate    |
| 4     | Good        |
| 5     | Excellent   |


These modifications results in a 6 label dataset saved as 'combined_string_scoring.csv'



