# Real-Time Sign Language Recognition Using Neural Networks

**Author: Manav Arya**

---
This project is solely owned and maintained by Manav Arya. For more projects, visit my GitHub: [nnfl-project](https://github.com/Manavarya09/nnfl-project)

## Overview
This project provides a real-time sign language detection system using an LSTM (Long Short-Term Memory) neural network. It enables users to recognize sign language gestures from video input, making communication more accessible for the hearing and speech impaired.

## Features
- Real-time detection of sign language gestures
- Deep learning model (LSTM) for sequence prediction
- Easy-to-use interface
- Pre-trained model weights included

## Project Structure
```
├── model_weights.h5         # Pre-trained model weights
├── model.h5                 # Model architecture
├── RealTimeSignLanguageDetection.ipynb  # Demo notebook
├── Train.ipynb              # Model training notebook
├── v2/
│   ├── main.py              # Main script for detection
│   ├── requirements.txt     # Python dependencies
│   └── README.md            # v2 module documentation
```

## Setup Instructions
1. **Clone the repository:**
   ```zsh
   git clone https://github.com/Manavarya09/Realtime-Sign-Language-Detection-Using-LSTM-Model.git
   cd Realtime-Sign-Language-Detection-Using-LSTM-Model-main
   ```
2. **Create and activate a virtual environment:**
   ```zsh
   python3 -m venv venv
   source venv/bin/activate
   ```
3. **Install dependencies:**
   ```zsh
   pip install -r v2/requirements.txt
   pip install notebook
   ```

## Usage
- **Run the main detection script:**
  ```zsh
  python v2/main.py
  ```
- **Open and run the demo notebook:**
  ```zsh
  jupyter notebook RealTimeSignLanguageDetection.ipynb
  ```

## Model Training
To retrain the model, use the `Train.ipynb` notebook. Make sure your dataset is properly formatted and update the paths as needed.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or contributions, please contact:
- Manav Arya (Manavarya09)
- GitHub: [Manavarya09](https://github.com/Manavarya09)

---
This project is solely owned and maintained by Manav Arya. Feel free to open issues or submit pull requests to improve this project!
