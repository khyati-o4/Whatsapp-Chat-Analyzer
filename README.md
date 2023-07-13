# Whatsapp-Chat-Analyzer
app to analyze WhatsApp chat statistics

# Objective

In this project, we aim to build a WhatsApp chat analyzer that provides chat analysis and statistics for the group as well as individual chats.

# About the Project

The project is based on the Streamlit framework and is a Python-oriented project to give chat analysis and statistics. This project helps to give the chat activity analysis by showcasing the total messages, total words, total media shared, total links shared, the chat daily, weekly and monthly activity, and the chat time chart to show the most and least busy conversation timelines. The app also enables the users to get a graphical inference of who chats the most in the group, in chronological order, from most active users to least active users.
The app also works on the chat words used and provides a word cloud with the most common words used, along with a bar chart for the most common words and their frequency in serial order. The best thing is that this chat analyzer aims to discard the stop words from this analysis and is also capable of Indian chats, wherein the messages are a mix of Hindi and English language. Lastly, the chat analyzer also gives the emoji analysis with a pie chart representation of the most common emoji used in the chat.


# Technology Framework Used

• Python  
• Streamlit Framework\
• Jupyter notebook\
• Matplotlib, pyplot\
• seaborn\


# Working

The app takes a text file of the WhatsApp chat as input. It must be made sure that the text file is in 24-hour format as the chat analyzer works for that specific timeline interface. The chat analyzer first pre-processes the chat data by segmenting the chats into a database with different columns for messages, names,date, and time (year, month, date, hour minute).
Next, the app processes the pre-processed data to extract the information required like counting total messages, etc, and finds the activity map and accordingly plots it using matplotlib libraries. The chat processes different segments divided into the helper.py file to make different analyses like the emoji analysis, most busy user analysis, word cloud, etc.


# Results and Discussion

App interface to upload file
![1](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/a1325220-a7b7-4057-b92e-344982254c0f)

Message statistics
![2](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/10c5c714-d722-4e6c-aba8-d1ffbee6126b)

Monthly timeline
![3](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/deac74f9-75ac-4a6b-93b5-d2df8381149d)

Daily timeline
![4](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/7c421217-ef00-4e70-85b9-37ab9c4618cf)

Activity Map
![5](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/374e5c3e-8fac-44c8-8ad3-0ab1e70bdeb5)

Weekly activity Map
![6](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/6100b623-7b5c-4a48-b1e0-9c035f7efa4b)

Most Busy Users
![7](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/f86a7f95-e338-4f15-abc0-7ba91ff974c3)

Word Cloud
![8](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/a64b1dc6-9c39-4d04-831f-aafe7f1a22a4)

Most Common Words
![9](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/30fd04a3-89e1-40e5-b2fe-4fb8a359a06e)

Emoji Analysis
![10](https://github.com/khyati-o4/Whatsapp-Chat-Analyzer/assets/77969213/c156a4cc-3ba6-499e-a09b-054df6345372)


