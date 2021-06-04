# KLTN

# SETUP

# STEP 1: Pull images
	* docker pull hauet2017/gateway:1.0.0
	* docker pull hauet2017/user-service:1.0.0
	* docker pull hauet2017/tour-service:1.0.0
	* docker pull hauet2017/car-hotel-service:1.0.0
	* docker pull hauet2017/frontend-client:1.0.0
	* docker pull hauet2017/frontend-admin:1.0.0
# STEP 2: Clone repository
	* git clone git@github.com:ha1999/KLTN.git

# STEP 3: Edit docker-compose.yml


# STEP 4: Run docker-compose.yml

	* docker-compose up - run container from images
	* docker-compose down - stop and remove containers are created from docker-compose
# STEP 5: View result

	* Edit /etc/hosts in linux or macos
		- Add to file a line: `127.0.0.1 www.viettraveluet-linux-ha.com`
	* Go to browser open [http://localhost:3005](http://localhost:3005) for client.
	* Go to browser open [http://localhost:3000](http://localhost:3000) for employee and admin.
 



