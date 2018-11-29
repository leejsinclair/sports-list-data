# List of sports from WikiPedia

## Installation

```
npm install sports-list-data --save
```

## Usage

```
let sports = require('sports-list-data')
let wrestlingSports = sports.filter( sport => sport.indexOf('wrestl')>=0 )
```