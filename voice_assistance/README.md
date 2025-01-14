# Assistance Agent with Llama 3.2 3B, Whisper, and Kokoro  

This repository contains an audio-based assistance agent leveraging advanced natural language processing, speech-to-text, and text-to-speech technologies. The agent is designed for efficient, voice-first interaction while prioritizing privacy and performance. All models run locally to ensure data privacy and control.

### Features  

1. **[Llama 3.2 (3B Model)](https://ollama.com/library/llama3.2)**  
   - Utilized via Ollama to power natural language understanding.  
   - A 3-billion-parameter model delivering robust and context-aware conversational abilities.  
   - Runs locally for secure, private, and efficient operation.  

2. **[LangGraph](https://github.com/langchain-ai/langgraph)**  
   - Provides a framework for defining complex workflows and decision-making processes.  
   - Works seamlessly with Llama to structure and manage conversations dynamically.  

3. **[Whisper (ASR)](https://github.com/openai/whisper)**  
   - Runs locally to convert user audio input into text.  
   - Ensures privacy and delivers high transcription accuracy.  

4. **[Kokoro (TTS)](https://huggingface.co/hexgrad/Kokoro-82M)**  
   - Runs locally to synthesize natural-sounding voice responses.  
   - Delivers human-like and engaging audio output.  

5. **DuckDuckGo Search Engine Integration**  
   - Provides quick, privacy-focused web search results for user queries.  

### Workflow  
1. **Input**: Users provide audio input to the agent.  
2. **Processing**:  
   - Whisper transcribes the audio to text.  
   - Llama 3.2 (3B), accessed via Ollama, interprets and processes the text.  
   - LangGraph manages workflows and structures the conversation.  
3. **Output**:  
   - Responses are synthesized into audio using Kokoro or delivered as text-based answers.  
   - Web search queries, when required, are resolved via DuckDuckGo.

### Use Cases  
- Personal assistant for daily tasks.  
- Privacy-conscious, audio-based information retrieval.  
- Accessibility solutions for hands-free operation.

---  