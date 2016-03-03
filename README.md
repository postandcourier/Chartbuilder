Chartbuilder :chart_with_upwards_trend:
============

Chartbuilder is a front-end charting application that facilitates easy creation of simple beautiful charts.

Chartbuilder is the user and export interface. [D4](https://github.com/heavysixer/d4) is the default charting framework.
This version of Chartbuilder is a fork from the version that powers all chart creation on [Atlas](http://atlas.qz.com), a
charting platform developed by Quartz.


Getting started with Chartbuilder
---------------------------------
If you are not interested in customizing the styles of your charts use the hosted version: http://quartz.github.io/Chartbuilder

To work on the Chartbuilder code, first download the project and install
dependencies:

####Download via github
1. Make sure you have a recent version of [node.js](https://github.com/joyent/node/wiki/Installation) (0.12 or above) (or [io.js](https://iojs.org/en/index.html))
2. [Download source](https://github.com/Quartz/Chartbuilder/archive/master.zip) (and unzip or clone using git)
3. from the terminal navigate to the source folder (on a Mac: `cd ~/Downloads/Chartbuilder-master/`)
4. Install the dependencies automatically by running `npm install`
5. Start the included web server by running `npm run dev`
6. Point your browser to [http://localhost:3000/](http://localhost:3000/)
7. When you're done developing, [build and deploy](docs/deploying.md) your Chartbuilder!

####Making a chart with Charbuilder
* [How to make a line chart with time series data](tutorials/basic-chart.md)
* [How to make a bar chart with ranking data](tutorials/bar-chart-with-ranking-data.md)
* [How to make a column chart with ordinal data](tutorials/column-chart-ordinal-data.md)

####Customizing your Chartbuilder
* [Getting to know the Chartbuilder code](docs/01-introduction.md)
* [Customizing chartbuilder](docs/02-customizing-chartbuilder.md)
* [Test things out](docs/testing.md)
* When you're done developing, [build and deploy](docs/deploying.md) your Chartbuilder!
* Keep your customized version [in sync with the master](docs/git-workflow-forks.md)

### Documentation

* The [Chartbuilder API docs](http://quartz.github.io/Chartbuilder/api-docs/)
document most of the React components, classes, and utilities in the code base.

##### Documentation for Chartbuilder's dependencies:
* [D3](https://github.com/mbostock/d3/wiki)
* [D4](http://visible.io/docs.html)
* [React](https://facebook.github.io/react/docs/getting-started.html)

