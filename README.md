# AI-Powered Medical Chatbot Based on Image Input

A web application that enables users to consult an AI-powered medical assistant using facial images and natural language questions. The chatbot analyzes uploaded images, processes health-related queries, and provides intelligent, informative responses leveraging state-of-the-art vision and language models.

---

## Features

- **Image Upload & Analysis:** Users can upload face images for medical assessment or skin concerns.
- **Ask Medical Questions:** Users can submit questions describing symptoms or concerns related to their image.
- **AI Model Integration:** Both vision and language models are used to analyze input and generate responses.
- **Interactive Chat Interface:** Web-based chat interface for user-friendly interaction.
- **Multi-Model Support:** Integrates multiple large vision-language models for robust health guidance.

---

## Demo

<img width="880" height="466" alt="image" src="https://github.com/user-attachments/assets/d88278ae-3cab-4f3a-a376-dfcf7869429d" />

---

## Getting Started

### 1. Prerequisites

- Python 3.8+
- Node.js & npm (if using frontend build tools)
- Tesseract OCR (for image-to-text workflows, if required)
- Required Python packages (see below)


## How It Works

1. **Upload an Image:** User selects or takes a picture of their face or affected area.
2. **Describe Symptoms:** User types a question or concern describing the issue.
3. **Model Inference:** The AI combines image analysis and natural language understanding using cutting-edge models.
4. **Get AI Response:** Receive helpful medical advice or guidance in the chat interface.

---

## Technologies Used

- **FastAPI** – Python web backend
- **Uvicorn** – ASGI server for FastAPI
- **Python-dotenv** – Loads environment variables for API keys
- **Pillow & Pytesseract** – Image processing and OCR
- **Groq API** – Access to vision-language foundation models
- **HTML/CSS/JavaScript** – Interactive frontend

---
## License

MIT License

