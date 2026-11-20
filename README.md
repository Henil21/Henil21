# Henilsinh Raj

AI engineer in Hyderabad. I build LLM and speech systems and take them all the way to deployment:
fine-tuning, quantization for edge hardware, and the APIs and apps around them.

- **Now:** AI Full Stack Developer at Mondee, building Indic-language medical voice-to-voice AI
  (speech recognition, MedGemma reasoning, speech synthesis with voice cloning).
- **Before:** Research intern with Bhashini at IIIT Hyderabad. Built offline text-to-speech for
  8 Indic languages and shipped it on Android with ONNX INT8.
- **Also:** Founder of AtomAI, an AI and software studio, and Axamine AI, a healthcare AI venture.

## Selected work

| Project | What it is |
|---|---|
| [indic-lekhan](https://huggingface.co/Henil1/indic-lekhan) | Streaming speech recognition for Hindi, Tamil, Telugu and Urdu: a 25.8M-parameter Zipformer transducer trained on about 1,240 hours, 28 MB as INT8 ONNX for low-end phones. |
| [Sravaani-1.0-GGUF](https://huggingface.co/Henil1/Sravaani-1.0-GGUF) | GGUF port of a 454M-parameter Indic ASR model for CPU inference with parakeet.cpp. Rebuilt the missing checkpoint from TorchScript, 705/705 tensors matched, 6 to 7x faster than real time on a laptop CPU. |
| [TTS-AVATAR-1](https://github.com/Henil21/TTS-AVATAR-1) | Real-time streaming talking-head avatar with Indic TTS. Splits rendering across two T4 GPUs to go from 0.51x to 1.0x real-time, streams frames over WebSocket with audio-clock A/V sync. |
| [Bhashini-TTS](https://github.com/Henil21/Bhashini-TTS) | Offline Indic text-to-speech (FastSpeech2-HS + HiFi-GAN) exported to ONNX INT8 for on-device Android. |
| [federated-learning-distilbert-Quantized](https://github.com/Henil21/federated-learning-distilbert-Quantized) | Federated (FedAvg) fine-tuning of DistilBERT for question answering, with INT16 weight transfer and ONNX INT8 export. |
| [LLM-Council](https://github.com/Henil21/LLM-Council) | Multi-model debate pipeline: supporting and opposing arguments, evidence check, final judgement. |

## Stack

Python, PyTorch, Hugging Face Transformers and PEFT (LoRA, QLoRA), llama.cpp (GGUF), ONNX Runtime,
Whisper, NeMo, FAISS, Flask, Node.js, React, Next.js, PostgreSQL, Android (Kotlin)

## Research and writing

- Best Paper Award, FICTA-2025, for a Transformer model for Hindi tokenization and generation
- Books: *Fundamentals of Natural Language Processing* and *Fundamentals of CNN with TensorFlow*

## Contact

[LinkedIn](https://www.linkedin.com/in/henilsinh-raj) | [Hugging Face](https://huggingface.co/Henil1) | [Email](mailto:henilsinhrajraj@gmail.com) | [Research site](https://henilsinh-raj-research.vercel.app)
