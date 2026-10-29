# Deep Learning Practical Exam – Set C

## Project Overview
This repository contains five mini-projects completed as part of the Deep Learning Practical Exam – Set C. The projects demonstrate Artificial Neural Networks, OpenCV, Convolutional Neural Networks, Recurrent Neural Networks, and Transformer models.

## Video Explanation Link : https://drive.google.com/drive/folders/1Hwk48L7Ays5TCz3vXhxAe2Xc3d2lO0B3?usp=drive_link
## Projects Covered

### 1. ANN – Artificial Neural Network
- **Task:** Classification
- **Purpose:** To learn how an artificial neural network classifies data.
- **Tools:** Python, TensorFlow/Keras, Pandas, NumPy, Scikit-learn.
- **Output:** Classification results and a saved model (`ann_wine_model.h5`).

### 2. OpenCV – Image Processing and Face Detection
- **Task:** Image preprocessing and face detection.
- **Purpose:** To process images and detect faces using OpenCV.
- **Tools:** Python, OpenCV.
- **Output:** Original images, processed images, and face detection results.

### 3. CNN – Convolutional Neural Network
- **Task:** Handwritten digit classification.
- **Dataset:** MNIST.
- **Purpose:** To classify handwritten digits using a CNN.
- **Tools:** TensorFlow/Keras, NumPy, Matplotlib.
- **Output:** Classification results and a saved model (`cnn_mnist_model.h5`).

### 4. RNN – Recurrent Neural Network
- **Task:** Time-series forecasting.
- **Dataset:** Daily Minimum Temperatures in Melbourne.
- **Purpose:** To predict the next day's minimum temperature using the previous 30 days.
- **Model:** GRU with 32 units.
- **Evaluation:** RMSE and MAE.
- **Output:** Actual-versus-predicted temperature plot and saved model (`rnn_temperature_model.h5`).

### 5. Transformers – NLP
- **Tasks:** Fill-mask prediction, question answering, and text generation.
- **Dataset:** Five India-related paragraphs and custom questions/prompts.
- **Models:** DistilBERT and DistilGPT-2.
- **Purpose:** To explore pretrained Transformer models for natural language processing.
- **Output:** Predicted words, answers, confidence scores, and generated text.

## Technologies Used
- Python
- Jupyter Notebook
- TensorFlow and Keras
- OpenCV
- NumPy and Pandas
- Matplotlib and Scikit-learn
- Hugging Face Transformers and PyTorch

## Repository Structure

```text
deep-learning-practical-exam-set-c/
├── DeepLearning_Practical_Exam_SetC.ipynb
├── ann_wine_model.h5
├── cnn_mnist_model.h5
├── rnn_temperature_model.h5
├── results_summary.csv
├── summary_report.md
├── requirements.txt
├── README.md
└── outputs/
    ├── original_images/
    ├── processed_images/
    └── face_detection_results/
```

*The folder structure above is a suggested structure. Include only files and folders that exist in your repository.*

## How to Run the Project

1. Clone or download this repository.
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `DeepLearning_Practical_Exam_SetC.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order.
5. Check the model outputs, evaluation metrics, plots, and generated files.

Some pretrained Transformer models and datasets may download automatically when the notebook is executed.

## Results and Evaluation

The projects use different evaluation methods:

- **ANN:** Classification accuracy.
- **OpenCV:** Number of faces detected and visual inspection of processed images.
- **CNN:** Classification accuracy on MNIST.
- **RNN:** RMSE and MAE for temperature prediction.
- **Transformers:** Question-answering results, confidence scores, and text-generation outputs.

Refer to `results_summary.csv` for the actual results obtained in each project.

## Learning Outcomes

Through these projects, I learned about:
- Neural network classification.
- Image processing and face detection.
- CNN-based image classification.
- Time-series forecasting with GRU.
- Pretrained Transformer models for natural language processing.
- Model evaluation, visualization, and saving trained models.
- Organizing and submitting projects using GitHub.

## Future Improvements

Future work could include hyperparameter tuning, comparing different model architectures, improving prediction accuracy, testing on additional datasets, and validating generated text against reliable sources.

## Author
PURVI TALAVIYA

**Deep Learning Practical Exam – Set C**

