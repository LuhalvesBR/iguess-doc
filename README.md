# iGuess Documentation

##### GuessLine 
Everything that linked with predictions.

##### GuessLeague 
About the users leagues.

## Tech Stack
* Node.js v8.x.x // NPM v5.X
* MongoDB v3.4
* PostgreSQL v9.6
* Redis v3.2.6
* React Native

## Git Branch Partner Name
Feature
* To create some new feature to the Repository
* feature{{FeatureNickName}}_{{HistoryNumber}}
* example: featureSignUp_04_23

Fix
* To fix something from development branchs to production branch
* fix{{FixNickName}}_{{HistoryNumber}}
* example: fixNavBar_05

Hot Fix
* To fix something from production branch to development branchs
* hfix{{HotFixNickName}}_{{HistoryNumber}}
* example: hfixPaymentCreditCard_08

Poc
* To development something to test new things
* poc{{PocNickName}}_{{HistoryNumber}}
* example: pocTestingGolf_06

# Style Guide
(The project's styleguide rule overwrite the general rule from this styleguide)
* Use always 2 spaces, without tabs or 4 spaces.
* Use always English name to variables.

TODO: Check the https://github.com/airbnb/javascript/blob/master/README.md


# Google Cloud Platform
#### App Engine Commands helpers:
* List all apps -> gcloud app versions list
* Deploy a version -> gcloud app deploy app.dev.yaml --version 0-0-5 --no-promote --quiet
* Stop a version -> gcloud app versions stop --service holi 0-0-5  --quiet
#### Compute Engine Commands helpers:
* List instances -> gcloud compute instances list
* Stop Redis -> gcloud compute instances stop redis-1-vm-1
* Start Redis -> gcloud compute instances start redis-1-vm-1
#### Cloud SQL Commands helpers:
* List instances -> gcloud sql instances list