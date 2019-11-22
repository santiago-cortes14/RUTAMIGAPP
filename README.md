# Rutamigapp

Rutamigapp is an web page where the school buses valet can care on childs  and the escolar bus have a permanent comunication with the family of kids. 

In this repository you can find:
  - Source codes
  - Data
  - Hardware requeriments
  - Software requeriment
  - How to install
  - How to run
  - Authors

# Hardware requeriments:

  - [Arduino UNO](https://www.vistronica.com/board-de-desarrollo/arduino/board/arduino-uno-r3-compatible-detail.html)
  - [Module GPS gy-Neo6mv2](https://www.vistronica.com/comunicaciones/modulo-gps-gy-neo6mv2-con-memoria-eeprom-detail.html)
  - Internet plan from 5 GB onwards (for the page)

# Hardware requeriments:

  - Python 3(serial, xlsxWriter, pandas, time, smtplib, MIMEMultipart, MIMEText, Flask, Flask-WTF, geopy, numpy, openpyxl, pyserial, requests)

# How to install
1. The first step is to install all libraries, you need to have this in python to run the website. The order does not matter:
    sudo apt-get upgrade python3
    sudo apt-get install python3
    sudo apt-get install python-pip
    sudo apt-get update
    sudo apt-get install python-requests
    sudo apt-get install python-xlsxwriter
    python pip install pyserial
    sudo pip install flask
    sudo pip install numpy
    sudo pip install pandas
    sudo pip install geopy
    sudo pip install Flask-WTF
2.  Download the folder called rutamigapp, there you can find the source code, templates, and html's codes.

# How to run
Now, open terminal on ubuntu with command ctr+alt+t, go to the folder rutamigapp, for example, if the folder is on downloads, you have to go there in terminal with command "cd Download/rutamigapp", and then your are on the folder to run the source python code called main.py, to run this write on terminal: python main.py.

# Authors
Universidad de Ibagué Programa de Electrónica Asignatura: Electrónica Digital III A2019

- [Santiago Cortes](mailto:2420171013@estudiantesunibague.edu.co)
- [Valentina Gomez](mailto:2420171072@estudiantesunibague.edu.co)
- [Harold F Murcia](http://haroldmurcia.com/) - Tutor
