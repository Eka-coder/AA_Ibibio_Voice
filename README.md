# Ibibio-Voice, ASR for Ibibio

## 📁 Project Structure

```
AA_Ibibio_Voice/
│
├── data/
│   ├── processed_128/          # Original 128×128 images
│   └── lowres_32/              # Downscaled 32×32 images
|   └── test/                   # Unseen dataset used to evaluate models
├── models/                    # Trained model weights
├── notebooks/                 # Notebook for classifiers A, SRGAN and B
|   └── logs/                  # Logs for Classifier A Training training
├── checkpoints/               # Model weights during training of SRGAN
├── output/                    # SRGAN-generated images
└── README.md                  # This file
```


## Author: Eka Ebong
- **Course**: Applied AI
- **Assignment**: Midterm Exam
- **Focus**: SRGAN implementation and evaluation
