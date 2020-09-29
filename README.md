# Serve-transmission-docker-compose
* Go to `/var` and create directory named wwww `cd wwww` ( [https://github.com/mohammadranjbar/serve-transmission-docker-compose/blob/master/docker-compose.yml](https://github.com/mohammadranjbar/serve-transmission-docker-compose/blob/master/docker-compose.yml))
* Change ownership of this directory `chown $USER:$USER www`
* `docker-compose up`
* Make sure the `9090` and `9091` ports are not blocked by your firewall
* You can login to transmission in this address `YOUR_IP:9091` and the user pass is the thing that are passed in docker-compose
* You can reach The downloaded file in `YOUR_IP:9090`
