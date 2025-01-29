# ADM+S 'Google Scholar-Clever' Sync Checker
This repository contains an automated approach for determining how 'in sync' your ADM+S Clever entries are with your Google Scholar profile.

To get yourself set up, create a new Python virtual environment, install the `requirements.txt` file, and then run the software as a command line script, by specifying your first and last name, as well as your Google Scholar profile ID (this is typically the part that sits after the `user=` parameter of your Google Scholar profile URL):

```
 python run.py <FIRST_NAME> <LAST_NAME> <GOOGLE_SCHOLAR_PROFILE_ID>
```

For example like so:

```
 python run.py "Abdul" "Obeid" "iAtNdR8AAAAJ"
```

Once executed, it will scrape your ADM+S research outputs and your Google Scholar profile, before outputting any entries that have not yet been added to ADM+S Clever.
