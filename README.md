# Embedded-Subtitle-Generation

# 🎬 Multilingual Subtitle Generator | Google Colab

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Colab Compatible](https://img.shields.io/badge/Run%20in-Google%20Colab-orange?logo=googlecolab)](https://colab.research.google.com/)
[![OpenAI Whisper](https://img.shields.io/badge/OpenAI-Whisper-8A2BE2?logo=openai)](https://github.com/openai/whisper)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow?logo=huggingface)](https://huggingface.co/docs/transformers)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

A seamless video subtitle pipeline powered by **OpenAI Whisper**, **Transformers**, and **FFmpeg**, optimized for Google Colab. This notebook transcribes audio, translates subtitles into multiple languages, and embeds them into the video—all with an intuitive, widget-driven interface.

---

## 🌟 Key Highlights

- 📁 **Drag-and-drop** or use sample videos  
- 🧠 **Auto transcription** using Whisper (Base model)  
- 🌐 **Translate** to 20+ languages (via HuggingFace MarianMT + Deep Translator)  
- 🎛️ **Widget-based UI** for video & language selection  
- 🎯 **Adaptive pipeline**: optimized paths for short and long videos  
- 🎞️ **Hardcoded subtitles** via FFmpeg (`.mkv` output)  
- ☁️ **Auto-Download to System**  
- 🧹 **Smart cleanup** of temporary artifacts (optional)  

---

## 🚀 Tech Stack

| Tech               | Role                                  |
|--------------------|----------------------------------------|
| `OpenAI Whisper`   | Speech recognition & transcription     |
| `Transformers`     | Neural machine translation (MarianMT) |
| `Deep Translator`  | Lightweight language support           |
| `FFmpeg`           | Subtitle embedding & muxing           |
| `MoviePy`          | Audio extraction from video            |
| `IPyWidgets`       | Interactive UI in Colab                |
| `Google Colab`     | Cloud-based, zero-setup environment    |

---

## 📦 Output

- 🎥 Final `.mkv` video with embedded multilingual subtitles  
- 💬 Subtitle streams selectable in players (e.g., VLC, MX Player)  
- 🔗 Auto-Download the final output to the system.

---

> ✨ Built for creators, educators, engineers & content localizers—this notebook delivers high-quality, multilingual video subtitles effortlessly.

---
