# UFO Sightings
Project using Javascript, CSS, and HTML to format and display UFO Sighting data for a website.

## Table of contents
* [Overview of Project](#overview-of-project)
* [Results](#results)
* [Summary](#summary)

### Resources
- Data source: data.js
- Tools: Javascript, HTML, CSS, VSCode

## Overview of Project
My client Dana wanted me to create a website with UFO sightings and filters for different objects such as date, city, state, country, and shape of event.

- Website Filter Function

![Filters](/static/images/Filters.png)

## Results
The webpage is built to automatically update the table upon changes to the filters. Input must be formatted correctly, but the code will execute input as lowercase, so there won't be discrepancies based on capitalization. Filters are reset when the input for the object is changed.

## Summary
Some drawback of the design are that
- Users may prefer having a button
- Some of the table data is not formatted uniformally, making input ineffective
- Input that isn't an exact match will not show on the table - IE: Ingleside for city will not return ingleside (canada)

- Duration Differences in the Table

![Filters](/static/images/Table.png)
