# Ganesha-AI-voice-chatbot
# 1️⃣ Get API Keys
# - OpenRouter API Key → https://openrouter.ai/keys (for text generation)
# - GAN.AI API Key     → https://gan.ai (for text-to-speech)

# 2️⃣ Run the app
streamlit run app.py

# 3️⃣ Open in browser
http://localhost:8501

# 4️⃣ Usage
# - Enter your OpenRouter API key in the sidebar
# - (Optional) Paste a GLB/GLTF 3D model URL or use local ganesha_model.glb
# - Type a message OR use 🎙 microphone input
# - Ganesha will reply with:
#   📝 Text response
#   🔊 Spoken audio (GAN.AI TTS)
#   🕉 Animated 3D model pulsing while speaking**

-----------------------------------------

Project Structure
├── app.py              # Main Streamlit app
├── ganesha_model.glb   # 3D model (optional, provide your own)
├── README.md           # Documentation

Notes

Audio autoplay may be blocked in some browsers. Click once on the canvas to enable sound.

GAN.AI TTS returns audio/wav. If switching to ElevenLabs or another TTS, adjust MIME type.

Keep your API keys private — they are only used locally in this app.

Access to the working demo - ganesha ai voice chatbot
https://drive.google.com/drive/folders/1L2aljlY89A_2BMYsNNAZZG3oLAvQRCFI?usp=sharing
