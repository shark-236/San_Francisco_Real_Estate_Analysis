# San Francisco Real Estate Analysis

A proptech company wants to offer an instant, one-click service for people to buy properties and then rent them. To test this service, the company is going to trial this offering in the San Francisco market. The set of code included in this repository (san_francisco_housing.ipynb) is a program that calls in San Francisco Neighborhood Census Data (and other supporting files) to create visualizations of rent and income trends in the SF market, which can then be analyzed to identify potential investment opportunities. 

---

## Technologies

This program uses Python version 3.9.12, Pandas, HVPlot and GeoViews (through HoloViz), and Pathlib. Pathlib should be included with Python version 3.4 and newer. 

---

## Installation Guide

To check your current Python version, run the following code in your terminal:  
python --version  
  
To check your installed packages, run one of the following lines of code in your terminal:  
pip list  
conda list  
  
If you need to install the aforementioned packages, run the following code:  
conda install pandas  
conda install pathlib  
conda install -c pyviz holoviz  

---

## Usage

Important: This program is intended purely for academic purposes, and is solely an example of what is possible. This program is not intended to be provided actual investment advice.   
  
To begin using this program, please download the following files (included in the repository) to your local machine:  
housing_per_year.csv  
neighborhoods_coordinates.csv  
sfo_neighborhoods_census_data.csv  
  
After opening the san_francisco_housing.ipynb file, ensure the Path to the above CSV files are mapped accurately. This program was built with the CSV files housed in the same folder; if you have saved the files elsewhere, please re-map your CSV files as needed.  
  
Once the CSV files are mapped, run each cell to retrieve the pertinent information. The widget in the "SF 2010 - 2016 Sale Price per Square Foot and Average Gross Rent (By Neighborhood)" plot can be adjusted to view different neighborhood trends. The "Sale Price per Square Foot and Gross Rent by Neighborhood" plot can be manipulated to retrive pertinent information.   

---

## Contributors

Shahrukh Alam

---

## License

Columbia Engineering: FinTech Bootcamp