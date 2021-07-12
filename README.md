# WhatsApp Group Chat Data Analysis
For the fun of it, and to throw bants, I have taken up this task. lol

## Introduction
WhatsApp Messenger is a cross-platform messaging and voice-over-IP (VoIP) service that allows users to send text messages and voice messages, make voice and video calls, and share images, documents, user locations, and other content.

The WhatsApp application runs on mobile devices but is also accessible from desktop computers, as long as the user's mobile device remains connected to the Internet while they use the desktop app.

In this project, the usage of WhatsApp in a Group Chat made up of colleagues from the same workspace in analyzed. The intent is to carry out an exploratory data analysis on the interactions within the group in order to discover patterns, test hypothesis, and summarize its main characteristics using basic visualization methods.

A couple of questions are also asked of the data as well, and no doubt, it sure gave us some interesting answers. 😎🥱

## Background Information
### Data Overview, Scope, Boundary, Approach 

The data source of the analysis is a download of the Group’s WhatsApp Chat record.  WhatsApp has a functionality that enables a download of the conversation logs of individual and group chats. To do this, just select any conversation, click on the dots on the top right, click on 'More' then 'Export chat'.

For this project, we have exported the logs `without media` files. This generates a `.txt` text file which is a time-ordered list of events that occurs within the chat mostly made up of text messages. Each line is a single message and is in the following format:

`date, time - sender: message`

The exported data for this project covers a period that ranges from:

`30/06/2020, 09:21 to 30/06/2021, 17:04`

And does not include an analysis of the usage of multimedia files such as audio, images, voice notes, video, etc sent within the group.


## Steps/Approaches

### Step 1
Our approach first involves importing all the necessary python libraries into the Jupyter notebook, that will be used for the analysis. 

### Step 2
We then define a python function that takes in the raw file (exported WhatsApp conversation) as it’s input and this file is parsed through a python regex function in order to convert it into a pandas dataframe, carrying the right type and format for the data in each column.

### Step 3
Performed various analysis on the data and recorded the observations and findings. Some of the questions asked of the data are listed below:

1. Most active users in the group?
2. Average number of messages per day?
3. Most active time of day in chat room?
4. Most active months of conversations?
5. The emoji y’all used the most or the least?
6. Emoji usage by specific group members?
7. A word cloud of the commonly used words?
8. Distinct conversations within the group?
9. Who starts the most conversations?
10. Weekday versus Weekend usage pattern?
11. etc…

## Suggestions on future work/Improvement plans

With every Data Analysis Project, there’s always room to expand upon the results, there’s always more questions that can be asked of the data, there’s always a hypothesis to test, there’s always more insights that can be gleaned.

Looking forward to hearing your thoughts on this, especially challenging the inferences and conclusions that the data has presented to us.

Let me know of any questions you would love to ask of the data; until then I don’t want any of you fighting over the results in this report. God bless y’all.
