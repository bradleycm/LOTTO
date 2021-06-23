# PyLotto

Recently restarted development on this and looking to add a neural network component to try and do some real predictions.

## Developer Instructions
1. You will need the following:
* Git
* Docker
* Python 3.7 or higher
* Linux-like dev environment (this project was designed on OSX)
2. Spin up local database
* `docker-compose up -d`


# OLD INFORMATION
# LOTTO

Basically trying to gather data from every Lotto and create an instance of each that will;

1. Gather Dates and their appropiate winning lottery numbers
2. Gather Every number that has been drawn and show the occurrence (in percentage),
in the future I want to be able to filter based on All time or past month.
3. Create a UI design to display this information

* This is only be tested for the American Mega Millions Lotto (83 pages of data as of January 17,2018)
* Change line 14 value depending on how far back you intend to go with 83 being the max number currently


Even though you shouldn't use this probablity as there are no static variables it is good to know and could increase your chances of wining.

Takes currently about 30sec - 1min to proccess data at max 83 pages.
I need help reducing the time and making program more efficient.
* I have not did the code for the Mega yet.
