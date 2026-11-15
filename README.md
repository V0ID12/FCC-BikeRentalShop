# Bike Rental Shop

An interactive Bash program for renting and returning bikes, backed by a PostgreSQL database.

## How it works

The main menu offers three choices: rent a bike, return a bike, or exit.

**Renting**
1. The script lists the bikes that are currently available, with their type and size.
2. You choose one and give your phone number. A new number prompts for your name and adds you as a customer.
3. The rental is recorded and the bike is marked as unavailable.

**Returning**
1. You give your phone number and the script lists the bikes you have out.
2. You choose one to return. The rental is closed and the bike becomes available again.

Invalid input at any step sends you back to the menu with a message explaining why.

## Files

- `bike-shop.sh`: the whole program.

This repo holds the script only. It expects a `bikes` database with `bikes`, `customers` and `rentals` tables, which the course builds step by step.

## Background

Built while following the *Learn Bash and SQL by Building a Bike Rental Shop* lesson in freeCodeCamp's Relational Database certification.
