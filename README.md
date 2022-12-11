## About The Project

Since the COVID-19 pandemic, free cancellation policy has become a common policy offered by most of the hotels in the U.S. to attract customers, since concerning the uncertain situations customers demand for more flexibility for their bookings [[eventtemple]](https://www.eventtemple.com/hotel-operations/hotel-cancellation-rates-a-thing-of-the-past/). Even though the COVID-19 situation is getting better, this policy is not likely to be cancelled, as hotels may be aware of losing their customers, considering that their competitors still maintain this policy. The research shows that the bookings cancellation rates in 2022 has reached 20%, which is a 33% increase from 2019 [[revenue-hub]](https://revenue-hub.com/three-most-common-trends-impacting-cancellation-rates/). The increase in cancellations does not only impact the hotel’s revenue, but also has an adverse impact on hotel’s marketing channels, since Online Travel Agencies keep track of cancellations of the hotel [[hotelminder]](https://www.hotelminder.com/everything-you-need-to-know-about-hotel-cancellations).

Given these facts, the goal of this project is to find solutions to help hotels reducing the number of cancellations. To achieve that goal, we will use machine learning techniques, specifically classification techniques, to determine which customers are likely to cancel their bookings, based on customers’ booking information, such as booking date, the length of stay, number of people, types of a deposit, and special requests. Knowing the probability of cancellation of each reservation, the hotels will be able to tackle this problem with various solutions. For instance, they will be able to target the customers that are prone to cancel their reservations and offer an additional promotion to make them reconsider their decisions. Moreover, the hotels will have a better approximation on how many staffs and hotel essential amenities they will need on specific date or month. Therefore, they will be able to minimize their costs and increase revenue. In addition to being able to identify the customers that are likely to cancel their bookings, the machine learning techniques will enable hotels to identify the leading factors that cause cancellations, which in turn will give hotels an insight of which areas they should improve to make them become successful hotels.


Considering the goal of this project, the task (`T`), performance (`P`), and experience (`E`) are as follows:


- `Task` is to identify the probability of cancellation of a reservation. Alternatively, we would like to know which customer is likely to cancel his/her reservation.


- `Performance` of this task is how precisely the hotels can point out the customers that are likely to cancel their reservations. More specifically, hotels want to correctly target the customers that tend to make cancellations, and do not want to miss any customer that they can reach out to convince them to not make cancellations.



- `Experience` is the historical data of the hotel reservations that will allow the hotels to more confidently identify which customers tend to cancel their reservations, using the machine learning techniques.

TLDR; Data Preprocessing, EDA, Modeling, Model Evaluation and campaign strategy [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YashashGaurav/hotel-customer-churn-modeling/blob/main/final_report.ipynb)

---
## Dataset

The Hotel Booking Demand dataset provides historical information related to hotel reservations, such as types of hotel, the date that the reservation was made, the number of children, the number of adults, the length of stays, the number of required parking spaces, and the number of special requests. It consists of one table with 32 columns and 119,390 rows.

It can be downloaded as a CSV file at the following [LINK](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand?select=hotel_bookings.csv)

---
## Prerequisites

A few packages that we expect installed - `scikeras` - essentially for ANN training (wrapping Keras Classifier for Scikit Learn Pipeline)

---
## Installation

No installation necessary! Just open it on Google Colab and you are ready to go!


---
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
## Video Explainer!

[![Link to YouTube Video](./assets/yt_thuumbnail.png)](https://www.youtube.com/watch?v=8nnSJDKhiQY)

---
## Current Owners:

Kulanit Hongsirikulkit - [LinkedIn](https://www.linkedin.com/in/kulanit-hongsirikulkit/)\
Yashash Gaurav - [Twitter](https://twitter.com/yashashgaurav) | [LinkedIn](https://www.linkedin.com/in/yashashgaurav/)

---
## Acknowledgments

Thanking [Prof. Raja](https://www.heinz.cmu.edu/faculty-research/profiles/sooriamurthi-raja) for encouraging us to meet deadline and present our findings on this dataset.

