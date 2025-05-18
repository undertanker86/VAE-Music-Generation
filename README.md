# Music Style Transfer with CVAE

Transform music between different genres using Conditional Variational Autoencoder (CVAE) with mel-spectrogram representation.

## Features

- 🎵 **Multi-genre Style Transfer**: Transform between rock, pop, jazz, classical, electronic, etc.
- 🏗️ **CVAE Architecture**: Skip connections for high-quality reconstruction  
- 🔊 **Audio Processing**: Mel-spectrogram conversion with Griffin-Lim reconstruction
- 📊 **Data Crawling**: Automated FreeMusic Archive collection

## Quick Start

### Installation
```bash
pip install torch torchaudio librosa scikit-learn streamlit selenium matplotlib tqdm
```
#### 1. Crawl data
- You can run vae-based-music-generation-crawldata.py or access here to get data:  https://drive.google.com/file/d/1PzzqApEdJXHmOMCO4HMyLN7v7O8368cW/view?usp=drive_link

#### 3. Inference
- After training you will have model (After training). Or you can access here get model: https://drive.google.com/file/d/18SIagaWJGFHylo9B5CxuuHg1lOTQiMk5/view?usp=drive_link

## Acknowledgments

- FreeMusic Archive for open-source music data
- Librosa for audio processing
- PyTorch for deep learning framework