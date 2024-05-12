# News-Analyzer-and-Summarizer
## Introduction
<p>Empowering eﬀicient news consumption: Our innovative application transforms multiple complex Google Search results into brief, insightful news summaries for a streamlined information experience.</p>

## Problem Statement
<p>The increasing volume and diversity of news sources pose a challenge for individuals to stay well-informed. This also leads to wastage of time as users may spend excess time navigating through lengthy news articles, missing out on rapid access to concise and crucial information.</p>

## Solution Overview
<p>This solution is a smart news analyzer that acts like a helpful guide for news consumption. It reads through a number of news articles, figures out what’s important, and gives you short, easy-to-understand summaries, saving user’s valuable time otherwise spent navigating through extensive content, making news consumption more efficient and accessible.</p>

## KEY FEATURES AND BENEFITS
### 1. Eﬀortless Summaries: Distills complex news stories into concise summaries for quick comprehension.
### 2. Streamlined User Experience: Presents relevant content without overwhelming users with a user-friendly interface.
### 3. Time Savings: Empowers users to grasp the essence of news stories eﬀiciently, eliminating the need to go through extensive content.
### 4. Innovative Technology: Integrates LangChain for advanced content analysis, ensuring accurate and relevant summaries.
### 5. Future of News Consumption: Represents a pioneering approach to news consumption, seeing a precedent for eﬀicient and tailored content delivery.sendSend messageChecking who can access ﬁle.

## TECHNOLOGIES USED
![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/fa35dfeb-3007-4181-99bf-46cb61df06ad)
### Hugging Face Transformers
<p>A model hub containing many pre-trained models. The 🤗 Transformers library that supports the download and use of these models for NLP applications and fine-tuning. </p>

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/f047e2f9-ae4d-4045-ba29-343909419812)
### LangChain
<p>LangChainis a framework designed to simplify the creation of applications using large language models.</p>

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/f50894bb-4e51-4b05-9ba5-73b860a6225f)
### BEAUTIFUL SOUP
<p>Beautiful Soup is a Python library for pulling data out of HTML and XML files.</p> 

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/e303c8b9-6fd0-4353-b99d-08a09a6acef1)
### STREAMLIT
<p>Streamlit is a user-friendly Python library that simpliﬁes the process of creating interactive web applications.</p>

## CODE SNIPPET

<center>
  <p>Dependencies Imported</p>
</center>

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/9f7a8a65-2d7f-4a2f-8286-6167935720a5)


<center>
  <p>Search button</p>
</center>

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/a4a522a9-aec4-4e1e-8e68-2173c5c1ea6d)



<center>
  <p>Search and summarize button</p>
</center>

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/38070b9c-0729-48b3-94b4-f9bd0591cbbc)


## User Interface

<center>
  <p>Home Page</p>
</center>

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/d0e9a834-1b74-421f-a05c-89f8c886fefe)

<center>
  <p>Search Button</p>
</center>

![image](https://github.com/VidushiRastogi15/News-Analyzer-and-Summarizer/assets/118375146/036d5424-a733-4c2e-bce6-5a7e3c3e5c68)


## CHALLANGES & SOLUTION
<li><b>Challanges</b> :
Cost Implications with OpenAI API: Initially, our project planned to leverage OpenAI API for text summarization. However, we encountered the challenge of associated costs with using the OpenAI API, which may not align with our budget constraints.

<b>Solution</b> : 
Transition to Hugging Face LLM: In response to the cost challenges posed by OpenAI API, we made a strategic decision to transition to Hugging Face’s Language Models (LLMs) for text summarization. Hugging Face provides a rich collection of pre-trained models, including some eﬀicient and cost-eﬀective options for our summarization needs.</li>

<li><b>Challanges</b> :
One challenge encountered was the inability of the UnstructuredURLLoader to fetch content from links in the desired format. Despite its basic functionality for making HTTP requests and retrieving web page data, it lacked the robust parsing capabilities necessary to extract structured content, particularly from complex HTML documents.

<b>Solution</b> : 
As a solution, we opted to utilize the Beautiful Soup library, which excels in parsing HTML and XML documents, providing a flexible and intuitive API for navigating the parse tree and extracting relevant content.</li>

## CONCLUSION
<p>The goal is to simplify the news consumption process, oﬀering users a time-saving solution that distills relevant information from the vast and varied landscape of news content.</p>


  
