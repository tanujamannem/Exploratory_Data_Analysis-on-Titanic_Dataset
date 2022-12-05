# Exploratory_Data_Analysis-on-Titanic_Dataset

Requirements

Python , colab notebook.
Numpy, Pandas, seaborn and sklearn library.
Dataset(titanic.txt), added in the repository.
This dataset has passenger information who boarded the Titanic along with other information like survival status, Class, Fare, and other variables. The unfortunate event which was occurred on 15 April 1912, the Titanic sank after colliding with an iceberg, aboard 2224 peoples.

This project addresses the following Data Analysis topics:

Data Exploration and Preparation

Data Representation and Transformation

Data Visualization and Presentation

Data Exploration and Preparation Learn about data: Are there missing data? Is it categorical? if not, min , max, avg values? if yes, what are the categories? distribution of variables Duplicate entry

Data Representation and Transformation Few Passengers didn't pay for the ticket, so there may be a possibility that they didn't purchase a ticket or it was "complimentary" (ticket No. 112050,112059). After checking sample entries, i found out some of the passengers did get a complimentary ticket. This may also help to analyze whom(Important figure in society) to distribute the promotion ticket.

Transformation on dataframe: Droping some of the columns which many not contribute much to our machine learning model such as Name, Ticket, Cabin etc

Data Visualization and Presentation Age distribution per class.
Upper-class passenger median Age - 36 years Middle-class passenger median Age - 29 years Lower- class passenger median Age - 26 years
