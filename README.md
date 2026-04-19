# face-recognition-pca-ann
Face Recognition using PCA (Eigenfaces) and ANN

## Project Overview
A face recognition system built using Principal Component Analysis (Eigenfaces) 
and Artificial Neural Network (Backpropagation) from scratch using Python.

## Dataset
Bollywood Celebrity Face Images — 9 subjects, 450 images (50 per person)

Subjects: Aamir, Ajay, Akshay, Alia, Amitabh, Deepika, Disha, Farhan, Ileana

Download dataset from:
https://github.com/robaita/introduction_to_machine_learning

## Libraries Used
- NumPy — matrix operations, eigenvalue decomposition
- OpenCV (cv2) — image reading and resizing
- scikit-learn — MLP classifier, StandardScaler
- Matplotlib — plotting graphs

## Results
| Experiment | Result |
|---|---|
| Best k (eigenfaces) | 150 |
| Test Accuracy | 75.6% |
| Impostor Rejection Rate | 54% (27/50) |

## How to Run
1. Clone this repository
2. Download the dataset and place in `dataset/faces/` folder
3. Open `Face_recognition.ipynb` in Jupyter Notebook
4. Run all cells in order
