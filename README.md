# Dataset for animal_classification
click here to download - https://www.kaggle.com/datasets/deepakladwal/15-category-animal-image-classification-dataset

This project implements a Deep Learning Image Classification System designed to categorize images of animals across 15 distinct classes (Bear, Bird, Cat, Cow, Dog, Dolphin, Elephant, Giraffe, Horse, Kangaroo, Lion, Panda, Tiger, Zebra).
The classification model utilizes Transfer Learning based on the pre-trained MobileNetV2 architecture, which allows for fast training and high accuracy

-run the main.ipynb file
The Jupyter Notebook containing the full workflow: data loading, preprocessing, model training, evaluation, and visualization of results and predictions.


⚙️ Setup and Installation
Follow these steps to set up the project locally and run the code.

1. Clone the Repository
git clone https://github.com/deepak3294/animal_classification.git
cd animal_classification

2. Download the Dataset
Please download the Animal Classification 15-Category Dataset(from top of the page), then extract the contents so the data folder is placed directly inside the project root directory (animal_classification/).

3. Install Dependencies
pip install -r requirements.txt

Open main.ipynb file
Run all cells in sequence to load the data, train the MobileNetV2 model (for 20 epochs), evaluate its performance, and display the accuracy/loss curves and sample predictions.


📊 Results and Performance(85%)-
accuracy increase as number of epoch increase
Metric	Training Result
Model	MobileNetV2 (Transfer Learning)
Input Image Size	128x128x3
Number of Classes	15
Total Epochs	20
Final Test Accuracy	[0.8406 ]
Final Test Loss	[0.5333]


