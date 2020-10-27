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
1. Run `pip install -r requirements.txt`
2. Clone the project repo onto your local machine https://github.com/NischalKash/TripSage_SENG2020_Phase2.git
3. Execute manage.py using the command `python3 manage.py runserver` at 'Phase2_TripSage/tripsage/'. This runs the Django server such that we can open the webUI for the project on the browser.
4. Next, open your browser and type in `localhost:8000` in the search bar to open the webUI of the application.
5. The UI typically looks as shown below and here you can enter the start and destination of your choice and look at the results based on your specifications.
</br>
![image](https://user-images.githubusercontent.com/65666095/97241847-aab7c380-17c8-11eb-9709-e0a604a3e597.png)</br>
### Project Structure:</br>
(Disclaimer: Need some knowledge of Django to understand Project structure, please go through above resources if needed)</br>
TripSage/</br>
&nbsp; tripHome/</br>
&nbsp;&nbsp; models.py </br>
&nbsp;&nbsp; views.py </br>
&nbsp;&nbsp;&nbsp; urls.py </br>
&nbsp;&nbsp;&nbsp; templates/ </br>
&nbsp;&nbsp;&nbsp;&nbsp; index.html </br>
&nbsp;&nbsp;&nbsp;&nbsp; base_generic.html </br>
&nbsp;&nbsp;&nbsp;&nbsp; result.html</br>
&nbsp;&nbsp;&nbsp; static/ </br>
&nbsp;&nbsp;&nbsp;&nbsp; js/ </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; custom.js </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; resultsPage.js </br>
</br>

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
