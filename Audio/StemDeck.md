# StemDeck

- Official repository: stemdeckapp/stemdeck
- License: Apache-2.0
- Offline: Yes after initial runtime/model setup.
- AI required: No cloud AI; stem separation uses local Demucs neural models.
- Internet/API: Initial app/model downloads need internet; local audio processing does not require cloud access. YouTube import requires network.
- API key: Not required for local processing.
- Local/self-hosted: Yes; prebuilt Windows/macOS/Linux packages and Docker are documented.
- Basic non-cloud workflow: import an owned audio/video file, run local six-stem separation, review vocals/drums/bass/guitar/piano/other, then export individual stems or a mix.
- Runtime prerequisites: current releases bundle the Python runtime and download FFmpeg/Demucs on first launch; NVIDIA builds use CUDA, while Apple Silicon can use MPS. Manual source setup uses Python/uv and FFmpeg.
- Limitation: project is still alpha; some platform-specific issues remain, including reported Linux playback/waveform problems. YouTube support should only be used for content the user has rights to process.
- Source verified: official GitHub repository/documentation.