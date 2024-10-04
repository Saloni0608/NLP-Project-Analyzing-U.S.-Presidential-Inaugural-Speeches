# Inaugural Speeches Analysis Project

## Overview
This project analyzes the vocabulary used in the inaugural speeches of U.S. presidents from George Washington to Joe Biden. Using Natural Language Processing (NLP) techniques, it calculates the vocabulary size for each president's speech, compares vocabulary usage across political parties, and visualizes the data in a bar plot.

## Features
- Downloads and processes the inaugural speeches corpus from the NLTK library.
- Calculates the unique vocabulary size of each speech.
- Compares the vocabulary size of speeches based on party affiliation (Democrat, Republican, Other).
- Visualizes the vocabulary sizes in a chronological bar plot.

## Installation
To run this project, you need to have Python installed along with the following libraries:

```bash
pip install nltk pandas matplotlib
```

## Dependencies
The following libraries are used in this project:
- `nltk`: For Natural Language Processing tasks.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.

## Usage
1. **Download NLTK Data**: The script automatically downloads the necessary NLTK datasets, specifically the inaugural speeches corpus.
   
2. **Data Processing**:
   - The script reads the inaugural speeches, extracts relevant information (president, year, party affiliation, and speech text), and creates a DataFrame.

3. **Vocabulary Calculation**: 
   - Each speech's vocabulary size is calculated using the `calculate_vocabulary_size` function, which tokenizes the speech text and counts unique words.

4. **Analysis**:
   - Identifies the president with the most and least vocabulary.
   - Calculates average vocabulary sizes by party affiliation.

5. **Visualization**: 
   - Generates a bar plot representing the vocabulary size of each president's inaugural speech.

## Example Outputs
- **President with the Most Vocabulary**: Harrison (1841) with 1,794 unique words.
- **President with the Least Vocabulary**: Washington (1793) with 90 unique words.
- **Average Vocabulary Size by Party Affiliation**:
    - Democrat: 660.43
    - Republican: 775.35
    - Other: 865.69

## Visualization
The bar plot visualizes the vocabulary sizes of presidential inaugural speeches, color-coded by party affiliation: 
- **Democrat**: Blue
- **Republican**: Red
- **Other**: Gray

## Conclusion
This project provides insights into the vocabulary trends of U.S. presidents over time and highlights differences in language use across political parties.
