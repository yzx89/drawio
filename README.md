[![Build Status](https://travis-ci.org/jgraph/drawio.svg?branch=master)](https://travis-ci.org/jgraph/drawio)

About
-----
[draw.io](https://www.draw.io) is an online diagramming web site that delivers the source in this project. It is a production-grade deployment, with full [security process](https://github.com/jgraph/security-privacy-legal).

draw.io is a client-side, static web application. There is no user authenication or data storage concept in this repo. The online version stores data in mainstream cloud storage options, currently Google Drive, OneDrive, Dropbox, GitHub, Gitlab or Trello.

There are a range of [integrations into other tools](https://about.draw.io/integrations-ecosystem/), some by this core team, some by third-parties.

draw.io has an official [Docker image](https://github.com/jgraph/docker-drawio) for local deployment, as well as [Desktop versions](https://github.com/jgraph/drawio-desktop) for MacOS, Linux and Windows.

draw.io uses the [mxGraph library](https://github.com/jgraph/mxgraph) as the base of the stack, with the [GraphEditor example](https://github.com/jgraph/mxgraph/tree/master/javascript/examples/grapheditor) from mxGraph as the base of the application part. The mxGraph library build used is stored under /etc/mxgraph/mxClient.js.

License
-------
draw.io is licensed under the Apache v2.

Development
-----------

A development guide is being started on the GitHub project wiki. There is a [draw.io](http://stackoverflow.com/questions/tagged/draw.io) tag on Stack Overflow currently, please make sure any questions adhere to their guidelines for question.

The [mxGraph documentation](https://jgraph.github.io/mxgraph/) provides a lot of the docs for the bottom part of the stack. There is an [mxgraph tag on SO](http://stackoverflow.com/questions/tagged/mxgraph).

Running
-------
One way to run draw.io is to fork this project, [publish the master branch to GitHub pages](https://help.github.com/categories/github-pages-basics/) and the [pages sites](https://jgraph.github.io/drawio/src/main/webapp/index.html) will have the full editor functionality (sans the integrations).

The full packaged .war of the client and servlets is built when the project is tagged and available on the [releases page](https://github.com/jgraph/draw.io/releases).

Supported Browsers
------------------
draw.io supports IE 11, Chrome 32+, Firefox 38+, Safari 9.1.x, 10.1.x and 11.0.x, Opera 20+, Native Android browser 5.1.x+, the default browser in the current and previous major iOS versions (e.g. 11.2.x and 10.3.x) and Edge 23+.
