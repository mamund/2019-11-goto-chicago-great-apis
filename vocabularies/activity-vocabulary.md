## Activity API Vocabulary

### Actions

 * CreateActivity
   * activityType(r), companyId (r), accountId, status(r), notes, dateScheduled
 * EditActivity
   * activityId, activityType(r), companyId (r), accountId, status(r), notes, dateScheduled
 * CloseActivity
   * accountId 
 * ChangeActivityStatus
   * accountId, status (r)
 * ListActivities
   * (none)
 * GetActiity
   * accountId
 * FilterActiities
   * actvityType status, companyId, accountId

### Properties

* activityId
* activityType (r)(e)
* companyId (r)
* accountId
* dataScheduled
* notes
* status (r)(e)
* dateCreated
* dateUpdated

Valid _activityType_ values are:
- email
- inperson
- phone
- letter

Valid _status_ values are:
 - suspended
 - pending
 - active
 - closed

