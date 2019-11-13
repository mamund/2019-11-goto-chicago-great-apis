## The Onboarding Story at BigCo, Inc.

repo: https://github.com/mamund/2019-02-ndc-porto/

We need a new API that combines the work of the *company*, *account*, and *activity* services all into one place. It should offer a seamless experince, collecting data and generating new valid *company*, *account*, and *activity* records.

Users should be able to start an onboarding process that:

 * creates an onboarding record (for reference later)
 * prompts the user for company data
 * creates a valid company record
 * prompts the user for account data (just one for now)
 * creates a valid account record
 * prompts the user for activity data (start w/ an email sent two weeks out)
 * creates a valid activity record.
 * allows the user to 
   * review and, if all is good, commit the data and create all the records
   * cancel the whole job, if they wish
   * or go back and edit each part before submitting (version 2)


### Questions
  * "reference later"
  * "cancel the whole job"
  * "edit each part (v2)"
  * There is no security here
  * Should it be a sinble blob of JSON?
  * What if a record (company/account) already exists?
  * What roles are affected by this?
  * Who is responsible for creating this (API, Client)
  * Do we need to implement a transaction?
  
