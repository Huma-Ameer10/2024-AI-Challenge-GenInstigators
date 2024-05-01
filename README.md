# 2024 AI Challenge- GenInstigators

# AI Equity Advisor

## Table of contents
* [Introduction](#introduction)
* [Features](#features)
* [Technologies](#technologies)
* [Getting Started](#getting-started)
* [Screenshots](#screenshots)
* [Feedback](#feedback)
  
## Introduction 

Welcome to the AI Equity Advisor! Our solution aims to revolutionize the investment recommendation process for financial stakeholders, providing transparency, efficiency, and accuracy in decision-making. By combining real-time analysis of news based event impacts in conjuction with technical indicators, our tool offers well-informed stock recommendations in the dynamic stock market environment.

## Features

- Automatic detection of real-time news based events and their impact on the market trend.
- Integration of technical indicators with actionable trading insights for comprehensive analysis.
- Efficient and personalized stock recommendations via. Custom Generative module.
- Chatbot integration allowing analysts to ask questions and recieve instant guidance from AI-stock Advisor.

## Technologies

- Programming Language: Python (version: 3.10.4)
- UI Framework: Streamlit (version: 1.12.0)
- Generative AI: Langchain, LLama2, GPT 3.5
- Technical Indicators Library: TA-Lib
- Data Visualization: plotly (version: 5.10.0)
- Embeddings Storage: VectorStore
  
## Getting Started 
1. You can utilize our tool via. the Hugging Face Hub [here](https://huggingface.co/spaces/GenInstigators/NLFF-AIChallenge).
2. Alternatively, you can run our Streamlit app by navigating to the directory containing `app.py` in your terminal and execute the following command: streamlit run app.py.
3. To utilize the GenAI module for recommendation inference, ensure to execute the "genai-recommendation-inference" notebook with GPU access enabled.
4. Provide the required parameters and preferences.
5. Receive GenAI based stock recommendations.

## Screenshots

1. <b>Market Analysis</b> module provides actionable market insights for the following day based on the Current Date selected. Each indicator generates trading signals based on data driven trading startegies employed. Preference based signal range can be selected to plot on the close trend.
   
   ![equity1](https://github.com/Huma-Ameer10/2024-AI-Challenge-GenInstigators/assets/92379160/71966943-e378-4403-80f3-7c48be5d9a47)

2. <b>News Analysis</b> module can automatically detect the events from the real-time news to highlight their impact on the market trend. Detail of events with high impacts is also in display for comprehensive analysis.

   ![nws](https://github.com/Huma-Ameer10/2024-AI-Challenge-GenInstigators/assets/88269723/3f35c04c-ffe5-448f-b7f1-eb743ecdeeca)
  
   ![events_identified](https://github.com/Huma-Ameer10/2024-AI-Challenge-GenInstigators/assets/88269723/9c432611-de57-41fc-b6a9-05567422bac0)

3. <b>GenAI Recommendations</b> is a module built with GenAI technology which provides Custom recommendations to the user based on his role as an equity analyst or an active trader. By analysing both the technical indicators and news based event impact, a risk tolerance based recommendation along with its rational is generated for the following day.For quick accuracy check of the generated recommendation market close price for current day and following day are also provided.

   ![genAIrecomm](https://github.com/Huma-Ameer10/2024-AI-Challenge-GenInstigators/assets/88269723/d5dd1413-1241-48c6-9215-880c347d0372)

6. <b>Ask AI Advisor</b> allows the user to have an instant guide on a matter of investment from an AI powered Stock Advisor.

   ![CHAT](https://github.com/Huma-Ameer10/2024-AI-Challenge-GenInstigators/assets/88269723/7153d2b4-a7d1-4da8-bc84-ea79b2aa9bba)

## Feedback

We value your feedback! If you have any query or suggestion, you may contact us at [gen.instigators@gmail.com](mailto:email@example.com).

