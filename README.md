# Collecting_Data_Final_Individual_Project
# Analysis of the Top 5 Popular Science Fiction Books on Project Gutenberg
This project conducts a comprehensive analysis of five of the most popular science fiction books available on Project Gutenberg. Using natural language processing (NLP) tools provided by spaCy and a range of visualization techniques, we explore the linguistic and thematic elements that have cemented these novels as classics in the science fiction genre.

### Corpus Description
The corpus consists of the following five seminal science fiction works:

1. "Frankenstein" by Mary Shelley
2. "The Strange Case of Dr. Jekyll and Mr. Hyde" by Robert Louis Stevenson
3. "The Time Machine" by H.G. Wells
4. "The War of the Worlds" by H.G. Wells
5. "Twenty Thousand Leagues under the Sea" by Jules Verne

### File Format and Content
- `.txt`: Raw text files containing the full text of each novel.
- `.csv`: Comma-separated values files created during the analysis, containing metadata, NER results, sentiment scores, etc.
- `.ipynb`: Jupyter Notebook files detailing the analysis process, including code, visualizations, and interpretative text.
 the notebook in this repository consists of three parts:
    - Part 1: Getting Started: This section walks users through setting up their environment, including installing necessary Python packages, downloading the spaCy language model, and loading the texts into the analysis environment.

    - Part 2: Text Enrichment with SpaCy: We use spaCy to enrich the text data through tokenization, part-of-speech tagging, and named entity recognition. This process allows us to extract meaningful patterns and insights from the raw text.

    - Part 3: Visualization: A variety of visualizations are presented, including word clouds, frequency histograms, and entity relationship graphs. These visualizations aim to make the data analysis more accessible and provide clear insights into the thematic and stylistic characteristics of the corpus.
   
### Target Audience
This project is intended for literary scholars, data scientists interested in NLP, and enthusiasts of classic science fiction literature.

### Intended Use
The analyses and visualizations provided here are intended for educational purposes, literary analysis, and further research into the field of digital humanities.

### Text Selection Criteria
The texts were selected based on their popularity, historical significance in the science fiction genre, and their availability as public domain works on Project Gutenberg.

### Data Collection Process
Texts were downloaded directly from Project Gutenberg using automated scripts that adhere to the site's robot.txt file and usage policies.

### Cleaning and Preprocessing
Text data underwent several cleaning and preprocessing steps to ensure quality analysis:

- **Metadata Removal**: Extraneous headers and footers provided by Project Gutenberg were removed.
- **Tokenization**: Texts were broken down into sentences and words for further analysis.
- **Normalization**: Words were standardized to lower case to ensure consistency in frequency analysis.
- **Stopword Removal**: Common English stopwords were removed to focus on the more meaningful content.
- **Lemmatization**: Words were reduced to their base or dictionary form.

After preprocessing, the text data was enriched with NLP techniques to facilitate the subsequent analysis.

**Contributors** 
- Yingyue Jiang

For detailed instructions, analyses, and findings, refer to the Jupyter Notebooks included in this project.
