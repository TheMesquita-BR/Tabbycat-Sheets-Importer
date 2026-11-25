# About

This script was created for use at a past edition of CMUDE some time ago, and after some time, ended in Brazil (Thanks Alelí!), when i (the maintainer of this repo) started to use it.

I did some little improvements to it (fixed the institutions headers, added the speaker cat import, etc), but most of the work was made by the past users, so all credits to them. 

# Usage
### Script Properties

To get this working, you need to set up 3 properties in the [project settings, under script properties](https://developers.google.com/apps-script/guides/properties):

- `API_KEY`: Accessible at the change password menu from the base URL
- `BASE_URL`: The base URL of a Tabbycat instance (Example: https://iiicnd.calicotab.com) + /api/v1 at the end (so should look like this: https:/iiicnd.calicotab.com/api/v1) **(ALWAYS USE HTTPS - CalicoTab and most providers refuse non-secure connections)**
- `TOURNAMENT_SLUG`: The tournament slug, found in the end of the URL (Example: https://iiicnd.calicotab.com/IIICND/ - IIICND would be the slug)

### Sheets Tab

This script expects the data to be displaced in 3 tabs:

- `ADJ`: For judges data
>Values: `name`, `instName`, `score`, `gender`, `email`
- `TEAMS`: For teams and speakers data
>Values: `teamName`, `shortName`,	`codeName`,	`instName`,	`fullName1`,	`email1`,	`gender1`,	`cat1`,	`fullName2`,	`email2`,	`gender2`,	`cat2`
- `INSTITUTIONS`: For institutions data
>Values: `instName`, `code`, `region`

### Values

***TBD***
