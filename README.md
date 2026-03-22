# Hotel Booking Analysis
A data analysis project exploring hotel booking trends, cancellation patterns, and customer behaviour using Python and Jupyter Notebook.

## Overview
This project performs exploratory data analysis (EDA) on hotel booking data to uncover insights about booking patterns, cancellation rates, seasonal trends, and guest demographics. The goal is to help hotel management and stakeholders make data-driven decisions to optimise revenue and reduce cancellations.

## Repository Structure
Hotel-Booking-Analysis/
│
├── Hotel-Booking-Analysis.ipynb   # Main Jupyter Notebook with full analysis
├── README.md                      # Project documentation
└── LICENSE                        # Apache 2.0 License

## Key Analysis Areas

Booking Cancellation Analysis — Identifying factors that contribute to cancellations
Seasonal Trends — Monthly and yearly booking patterns
Guest Demographics — Country of origin, market segment, and customer type
Lead Time — Relationship between booking lead time and cancellation rates
Room Type & Pricing — Average daily rate (ADR) across room types and hotel categories
Special Requests — Impact of special requests on cancellation likelihood
Distribution Channels — Comparing bookings from direct, online TA, corporate, etc.


## Tech Stack
ToolPurposePython 3.xCore programming languagePandasData manipulation and wranglingNumPyNumerical computationsMatplotlibData visualisationSeabornStatistical plottingJupyter NotebookInteractive analysis environment

## Getting Started
Prerequisites
Make sure you have Python 3.7+ and pip installed.
Installation

Clone the repository

bash   git clone https://github.com/sakshi-nandgude/Hotel-Booking-Analysis.git
   cd Hotel-Booking-Analysis

Install required libraries

bash   pip install pandas numpy matplotlib seaborn jupyter

Launch Jupyter Notebook

bash   jupyter notebook Hotel-Booking-Analysis.ipynb

## Dataset
The analysis uses the well-known Hotel Booking Demand dataset, which contains booking information for a city hotel and a resort hotel. Key features include:

hotel — Hotel type (City Hotel / Resort Hotel)
is_canceled — Whether the booking was cancelled
lead_time — Days between booking and arrival
arrival_date_* — Year, month, week number, day of month
stays_in_weekend_nights / stays_in_week_nights — Length of stay
adults, children, babies — Guest composition
meal — Meal plan booked
country — Country of origin
market_segment / distribution_channel — How the booking was made
reserved_room_type / assigned_room_type — Room details
adr — Average Daily Rate
special_requests — Number of special requests made


Source: Hotel Booking Demand Dataset — Kaggle


## Key Insights

City hotels have a significantly higher cancellation rate than resort hotels.
Bookings made through online travel agents (OTAs) show higher cancellation rates compared to direct bookings.
Lead time is positively correlated with cancellation probability — the further in advance a booking is made, the more likely it is to be cancelled.
Peak booking months are July and August, with the lowest activity in January and February.
Portugal (PRT) is the most common country of origin for guests.


## License
This project is licensed under the Apache 2.0 License.


## Author
Sakshi Nandgude
GitHub Profile

Feel free to ⭐ this repo if you found it helpful!
