# Tanzania_Water_Wells_Modeling_Project

Author: Nesphory Mwakale

## Project Overview
The project analyses a dataset to predict the status of wells in Tanzania on behalf of an NGO and the Central Government of Tanzania. The goal is to predict the state of wells and figure out if the wells are `functional`, `non-functional` or `functional but needs repair`.

## Repo Structure
* README.md - Top level summary of the project
* notebook.ipynb - Detailed Jupyter notebook documentation for the project
* MajiSafiAid Presentation.pdf - Presentation slides for the project in PDF format
* Data Folder - Contains the datasets used in the project

## Business Problem
> Build a classifier to predict the condition of a water well, using information about the sort of pump, when it was installed, etc. Your audience is an NGO or the Government of Tanzania focused on locating wells needing repair and looking to find patterns in non-functional wells to influence how new wells are built.

## Key Question Answered
* What features are necessary to figure out the state of a well?
* How accurate is the model in identifying the state of a well?
* Which model performed best for this project?

## Data
The dataset used was taken from [DrivenData](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/). At the time of completing this project, it was an active competition with 59,400 records in the dataset.

## Approach
The main approach was to learn to create as many models as possible. To figure out how various models works and how it affects performance and accuracy.
CRISP-DM was the underlying methodology utilized in this project.

## Tools Used
* Python - Pandas, Sklearn, Numpy, Matplotib, Seaborn, Scipy
* Jupyter Notebooks
* Visual Studio Code

## Business Recommendations
* MajiSafi Aid can focus on regions like Lindi, Mtwara, Rukwa, Mara, Mwanza, Singida and Tabora should be focus regions as they have more non-functional wells than functional or almost the same number of functional and non-functional wells.
* Some wells support a population of zero. The Tanzanian government and MajiSafi Aid can focus on building a few deep wells in every region and reservoirs and focus on water transportation pipelines to reduce distance travelled by villagers to get water.
* Water cleaning technology like reverse osmosis and filtration can be established in areas with milky, salty, colored and fluoride water to ensure clean water access.

## Future Directions
* The best model was able to corretly identify 68% of all wells. Most models however failed to identify the models that need repair. More data is necessary to help train the data and correctly predict more wells accurately. Especially data on wells that need repair.
* More models can be implemented on this model; especially because this model was full of categorical data. Further tuning can also be done to improve the accuracy of the models. More experience, of course, is also needed to know where to improve and to increase domain knowledge in the sector. Otherwise, this was good practice.
* Investing in data validation during the data collection stage can help reduce the data errors that were observed in the installer and funder columns of this data set.
