# 🌟 **GeminiStream: Real-Time Multimodal API Integrator**

---

## 🚀 **Project Overview**
**GeminiStream** is an advanced multi-functional tool leveraging the power of the **Multimodal Live API** and **Websockets**. Designed for seamless real-time streaming and interaction with generative models, it supports various data modalities such as text and audio. This project showcases the efficient use of **Google AI's Gemini 2.0 capabilities**, emphasizing dynamic responses and robust multimodal content generation.

---

## 💡 **Key Features**
- ⚡ **Real-Time Multimodal Streaming:** Generate and process text and audio in real time.
- 🌐 **Websocket Integration:** Provides efficient, bidirectional communication using Python websockets.
- 🔒 **Secure API Management:** Incorporates Google API key handling for secure and reliable connections.
- 🎧 **Audio Processing:** Converts generated audio from base64 encoding and saves it as WAV files.
- 🛠️ **Highly Customizable Tools:** Flexible structure allows for easy addition and modification of generative tools.

---

## 🛠️ **Installation Guide**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/KishoreMuruganantham/GeminiStream-Real-Time-Multimodal-API-Integrator.git
cd geministream
```

### 2️⃣ **Install Required Dependencies**
```bash
pip install -r requirements.txt
```

**Dependencies:**
- `websockets`
- `altair`
- `google-api-core`

### 3️⃣ **Configure API Keys Securely**
```python
from google.colab import userdata
MAPS_API_KEY = userdata.get('MAPS_API_KEY')
GOOGLE_API_KEY = userdata.get('GOOGLE_API_KEY')
```

---

## 🔄 **Usage Instructions**

### ⚡ **Run the Application**
```bash
python main.py
```

### 💬 **Send Prompts for Generation**
```python
await send(ws, "Generate a summary of AI advancements in 2025.")
```

### 🎧 **Audio Output Handling**
Generated audio files are automatically saved as WAV files in the `audio_output/` directory.

---

## 💻 **Project Structure**
```
GeminiStream/
├── main.py               # Main application logic
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── audio_output/         # Directory for generated audio files
```

---

## ✨ **Core Components**
- **setup()**: Initializes the WebSocket session for multimodal generation.
- **send()**: Facilitates prompt submissions and user interaction handling.
- **handle_server_content()**: Processes server responses, including text and audio outputs.
- **wave_file()**: Manages audio file creation and proper formatting.

---

## 🌟 **Contributing Guidelines**
We welcome contributions! Follow these steps to contribute:
1. **Fork** the repository.
2. **Create a new branch** (`git checkout -b feature-branch`).
3. **Commit** your changes (`git commit -m 'Add new feature'`).
4. **Push** to the branch (`git push origin feature-branch`).
5. **Submit a Pull Request** for review.

---

## 📜 **License**
This project is licensed under the [MIT License](LICENSE).

---

## 🤝 **Acknowledgements**
- [Google AI](https://ai.google/) for the Multimodal Live API.
- [Altair](https://altair-viz.github.io/) for visualization support.
- [Websockets](https://websockets.readthedocs.io/) for seamless real-time communication.

---

## 📬 **Contact Information**
- **Author:** Kishore Muruganantham  
- 📧 **Email:** kishore.muruganantham@gmail.com

---

⭐ *If you enjoyed this project, give it a star ⭐ and share it with your peers!* 🌟

