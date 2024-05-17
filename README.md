## About The Project

The main purpose of this project is to design and implement a Convolutional Neural Network (CNN) capable of accurately classifying MRI scan images to determine the presence or absence of a brain tumor. Through extensive training on a mixture of two separate datasets (over 800 images each, for both tumor and non-tumor classification) the resulting model achieves an accuracy rate of above 90% every time.




## Built With

- Python
- Python Libraries, such as PyTorch, Matplotlib, scikit-learn
- Jupyter Notebooks
- Git
- Kaggle Dataset: ["Brain MRI Images for Brain Tumor Detection" by NAVONEEL CHAKRABARTY](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
- Research Dataset: ["JMCD Dataset for Brain Tumor Detection and Analysis Using Explainable Deep Learning" by Aryan Verma, Nidhi Gupta, Pushpraj Bhatele & Pritee Khanna](https://link.springer.com/article/10.1007/s42979-023-02308-9)



## Installation

**Requirements:**

- Python (tested on Version [3.11.8](https://www.python.org/downloads/release/python-3118/))
- An environment to run Jupyter Notebooks in, eg.: [Visual Studio Code](https://code.visualstudio.com/download)
- (only tested on Windows)


**Installation steps:**

1. Clone this repository and open it in the environment of your choice.

2. Open your terminal and navigate to the root of this project.

3. Install the required libraries by running the following command in your terminal:
```
py -m pip install -r requirements.txt
```

4. Install the necessary pytorch versions (only tested on CUDA graphics processing units):
```
py -m pip install torch==2.2.1 torchvision==0.17.1 --index-url https://download.pytorch.org/whl/cu121
```





## Usage

After the successfully completing all steps in the `Installation`, you can simply run all the cells in the `notebook.ipynb` file.

With the help of the bottom two cells you can have the finished model make a prediction for your own MRI brain scan images. Please have a look at the accompaning instructions written above the last 2 cells inside the notebook.




## Contact

LinkedIn: Dina Mahdi-Joest [https://www.linkedin.com/in/dina-mahdi-joest-340204220/](https://www.linkedin.com/in/dina-mahdi-joest-340204220/)

GitHub: https://github.com/dinamj

E-Mail: dinamahdijoest@gmail.com

