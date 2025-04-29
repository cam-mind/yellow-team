## MIND Hackathon - Team Yellow

# Project Overview

We explore the relationship between brain activity and music perception by building a cross-modal learning framework that fuses EEG, fMRI, and musical features.

# Pipeline

1. Pre-Processing
- fMRI: Activation masking based on intensity.
- EEG: Filtering using Notch and Bandpass filters.
2. Audio Pre-Processing
- Audio-to-Notes model based on a Transformer architecture (Transkun, Yan, 2024).
- Audio-to-Chords translation.
- Notes features extracted: Average pitch, Variance in pitch
3. Model Architecture
- Temporal Encoding: Using S4 layers to capture temporal dependencies and reduce information loss.
- Cross-Modal Fusion: Supervised and Self-Supervised learning, Separate towers for EEG and fMRI signals, Resampling for temporal alignment.
- Joint Embedding Space: Enables downstream tasks and interpretability through full linearity.

# Key Ideas

- Temporal Alignment of EEG and fMRI signals with musical features.
- Supervised and Self-Supervised Cross-Modal Fusion for robust representation learning.
- Full Linearity for better feature interpretability.
- Brain Activity Captures Musical Semantics.

# Team Yellow – MIND Hackathon
