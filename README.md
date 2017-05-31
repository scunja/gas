GAS = 

Web-app for aviation coordination dispatching and management

Hi everybody!

I'm learning to code with python and django and I would like to know wich technology it will be the most apropiated to my project.
I need to set up a web app with login for differents users in order to have access for the different features.
My app is concerning the private jets ground coordination so in the main page there will be a list of all the flights operating during the day with all the information concerning "aircraft type", "registration", "passengers in and out", "arrival from", "departure to", "tima arrival and departure", "agents operating the flights", "fuel info", catering info", "services require" (services to be putted in the bill)"

The global structure will be like this:

- MAIN PAGE with realtime flights overview (something like google sheet without all the formulas). in this page I need to have interactives cells eg.: right click on cell to have fonctions to be sended to different fonctions (send e-mail, put in the bill, information about the airport, etc...) -

- COORDINATION PAGE it contains the forms to add new flights for the next days or the same day with all the relatives informations concerning services, special request as limousine helicopters catering etc.... - 

- COMPANY PAGE it contains the list of all the companies with relative prices for a given service, eg.: COMPANY_A is paying 100€ for ground power unit but COMPANY_B is paying 80€ for the same service. All the contacts and the informations. It's a sort of database, well it is. -

- AIRCRAFT PAGE it contains all the informations concerning each aircraft operaing at X airport, those information are concerning the aircraft weight, the registration, the passengers details, etc.... - 

- BILLING SECTION it contains all the inforamtion concerning each service with the relative price. I would like to create a web app that will fit automaticly the bill details when the price for each service is already defined otherwise it can be filled manually for other services that have a variable price as the catering, the fuel, etc... - 


Actually i'm looking at something like google sheet with realtime update, each line is defined for a single flight (one aircraft) that have (in relatives columns) its aircraft type, registration, passengers in and out, arrival from, departure to, etc...
I really don't need all the excel fonctions i just need to create an interactive table the same as google sheet without all the formulas and fonctions. 
Eg.: I need to put a color on a cell to let everybody know that the aircraft is airborn, if the color is green the aircraft is airbon, white is on the ground, grey has landed. It will be the same with other cells; if the crew is on board of the aircraft the cell color is blue otherwise is white. whe the flight is finished all the line is grey, I need to put the color manually.
I would like to put the most of the fonctions in the MAIN PAGE, eg.: if I add a service for an aircraft like "lavatory service", i would like that it will be added automaticly in the bill, the same with other services but for some services from third part company as catering, fuel etc... the price it will be added in the bill manually.

So the project need a database, a web interface with login for different users and pages for specific features: Dispatchin, administration, coordination, etc...

If you could help me to find out which language I need to use for this project and if you could tell me how to start it will be much appreciated. 

At the end of this project the intention is to monthly rent the web-app to all the gournd handling that operate privates jets.
If someone is iterested to share this project with me please do not hesitate to contact me.

I hop that you have all the informations that you need...

Thank you for your help!

scunja
