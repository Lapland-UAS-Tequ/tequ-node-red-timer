tequ-node-red-timer
=====================

Timer. Release every 1-3600 seconds.

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install Lapland-UAS-Tequ/tequ-node-red-timer

## Information

## Timer for data acquisition purposes.

Node is developed to inject timestamp every configured interval.

For example if interval is configured to 5 minutes, node releases 12:00:00 then 
12:05:00, 12:10:00 etc. 

Accurate to one second. Milliseconds reading can vary. 
