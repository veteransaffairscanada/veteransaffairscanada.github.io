---
layout: page
title:  "Changelog"
lang: en
permalink: "/changelog/"
trans_url: "/journal-des-modifications/"
---

_Find benefits and services_ will have consistent updates throughout the beta phase. All notable changes to this project will be documented on this page.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/). This product does not adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 2019-03-29
### Added
* Added UTM tags to outgoing links in the benefit cards for tracking

### Fixed
* Updated alert for the Treatment Benefits card
* Updated ‘Learn more’ links for the Pension for Life benefit cards
* Fixed some style inconsistencies

### Removed
* Remove alert for Vocational assistance card


## 2019-03-15
### Added
* Reintroduced the left hand persistent Edit Selections menu to the Directory page
* Added benefit cards for Pension for Life
* Added a distinct remove button to the saved list for clarity

### Fixed
* Header and footer that matches veterans.gc.ca
* Made logic updates to improve the results generated

### Removed
* Removed the ‘Service related health injury’ question
* Removed paths related to ‘Still serving’


## 2019-02-28
### Changed
* Look and feel of the application to match the new [VAC website](https://www.veterans.gc.ca/)
* Benefit card example information, additional benefit eligibility, and the program page link are no longer buried under "See more"
* Language for the next step on health records are agnostic to the user path

### Fixed
* URLs that broke with the VAC website update
* Translations for some benefit card content
* Bug that caused a failure when clicking "View results" after completing the selections in Internet Explorer
* Bug that caused all the benefit cards to be auto-expanded when the user lands on their results in Internet Explorer
* Copy link functionality works consistently
* Printing from the saved list prints the saved selections only

### Removed
* The summary page that confirmed users' selections before showing the results (users are now taken directly to their results)
* Feature for users to locate the closest VAC office (the app now directs users to VAC's contact page)


## 2019-02-15
### Added
* Feedback mechanisms for people to submit general feedback, report if something went wrong, and indicate if information is useful
* The benefit card for operational stress injury (OSI) clinics has an alert saying a case manager referral is necessary
* Content to let people know that selecting multiple categories will narrow down their results

### Changed
* Update "Next steps" content to more accurately reflect the person's chosen path and category selections

### Fixed
* Skipping previously answered profile questions now skips the dependent questions as well
