
The London Node User Group Website

http://lnug.org

![Supporting 24PullRequests](https://img.shields.io/badge/Supporting-24PullRequests-red.svg)

# Install


How to run
----------
You can serve this with *any* static web server, but we'll use [mongoose](https://code.google.com/p/mongoose/).

1. `git clone git@github.com:lnug/lnug.github.io.git`
2. `cd lnug.github.io`
3. `npm install`
4. `npm run build`
3. `npm start`
4. go to http://localhost:5001


# Contributing

Please note the HTML files in the root of this repository are generated. 

If you want to change the templates look in the pages folder.

Please ensure that any changes you make persist after you run the update command documented below.


# Update

This site can be updated by running:

```
  npm run build
```

build pulls in the speakers from the github issues and updates the json files.

It then generates the html for the index and archive.html files.

Once you have built the site confirm it works locally before pushing to master as that will deploy the site.

Check the package.json file for a full list of commands you can run.


To run the update you need permission to execute the bin directory.

  chmod 775 ./bin/*
