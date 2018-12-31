# dashing-js

## Getting Started

1. Install from npm

```shell
$ npm install -g pp-dashing-js
```

2. Generate a new project

```shell
$ dashing-js new sweet_dashboard_project
```

3. Change your directory to sweet_dashboard_project and install required modules

```shell
$ cd sweet_dashboard_project && npm install
```

4. Start the server!

```shell
$ dashing-js start
```

5. Point your browser at http://localhost:3030/ and have fun!

***

Every new Dashing project comes with sample widgets & sample dashboards for you to explore. The directory is setup as follows:


Run `dashing-js` from command line to find out what command line tools are available to you.

## Deployment
dashing-js is setup to be easily deployed on a Joyent Node SmartMachine. This means that:

1. The version of Node is defined in package.json
2. The main script to run is server.js
3. The web server port is pulled from process.env.PORT

"# pp-dashing-js" 
