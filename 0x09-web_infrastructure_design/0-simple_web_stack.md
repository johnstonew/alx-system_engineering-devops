## Questions
You must be able to explain what the issues are with this infrastructure:
## 1. SPOF
There is only one webserver hosting the application files and database. If the webserver fails the website stops functioning.
## 2. Downtime when maintenance needed (like deploying new code web server needs to be restarted)
Downtime is experienced when maintenance is needed, because there is only one code base used hence there is no other webserver that can serve the clients when the maintenance is on going.
## 3. Cannot scale if too much incoming traffic
Since one webserver is used, when there is too much trafic and the site becomes slow as the load is not distributed.
