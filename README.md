# Senior-Thesis

This repository contains all of the jupyter notebook files and my final report used during my undergraduate American Studies senior thesis. Below is the abstract of my final essay. 

# Abstract

On September 17th, 2011, hundreds of activists gathered around Zuccotti Park in lower Manhattan to advocate for a radical restructuring of our socioeconomic system under the title Occupy Wall Street. As a result of the massive scale of both the on-the-ground protests and the online discussions that occurred on social media sites such as Twitter, the digital and the physical dialectical landscapes developed into distinct spaces of conversation. This paper aims to answer what the key messages and topics of these two spaces were and how they potentially impacted one another. Through the use of topic modeling and sentiment analysis to analysis to analyze online discussions on Twitter during this time and close readings of print sources written by those present at the Occupy movement, we were able to identify key topics in each landscape. Tweets about OWS fell into one of seven categories: 1) Other political groups and movements, 2) Policy discussions, 3) On-the-ground updates 4) Occupying other spaces 5) Police violence 6) Occupy strategy and theory, or 7) Solidarity and support. While on the ground, the main topics discussed were 1) Police, 2) Movement concerns, 3) Theory, Strategy, and Messaging, and 4) Goals. Ultimately, despite having very similar topics of conversation, how each of these topics was addressed varied wildly online versus on the ground. While on the ground, the movement was able to focus on a few key issues, messages, and demands due to the organizational structure of the New York General Assembly, online the discussion was disorganized and unable to reach consensus on many key topics such as strategy, theory, and goals, due to its lack of a rallying voice. This also left the discussion online ripe for infiltration by outsiders and dissidents who would use the same hashtags and keywords to spread their own messages as well as speak negatively about the movement. This project provides a look at how online activism can differ while still impacting traditional activism.

# Project Details

Exploratory Data Analysis was first performed using pandas and plotly. Then topic modeling was performed using gensim's LDA modeling functions. Finally sentiment analysis was performed using VADER. The tweet dataset was supplied by researcher Cheng-Jun Wang of Nanjing University. The dataset comes from his team’s research project, “Discussing Occupy Wall Street on Twitter: Longitudinal Network Analysis of Equality, Emotion, and Stability of Public Discussion.” It features over six million tweets posted between October 1st, 2011, and February 22, 2012. These tweets were obtained through Twitter's open API by R-shief. Each tweet contains keywords relating to OWS, such as #ows, #occupywallstreet, and #occupy. Dr. Wang asked that the dataset not be shared publicly though so I am unable to add it to this repo. All notebooks were originally written and run in Google colab. 
