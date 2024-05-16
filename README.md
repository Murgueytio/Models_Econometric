Econometrics | Geopolitics

This model is the initial part of a project that aims to predict the behavior of various types of markets 
in the face of geopolitical factors (multilateralism, immigration, levels of war, climate change, among others).

The XLSX files are extracted from the World Bank Open Data, except 'Trade', which is the result of the subtraction between the values of 'Exports' and 'Imports'; nor 'GPI', the Global Peace Index that I obtained manually from each of the annual reports of the Institute for Economics and Peace. While 'Codex' contains the codes of each country and the regions to which they belong.
CSV starting with 'main_' is the result of data preparation. And those that start with 'df_' are the general 'combined' data set, and the other two are the data segmentation by country and worldwide. I had to discard the regional levels due to difficulties in maintaining solvent values.
The '.ipynb' files are deductible from the development of the work of the previous CSVs. The ones that are special in this case are both 'Econometric_Combined.ipynb' and 'Econometric_Countries.ipynb'.

The equation will be used: GDP = C + G + I + (X - M) = C + G + I + T

The real names of each indicator are:
1.- Final Consumption Expenditure (constant LCU) as C.
2.- GDP (constant 2015 US$) as GDP.
3.- General Government Final Consumption Expenditure (constant LCU) as G.
4.- Gross Fixed Capital Formation (constant 2015 US$) as I.
5.- Trade Balance in Constant Dollars as T.
As part of the training, the Inflation, Interest Rates and GPI indicators will be incorporated to evaluate the model.
