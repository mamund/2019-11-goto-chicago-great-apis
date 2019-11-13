## Account API Vocabulary

### Action Elements
The following actions need to be supported:

 * CreateAccount
   * division, companyId, spendingLimit, discountPercentage,status)
 * EditAccount
   * accountId, division, companyId, spendingLimit, discountPercentage,status)
 * CloseAccount
   * accountId
 * UpdateAccountLimits
   * accountId, spendingLimit, discountPercentage
 * SetAccountStatus
   * accountId, status

### Data Elements
The following data properties need to be supported:

#### AccountData

* accountId
* division (r)(e))
* companyId (r)
* spendingLimit
* discountPercentage
* status (r)(e)
* dateCreated
* dateUpdated

The value for _acountId_ MUST be unique

The value of _companyID MUST already exist in the system

Valid _division_ values are:

 - DryGoods
 - Hardware
 - Software
 - Grocery
 - Pharmacy
 - Military

Valid _status_ values are:
 - suspended
 - pending
 - active
 - closed

