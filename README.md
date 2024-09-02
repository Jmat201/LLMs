# LLMs Projects 
TECH 16 stanford coursework and other LLM projects

1) 911_call_transcript -
  This project was to build an LLM powered chatbot assistant to respond to 911 calls based on learnings from the call record   transcript published on kaggle - 911 Recordings - https://www.kaggle.com/datasets/louisteitelbaum/911-recordings.

  Goals: 
  1. Transcribing audio to text using Open AI Whisper.
  2. Build a RAG system based on these transcripts 
  3. Build a simple chatbot to query the data 
  4. Need to consider how to implement voice-to-text to chat with this assistant. 

  Part 3 and 4 did not work out as expected. So, The current project is limited to goals 1 and 2. I used whisperX instead of   Whisper as it had better transcription. I used a sample of four audio files from the full-length calls in the kaggle  
  dataset. 

