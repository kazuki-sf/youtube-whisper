# YouTube Video Transcription with OpenAI's Whisper
    
[![License](https://img.shields.io/github/license/kazuki-sf/youtube-whisper)](https://github.com/kazuki-sf/youtube-whisper)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kazuki-sf/youtube-whisper/blob/main/youtube_whisper.ipynb)

This is a simple example of how to use OpenAI's Whisper to transcribe a YouTube video and shorts. The code is written in Python and can be run on Google Colab. The notebook will guide you through the process of transcribing a YouTube video or shorts using OpenAI's Whisper.

## How to Use
1. Open the [Google Colab](https://colab.research.google.com/github/kazuki-sf/youtube-whisper/blob/main/youtube_whisper.ipynb) page.
2. Feel free to `Copy to Drive` the notebook or run it directly.
3. Enter the URL of the YouTube video or shorts you want to transcribe.
4. Choose the whisper model you want to use.
5. Run the code cell (Step 1-3) and wait for the transcription to complete.

## Notes
* Whenever you change the YouTube URL or Whisper Model, please run the `Step 1` and then run `Step 3` (You can skip `Step 2` if you already ran it before)
* When you run `Step 3`, the website might ask you a permission to download multiple files.
* Here's a list of whisper model and the relative speed of each model. For more information, please visit the official GitHub page: https://github.com/openai/whisper#available-models-and-languages
---

|  Size  | Parameters | English-only model | Multilingual model | Required VRAM | Relative speed |
|:------:|:----------:|:------------------:|:------------------:|:-------------:|:--------------:|
|  tiny  |    39 M    |     `tiny.en`      |       `tiny`       |     ~1 GB     |      ~32x      |
|  base  |    74 M    |     `base.en`      |       `base`       |     ~1 GB     |      ~16x      |
| small  |   244 M    |     `small.en`     |      `small`       |     ~2 GB     |      ~6x       |
| medium |   769 M    |    `medium.en`     |      `medium`      |     ~5 GB     |      ~2x       |
| large  |   1550 M   |        N/A         |      `large`       |    ~10 GB     |       1x       |


## License
This project is licensed under the terms of the MIT license. For more information, please refer to the [LICENSE](LICENSE) file.

## Disclaimer
This project is not affiliated with OpenAI. The code provided here is for educational purposes only. Please use it responsibly and respect the terms of service of the platforms you are using.
