# Audio-Text Multimodal ML Course

A private, self-paced study guide for learning machine learning from the
fundamentals through audio/text multimodality, ASR, TTS, speech-to-speech
systems, efficient transformers, and efficient inference hosting.

Open `index.html` in a browser to read the website locally.

## Course Shape

- Foundation: math, Python, tensors, optimization, evaluation.
- Audio basics: waveform, STFT, mel features, tokenization, datasets.
- Text and sequence modeling: language modeling, attention, transformers.
- ASR: HMM/GMM history, CTC, encoder-decoder, RNN-T, Conformer, wav2vec 2.0,
  Whisper-style weak supervision.
- TTS: concatenative and parametric systems, Tacotron/WaveNet era,
  non-autoregressive TTS, VITS, neural codecs.
- Speech-to-speech: cascaded systems, shared state, streaming, barge-in,
  full-duplex constraints, direct speech models.
- System design: service decomposition, launch gates, latency budgets,
  privacy-safe telemetry, rollback, cost controls, and production incidents.
- Evaluation and RAG: WER/CER/entity metrics, retrieval recall, grounded answer
  evaluation, LLM judges, human review, monitoring, and rollout gates.
- Efficiency: quantization, distillation, adapters, LoRA, FlashAttention,
  KV-cache management, batching, llama.cpp/MLX/vLLM-style serving.

## Suggested Use

Use this as a living repository:

1. Read one module.
2. Implement the lab.
3. Write a short note in `notes/`.
4. Add benchmark results under `experiments/` without committing private audio.
5. Update the course when a concept becomes clear.

## Privacy

Do not commit private recordings, transcripts, voiceprints, or API tokens.
Use `data/private/` and `outputs/private/` for local-only material.
