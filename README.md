JobPortal Application

Overview

This JobPortal application is an Angular project designed to connect employers with potential job seekers. It features a modern user interface where users can view, post, and apply for job vacancies.

Features
User Authentication: Secure login functionality.
Job Offers Listing: View a list of available job offers.
Job Offer Details: Access detailed information about each job offer.
Post a Job Offer: Employers can post new job vacancies.
Delete a Job Offer: Remove existing job offers from the listing.
Installation

To run this application locally, follow these steps:

Clone this repository.
Navigate to the project directory and install dependencies with npm install.
Start the development server with ng serve.
Open http://localhost:4200/ in your web browser.
Usage

The application is split into several main components:

HomeComponent: The landing page that lists all job offers.
LoginComponent: Handles user authentication.
NewOfferComponent: Allows employers to post new job offers.
OfferComponent: Displays detailed information about a specific job offer.
OffersComponent: Provides an interface for managing job offers.
Notes

The backend API used by this application is provided by an educational institution for development and learning purposes and is therefore not included in this repository.
All interactions with the API are handled through the ApiService.