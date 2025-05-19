# AI Voice Agent using Livekit

## Description

This project demonstrates the creation of an AI voice agent using the power of Livekit, OpenAI, Elevenlabs, and WebRTC. Initially, we built a basic pipeline incorporating:

- Speech-to-Text (STT)
- Language Model (LLM)
- Text-to-Speech (TTS)

We then optimized the experience by leveraging WebRTC through Livekit to enable low-latency, real-time communication. The result is a conversational AI voice agent capable of understanding and responding to voice inputs in real-time.

## Features

- Real-time voice conversations with AI
- Integration with Livekit for WebRTC-based audio streaming
- Modular STT → LLM → TTS pipeline
- Exploration of low-latency voice AI applications

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ai-voice-agent-livekit.git
   cd ai-voice-agent-livekit
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter notebooks to explore or run the pipeline:

   - [Basic AI Voice Agent Notebook](voice_agent.ipynb)  
   - [Livekit WebRTC-Optimized Voice Agent Notebook](optimized_voice_agent.ipynb)  


## Technologies Used

- Python
- Jupyter Notebook
- APIs: 
  - [OpenAI](https://openai.com/)
  - [Elevenlabs](https://www.elevenlabs.io/)
  - [Livekit](https://livekit.io/)
  - [WebRTC](https://webrtc.org/)

## Credits

Special thanks to the open-source and commercial platforms powering this project:

- [OpenAI](https://openai.com/) for LLM integration
- [Elevenlabs](https://www.elevenlabs.io/) for high-quality TTS
- [Livekit](https://livekit.io/) for real-time audio streaming with WebRTC
- [WebRTC](https://webrtc.org/) project for enabling peer-to-peer communication

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
