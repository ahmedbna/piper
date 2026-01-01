# Piper TTS Models (Mobile / Expo Friendly)

This repository hosts **pre-zipped Piper (VITS) Text-to-Speech models** optimized for **mobile apps**, especially **Expo / React Native** projects using **sherpa-onnx offline TTS**.

The models are provided as **`.zip` archives** to ensure compatibility with:

- iOS
- Android
- Expo FileSystem
- react-native-zip-archive

---

## 🚀 Why This Repository Exists

Official Piper releases are distributed as `.tar.bz2` archives, which **cannot be reliably extracted in React Native / Expo environments**.

This repo solves that problem by providing:

- ✅ Pre-extracted
- ✅ Correctly structured
- ✅ Re-packed `.zip` models
- ✅ Ready for on-device offline TTS

---

## 📦 Model Structure

Each ZIP contains **one model folder** with the exact structure required by Piper / sherpa-onnx:

> ⚠️ The folder name inside the ZIP must match the model name exactly.

---

## 🗣️ Available Voices

| Language     | Voice    | Quality |
| ------------ | -------- | ------- |
| English (US) | Amy      | Low     |
| English (UK) | Alan     | Low     |
| French       | Siwis    | Low     |
| German       | Thorsten | Low     |
| Spanish (ES) | Carlfm   | X-Low   |
| Spanish (MX) | Aldo     | X-Low   |
| Italian      | Riccardo | X-Low   |

> Low / X-Low models are recommended for **mobile performance and size**.

---

## 📥 Downloading Models

Models are hosted via **GitHub Releases**.

Example direct download URL:
`https://github.com/<your-username>/piper-tts-models/releases/download/v1/en_US-amy-low.zip`

These URLs are:

- ✅ Public
- ✅ CDN-backed
- ✅ No authentication required
- ✅ Safe for App Store apps

---

## 📱 Mobile Recommendations

- Download models on demand
- Cache models locally after first download
- Allow users to delete unused voices
- Prefer Low / X-Low models for memory efficiency

## 📜 License

Piper models are released under their respective open-source licenses
This repository only redistributes unmodified model data
No proprietary or executable code is included

Original project:
[https://github.com/OHF-Voice/piper1-gpl](https://github.com/OHF-Voice/piper1-gpl)

TTS-Models
[https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models](https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models)

Piper Voices
[https://rhasspy.github.io/piper-samples/](https://rhasspy.github.io/piper-samples/)

react-native-sherpa-onnx-offline-tts
[https://github.com/kislay99/react-native-sherpa-onnx-offline-tts](https://github.com/kislay99/react-native-sherpa-onnx-offline-tts)

## ⚠️ Important Notes

This repo contains data files only
No tracking, analytics, or executable code
Safe for offline use
Suitable for educational and commercial apps

## 🤝 Contributions

If you add:

- New languages
- Better quality mobile-optimized models
- Smaller compressed variants

Please ensure:

- Correct folder structure
- ZIP format only
- Clear naming conventions

Pull requests are welcome ❤️
