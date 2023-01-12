# Capstone: Restaurant Reservation System

<h3>Deployed Demo</h3>
<hr>
<a href ="https://reservation-front-end.onrender.com">Restaurant Reservation System</a>

<p>This is a full stack capstone project for Thinkful's software engineering bootcamp. The following scenario was given as a prompt:</p>


> You have been hired as a full stack developer at _Periodic Tables_, a startup that is creating a reservation system for fine dining restaurants.
> The software is used only by restaurant personnel when a customer calls to request a reservation.
> At this point, the customers will not access the system online.

<h3>User Stories</h3>
<hr>


### US-01 Create and list reservations

Create a new reservation when a customer calls<br/>
so that I know how many customers will arrive at the restaurant on a given day.

![dashboard](https://github.com/malgron/Restaurant-Reservation/blob/main/readme-images/dashboard.PNG)


### US-02 Create reservation on a future, working date

As a restaurant manager<br/>
I only want to allow reservations to be created on a day when we are open<br/>
so that users do not accidentally create a reservation for days when we are closed.<br/>

![future reservation error testing](https://github.com/malgron/Restaurant-Reservation/blob/main/readme-images/user_story_01.PNG)

### US-03 Create reservation within eligible timeframe

As a restaurant manager<br/>
I only want to allow reservations to be created during business hours, up to 60 minutes before closing<br/>
so that users do not accidentally create a reservation for a time we cannot accommodate.

![new reservation](https://github.com/malgron/Restaurant-Reservation/blob/main/readme-images/new_reservation.PNG)

### US-04 Seat reservation

As a restaurant manager, <br/>
When a customer with an existing reservation arrives at the restaurant<br/>
I want to seat (assign) their reservation to a specific table<br/>
so that I know which tables are occupied and free.

![seat reservation](https://github.com/malgron/Restaurant-Reservation/blob/main/readme-images/search02.PNG)

### US-05 Finish an occupied table

As a restaurant manager<br/>
I want to free up an occupied table when the guests leave<br/>
so that I can seat new guests at that table.<br/>

### US-06 Reservation Status

As a restaurant manager<br/>
I want a reservation to have a status of either booked, seated, or finished<br/>
so that I can see which reservation parties are seated, and finished reservations are hidden from the dashboard.

### US-07 Search for a reservation by phone number

As a restaurant manager<br/>
I want to search for a reservation by phone number (partial or complete)<br/>
so that I can quickly access a customer's reservation when they call about their reservation.<br/>

![reservation search](https://github.com/malgron/Restaurant-Reservation/blob/main/readme-images/search01.PNG)


### US-08 Change an existing reservation

As a restaurant manager<br/>
I want to be able to modify a reservation if a customer calls to change or cancel their reservation<br/>
so that reservations are accurate and current.


