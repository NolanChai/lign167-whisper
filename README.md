# Fine-tuning Whisper Models for Child Speech Recognition: Evaluation Pitfalls and Early Stage Fine-Tuning on the Ohio Child Speech Corpus

This is the repository hosting some code used in our paper, Fine-tuning Whisper Models for Child Speech Recognition, for LIGN 167. Specifically,
- `lign_167_preprocessing` contains an annotated notebook to preprocess data for training and generating manifest files
- `fine_tune_1500.ipynb` contains an annotated notebook used to fine tune OpenAI Whisper-Medium
- `OCSC_eval.ipynb` contains exploratory code for error analysis and running evaluations
These three notebooks specifically are hosted on Google Colaboratory. We have other residual files in the repository from experimenting with setting things up locally using astral's uv for our Python environment.