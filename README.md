# Youtube-Statistics-Database
 This project discusses and implements a  database for major video streaming  platform called YouTube, this project store  and represent trending video statistics  based on different characteristics or  properties. Using this implemented  database, we can write queries to fetch  most liked videos, trending videos or any  video record. The dataset “Trending  YouTube Videos” is normalized to  represent different features or categories.

 A UI is also implemented for the same database to represent in the web using jam.py framework.


 Dataset links:
 
       a. YouTube Trending Video Dataset : https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset
 
       b. Trending YouTube Video Statistics and Comments: https://www.kaggle.com/datasets/datasnaek/youtube

The above mentioned datasets are normalized into 12 different tables as mentioned in provided Data model.

In order to Load project- you must have postgresql installed in your system.

To Download postgreSQL follow the mentioned link and choose your installer as required: https://www.postgresql.org/download/

To Install postgreSQL on windows follow this link: https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/

To Install postgreSQL on UNIX systems follow this link: https://www.postgresql.org/docs/current/installation.html

After your postgreSQL application is installed, you can log in to pgadmin using the credentials you provided during the installation process.

To load Database into your application:

         1. Create a Database by right clicking on the database option on left navigation panel.
         2. Provide the name of database in "database" column and click save.
         3. From left navigation righr click on the  newly created database and select "Restore".
         4. In the pop-up window - select "Custom or tar" in "Format" column and select the path of your sql file in "Filename" column.
         5. Click restore and give some time for the processes to load the database properly.
         6. Your database is now ready to use.
         7. To test functionality, try running SQL statements.

To load the Web UI for your application:

  1. You must have an recent version of python installed in your system.
  2. To install python in your system follow the instructions provided in this link: https://realpython.com/installing-python/
  3. After python is installed properly, install the Jam.py framework in your system.
  4. To install Jam.py in your system download latest release of jam.py :https://jam-py.com/
  5. If you are on a windows system : Extract the downloaded tar file and extract it.
  
                a. Navigate to the extracted file.
                b. Navigate to the mentioned path in file :"\jam.py-5.4.126.tar.gz\dist\jam.py-5.4.126.tar\jam.py-5.4.126\jam\project\".
                c. Run the "server.py" file to start the local host.
                d. Navigate to "http://127.0.0.1:8080/builder.html" in your browser.

  6. If you are on a UNIX system :
   
                a. To install and set up  jam.py follow these instructions: https://jam-py.com/docs/intro/install.html
                b. Follow the instrution in the provided link to create a project and start server.
                c. Navigate to "http://127.0.0.1:8080/builder.html" in your browser.		
  7. To run postgreSQL DB project in jam.py , you need to install a python dependency package.

                a. Open "terminal" in your system.
                b. Enter the command "pip install psycopg2" in your terminal to download and install it.
                c. To know more about psycopg2 follow this link: https://www.psycopg.org/docs/install.html								
  8. Connect your Database to the Web UI.

                a. Click on the "Database" button on the right navigation of "http://127.0.0.1:8080/builder.html" page.
                b. Select the DB type as "postgreSQl"
                c. Enter your DB name in Database field.
                d. Enter your server username and password in Login, Password fields respectively.
                e. Enter your host name and port number in Host, Port respectively.
                f. Click ok 
  NOTE: If you are running in your local system with defaults- Host:localhost, port:5432. and your database must be active to connnect to a server.
  
  9. To import the data into your web UI application.
  
                a. a. Click on the "Import" button on the right navigation of "http://127.0.0.1:8080/builder.html" page.
                b. A file window will be opened to select the zip file.
                c. Select the provided "Youtube Database Web UI- jam.py" zip file and click ok
                d. Your Data is uploaded into the UI now.
  
 10.Navigate to "http://127.0.0.1:8080/" in a web page and validate the data.
				
    







