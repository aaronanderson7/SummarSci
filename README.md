# SummarSci

Name: Aaron Anderson, Jonathan Lau, Dominic Bell
Date: 06/10/2024
Summaery: GPT 3.5 API Web Application

# Introduction

Since the inauguration of GPT AI technologies in November of 2022, a great deal of focus and attention has been placed on how to best utilize the AI and how it might benefit not only technological users but also software development. The general web application interface for GPT has been strongly supported for everyday use, but our project at its core strives to research and understand how we might be able to utilize GPT for a specific application, when accessing GPT through its API. Through the course of this project, our team aimed to not only familiarize ourselves with how to use GPT API but also better understand how to fine-tune the AI for better utilization and potential application. 

The goal of our software was to build a web application that uses GPT 3.5 to accurately summarize a user-uploaded scientific publication. Our team did construct a fine-tuned GPT 3.5 model with scientific publication training datasets, however due to the reduced cost and effective output when utilizing prompt-engineering, our team decided to use the standard GPT 3.5 model. We have named our software SummarSci, a portmanteau of Summarize and Science. The application provides an accurate and detailed summary of a user-uploaded scientific publication.

# User Perspective

Reading and understanding scientific articles is time-consuming. The purpose of this software (SummarSci) is to help the user save time researching and analyzing scientific publications. SummarSci can take a user-inputted scientific publication and return a detailed and precise summary of the article. When using the web app, the user will first be prompted to upload a PDF of the publication. Once the publication has been uploaded, a summary of the publication ranging from 4 - 6 paragraphs will be displayed. 

The Home Page features a large upload button area, that when clicked, launches the users directory and asks them to choose a pdf file for upload. Furthermore, if the user uploads an article for summarization, but later decides to choose a different article, they can press the delete icon (a trash can) to get rid of the article and upload a new one. If the user tries to upload an article that is larger than 2000 KB, SummarSci will output an error message stating that the file is too large. Finally, once the user has uploaded their selected article, when they press submit, SummarSci will display a loading circle, while the summarization takes place. Once the summarization has completed, the user will be directed to a Results Page, with the summary outputted for their use. At the bottom of the Results page is a button that returns them to the Home Page. 

The user can access SummarSci’s article summarization on the Home Page of the web application. However, the user can also navigate to the About Page, and find detailed information about the web app and it’s creators (our team). The user can also navigate to the Contact Page, to submit a Google Form to contact the creators and submit any questions, errors, or suggestions. 

# Technologies

## Hosting
Google Cloud App Engine: Used to deploy both the frontend and backend applications as separate services.

## Backend
1. Python:
- Chosen as the backend language due to the OpenAI API having a lot of examples in Python and just for overall language familiarity across team members.2.
2. Flask:
- Chosen as the backend framework due to it being lightweight and easy to use.
3. The OpenAI API:
- Used as the GPT API for summarizations. 
4. aiohttp and asyncio libraries:
- Used for asynchronous operations.
5. pypdf and nltk libraries:
- Used for pdf parsing and summary complexity estimation.
6. Google Cloud Storage:
- Used for temporary file storage in the backend. Chosen since we knew we were going to host on Google Cloud and it made sense to keep everything with one provider.

## Frontend
1. React
- Chosen as the frontend framework due to team familiarity.
- Used for building the user interface with a component-based architecture.
2. React Router
- Used to manage routing across the different pages of the application without reloading the whole page.
3. React Hooks 
- Used for state management within components.
4. React Icons
5. CSS
- Used for overall styling of the application.
- Incorporated Google Fonts.
- Utilized media queries to make the application more responsive across various monitor screen sizes.


# Conclusion
Our Capstone project team chose the GPT API Project because we all had a curiosity and desire to learn more about the technology and how to best utilize it. And while there is still much left to learn, we can confidently say that we have a great deal of experience now when navigating not only GPT but also use of its API, prompt-engineering, fine-tuning, and ultimately how to best utilize it in software development. SummarSci is an important application that can help scientists and students alike in their goals of research and discovery, and we are proud of the product that we have built. There were a few deviations along the way of the construction of SummarSci, but it was immensely satisfying building a project from scratch and seeing it come to fruition. We hope to further expand on SummarSci’s functionality and continue to build applications using GPT API.

# UML

![GPT API](https://github.com/aaronanderson7/SummarSci/assets/107898465/b0c02595-6a6e-4f95-b82e-c00a12c34111)


# Poster

![SummarSci Poster pptx](https://github.com/aaronanderson7/SummarSci/assets/107898465/da0e4643-c95a-4e20-85a1-51cc4f3040a7)

