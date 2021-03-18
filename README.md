# How to run, quick and dirty
Make sure you have your mongodb uri. "mongodb+srv://\[user]:\[password]@\[cluster].xhpae.mongodb.net/\[database]?retryWrites=true&w=majority". Make sure that there are no quotes! put this in dbrefresh under mongodb_uri and do NOT push this change.

Then run: 

```npm run db:refresh```

# 5e-database
![Build Status](https://github.com/bagelbits/5e-database/workflows/5e%20Database%20CI/badge.svg?branch=main)
[![Discord](https://img.shields.io/discord/656547667601653787)](https://discord.gg/TQuYTv7)

Holds the database for the D&D 5th Edition API at http://dnd5eapi.co/

Talk to us [on Discord!](https://discord.gg/TQuYTv7)

# How to run

## With Docker
You should be able to build locally and then run the local Docker image.

## Without Docker
First you need to make sure you have [MongoDB installed locally.](https://docs.mongodb.com/manual/installation/)
Also ensure that you have the [MongoDB Database tools installed.](https://www.mongodb.com/try/download/database-tools?tck=docs_databasetools)
Lastly, ensure that both are hooked up to your PATH variable and that you ```npm install```

You can load this data locally by running:
```
$env:MONGODB_URI="connectionString"; npm run db:refresh
```

# API Issues
If you see anything wrong with the API and not the data, please open an issue or PR over [here](https://github.com/bagelbits/5e-srd-api).

# Contributing
 * Fork this repository
 * Create a new branch for your work
 * Push up any changes to your branch, and open a pull request. Don't feel it needs to be perfect — incomplete work is totally fine. We'd love to help get it ready for merging.

# License
This project is licensed under the terms of the MIT license. The underlying material
is released using the [Open Gaming License Version 1.0a](https://www.wizards.com/default.asp?x=d20/oglfaq/20040123f)
