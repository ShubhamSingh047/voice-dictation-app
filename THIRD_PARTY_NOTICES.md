# Third-party notices

Dictation and Dictation Lite include the following software and models.

## Speech models

| Model | Used in | Licence | Source |
|---|---|---|---|
| Whisper-Hindi2Hinglish-Apex (converted to whisper.cpp q5_0) | Dictation | Apache-2.0 | Oriserve, https://huggingface.co/Oriserve/Whisper-Hindi2Hinglish-Apex (based on OpenAI whisper-large-v3-turbo, MIT) |
| Dictation Lite student model v1 (converted to whisper.cpp q5_0) | Dictation Lite | CC BY-SA 4.0 | Fine-tuned from Oriserve Whisper-Hindi2Hinglish-Swift (Apache-2.0, based on OpenAI whisper-base, MIT) on the datasets below, using transcripts produced by Whisper-Hindi2Hinglish-Apex. Modified: fine-tuned and quantized. |
| Silero VAD v5.1.2 (ggml) | both | MIT | https://github.com/snakers4/silero-vad |

### Training data of the Dictation Lite model

| Dataset | Licence | Credit |
|---|---|---|
| MUCS 2021 Hindi-English code-switched speech (sub-task 2) | CC BY-SA 4.0 | MUCS 2021 challenge, https://www.openslr.org/104/ (audio from the Spoken Tutorial project) |
| IndicVoices (Hindi subset) | CC BY 4.0 | AI4Bharat, IIT Madras |
| LibriSpeech | CC BY 4.0 | Panayotov et al., OpenSLR SLR12 |

Because MUCS 2021 is CC BY-SA 4.0, the Dictation Lite model is distributed under CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/).

## Libraries

| Library | Licence |
|---|---|
| whisper.cpp / ggml | MIT |
| whisper-rs | Unlicense |
| Slint | Slint Royalty-free License 2.0 (attribution: "Made with Slint" badge on the download page) |
| handy-keys, handy-recorder | MIT |
| tray-icon, enigo, arboard, objc2 | MIT or Apache-2.0 |

Full licence texts are available from each project's repository.
