# AI Voice Detector
- The system focuses on comparing metric outputs from Handcraft Feature, Transformer models, and attempting to enhance Rawnet2 with them.

## Dataset

### English
- [ASVspoof 2021](https://www.asvspoof.org/index2021.html) (Large-scale dataset used for AI voice detection competitions, containing both genuine and spoofed voices, total 56251 files or 7.23 GB)

### Thai
- [Mozilla Common Voice Corpus 16.1](https://commonvoice.mozilla.org/th/datasets) First Validated 10000 files (Bonafide)
- [AI For Thai](https://aiforthai.in.th/corpus.php) Fake audio for thai voice 49891 files (Spoof)

## Front-end
- **Raw**

- **Handcrafted Feature**
  - LFCC
  - Mel spectrogram
- **Feature Extractor**
  - [Wav2vec](https://huggingface.co/facebook/wav2vec2-base-960h)

## Classifier
- RawNet2
- Random Forest
- ANN (Artificial Neural Networks)
- KAN (Kolmogorov-Arnold Networks)

## Metric
- Accuracy
- min t-DCF
- EER

## Our Experiment
- 

## Baseline

- [ASVspoof Challenge 2021](https://github.com/asvspoof-challenge/2021)
 ![Baseline Score](base-line-score.png)


## Deploy on 
- 

## Framework
- 

## Check our website here 🚀🚀🚀
- https://vocalsense.pythonanywhere.com/
