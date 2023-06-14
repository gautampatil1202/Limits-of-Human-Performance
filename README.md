# Limits-of-Human-Performance
Prediction the Limits of Human Performance with Python with modeling exponential decay using SciPy.

About:
=====

Human performance, like many other traits, follows a [Bell Curve distribution](https://en.wikipedia.org/wiki/Normal_distribution). This means that most people fall within the average range, near the peak of the curve, with only a small percentage being exceptionally slow or fast. As we move farther away from the peak, the number of individuals with that level of performance drops off exponentially. In the case of sprinting, this means that the fastest sprinters have already reached the flattened, tapered part of the curve. As a result, making significant speed improvements will become increasingly difficult.

![](output/pic1.jpg)


The data utilized in the analysis was obtained from the [topend sports site](https://www.topendsports.com/sport/athletics/record-100m.htm), which provides a comprehensive list of world records in the men's 100m event. The dataset consists of fewer than two dozen records, indicating the infrequent occurrence of significant record-breaking events in this category. To facilitate data manipulation and analysis, the records were transformed into a dictionary format and subsequently converted into a pandas DataFrame.

To enhance the analysis, an additional column was incorporated into the DataFrame to denote the number of years elapsed since the establishment of the first recorded record. This allows for an examination of the relationship between the recorded times (measured in seconds) and the passage of time since the initial record was set.



The SciPy Library:
======

The open-source SciPy library expands on NumPy by providing physical constants, conversion factors, and numerical routines for mathematics, science, and engineering use. These include optimization routines for curve fitting, which is just what we need for this project.

1. Scipy:  https://scipy.org

Steps to run the file:
=======

Step 1: Download the files and upload the .ipynb and the .csv file using either Google Colab or Jupyter Notebook.

Step 2: Once uploaded, for Google Colab run every cell starting from the first one to reach the output or click on "Run All" cells. For Jupyter notebook, install the required libraries in your Windows/MAC/Linux devices to run the code.

Step 3: Analyse the graph and the dataset along with the prediction of limits of the performance with the desired parameter and without the same.


![](output/pic2.jpg)

![](output/pic3.jpg)

![](output/pic4.jpg)

 


