# Semantic Composition Research
In natural language processing, the aggregation of words in an accurate fashion is invaluable. Models and architectures strive to achieve the highest accuracy in providing accurate meanings for words in the right contexts. Definitions of words can help develop these meanings and contexts. Since the definitions are themselves just a series of words, we can describe both the word and its definition using embeddings. The goal of this research is to create an architecture that can combine the series of embeddings of the definition of a word such that it is equal to the word's embedding. As of June 22, 2024, a prototype of such an architecture is in development using only 3,005 words.

## Phase 1: Data Extraction and Web Scraping
In this phase, the dataset needed to train such an architecture will be created. Five dictionaries will be scraped for the definitions of words, some of which include the Merriam-Webster's Dictionary and the Cambridge Dictionary. HTML and JSON files will be stored in the repository and will then be scraped for the definitions of the words they contain, meaning the dataset will consist of at least 15,000 instances.
