# StarbucksOfferAnalysis

# Introduction

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.


Not all users receive the same offer, and that is the challenge to solve with this data set.


Your task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

# Discription

Here is the schema and explanation of each variable in the files:



### portfolio.json


id (string) - offer id

offer_type (string) - type of offer ie BOGO, discount, informational

difficulty (int) - minimum required spend to complete an offer

reward (int) - reward given for completing an offer

duration (int) - time for offer to be open, in days

channels (list of strings)


### profile.json



age (int) - age of the customer

became_member_on (int) - date when customer created an app account

gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)

id (str) - customer id

income (float) - customer's income

### transcript.json


event (str) - record description (ie transaction, offer received, offer viewed, etc.)

person (str) - customer id

time (int) - time in hours since start of test. The data begins at time t=0

value - (dict of strings) - either an offer id or transaction amount depending on the record



## Problem Statement 

Whether a customer will respond to an offer or not and visualise success of an offer


## Blog

https://medium.com/@shaktiyashdeep/starbucks-offers-analysis-94fb3d65942e


## Repo link

https://github.com/YashdeepShakti/StarbucksOfferAnalysis

## Requirements

Anocondas distribution of python libaries



