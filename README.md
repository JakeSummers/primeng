# PrimeNG
UI Components for AngularJS 2

See [PrimeNG homepage](http://www.primefaces.org/primeng) for live showcase and documentation.

![alt text](http://www.primefaces.org/images/primeng.png "PrimeNG")

# Jake's Instructions on running:

Based loosely on the (outdated) instrustions here: https://github.com/primefaces/primeng/wiki/Building-From-Source

Pull the repo: 
	
	# Go somewhere: 
	cd ~/reposOther

	# Checkout the repo:
	git clone git@github.com:primefaces/primeng.git

Do these things once: 

	npm install typings --global
	npm install webpack-dev-server --global

Do these things before starting the webapp: 

	cd primeng
	npm install
	typings install
	npm run

Then you can access it here (with status): 

	http://localhost:8080/webpack-dev-server/

Or here:

	http://localhost:8080/
