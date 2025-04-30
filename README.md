# Whatsap Chat Analyzer
A Python-based tool to analyze WhatsApp chat exports and generate insights like message counts, word frequencies, most active users, and more.
WhatsApp Chat Analyzer is a data visualization and analysis tool that helps users understand patterns in their WhatsApp messages. After exporting a chat, the tool can reveal trends like:
       
       When and how frequently users message
       Who talks the most in a group
       What words and emojis are used most often
       How message activity changes over time


# 📊 Types of Analysis
1. Top Statistics

        Total messages, words, links, and media
        Sentiment analysis (optional with TextBlob/NLTK)
2. User Analysis (Group Chats)

       Most active users
       Contribution percentages
4. Time-Based Trends
   
        Monthly & daily message count
        Weekly activity map
        Activity heatmap (hour × day)
5. Text Analysis

        Most common words (excluding stopwords like "the", "and", etc.)
        Word cloud for quick insight
6. Emoji Analysis

        Most frequently used emojis
        Emoji counts


# 📦 Dependencies
Here are some of the main libraries used:
pandas – Data analysis and DataFrame operations
matplotlib & seaborn – Visualization
streamlit – Web interface
wordcloud – Word cloud generation
emoji – For identifying and counting emojis
re – Regular expressions for chat parsing


# 🔧 Features

       Message Statistics: Provides counts of total messages, words, media shared, and links.
       Participant Activity: Identifies the most active participants in the chat.
       Temporal Analysis: Displays daily and monthly message trends.
       Emoji Usage: Analyzes the frequency and types of emojis used.
       Word Cloud Generation: Creates a visual representation of the most frequently used words.



# 📂 Repository Structure
   
     app.py: Main application script for the Streamlit interface.
     helper.py: Contains functions to assist with data processing and visualization.
     preprocessor.py: Handles the preprocessing of chat data.
     hinglish1.txt: A list of stop words for filtering out common words in Hinglish.​


# 🧰 Tech Stack
    
    Python 3.7+
    Streamlit
    Pandas
    Matplotlib & Seaborn
    WordCloud
    Emoji


# 🛠️ Installation & Usage

     1.Clone the Repository:  https://github.com/Shauryy03/WhatsApp-Chat-Analyzer.
     2.Install Dependencies: pip install pandas matplotlib seaborn wordcloud emoji regex
     3.Run the Application: streamlit run app.py
     4.Analyze Your Chat:
          Export your WhatsApp chat as a .txt file (without media).
          Upload the file through the application interface.
          Choose between group or individual chat analysis.
          Click on "Show Analysis" to view the results.​


# 📄 How to Use
  
     Export your WhatsApp chat from your phone without media.
     Upload the .txt file into the web interface.
     Choose group or individual chat.
     Click "Show Analysis" to explore detailed stats.


