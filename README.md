# Agriculture-Harvest-Management-Web

A website to develop a market for the farmers, where the farmers can feed their harvest and company can buy them.

-------------------------------------------------------------------------------------------------------------------
How to run this:

extract the zip under localhost
makesure to rename the extracted folder as "market"


change database variables

market/db.php
market/admin/reps/connect.php
market/data.php
market/admin/charts/data.php & data2.php
market/admin/tb/db.php


dump data into "vmarket" databse via sql

*optional* - change google map api keys if needed.(do not share current api key with anyone :()


login details : 

username : pass
admin : 123
doa : 123
keels : 123
123 : 123 > farmer

---------------------------

changing db var 

ex: 
    <?php

    $host = "127.0.0.1"; --> dont change this unless ur server is not local
    $username = "root";  --> authorized username of the databse
    $pass = "localserver2020"; --> if there's no passwords for ur db : replace whole line with this : $pass = "";
    $database = "vmarket"; --> name of the created db

    $db = mysqli_connect($host, $username, $pass, $database); --> do not change this data line

    ?>


example 2 :

		            (1)	     (2)     (3)              (4)
$conn = mysqli_connect("127.0.0.1","root","localserver2020","vmarket");

change these values according to ur db (same values as above ex)
