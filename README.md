# FHIR API Viewer
This is a simple web application that allows users to call FHIR APIs and view the returned FHIR data.

## Features
Call any public FHIR API by entering the URL
Displays the raw JSON response from the API
Parses the JSON and shows the data in a readable format
Supports FHIR resources like Patient, Observation, Medication, etc.
Usage
Enter the URL of any public FHIR API endpoint
Click "Call API"
The raw JSON response will be displayed
The parsed/formatted data will be shown below the raw JSON

For example, you could enter:


> https://hapi.fhir.org/baseR4/Patient
This will call the public HAPI FHIR server and return Patient resources.

## Implementation
This app is built using:

React for the frontend UI
Axios for making the FHIR API calls
Bootstrap for styling

The main components are:

ApiCallForm - Form to enter the FHIR API URL
ApiResponse - Displays the raw JSON response
FormattedData - Parses the JSON and formats it to be human-readable
The app calls the API using Axios, parses the data, and displays it using React components.

## Running Locally
To run this app locally:

Clone this repo
Run npm install
Run npm start
The app will be running on http://localhost:3000
Deployment
This app can be easily deployed to any hosting provider that supports Node & React. Some options are:

Netlify
Vercel
AWS Amplify
Google App Engine
Azure Static Web Apps
Simply configure the provider to build & run the React app on their servers.

License
This project is open source and available under the MIT License.
