# State-crime-Prediction
# Model Evaluation and Validation


### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)



### Code

Template code is provided in the `final_project_Agalya.ipynb` notebook file. You will also be required  the `state crime.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. 




### Data

The modified State crime dataset consists of 2751 data points, with each datapoint having 21 features.(https://corgis-edu.github.io/corgis/csv/state_crime/).

**Features**	<br>
1.State	:	The long name of the state that this report was made for.	<br>

2.Year	:	The year that this report was made in.	<br>

3.Data.Population:	The number of people living in this state at the time the report was created.		<br>

4.Data.Rates.Property.All	Float	Rates are the number of reported offenses per 100,000 population. This property reflects all of the Property-related crimes, including burglaries, larcenies, and motor crimes.		<br>	

5.Data.Rates.Property.Burglary	:	Rates are the number of reported offenses per 100,000 population. This property reflects the number of burglaries, or entry into a building illegally with intent to commit a crime, especially theft.		<br>

6.Data.Rates.Property.Larceny	:	Rates are the number of reported offenses per 100,000 population. This property reflects the number of burglaries, or theft of personal property.	<br>

7.Data.Rates.Property.Motor	:	Rates are the number of reported offenses per 100,000 population. This property reflects the number of crimes where a motor vehicle was stolen.		<br>

8.Data.Rates.Violent.All	:	Rates are the number of reported offenses per 100,000 population. This property reflects all of the Violent crimes, including assaults, murders, rapes, and robberies.		<br>

9.Data.Rates.Violent.Assault	:	Rates are the number of reported offenses per 100,000 population. This property reflects the number of crimes where someone made an attempt to initiate harmful or offensive contact with a person, or made a threat to do so.		<br>

10.Data.Rates.Violent.Murder:	Rates are the number of reported offenses per 100,000 population. This property reflects the number of crimes where someone committed the unlawful killing of another human being without justification.		<br>

11.Data.Rates.Violent.Rape	:	Rates are the number of reported offenses per 100,000 population. This property reflects the number of crimes where someone committed rape. The FBI UCR definition of rape, before 2013, is the carnal knowledge of a female forcibly and against her will.	<br>	

12.Data.Rates.Violent.Robbery	:	Rates are the number of reported offenses per 100,000 population. This property reflects the number of crimes where someone took or attempted to take anything of value by force or threat of force or by putting the victim in fear.	<br>

13.Data.Totals.Property.All	:	This property reflects all of the Property-related crimes, including burglaries, larcenies, and motor crimes.	<br>

14.Data.Totals.Property.Burglary	:	This property reflects the number of burglaries, or entry into a building illegally with intent to commit a crime, especially theft.		<br>

15.Data.Totals.Property.Larceny	:	This property reflects the number of burglaries, or theft of personal property.		<br>

16.Data.Totals.Property.Motor	:	This property reflects the number of crimes where a motor vehicle was stolen.	<br>

17.Data.Totals.Violent.All	:	This property reflects all of the Violent crimes, including assaults, murders, rapes, and robberies.		<br>

18.Data.Totals.Violent.Assault	:	This property reflects the number of crimes where someone made an attempt to initiate harmful or offensive contact with a person, or made a threat to do so.		<br>

19.Data.Totals.Violent.Murder	:	This property reflects the number of crimes where someone committed the unlawful killing of another human being without justification.	<br>	

20.Data.Totals.Violent.Rape	:	This property reflects the number of crimes where someone committed rape. The FBI UCR definition of rape, before 2013, is the carnal knowledge of a female forcibly and against her will.		<br>

21.Data.Totals.Violent.Robbery	:	This property reflects the number of crimes where someone took or attempted to take anything of value by force or threat of force or by putting the victim in fear.	<br>

