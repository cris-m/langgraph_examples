# Examples Repository  

This repository contains a collection of examples demonstrating the usage of [LangGraph](https://github.com/langchain-ai/langgraph) in various applications. LangGraph is a powerful framework for building dynamic, decision-making workflows with natural language processing capabilities.

### Overview  
LangGraph provides a way to model complex conversational flows, manage state, and integrate external tools and APIs seamlessly. The examples in this repository aim to showcase the versatility of LangGraph for different real-world use cases, from personal assistants to privacy-focused agents.  

Each folder represents a different project or example that demonstrates how LangGraph can be combined with various technologies like OpenAI models, audio-based input/output, and external web services.

### Featured Examples  

1. **Voice Assistance**  
   This project demonstrates a voice-based assistant that uses:  
   - **Llama 3.2 (3B)** for natural language understanding (via [Ollama](https://ollama.com/library/llama3.2))  
   - **[Whisper](https://github.com/openai/whisper)** for local audio transcription  
   - **[Kokoro](https://huggingface.co/hexgrad/Kokoro-82M)** for local text-to-speech (TTS)  
   - **DuckDuckGo** for privacy-focused web searches.  

   **Note**: This project runs 100% locally, using open-source models to ensure privacy and control over data.  
   [Link to Voice Assistance Project](https://github.com/cris-m/langraph_examples/blob/main/voice_assistance/voice_assistance.ipynb)

### Future Updates 
This repository will be gradually updated with more examples showcasing the diverse applications of LangGraph. Stay tuned for new projects and enhancements!

---