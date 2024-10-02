# Prerequisites
* Python: Version 3.12.0
* PostgreSQL: Version 16.1
* API Key: Generated from 2factor.
* App Password: Generated from your Google account. Refer to Google's guide on App Passwords.

# Setup Instructions

1. Create the Database:
* In PostgreSQL, create a database named Digital_Voting.

2. Configure Settings:
* Open settings.py and update the following:
    - DB USER and DB PASSWORD for your PostgreSQL credentials.
    - EMAIL_HOST_USER and EMAIL_HOST_PASSWORD for your email service.
    - TWO_FACTOR_API_KEY with the API key generated from 2factor.

3. Install Dependencies:
* Run the following command to install project dependencies:
    - pip install -r requirements.txt

4. Apply Migrations:
* Run the migrations to set up the database tables:
    - python manage.py migrate

5. Create Superuser:
* Create a superuser for admin access:
    - python manage.py createsuperuser

# Running the Project

1. Start the Django development server:
    - python manage.py runserver

2. Log in to the Django Admin Panel using the superuser credentials you created, then:
    - Add the superuser details to the EC_Admins group.


# How to Use

1. Admin Tasks:

    - Navigate to the Login Page, select Login as Admin, and:
    - Add voter details.
    - Add candidate details.
    - Generate an election.
    - Log out from the Admin dashboard.
        
2. Voter Registration:
    - Click on Register and fill out the voter registration form.
    - Record and upload a 5-10 second video for face registration.

3. Voting Process:

    - Log in as a Voter and:
    - Select the ongoing election and choose a candidate.
    - Record and upload a 5-10 second video for face verification.
    - Enter the SMS OTP and Email OTP for two-factor authentication.

4. Election Completion:

    - Log in as Admin to complete the election and generate the results.


                                
                                
                                -- Sangangouda Patil --