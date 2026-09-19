# VoiceStudio

- Official repository: niaodian/voicestudio
- License: AGPL-3.0 for the application; optional engines/models retain their own licenses.
- Offline: Yes after required models are installed.
- AI required: Yes for voice cloning, TTS, ASR and dubbing; the core engines run locally rather than requiring a cloud AI service.
- Internet/API: First launch/model downloads need network; remote workers and remote/OpenAI-compatible providers are optional.
- API key: Not required for the core local workflow or loopback API; remote access/providers may require credentials.
- Local/self-hosted: Yes; desktop apps for macOS/Windows/Linux and Docker are documented.
- Basic non-cloud workflow: run local TTS/ASR/dubbing with installed engines, keep voices/projects/outputs on the machine, then export audio/video.
- Runtime prerequisites: prebuilt packages manage the Python environment; hardware requirements vary by engine. Current default guidance lists 8 GB RAM minimum, 10 GB free disk, optional GPU and 4 GB VRAM minimum for acceleration.
- Limitation: active beta; Intel Macs cannot run the local Python backend. Optional engines/models have separate licenses.
- Source verified: official GitHub repository/documentation. 
