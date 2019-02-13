# Car-trade
Car-trade is a web application that enables users to trade cars.

**Usage**
### Prerequisites

```
Html5, CSS3, python, Django, PSQL
```

##  Getting Started  ##

  1. Clone this repository:
  
    `git clone https://github.com/katherine95/Car-trade.git`

  2. Change the directory into the project directory:

    `cd Car-trade`

  2. Fetch all origin to get all branches:

    `git fetch origin`

  3. Checkout to `develop` branch:

    `git checkout develop`

  4. Create a virtual environment to allow you to manage separate package installations for different projects:

    `virtualenv -p python3 venv`

  5. Activate virtual environment:

    `source venv/bin/activate`

  6. Install requirements(all packages that the project needs):

    `pip install -r requirements.txt`

  7. Start server

    `python manage.py runserver`

  8. Setup database:

    `sudo -u postgres psql`
    `CREATE DATABASE dbname;`

  9. Configure database in projectname/settings.py file(dbname,user,password and maybe port if necessary):

  10. Create an admin user:

    `python manage.py createsuperuser`

  11. Start server and head over to admin url on browser `localhost:8000/admin`:

    `python manage.py runserver`

