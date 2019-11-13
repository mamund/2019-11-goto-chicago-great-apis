## Activity Story at BigCo, Inc.

We keep track of company & account cusomer service activity at BigCo, Inc. 

Each company or company+account pair has one or more assocaited activity records. These records list the various ways (and reasons) BigCo staff will be contacting the company on various matters. It is, essentially, a contact scheduler and log. Current activityTypes in the system are email, inperson, phone, and letter.

Each activity record has the activityType, company identifier, account identifier, dateScheduled, and notes fields. There is also a status value (suspended, active, pending, closed). We also track the date/time the record was created and the date/time it was last updated. Account records cannot be deleted. 

Typical actions for Accounts are creating, editing, and closing (with notes).  You can also change the account status value. You cannot delete activity records. List filtering should be supported using status, companyId, and accountId.


