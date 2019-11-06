# github-organization-teams-report
    
## Description

Python script that generates a html report about teams, users, and repositories
Created to easily generate data to provide for a SOC audit of github permissions

---
### Scripts

`user_group_report.py`

The script requires two environment variables to be set

#### Environment variables required

`GIT_ACCESS_TOKEN` is used to authenticate against github to use their API (https://github.com/settings/tokens)

`ORGANIZATION` is the name of the organization you want to collect data for.

## Dependencies

To install dependencies

`virtualenv -p python3 venv`

`source venv/bin/activate`

`pip3 install -r requirements.txt`
