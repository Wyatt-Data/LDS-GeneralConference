# LDS General Conference Talk Analyzer

This is a personal NLP project I built to convert LDS General Conference talks into engaging, tailored lessons for Sunday study or quick personal reflection.

## Motivation

I once had an Elder's Quorum President who would lead lessons by simply popcorn-reading conference talks. It was dry and uninspiring—I've been guilty of dozing off. So I decided to build something better.

Every Sunday, I now use this tool to break down General Conference talks into actionable insights, summaries, and core themes. It's helped me teach and learn with more purpose.

## Features

- 📝 **Text Preprocessing**  
  - Paragraph segmentation  
  - Lemmatization and stopword removal

- 📊 **TF-IDF Sentence Ranking**  
  - Ranks sentences by importance within each paragraph  
  - Highlights key ideas and concepts

- 🧠 **Theme Extraction**  
  - Uses TF-IDF keywords to derive core sermon themes

- 📚 **Automatic Summarization**  
  - Delivers a concise, readable summary of any General Conference talk

- 🎛️ **Streamlit UI**  
  - Easy-to-use web interface  
  - Select talks, view summaries, and prepare lessons on the fly

## How It Works

1. Paste a General Conference talk URL.
2. The NLP pipeline processes and cleans the text.
3. TF-IDF analysis identifies the most important words and sentences.
4. Summary and themes are generated and displayed in a user-friendly format.

## Tech Stack

- **Python**
- **Streamlit** – for the web interface
- **NLTK** – for text processing
- **scikit-learn** – for TF-IDF and vectorization

## Use Cases

- Sunday lesson prep  
- Personal study  
- Youth or Gospel Doctrine teaching aids  
- Quick theme analysis for any talk

## Example



## Try it Out

https://generalconferenceanalysis.streamlit.app/


