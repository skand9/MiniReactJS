# Simple React JS Project

## About

This Project is a Simple ReactJS Project which demonstrates the following
1. Create a react component
2. HTTP calls
3. Parent and child component communication
4. Integrating bootstrap to React
5. Basic routing

The project Template can be used to build bigger projects

## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g create-react-app
```

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**

## Application design

#### Components

1. **Customers** Component : The component is used to display a list of names. Data is retrieved from a json file in asset folder.

2. **CustomerDetails** Component : Displays the details of selected names. Child component.


#### HTTP client

**axios** library is used to make HTTP Calls

#### URL

The application has just one url /customerlist which ties to *Customers* Component

