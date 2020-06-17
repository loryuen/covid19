# covid-19 dashboard
Website shows trends of COVID-19 cases in the US. 

Landing page:
*Plot built using D3.js and calling two separate APIs for national cases and state cases. Integrates interactivity (tooltips, buttons, dropdown) using D3.js so user can conduct analysis of data.
*Map created using leaflet and data (API) read in and parsed using D3.js. Popups boxes show number of COVID-19 cases and deaths for each county.


Internet Usage instructions:
Steps to run (Mac):

Start script:  python internet_scrape.py
Start mongodb: mongod --config /usr/local/etc/mongod.conf
Connect: http://localhost:5000
