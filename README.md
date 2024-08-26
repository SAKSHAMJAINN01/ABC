### Project Description
The Student Community Service project creates a versatile student volunteer web application that can be adopted by any university. It addresses the diverse struggles that college students commonly face, providing a centralized platform for students to earn service hours, engage in social activities, and contribute to their community while earning recognition points.

By allowing account registration for students with valid university email addresses, this service ensures safety and accountability. The product distinguishes itself from general service board websites by offering free, peer-to-peer assistance within a secure volunteer network.

### Challenge Statement and Solution
Challenge
College students, particularly first-year and first-generation students, often struggle with managing new challenges and environments across various universities. These difficulties can impede their learning experience and overall college journey.

### Solution
The Student Community Service platform facilitates peer support among college students. It enables students who have overcome similar challenges to share their experiences and provide assistance. The website allows students to earn volunteer hours by offering services such as meal planning, resume reviews, campus food bank assistance, and time management coaching.

This solution is designed to be adaptable for implementation at any university, creating a scalable model for student-led community support in higher education institutions nationwide.


### Project setup and running

0. python version: Python 3.12.1

1. Install postgresSQL:
    - On Windows: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
    -  On Mac, run this command in the terminal to install postgres: `brew install postgres`

2. Run following commands in the Windows:
- `pip install virtualenv`
- `python -m virtualenv <your_env_name>`
- `.\<your_env_name>\Scripts\activate`
- `pip install -r requirements.txt`
- `python manage.py makemigrations` 
- `python manage.py migrate`     
- `python manage.py runserver`
- Copy the *http://...* link in your browser and run.
- When done running. Close the environment: `deactivate`

3. Run following commands in the Mac:
- `pip3 install virtualenv`
- `python3 -m venv <your_env_name>`
- `source <your_env_name>/bin/activate`
- `pip3 install -r requirements.txt`
- `python3 manage.py makemigrations` 
- `python3 manage.py migrate`     
- `python3 manage.py runserver`
- Copy the *http://...* link in your browser and run.
- When done running. Close the environment: `deactivate`
