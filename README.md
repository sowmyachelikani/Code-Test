
## Steps to run this app
* clone the repo and go to index.html
* run the python SimpleHTTPServer using command python -m SimpleHTTPServer 8000
* open the browser and run the app by hitting the URL 127.0.0.1:8000, this will redirect you to the index.html

# Feature Request Application
This app takes a user input from UI and process.

## Feature Request App
Build a web application that allows the user to create "feature requests".

A "feature request" is a request for a new feature that will be added onto an existing piece of
software. Assume that the user is an employee at IWS who would be entering this information after
having some correspondence with the client that is requesting the feature.  The necessary fields
are:

* **Title:** A short, descriptive name of the feature request.
* **Description:** A long description of the feature request.
* **Client:** A selection list of clients (use "Client A", "Client B", "Client C")
* **Client Priority:** A numbered priority according to the client (1...n). Client Priority numbers
should not repeat for the given client, so if a priority is set on a new feature as "1", then all
other feature requests for that client should be reordered.
* **Target Date:** The date that the client is hoping to have the feature.
* **Product Area:** A selection list of product areas (use 'Policies', 'Billing', 'Claims',
'Reports')

## Tech Stack Requirements
The following are requirements on the tech stack. This stack demonstrates mastery of tools our team favors.

* OS: Ubuntu
* Server Side Scripting: Python 2.7+ or 3.5+
* Server Framework: Flask or SimpleHTTPServer
* ORM: Sql-Alchemy
* JavaScript: KnockoutJS

