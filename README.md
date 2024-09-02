# LLMs Projects 
TECH 16 stanford coursework and other LLM projects

**1) 911_call_transcript** :
  This project was to build an LLM powered chatbot assistant to respond to 911 calls based on learnings from the call record   transcript published on kaggle - 911 Recordings - https://www.kaggle.com/datasets/louisteitelbaum/911-recordings.

  Goals: 
  1. Transcribing audio to text using Open AI Whisper.
  2. Build a RAG system based on these transcripts 
  3. Build a simple chatbot to query the data 
  4. Need to consider how to implement voice-to-text to chat with this assistant. 

  Part 3 and 4 did not work out as expected. So, The current project is limited to goals 1 and 2. I used whisperX instead of   Whisper as it had better transcription. I used a sample of four audio files from the full-length calls in the kaggle  
  dataset. 

**2) Course_recommender** : 

The idea behind the course recommender project was to create a sequential crew of agents to analyse a user's resume and list 5 technical skills the user has. 
* At first, a 'career_counsellor' agent analyses the user's resume and looks for technical skills in the resume (task1). 
After this, I took input from the user for the job positions or roles they were seeking. 
* Based on the role the user is seeking, 'research_analayst_1' agent does 'task2', which looks for skills that job role requires (using websearchtool). 
* Based on the output of 'task2', 'research_analyst_2' agent does 'task3' which looks for courses linked to those skills(using websearchtool). 
* Based on the output of 'task3', 'research_analyst_3' compares and critiques if the recommended courses and skills match, before making its final 2 recommendation of course

The execution did not work as intended due to compute limitations. Message error: 'Agent stopped due to iteration limit or time limit.' I modified the crew to 2 research analysts and the agents did not execute. However, I will be continue working on this project to determine its feasibility. 

