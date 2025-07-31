# Clippie

**The Open Agent for Ad Video Generation**

Clippie is an open-source AI agent that helps you generate engaging ad videos using smart scripting, asset reuse, AI-powered generation, and timeline assembly — all from a single modular workflow.

Whether you're a creative developer, an ads engineer, or an indie marketer, Clippie gives you a fully automatable pipeline to turn rough ideas and raw footage into scroll-stopping short-form ads.

---

## ✨ Key Features

- 🧠 **Script Generation** – Create structured ad scripts (hooks, value props, CTAs) from briefs or competitor ads  
- 🎬 **Asset Understanding** – Analyze videos/images and extract semantic tags, cuts, speech, and embeddings  
- 🧩 **Reuse vs. Generate** – Decide which beats use existing assets and which require AI-generated clips  
- 🛠️ **Clip Assembly** – Compose clips, overlays, captions, transitions, and layout into an EDL (edit decision list)  
- 🎵 **Audio Layering** – Add soundtrack, TTS voiceover, auto-ducking, and pacing adjustments  
- ✅ **Quality Check & Retry** – Automatically validate format, pacing, contrast, hook effectiveness — and retry if needed  
- 📦 **Final Output** – Export both the video and a full structured trace (JSON/EDL) for debugging or fine-tuning

---

## 📦 Example Usage

```bash
clippie run \
  --assets ./assets/ \
  --competitor-scripts ./samples/ \
  --platform tiktok \
  --output ./output/

## 📃 License

Clippie is licensed under the Apache 2.0 License.  
You are free to use, modify, and distribute it, including for commercial purposes.

See the [LICENSE](./LICENSE) file for details.

