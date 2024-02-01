# Prizewinner Portal POC

A repository to prove the concept of a prizewinner portal for radio competitions. Born out of the Innovation Challenge, and replicating 'delivery tracking' functionality.

## Build Details

- Built in Craft CMS, running on DDEV and Docker.

## How to run
1. Pull this repo
2. You must have Docker running, then run `ddev start`.
3. To install any craft-specific packages, then run `ddev composer install`.
4. You can then import the database - contact matthew.gibbs@bauermedia.co.uk for the backup of this. Use `ddev import-db --file="/file-location/database-name.sql`.
5. You should be all good to go!