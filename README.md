![GitHub contributors](https://img.shields.io/github/contributors/NischalKash/TripSage_SENG2020_Phase2)
![GitHub language count](https://img.shields.io/github/languages/count/NischalKash/TripSage_SENG2020_Phase2)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/NischalKash/TripSage_SENG2020_Phase2)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![Build Status](https://travis-ci.org/NischalKash/TripSage_SENG2020_Phase2.svg?branch=main)](https://travis-ci.org/NischalKash/TripSage_SENG2020_Phase2)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![codecov](https://codecov.io/gh/NischalKash/TripSage_SENG2020_Phase2/branch/main/graph/badge.svg?token=6X0OPSX1VY)](undefined)
[![DOI](https://zenodo.org/badge/306192455.svg)](https://zenodo.org/badge/latestdoi/306192455)
# TripSage
The only Itinerary planner, you will ever need

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/yO8Xo6UvWUQ/0.jpg)](https://www.youtube.com/watch?v=yO8Xo6UvWUQ)
</br>
</br>
</br>
## Hello! Welcome to TripSage! </br>
### Why TripSage? </br>
Travelling to a new country can be stressful. Couple that with COVID, almost impossible. But the mental health benefits of travelling to new and exciting places doesn’t have to be so risky and expensive. </br>
TripSage is a website that plans trips for users inside their home country. Simply, pick a destination state and cities, and you’ll be directed to your ideal trip. We have plans to include tags for: COVID -19 hotspots, whether the location is indoors, and the general population at that location to make sure users can practice safe travelling.</br>
</br>
A new way of life doesn’t have to mean you can’t travel.</br>
Explore the new of travelling with TripSage.</br>
</br>
### Tools used </br>
We use Django, SQLite3, HTML, CSS, and Javascript. </br>
</br>
### New to Django? </br>
Check out the basics: https://docs.djangoproject.com/en/3.1/intro/tutorial01/ </br>
The first 3 tutorials should be enough to get you started with our project. </br>
</br>
Want a more in-depth look at server-side development? </br>
Check out the basics: https://developer.mozilla.org/en-US/docs/Learn/Server-side </br>
This tutorial also covers Django.</br>
</br>
### How to Run: </br>
1. Clone the project repo onto your local machine https://github.com/NischalKash/TripSage_SENG2020_Phase2.git
2. Run `pip install -r requirements.txt`
3. Execute manage.py using the command `python3 manage.py runserver` at 'Phase2_TripSage/tripsage/'. This runs the Django server such that we can open the webUI for the project on the browser.
4. Next, open your browser and type in `localhost:8000` in the search bar to open the webUI of the application.
5. The UI typically looks as shown below and here you can enter the start and destination of your choice and look at the results based on your specifications.
</br>

### Home page of TripSage App:

![1](https://user-images.githubusercontent.com/65666095/97259147-735d0d00-17f0-11eb-9ef3-e78cecf28be9.jpeg)

### Route map for trip from Raleigh to Seattle

![2](https://user-images.githubusercontent.com/65666095/97259330-f2524580-17f0-11eb-933c-09cceca4663f.jpeg)

![3](https://user-images.githubusercontent.com/65666095/97259498-478e5700-17f1-11eb-95bc-620563edc020.jpeg)

### Result of adventurous places to visit between the jouney from Raleigh to Seattle

![4](https://user-images.githubusercontent.com/65666095/97259512-507f2880-17f1-11eb-931e-d11dfb727dce.jpeg)

### You can also review places to visit at any intermeditiary city on the journey

![5](https://user-images.githubusercontent.com/65666095/97259595-89b79880-17f1-11eb-8aae-76911ad5627d.jpeg)

### Project Structure:</br>
(Disclaimer: Need some knowledge of Django to understand Project structure, please go through above resources if needed)</br>
Phase2_TripSage/</br>
&nbsp; tripsage/</br>
&nbsp;&nbsp; tripsage/ </br>
&nbsp;&nbsp;&nbsp; urls.py </br>
&nbsp;&nbsp; planner/ </br>
&nbsp;&nbsp;&nbsp; templates </br>
&nbsp;&nbsp;&nbsp;&nbsp; directions.html </br>
&nbsp;&nbsp;&nbsp;&nbsp; home.html </br>
&nbsp;&nbsp;&nbsp;&nbsp; recommendations.html </br>
&nbsp;&nbsp;&nbsp; views.py</br>
&nbsp;&nbsp;&nbsp; functionaltesting.py</br>

</br>

### Phase 1 Completed Deliverables

<ul>
  <li>Setup design and architecture of project (Django MVC)</li>
  <li>Implemented call to Google Maps API to retrieve location details.</li>
  <li>Setup Database Models required for the application. </li>
  <li>Designed UI Mockups for the front end of the application.</li>
</ul>

### Phase 2 Planned Deliverables
<ul>
<li>Improve the front-end of the design</li>
 <li>Addition of style checkers for codebase</li>
  <li>Adding Formatting guide and Code coverage to the code</li>
  <li>Implementing core functionalities using the UI Mockups as a reference</li>
</ul>
