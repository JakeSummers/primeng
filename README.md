# PrimeNG
UI Components for AngularJS 2

See [PrimeNG homepage](http://www.primefaces.org/primeng) for live showcase and documentation.

![alt text](http://www.primefaces.org/images/primeng.png "PrimeNG")

# Instructions on running:

Based loosely on the (outdated) instrustions here: https://github.com/primefaces/primeng/wiki/Building-From-Source

Pull the repo: 
	
	# Go somewhere: 
	cd ~/reposOther

	# Checkout the repo:
	git clone git@github.com:primefaces/primeng.git

Do these things once: 

	npm install typings --global
	npm install webpack-dev-server --global

Do these things to build & start the webapp:

	cd ~/reposOther/primeng

	# Manual Step: 	
	# Now update the package.json to include dependancies!
	# The package.json on this branch has been updated.  See that!

	echo "npm cache clean"
	npm cache clean

	echo "npm prune"
	npm prune

	echo "npm install"
	npm install

	echo "typings install"
	typings install

	echo "npm start"
	npm start


Then you can access it here (with status): 

	http://localhost:8080/webpack-dev-server/

Or here:

	http://localhost:8080/
