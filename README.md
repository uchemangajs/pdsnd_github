#  Data Exploration with Python, Numpy and Pandas on Bikeshare Data
_Udacity project using pandas library in Python for their bikeshare data exploration._

# Project Overview:

This project focuses on pandas library usage and simple statistics methods to perform a rudimentary analysis on the bikeshare data from three major U.S. cities - Chicago, Washington, and New York City - to display information such as most popular times of travel, trip durations or most common stations.

### Running the program:

You can input 'python bikeshare.py' on your terminal to run this program. I use Anaconda's command prompt on a Windows 8.1 machine.

### Program Details:

The program takes user input for the city (e.g. Chicago), month for which the user wants to view data (e.g. January; also includes an 'all' option), and day for which the user wants to view data (e.g. Monday; also includes an 'all' option).

Upon receiving the user input, it goes ahead and asks the user if they want to view the raw data (5 rows of data initially) or not. Following the input received, the program prints the following details:

* Most popular month of year
* Most popular day of week
* Most popular hour of day
* Most popular start station
* Most popular end station
* Most popular combination of start and end stations
* Total trip duration
* Average trip durationti
* Types of users by number
* Types of users by gender (only available for NYC and Chicago)
* The oldest user (only available for NYC and Chicago)
* The youngest user (if available)
* The most common birth year amongst users (if availableonly available for NYC and Chicago)

Finally, the user is prompted with the choice of starting all over or view raw data or exit the program.

# Requirements:

* Language: Python 3.6 or above
* Libraries: pandas, numpy, time

# Project Data:

* chicago.csv - Stored in the data folder, the chicago.csv file is the dataset containing all bikeshare information for the city of Chicago provided by Udacity.

* new_york_city.csv - Dataset containing all bikeshare information for the city of New York provided by Udacity.

* washington.csv - Dataset containing all bikeshare information for the city of Washington provided by Udacity. Note: This does not include the 'Gender' or 'Birth Year' data.

# Built with:

* [Python 3.6.6](https://www.python.org/) - The language used to develop this.
* [pandas](https://pandas.pydata.org/) - One of the libraries used for this.
* [numpy](http://www.numpy.org/) - One of the libraries used for this.
* [time](https://docs.python.org/2/library/time.html) - One of the libraries used for this.

# Author:

 * [UchennaNwajideobi](https://github.com/uchemangajs) - Sole author for this program. Mentioned all the help received in 'Acknowledgements' section.
  
# Acknowledgements: 
* [Juno Lee](https://github.com/junolee) - she is an excellent course instructor.
* [pandas docs](http://pandas.pydata.org/pandas-docs/stable/) - pandas documentation was immensely helpful in understanding the implemention of pandas methods used in this project.
* [Udacity](https://udacity.com) - Udacity's Data Analyst Nanodegree program and their instructors were extremely helpful while I was pursuing this project.
* Finally, I'd like to mention my college courses on Principles of Econometrics and Intermediary Econometrics for introducing me to data analysis and Eviews. The concepts embodied in the pandas library (e.g. data frame) were very similar to the ones used while I was working on my stata projects for college project.