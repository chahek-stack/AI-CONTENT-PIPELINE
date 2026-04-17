# AI-CONTENT-PIPELINE
This project is a AI-powered automation pipeline built using MAKE.COM.It collects data from RSS feeds and processes it using a large language model via the GROQ API to generate summaries.
The data is stored in google sheets with field like title,summary,URL,and send a summarized email using Gmail.
This project demonstates API integration , automation , and AI-based content processing in a real - world use case.
# workflow
  RSS -> Fetch latest articles
  HTTP -> Send data to AI  model
  AI-> Generate summary
  GOOGLE SHEETS -> Store structured data
  WEEKLY SCENERIO -> Aggregate last 7 days data and send email
# TECH STACK
 - MAKE.COM(automation)
 - GROQ API(Llama 3)
 - google sheets
 - gmail
 - RSS FEEDS
# FEATURES
   - Automated data collection
   - AI-based summarization
   - structureed storage
   - weekly email digest
# OUTPUT
- Data stored in googlesheets(TITLE,SUMMARY,URL,DATE,SOURCE)
- Weekly summarized email sent via Gmail  
