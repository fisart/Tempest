# Tempest

A.) Tempest Forecast is a PHP Script which needs the following preconditions :

1.) a Tempest Weather Station from Weather flow, 
2.) a Token you can generate here : https://tempestwx.com/settings/tokens/ 
3.) the Station ID from the weather station 
4.) IP Symcon which you can find here : https://www.symcon.de/

The Software will install itself and will create four html pages which give you details of the daily, hourly and immediate Weather condition 
(This Data comes from Weatherflow) plus a HTML table for the Device Data generated from the Tempest Station Skript (This Data comes from your local Tempest Weatherstation).
The Script allows for a large degree of customization. Those parameters can be stored locally and  used on the fly
The source of the Data is Weatherflow and you need an Internet Connection

The devleopment of the Software is discussed in the following Forum : https://community.symcon.de/t/tempest/51636

More details can be found in the header of the script 


B.) Tempest Station is a PHP Script which needs the following preconditions :

1.) a Tempest Weather Station from Weather flow, 
2.) IP Symcon which you can find here : https://www.symcon.de/
3.) a UDP Socket in IP Symcon with Port 50222

The Program receives realtime Data from the local Tempest Weatherstation and Stores the Data in a number of Variables
