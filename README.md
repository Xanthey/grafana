# Grafana
<img src="https://docs.checkmk.com/latest/images/grafana_logo.png" width="200px"><img src="https://influxdata.github.io/branding/img/downloads/influxdata-logo--symbol--pool-alpha.png" width="200px"><img src="https://cdn.freebiesupply.com/logos/thumbs/2x/influxdb-logo.png" width="250px"><BR>
Grafana with Telegraf and InfluxDB

# Things to take note of:
* Read these files, you will see several things that need to be changed for your install.
* Examples would be server names, usernames, passwords, etc.
* I did my best to make it obvious what to change, and to what.
* Once again, read the files... once all of that is changed all you have to do is init the compose and you're good.

----

# Installation Notes:
* Copy all files to a directory of your choosing
> I use home/{username}/docker/{project-name}/
* Open the ```env``` file and edit appropriately
> If you need to generate a hex key head to https://www.browserling.com/tools/random-hex
* Open the ```docker-compose.yml``` file and edit appropriately
> Please make sure to note the ports you choose and any server addresses you may need to change.
* Open a terminal in this directory
* ``` sudo docker-compose down ```
* ``` sudo docker-compose up -d ```
* Visit  http://127.0.0.1:777 in your browser. (Substitute the port for one that you configured, if you changed it.)
* Continue setup from here, within your browser.
> **Configuring Grafana, Telegraf, Prometheus, InfluxDB, and your dashboards is outside the scope of this readme.**
