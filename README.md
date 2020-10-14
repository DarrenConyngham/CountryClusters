# CountryClusters

## 1. What is this project?
Countries clusters is commonly used by international institutions to group countries based on common features. For example, many institutions split countries into Developed Countries and Developing Countries based on various factors relating to the average quality of life (income, health etc.) in a country. This project uses the World Bank's World Development Indicators dataset and Unsupervised Learning to cluster countries of the world. This project is an attempt to come up with its own set of clusters. One advantage of using Hierarchical Clustering is you do not need to specify how many clusters to divide the data into. This allows you to gety a much more granular look at the similarities and differences between countries.

## 2. What does it do?
The code to run the file can be found in `CountryClusteringAnalysisv2.ipynb`. The code outputs two images which, by default, when run show up in the `images\` subfolder. The data used to create this analysis can be found in the `data_and_metadata/WDIData_2010_onwards.csv`. This is the same file the can be found on the World Bank website; just filtered for datapoints from 2010 onwards.  

## 3. How do run the code?
The Python code (`CountryClusteringAnalysisv2.ipynb`) is in the form of a Jupyter Notebook. If you download the code and the data (`data_and_metadata/WDIData_2010_onwards.csv`) and run it locally; it should run and produce the two images as outputs. Due to missing values, these needed to be filled in and certain indicators and countries were removed. These were "subjective" decisions. Please feel free to deal with missing values as you see fit and see if your results differ from mine.

## 4. What are the results?
Please see the bottom of the Jupyter Notebook for the full results but two interesting observations I found by looking at the chart are: 1) Countries with similar wealth tended to be very similar, 2) Countries with geographic proximity tended to be grouped together. 
