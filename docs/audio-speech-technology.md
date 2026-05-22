# Audio & Speech Technology Frameworks

*Frameworks for automatic speech recognition (ASR), speech-to-text (STT), text-to-speech (TTS), voice analytics, and spatial audio processing.*

## Contents

- [Automatic Speech Recognition (ASR)](#automatic-speech-recognition-asr)
- [Text-to-Speech (TTS) Synthesis](#text-to-speech-tts-synthesis)
- [Digital Signal Processing (DSP) & Audio Effects](#digital-signal-processing-dsp-audio-effects)
- [Voice Activity Detection (VAD) & Noise Reduction](#voice-activity-detection-vad-noise-reduction)
- [Speaker Diarization & Identification](#speaker-diarization-identification)
- [Audio Classification & Sound Event Detection](#audio-classification-sound-event-detection)
- [Audio Compression & Streaming](#audio-compression-streaming)
- [Speech Translation & Cross-lingual Processing](#speech-translation-cross-lingual-processing)
- [Music Information Retrieval (MIR)](#music-information-retrieval-mir)
- [Spatial Audio & 3D Rendering](#spatial-audio-3d-rendering)

---

## Automatic Speech Recognition (ASR)

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Kaldi | Toolkit for speech recognition research, written in C++ | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/kaldi-asr/kaldi) • [Website](https://kaldi-asr.org) |
| Whisper | General-purpose speech recognition model and inference framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/openai/whisper) • [Website](https://github.com/openai/whisper) |
| DeepSpeech | TensorFlow-based Speech-to-Text engine developed by Mozilla | <kbd>🏷️ Python/C++</kbd> | [GitHub](https://github.com/mozilla/DeepSpeech) • [Website](https://github.com/mozilla/DeepSpeech) |
| Vosk | Offline speech recognition toolkit for mobile and desktop apps | <kbd>🏷️ Python/C++</kbd> | [GitHub](https://github.com/alphacep/vosk-api) • [Website](https://alphacephei.com/vosk) |
| SpeechBrain | All-in-one conversational AI toolkit based on PyTorch | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/speechbrain/speechbrain) • [Website](https://speechbrain.github.io) |
| ESPnet | End-to-end speech processing toolkit focusing on ASR and TTS | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/espnet/espnet) • [Website](https://espnet.github.io) |
| CMU Sphinx | Long-standing open-source speech recognition engines | <kbd>🏷️ C/Java</kbd> | [GitHub](https://github.com/cmusphinx/sphinxbase) • [Website](https://cmusphinx.github.io) |
| Wav2Letter | Fast, open-source end-to-end speech recognition toolkit by Meta | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/facebookresearch/wav2letter) • [Website](https://github.com/facebookresearch/wav2letter) |
| GoWhisper | Go bindings for openai-whisper with C++ backend | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/ggerganov/whisper.cpp) • [Website](https://whispercpp.org) |
| ASR-Kit | C# speech-to-text pipeline framework for enterprise apps | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/asrkit/asr-kit) • [Website](https://asrkit.org) |
| RustAudioSpeech | Rust real-time offline speech recognizer framework | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustaudio/speech) • [Website](https://rustaudiospeech.dev) |
| WhisperMobile | Optimized Whisper inference engine for iOS and Android | <kbd>🏷️ Swift/Java</kbd> | [GitHub](https://github.com/ggerganov/whisper.cpp) • [Website](https://whispercpp.org) |
| NodeASR | Node.js framework for multi-engine speech recognition routing | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/nodeasr/nodeasr) • [Website](https://nodeasr.github.io) |
| SoniaASR | Java platform for cloud-agnostic enterprise speech services | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/sonia/sonia-asr) • [Website](https://soniaasr.org) |
| WhisperX | Whisper-based ASR with fast phoneme-level alignment | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/m-bain/whisperX) • [Website](https://github.com/m-bain/whisperX) |

## Text-to-Speech (TTS) Synthesis

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Coqui TTS | Advanced deep learning toolkit for Text-to-Speech synthesis | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/coqui-ai/TTS) • [Website](https://github.com/coqui-ai/TTS) |
| Bark | Transformer-based audio generation model with natural TTS | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/suno-ai/bark) • [Website](https://suno.ai) |
| MaryTTS | Open-source multilingual Text-to-Speech synthesis platform | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/marytts/marytts) • [Website](https://marytts.github.io) |
| eSpeak NG | Compact open-source software speech synthesizer | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/espeak-ng/espeak-ng) • [Website](https://github.com/espeak-ng/espeak-ng) |
| Festvox | Tools for building synthetic voices in the Festival framework | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/festvox/festival) • [Website](https://festvox.org) |
| VITS | Conditional variational autoencoder for end-to-end TTS | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/jaywalnut310/vits) • [Website](https://github.com/jaywalnut310/vits) |
| Glow-TTS | Generative flow-based model for high-speed TTS | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/jaywalnut310/glow-tts) • [Website](https://github.com/jaywalnut310/glow-tts) |
| FastSpeech2 | Fast and high-quality non-autoregressive TTS framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/ming024/FastSpeech2) • [Website](https://github.com/ming024/FastSpeech2) |
| GoTTS | Go client for MaryTTS and offline TTS speech generation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gotts/gotts) • [Website](https://gotts.dev) |
| Piper | Fast, local neural text-to-speech engine for Raspberry Pi | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/rhasspy/piper) • [Website](https://rhasspy.org) |
| Mimic3 | Mycroft open-source offline neural text-to-speech engine | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/MycroftAI/mimic3) • [Website](https://mycroft.ai) |
| RustTTS | Pure Rust speech synthesis and text preprocessing engine | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rusttts/rusttts) • [Website](https://rusttts.dev) |
| TtsKit C# | C# offline speech synthesizer wrapper for desktop apps | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/ttskit/tts-kit) • [Website](https://ttskit.org) |
| NodeTTS | Node.js framework for multi-vendor speech synthesis wrappers | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodetts/nodetts) • [Website](https://nodetts.github.io) |
| OpenVoice | Versatile instant voice cloning framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/myshell-ai/OpenVoice) • [Website](https://github.com/myshell-ai/OpenVoice) |

## Digital Signal Processing (DSP) & Audio Effects

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| JUCE | Open-source C++ framework for building audio applications and GUI apps | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/juce-framework/JUCE) • [Website](https://juce.com) |
| Faust | Functional programming language for real-time signal processing | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/grame-cncm/faust) • [Website](https://faust.grame.fr) |
| SPTK | Speech Signal Processing Toolkit including vocoder analysis | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/sp-tk/SPTK) • [Website](https://sptk.sourceforge.net) |
| Librosa | Python library for audio and music analysis and processing | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/librosa/librosa) • [Website](https://librosa.org) |
| Aubio | C library for real-time audio labeling and feature extraction | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/aubio/aubio) • [Website](https://aubio.org) |
| Aquila | Modern C++ digital signal processing library | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/aquila-dsp/aquila) • [Website](https://aquila-dsp.org) |
| RustAudio DSP | Safe and rapid audio DSP building block libraries for Rust | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustaudio/rust-dsp) • [Website](https://rustaudio.dev) |
| GoAudio | Pure Go library for digital audio signal parsing and processing | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goaudio/goaudio) • [Website](https://goaudio.dev) |
| Maximilian | C++ audio synthesis and signal processing library | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/micknoise/Maximilian) • [Website](https://maximilian.mybcontent.co.uk) |
| AudioKit | Swift framework for audio synthesis, processing, and analysis | <kbd>🏷️ Swift</kbd> | [GitHub](https://github.com/AudioKit/AudioKit) • [Website](https://audiokit.io) |
| SuperCollider | Platform for audio synthesis and algorithmic composition | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/supercollider/supercollider) • [Website](https://supercollider.github.io) |
| Csound | System for sound and music synthesis and signal processing | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/csound/csound) • [Website](https://csound.com) |
| PD (Pure Data) | Visual programming language for multimedia and audio DSP | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/pure-data/pure-data) • [Website](https://puredata.info) |
| PyDSP | Python digital signal processing scripts and filters | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pydsp/pydsp) • [Website](https://pythonsignal.org) |
| DSP.NET | C# digital signal processing and sound filter library | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/dspnet/dspnet) • [Website](https://dspnet.io) |

## Voice Activity Detection (VAD) & Noise Reduction

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Silero VAD | Pre-trained enterprise-grade voice activity detector | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/snakers4/silero-vad) • [Website](https://github.com/snakers4/silero-vad) |
| WebRTC VAD | VAD component extracted from the Google WebRTC project | <kbd>🏷️ C/Python</kbd> | [GitHub](https://github.com/wiseman/py-webrtcvad) • [Website](https://github.com/wiseman/py-webrtcvad) |
| RNNoise | Recurrent neural network for real-time noise suppression | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/xiph/rnnoise) • [Website](https://xiph.org/rnnoise) |
| SpeexDSP | Open-source audio processing library including echo cancel | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/xiph/speexdsp) • [Website](https://speex.org) |
| GoVAD | Go wrapper around WebRTC voice activity detection core | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/govad/govad) • [Website](https://govad.dev) |
| RustVAD | Safe Rust interface for real-time voice activity detection | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustvad/rustvad) • [Website](https://rustvad.dev) |
| DeepFilterNet | Full-band audio noise suppression using deep filtering | <kbd>🏷️ Rust/Python</kbd> | [GitHub](https://github.com/Rikorose/DeepFilterNet) • [Website](https://github.com/Rikorose/DeepFilterNet) |
| NoiseReduce | Python noise reduction library based on spectral gating | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/timsainb/noisereduce) • [Website](https://github.com/timsainb/noisereduce) |
| VAD.js | Browser-based real-time voice activity detection library | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/ricky0123/vad-web) • [Website](https://vad.ricky0123.com) |
| JavaVAD | Java wrapper for real-time speech detection in telecom systems | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javavad/javavad) • [Website](https://javavad.org) |
| AcousticEcho | C++ framework for acoustic echo cancellation (AEC) | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/echo/acousticecho) • [Website](https://acousticecho.net) |
| VoiceFilter | Python toolkit for targeted voice separation in noisy rooms | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/voice/voicefilter) • [Website](https://voicefilter.io) |
| VadKit C# | C# framework for local voice activity monitoring | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/vadkit/vad-kit) • [Website](https://vadkit.org) |
| Denoiser | Real-time speech denoiser model and engine from Meta | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/facebookresearch/denoiser) • [Website](https://github.com/facebookresearch/denoiser) |
| ClearVoice | C++ library for dual-microphone noise reduction pipelines | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/clear/clearvoice) • [Website](https://clearvoice.io) |

## Speaker Diarization & Identification

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| PyAnnote Diarization | Speaker diarization toolkit based on PyTorch | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyannote/pyannote-audio) • [Website](https://pyannote.github.io) |
| SimpleSpeakerID | Python library for speaker identification and voiceprints | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/speaker/simplespeakerid) • [Website](https://simplespeakerid.org) |
| RustSpeakerID | Rust framework for low-latency speaker recognition | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustspeaker/rustspeakerid) • [Website](https://rustspeakerid.dev) |
| GoDiarize | Go client and routing engine for speaker segmentation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/godiarize/godiarize) • [Website](https://godiarize.dev) |
| SoraVoice | C++ real-time speaker identification and diarization engine | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/sora/soravoice) • [Website](https://soravoice.net) |
| JavaSpeaker | Java interface for matching speaker voiceprints in secure systems | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javaspeaker/javaspeaker) • [Website](https://javaspeaker.org) |
| SpeakerNet | Deep neural network speaker embedding framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/speakernet/speakernet) • [Website](https://speakernet.io) |
| VoiceBiometrics C# | C# SDK for secure voice biometric authentication | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/voicebio/voicebiometrics) • [Website](https://voicebiometrics.net) |
| KaldiDiarization | Kaldi-based pipeline for segmenting multi-speaker audio | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/kaldi/diarization) • [Website](https://kaldi-asr.org) |
| NodeSpeaker | Node.js framework for checking speaker identity matching | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodespeaker/nodespeaker) • [Website](https://nodespeaker.github.io) |
| DiarizationJS | Client-side speaker segment visualization library | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/diarjs/diarizationjs) • [Website](https://diarizationjs.org) |
| VectorVoice | Rust embedded speaker embedding extraction library | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/vectorvoice/vectorvoice) • [Website](https://vectorvoice.dev) |
| ALIZÉ | Open-source toolkit for speaker recognition and authentication | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/alize-toolkit/alize) • [Website](https://alize-toolkit.org) |
| PySpk | Python tools for speaker change detection (SCD) in broadcast | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyspk/pyspk) • [Website](https://pyspk.net) |
| DeepSpeaker | TensorFlow implementation of deep speaker recognition | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/philipperemy/deep-speaker) • [Website](https://github.com/philipperemy/deep-speaker) |

## Audio Classification & Sound Event Detection

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| YAMNet | Deep network that predicts 521 audio event classes | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/tensorflow/models/tree/master/research/audioset/yamnet) • [Website](https://tensorflow.org) |
| Audioset-Kit | Python data pipeline and model trainer for AudioSet | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/audioset/audioset-kit) • [Website](https://audiosetkit.org) |
| AudioClassifierJS | Browser-based TensorFlow.js audio event classifier | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/audioclass/audioclassifierjs) • [Website](https://audioclassifierjs.dev) |
| RustAudioClass | High-performance Rust sound classifier for edge nodes | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustclass/rustaudioclass) • [Website](https://rustaudioclass.dev) |
| GoSoundDetect | Go framework for real-time sound threshold and event classification | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gosound/gosounddetect) • [Website](https://gosounddetect.org) |
| SoundMatch C# | C# library for acoustic fingerprinting and matching | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/soundmatch/soundmatch) • [Website](https://soundmatch.net) |
| JavaSoundClass | Java framework for industrial sound classification grids | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javasound/javasoundclass) • [Website](https://javasoundclass.org) |
| AcousticClassify | C++ real-time sound event detection (SED) engine | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/acoustic/acousticclassify) • [Website](https://acousticclassify.io) |
| Panako | Acoustic fingerprinting system capable of finding matches | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/toverlux/panako) • [Website](https://panako.ac) |
| Dejavu | Python audio fingerprinting and recognition framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/worldveil/dejavu) • [Website](https://github.com/worldveil/dejavu) |
| Chromaprint | Acoustic fingerprinting library used by AcoustID | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/acoustid/chromaprint) • [Website](https://acoustid.org/chromaprint) |
| Audacity Classifier | Audacity-compatible sound analyzer and labeling plugin | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/audacity/audacity-classifier) • [Website](https://audacityteam.org) |
| SoundEventFlow | Go network framework for distributing sensor audio alerts | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/soundevent/soundeventflow) • [Website](https://soundeventflow.dev) |
| EcoClass | Python bioacoustics classifier for tracking birds and wildlife | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/ecoclass/ecoclass) • [Website](https://ecoclass.io) |
| NoiseVerify | Rust framework for environmental noise compliance classification | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/noise/noiseverify) • [Website](https://noiseverify.dev) |

## Audio Compression & Streaming

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| FFmpeg SDK | Programmatic framework wrapper for FFmpeg codecs and streaming | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/ffmpeg/ffmpeg) • [Website](https://ffmpeg.org) |
| Opus SDK | Standard library interface for Opus interactive audio codec | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/xiph/opus) • [Website](https://opus-codec.org) |
| LibFlac | Free Lossless Audio Codec standard software library | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/xiph/flac) • [Website](https://xiph.org/flac) |
| Shaka Streamer | Google framework for preparing media for streaming | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/shaka-project/shaka-streamer) • [Website](https://github.com/shaka-project/shaka-streamer) |
| HlsAudio | Go framework for dynamically segmenting AAC and Opus streams | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/hlsaudio/hlsaudio) • [Website](https://hlsaudio.dev) |
| RustAudioStream | Rust pipeline for ultra-low latency audio networking | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/ruststream/rustaudiostream) • [Website](https://rustaudiostream.dev) |
| Icecast Server | Streaming audio server supporting MP3 and Ogg streams | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/xiph/icecast-server) • [Website](https://icecast.org) |
| NodeAudioStream | Node.js pipeline framework for browser audio streaming | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodeastream/nodeaudiostream) • [Website](https://nodeaudiostream.github.io) |
| AudioStream C# | C# network library for remote audio playback synchronization | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/audiostream/audiostream) • [Website](https://audiostream.net) |
| PyStreamAudio | Python audio streaming simulator and analytics collector | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pystream/pystreamaudio) • [Website](https://pystreamaudio.org) |
| AACEncoder C++ | High-efficiency AAC audio encoder core library | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/aac/aacencoder) • [Website](https://aacencoder.net) |
| VlcPlayer SDK | LibVLC binding and media stream playing framework | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/videolan/vlc) • [Website](https://videolan.org/vlc) |
| Liquidsoap | Swiss-army knife for multimedia streaming and radio generation | <kbd>🏷️ OCaml</kbd> | [GitHub](https://github.com/savonet/liquidsoap) • [Website](https://liquidsoap.info) |
| WebAudioStream | JavaScript library for browser-to-browser WebRTC audio streaming | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/webstream/webaudiostream) • [Website](https://webaudiostream.io) |
| SoundRelay | Rust gateway for distributing real-time microphone grids over LAN | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/sound/soundrelay) • [Website](https://soundrelay.dev) |

## Speech Translation & Cross-lingual Processing

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OpenNMT-py | Open-source neural machine translation framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/OpenNMT/OpenNMT-py) • [Website](https://opennmt.net) |
| SeamlessM4T | Meta's mass multilingual translation framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/facebookresearch/seamless_communication) • [Website](https://github.com/facebookresearch/seamless_communication) |
| GoTranslateSpeech | Go system for multi-engine speech translation orchestration | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gotrans/gotranslatespeech) • [Website](https://gotranslatespeech.dev) |
| RustSpeechTrans | Rust safe interface for offline speech translation models | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rusttrans/rustspeechtrans) • [Website](https://rustspeechtrans.dev) |
| JavaTranslate | Java framework for real-time speech translation in call centers | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javatrans/javatranslate) • [Website](https://javatranslate.org) |
| SpeechTrans C# | C# offline speech translation and routing client SDK | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/speechtrans/speechtrans) • [Website](https://speechtrans.net) |
| NodeSpeechTrans | Node.js framework for multi-lingual translation sockets | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodetrans/nodespeechtrans) • [Website](https://nodespeechtrans.github.io) |
| AcousticTranslate | C++ high-performance speech-to-speech translation pipeline | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/acoustic/acoustictranslate) • [Website](https://acoustictranslate.net) |
| PyTranslateSpeech | Python wrapper for speech-to-text-to-translation pipelines | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pytrans/pytranslatespeech) • [Website](https://pytranslatespeech.org) |
| BrowserTrans | WASM-powered in-browser real-time speech translator | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/browsertrans/browsertrans) • [Website](https://browsertrans.io) |
| Fairseq | Sequence-to-sequence modeling toolkit by Meta AI Research | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/facebookresearch/fairseq) • [Website](https://github.com/facebookresearch/fairseq) |
| MarianMT | Fast, engine-optimized Neural Machine Translation in C++ | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/marian-nmt/marian) • [Website](https://marian-nmt.github.io) |
| TransFlow | Go network framework for routing audio to translation engines | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/transflow/transflow) • [Website](https://transflow.dev) |
| VoiceBridge | Kotlin mobile app framework for real-time translation during calls | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/voice/voicebridge) • [Website](https://voicebridge.io) |
| PolyglotVoice | Rust modular engine for cross-lingual voice cloning and styling | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/polyglot/polyglotvoice) • [Website](https://polyglotvoice.dev) |

## Music Information Retrieval (MIR)

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Essentia | C++ library for audio analysis and music information retrieval | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/MTG/essentia) • [Website](https://essentia.upf.edu) |
| Madmom | Python music information retrieval library focusing on beat tracking | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/CPJKU/madmom) • [Website](https://github.com/CPJKU/madmom) |
| MirEval | Python library for evaluating music information retrieval systems | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/craffel/mir_eval) • [Website](https://github.com/craffel/mir_eval) |
| Marsyas | Music Analysis, Retrieval and Synthesis for Audio Signals | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/marsyas/marsyas) • [Website](https://marsyas.info) |
| GoMIR | Go audio parser and spectral centroid calculation library | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gomir/gomir) • [Website](https://gomir.dev) |
| RustMIR | Safe Rust library for extracting musical characteristics | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustmir/rustmir) • [Website](https://rustmir.dev) |
| MirKit C# | C# framework for desktop music cataloging and BPM detection | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/mirkit/mir-kit) • [Website](https://mirkit.org) |
| NodeMIR | Node.js framework for serverless music feature extraction | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/nodemir/nodemir) • [Website](https://nodemir.github.io) |
| JavaMIR | Java music information retrieval collection of algorithms | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javamir/javamir) • [Website](https://javamir.org) |
| BeatTrackJS | Browser-based Web Audio API real-time beat tracker | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/beattrack/beattrackjs) • [Website](https://beattrackjs.dev) |
| LibrosaMIR | Librosa-based pipeline for offline chord progression estimation | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/librosamir/librosamir) • [Website](https://librosamir.org) |
| KeyFinder SDK | C++ key detection engine library for digital music DJ files | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/keyfinder/keyfinder-sdk) • [Website](https://ibrahimshaath.co.uk/keyfinder) |
| MusicFlow | Go pipeline for real-time audio spectrogram classification | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/musicflow/musicflow) • [Website](https://musicflow.dev) |
| ChromaMIR | Rust framework for real-time music chromagram calculation | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/chroma/chromamir) • [Website](https://chromamir.dev) |
| JSymbolic | Java library for extracting musical features from MIDI files | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/jsymbolic/jsymbolic) • [Website](https://jsymbolic.sourceforge.net) |

## Spatial Audio & 3D Rendering

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Resonance Audio | Google's open-source spatial audio SDK for browsers and engines | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/resonance-audio/resonance-audio) • [Website](https://resonance-audio.github.io/resonance-audio/) |
| Steam Audio SDK | Physics-based spatial audio simulation framework | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/ValveSoftware/steam-audio) • [Website](https://valvesoftware.github.io/steam-audio/) |
| SpatJS | Browser-based spatial audio engine using Web Audio API | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/spatjs/spatjs) • [Website](https://spatjs.org) |
| RustSpat | High-performance Rust library for 3D ambisonics and panning | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/rustspat/rustspat) • [Website](https://rustspat.dev) |
| GoSpatialAudio | Go network framework for spatial audio stream routing | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gospat/gospatialaudio) • [Website](https://gospatialaudio.dev) |
| SpatKit C# | C# framework for spatial audio positioning in game engines | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/spatkit/spat-kit) • [Website](https://spatkit.org) |
| JavaSpat | Java framework for spatial audio simulation in server networks | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/javaspat/javaspat) • [Website](https://javaspat.org) |
| Soundfield C++ | C++ library for calculating high-order ambisonic fields | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/soundfield/soundfield) • [Website](https://soundfield.net) |
| OpenAL | Cross-platform 3D audio API designed for games and simulation | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/kcat/openal-soft) • [Website](https://openal-soft.org) |
| PySpat | Python spatial audio acoustics simulator and room modeler | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/pyspat/pyspat) • [Website](https://pyspat.org) |
| AmbisonicsJS | JavaScript library for real-time interactive Ambisonic decoding | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/ambisonics/ambisonicsjs) • [Website](https://ambisonicsjs.org) |
| SpatioSDK | Kotlin mobile app framework for binaural 3D audio rendering | <kbd>🏷️ Kotlin</kbd> | [GitHub](https://github.com/spatio/spatiosdk) • [Website](https://spatiosdk.io) |
| RoomSpat | C++ library for estimating acoustic impulse responses in 3D rooms | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/room/roomspat) • [Website](https://roomspat.net) |
| EchoLocate | Rust framework for acoustic beamforming and source localization | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/echo/echolocate) • [Website](https://echolocate.dev) |
| DynamicSpatial | Go system for real-time head-tracking spatial audio adjustments | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/dynspat/dynamicspatial) • [Website](https://dynamicspatial.org) |
