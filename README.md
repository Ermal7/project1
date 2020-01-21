# HOW TO USE
1. In a terminal window, navigate into your project1 directory.
2. Run ( pip3 install -r requirements.txt ) in your terminal window to make sure that all of the necessary Python packages (Flask and
      SQLAlchemy, for instance) are installed.
3. Set the environment variable FLASK_APP to be application.py. On a Mac or on Linux, the command to do this is
      ( export FLASK_APP=application.py )
4. You may optionally want to set the environment variable FLASK_DEBUG to 1,
      ( FLASK_DEBUG=1 )   which will activate Flask’s debugger and will automatically reload your web application whenever
      you save a change to a file.
5. Set the environment variable DATABASE_URL to be the URI of your database,
    ( export DATABASE_URL="postgres://bghznsemeoetwb:c6d23f0d70c0d3adc488bad96c1b5e642d4c5413e4dcd695aab054b861051f9b@ec2-46-137-91-216.eu-west-1.compute.amazonaws.com:5432/d56kqct6ampiv1" ) .which you should be able to see from the credentials page on Heroku.
6. Run ( flask run ) to start up your Flask application.

# When You first Create the Database
------------------- LOCAL DATABASE CONNECTION----------------------------------------------------------------
   i. Start database => sudo service postgresql start
   ii.Create Database => sudo -u postgres psql -c "CREATE DATABASE nameofthedatabase;"
   iii.Access Database through terminal => psql nameofthedatabase
   iv.Create Tables and SQL commands are found on 'createtables.sql' file inside the 'project1' directory.
   v. run 'python import.py' to import the files to the database.
-------------------------------------------------------------------------------------------------------------
# How the Python Flask Program Works
