# Squid

Squid is a small cool tool that give you a quick access to all your Github repositories, straight from from your Mac OS X menu bar.

### Builded on top of:

* [nw.js](http://nwjs.io/)
* [react.js](https://facebook.github.io/react/)
* [Github API](https://developer.github.com/v3/)

### Contributors:

* [Didier Forest](https://github.com/welcometothesky) for the cool design 
* [Adrien Griveau](https://dribbble.com/adrien-griveau) for the nice icons
* [e-Founders](http://www.e-founders.com) for the time

## Dev Env

After you clone this repository on your workstation, follow these 4 steps to run Squid into developer mode:

* first install Node.js packages:

		npm install
		
* into `package.json` set `debug` property to true (optional but useful)
	
* finaly run Gulp command

		gulp
		
* In a new terminal window run:

	npm start
	
## Build app

Run these command

	sh build.sh
	
The freshly builded app will be available into the `release` folder.

## Roadmap

See the [roadmap](https://github.com/michael-lefebvre/Squid/milestones) future developments.


## Personal reminders / Troubleshoots

if gulp throw a `'Error: EMFILE, open '/path/to/package.json' error`, run the following command: 

	ulimit -S -n 2048 
