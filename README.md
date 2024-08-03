  

# Persian Search Engine

  

Developed for the Information Retrieval course instructed by Dr. Ahmad Nikabadi in Fall 2022

  

## Development Phases

The project unfolded in two phases:

  

### Phase 1

tasks

  

-  **Data Preprocessing**:

-  **Normalization**: Using the `hazm` library, the text is normalized to handle different variations of words
-  **Removing Punctuation**: Eliminating punctuation marks from the text.

-  **Tokenization**: Splitting the text into individual tokens or words.

-  **Stemming**: Reducing words to their root forms (e.g., "wants" and "wanted" to "want").

-  **Stop Words Removal**: Removing common words (e.g., "the", "and").

  
  

### Phase 2

In the second phase, the focus was on improving retrieval effectiveness and optimizing the index:

  

-  **Enhancing Retrieval Effectiveness**:

-  **TF-IDF Scoring**: Using Term Frequency-Inverse Document Frequency (TF-IDF) to rank documents.
-  **Cosine Similarity**: Implementing cosine similarity to measure the similarity between query and document vectors.

-  **Index Optimization**:

-  **Champion Lists**: Creating champion lists to speed up query processing.
  
  

## Contributors

- Mahla Sharifi

- [Hosna Oyarhoseini](https://github.com/hosnahoseini)

  

## Diagrams

  

### Diagram 1: Heap's Law

Heap's Law describes the relationship between the size of the vocabulary and the number of words in a document collection. It suggests that as the size of the collection increases, the vocabulary size grows, but at a decreasing rate.

  

#### Heap's Law with Stop Words

![Heap's Law with Stop Words](![https://github.com/mahlashrifi/Persian_Search_Engine/blob/main/report.pdf/screen_shots/Heap_with_stop_words.png)

  

#### Heap's Law without Stop Words

![Heap's Law without Stop Words](![https://github.com/mahlashrifi/Persian_Search_Engine/blob/main/report.pdf/screen_shots/Heap_without_stop_words.png)

  

### Diagram 2: Zipf's Law

Zipf's Law states that in a given corpus of natural language, the frequency of any word is inversely proportional to its rank in the frequency table. T

  
  

#### Zipf's Law with Stop Words

![Zipf's Law without Stop Words](![https://github.com/mahlashrifi/Persian_Search_Engine/blob/main/report.pdf/screen_shots/Zipf_with_stop_words.png)

  

#### Zipf's Law without Stop Words

![Zipf's Law without Stop Words](![https://github.com/mahlashrifi/Persian_Search_Engine/blob/main/report.pdf/screen_shots/Zipf_without_stop_words.png)