# Brain Tumor MRI Classification: CNN Robustness Training and Analysis

# Requirements

- Python 3.3+
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- SciPy
- kagglehub

Install via:
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn scipy kagglehub

The code uses the Brain Rumor MRI Dataset by Masoud Nickparvar
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/code

Trains 2 CNN's, one which identifies the type of brain tumor with original data
the second CNN trains from degraded versions of the images (70% degraded, 30% clean)
using the following methods of degradation: gaussian noise, salt & pepper, contrast reduction, and speckle noise
