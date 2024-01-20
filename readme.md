# YouTube Assistant

YouTube Assistant is an application that harnesses the power of LangChain and the OpenAI model, combined with Streamlit, to provide users with an interactive interface. This interface allows users to input a YouTube video URL containing transcripts and ask questions related to the video content.

## Functionality

The core functionality of YouTube Assistant involves passing the video transcript through embeddings to the OpenAI model using FAISS (Facebook AI Similarity Search). This process enhances the analysis of the content, enabling users to make more nuanced and informed inquiries about the video.

## Usage

To run YouTube Assistant, execute the following command in your terminal:

```bash
streamlit run main.py
```

## Features

- **User-Friendly Interface:** Streamlined and intuitive interface powered by Streamlit.
- **Transcript Analysis:** Utilizes LangChain and OpenAI models for comprehensive video transcript analysis.
- **Question and Answer Capability:** Enables users to ask questions about the content of the video.


The example is taken from this video: [Freecodecamp](https://youtu.be/lG7Uxts9SXs?si=sK0sYVuGC0O86gkg)