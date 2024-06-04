# SLM Text Summarization Script
This python script provides a simple tool for summarizing long texts using the Small Language Model (SLM) technique. Using natural language processing (NLP) techniques to preserving key information from the original text, yet summarizing the text.

## Installation
1. Install Python (if not already installed) from the official website: https://www.python.org/downloads/

2. Install the required libraries using pip:

```
!pip install nltk
```
3. Download NLTK resources by running the following commands:
```
python -m nltk.downloader punkt
python -m nltk.downloader stopwords
 ```
## Usage 
1. Clone the repository or download the Python script (slm_text_summarization.py)

2. Open the Python script your IDE

3. Add your long quote or excerpt that you want summarized

4. Run the Python script.
```
   python slm_text_summarization.py
```

## Example
```
text = 
"We can view LLMs and SLMs as two ends of a spectrum with overlap in between. Overall SLMs distinguish themselves from LLMs
in one or more of the following ways. SLMs are more fine-tuned because vendors or companies train them on detailed,
domain-specific data, for example to assist complex data engineering tasks. They enrich user prompts, for example
by injecting domain-specific data into a user’s question to make the response more accurate. Data pipeline vendors
are building SLMs with these capabilities now, often alongside LLMs, to help companies tackle specialized data engineering
problems with better governance. This will help data teams boost productivity while reducing risks related to data quality,
fairness, and explainability. We should get ready for a boom of small language models in data engineering and many other fields."

- Kevin Petrie in Should AI Bots Build Your Data Pipelines? Part III: The Emergence of Small Language Models
for Data Engineering June 21, 2023
(Blog)

summary = summarize_text(text)
print("Summary:")
print(summary)
```
The output may look like
- "Small language models will help data teams boost productivity while reducing risks related to data quality, fairness, and explainability."

## Acknowledgments
The script uses NLTK (Natural Language Toolkit) for text processing.
