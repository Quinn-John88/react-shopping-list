# React Shopping List

## Description

_Duration: 2 Day Sprint_

This App is an easy to use way to build a shopping list displaying a list of items, the amount of items, and what unit they are measured in.

### Prerequisites

Link to software that is required to install the app (e.g. node).

- [Node.js](https://nodejs.org/en/)

## Installation

1. Create a database named `fs-react-shopping`,
2. The queries in the `database.sql` file are set up to create all the necessary tables and populate the needed data to allow the application to run correctly. The project is built on [Postgres](https://www.postgresql.org/download/), so you will need to make sure to have that installed. We recommend using Postico to run those queries as that was used to create the queries, 
3. Open up your editor of choice and run an `npm install`
4. Run `npm run server` in your terminal
5. Run `npm run client` in your terminal
6. The `npm run client` command will open up a new browser tab for you!

## Usage

1. Start by entering in the information for the item you would like to add and hit the submit button.
2. Once the item is submitted the item will be displayed on the item list table.
3. From there you can either "puchase" or "delete" the item from the list. doing so will either indicate it has been purchased or remove the item from the list.
4. If you would like to "reset" the purchases or "clear" every item from the table, simple hit either the "reset" or "clear" button respectively.

## Built With

PostgreSQL
ReactJs
SweetAlerts2