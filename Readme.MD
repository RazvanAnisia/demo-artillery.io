### Load testing socket server
* First you need to install Artillery.io globally on your machine. Run: `npm i -g artillery`
* Clone the repo.
* Inside the `load-test.yaml` file set target to your own machine with the correct port fort the socket server:
 `wss://domain:9008`
* To run the script run `artillery run load-test.yaml`
 There is a `users.csv` attached, which was exported from pgAdmin.It is used to get the ids of users so the client can emit the "room" event and their user id.
Artillery docs :https://artillery.io/ <br>
Really good article: [link](https://medium.com/@kyle_martin/load-testing-socket-io-web-applications-and-infrastructure-3e96011898e0) 
