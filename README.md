# Node DB 4 Guided Project

Guided project for **Node DB 4** Module.

## Prerequisites

- [SQLite Studio](https://sqlitestudio.pl/index.rvt?act=download) installed.
- a rest client like [Insomnia](https://insomnia.rest/download/) or [Postman](https://www.getpostman.com/downloads/) installed.

## Project Setup

- [ ] **import** and clone this repository.
- [ ] **CD into the folder** where you cloned **your version**.
- [ ] type `npm i` to download dependencies.
- [ ] type `npm run server` to start the API.

Please follow along as the instructor uses Knex migrations and seeding to create a multi-table database schema.

## Virtual Assistant Example

- List of virtual assistants
- list of clients
- multiple clients per VA
- Keep track of engagement questions
  - Did the client have a particular question asked

## A good data model

- Captures ALL the information the system needs
- Captures ONLY the information the system needs.
- Reflect reality.
- Is flexible, can evolve with our knowledge of the system/domain
- Guarantee data integrity, without sacrificing (too much) performance.
- Is driven by the way we access the data, the data we need to see.

## Components

- Entities (Resources) -> nouns (Ex: A client, a Virtual Assistant)
- relationships -> foreign keys
- Properties (fields, attributes) --> columns

## Workflow

- one to one. Not common.
- one to many. This is it!
- many to many. this is a trick.

## Mantras

- every table MUST have a primary key
- many to many -> third table.
- do two or three entities at a time
- one to many -> foreign key
- foreign key where? -> many side.
- The third table can have extra information
