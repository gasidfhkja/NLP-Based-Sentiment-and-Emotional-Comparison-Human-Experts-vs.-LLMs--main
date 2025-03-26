# NLP-Based Sentiment and Emotional Comparison: Human Experts vs. LLMs

### Email: adityaanand10122002@gmail.com

## Code Repository

* **PYTHON (Jupyter Notebook) Code** : [PROJECT.IPYNB](https://colab.research.google.com/drive/1I56j0Nsq9zJrfJOkkZe-LZc9SpsCblKz?usp=sharing)

1. Download the all Files
2. Open the Google Collab/Jupeter Notebook and runcode .
3. Make Changes , adding your own feched data, etc .

## Requirements

- Python
- Google collab /Jupyter Notebook
- Excel
- NLP Python Libraries

## Abstract

Two years ago , we never thought that LLMs could be a possibility in the near future but in just a span of 6 months ,chatgpt took over the world. Humans are still trying to figure out how the world would be with LLMs and what will be the job opportunities with AI taking over.

## Methodology

##### Data Collection:

We aggregate our data from two sources: onsite interviews with corporate experts and five widely popular LLMs: ChatGPT, Google Gemini, Microsoft Copilot, Claude, and Perplexity. We directed all questions asked, both to human experts and LLMs, in a business context.

![1731746917529](image/README/1731746917529.png)

##### Data Extraction & Structuring :

Both manual and automated transcription methods were used to convert audio interview responses to text. The transcribed data was organized into structured tables for analysis, with each question paired with human and AI responses.

[ORIGNAL RESPONSE DATA ](https://github.com/ONESHOT07GIT/NLP-Based-Sentiment-and-Emotional-Comparison-Human-Experts-vs.-LLMs-/blob/main/Response%20data%20All.csv "CSV FILE")

##### Preprocessing Techniques:

**We performed the following NLP preprocessings:**

![1731746929448](image/README/1731746929448.png)

[PREPROCESSED DATA](https://github.com/ONESHOT07GIT/NLP-Based-Sentiment-and-Emotional-Comparison-Human-Experts-vs.-LLMs-/blob/main/preprocessed_responses.csv "CSV FILE")

##### NLP and sentiment analysis:

We got score responses from humans and AI with the help of Emotional analysis and sentiment analysis .Then we given them range and respective sentimental , emotional label

##### Data visualization:

Each response was labeled and categorized to facilitate comparative analysis, with a consistent format applied to both human and AI-generated responses.

##### Manual comparison:

Everything is not just about code,algorithm and output, so we manually analyze how human responses give a sense of connectivity and how their life decision affect the output of their responses

## Model Details

* **LLMs** Used: **ChatGPT, Google Gemini, Microsoft Copilot, Claude,** and **Perplexity,** each chosenfor their distinct **NLP** capabilities.
* **Sentiment and Emotional Analysis** Models: **FinBERT** for corporate sentiment, **TextBlob** and **VADER** for general sentiment analysis, and **DistilRoBERTa (Transformers)** for emotion detection.

## Objective

We used five large language models (LLMs)—ChatGPT, Google Gemini, Microsoft Copilot, Claude, and Perplexity—to generate responses to questions asked of corporate specialists. These AI-generated responses are then analyzed to compare emotional depth, sentiment, lexical complexity, and other factors against responses from human professionals.

![1731747096514](image/README/1731747096514.png)

## Theoretical/Experimental Work

##### Distribution and Length Analysis:

Using descriptive statistics, we evaluated the average length and word diversity in responses to identify differences in information density and engagement.

##### Sentiment Analysis:

![1731746955606](image/README/1731746955606.png)

##### Emotional Analysis

![1731746970699](image/README/1731746970699.png)

## Results and Discussion

### Descriptive Statistics

![1731746985227](image/README/1731746985227.png)

![1731746994879](image/README/1731746994879.png)

### Sentiment Analysis Results

![1731747004516](image/README/1731747004516.png)

![1731747012444](image/README/1731747012444.png)

![1731747072164](image/README/1731747072164.png)

### Emotional Diversity Analysis Results

![1731747082042](image/README/1731747082042.png)

### Manual comparison

* Humans answer have a lot to say of their life experience compare to LLM Models Humans answer based on the facial expression the other person was giving ( that make the interaction wholesome)
* Human answers were more effective for audiences seeking practical, experience-backed insights, while AI answers were appeals to those looking for a more straightforward, data oriented response. Each script has value, but Script 1 stands out for its ability to connect complex ideas with personal anecdotes that illustrate the irreplaceable role of human judgment in the world
* AI answers were mostly diplomatic and to the general believe but human answer gives a sence of
  perspective.
* AI answers were less about the speaker's personal journey and more about the general implications, such as efficiency gains and ethical oversight.
* Human conversational almost storytelling-like answers make the speaker's points more engaging and memorable. By discussing topics like “gut feeling” or using language nuances (e.g., how “maybe” isinterpreted), the speaker illustrates why personal experience is indispensable
* Because it lacks the speaker's personal touch, AI answer may come across as less persuasive or relatablefor audiences who are looking for experiential insights that ground theoretical concepts in real-world practice.
* The Human frequently uses everyday analogies, such as how different people might perceive an“apple” differently (red vs. green vs. violet), to illustrate the subjectivity in finance. This adds clarity and accessibility, allowing the listener to understand complex ideas through relatable concepts.
* We concluded that current LLM models cant be used to pursue humans to do a particular things or introduce to new ideas and opportunity that can alter his/her life
* [ Manual comparison of Chatgpt(OpenAI) vs Human](https://docs.google.com/document/d/1hrbPueV9qCctJtxesongnHSweEPnDw86VgcWKnhSf-Q/edit?usp=sharing "DOCX FILE")

## Conclusion

##### What AI Can't do

* We concluded that even LLMs are effective then too they can’t pursue humans as pursuing human to a cause require real emotions
* Change answer to the facial expression of Humaas
* Can't give perspective oriented answer,as it is generalize
* LLMs are neutral as companies owning that LLMs do not allow them to incline to any cause
* Can't give practical knowledge
* Humans have better story telling capabilities compare to LLMs as stories comes with experience
* Sometime to understand a problem, human need context, not just some concise explanations

##### Recommendations

* Training LLMs on datasets that are supposed to be replete with complex emotional cues so as to mirror
  human response diversity more competently.
* Calibrating the outputs of AI sentiments in such a manner so not to sound overly positive, insincere,
  and unnatural.
* The integration of real-world experiential data to balance and nuance AI responses

### References

##### Links to Documentation

* [https://www.nltk.org/- The official documentation of NLTK library.]()
* [https://github.com/ProsusAI/finBERT- The official github page of Finbert.]()
* [https://spacy.io/api/doc- The documentation of SpaCy]()
* [https://pypi.org/project/vaderSentiment/- The documentation of Vader.]()

##### People Interviewed

**Shivam Verma (CTO Chat360),Vikrant Kulkarni (Director ,Bank of New York), Rahul Barve (Executive VP , ZEE NEWS), Shantamona Bharadwaj(VP Talent Acquisition , DBS), Amrita Singh (CDO,Tata Motors), Aditya Agarwal (Director(Marketing) , LeadSquare), Pankaj Mishra (Director- Autodesk),Akhil Sharma (Director(product)- Razorpay)**
