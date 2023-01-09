# Market Attribution using Market Mix Modelling 

## Why is this relevant?
Market Mix Modelling(MMM) is a statistical technique used to estimate the impact of marketing activities and hence helps optimize marketing spend for the future. Such 
a modelling technique considers various marketing and non-marketing factors that might help in finding the signal among the noise.

## About this implementation
MMM at its core is regression model where you consider the sales as the dependent variable and regress it against factors that we are trying to break the contribution 
out to- the independent variables. These could be a bunch of factors mainly divided into 2 major categories:

* Base Drivers:
This are non-marketing dependent variables which would influence the sales irrespective of the marketing activities. Factors like GDP, growth rate, seasonality, holidays 
can be considered as base drivers.

* Incremental Drivers:
These are marketing dependent variables that have an impact on the sales. These can be categorized in 2 major categories of Digital( FB, Instagram, Snapchat) or 
Non-Digital(OOH, newspaper). Within Digital marketing, there can be 2 further subdivisions of activities as
1)Marketing activities which raises awareness for the brand(For e.g. TV)
2)Marketing activities which guide the user to the site by attaching clickable links which take the user to the site(For e.g. FB, Instagram).
