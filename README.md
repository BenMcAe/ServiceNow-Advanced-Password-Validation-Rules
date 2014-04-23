ServiceNow-Advanced-Password-Validation-Rules
=============================================

Enforce standard password validation rules with a stronger and configurable algorithm

-----------------------------------------------------------------------------------------------------------------------------------------
Features
-----------------------------------------------------------------------------------------------------------------------------------------
 How to enforce stronger password when users are reseting theirs passwords ? 

- New passwords must be different than previouses
- At least X characters
- X out of four character types (upper, lower, number, special)

All message are included in English.

Built from : http://wiki.servicenow.com/index.php?title=Strengthening_Password_Validation_Rules 

-----------------------------------------------------------------------------------------------------------------------------------------
Configuration
-----------------------------------------------------------------------------------------------------------------------------------------
- Choose the minium lenght of passwords (12 by default) : update the system property named "validatepasswordextrastronger.min_len", a integer is expected (min 1)

- Choose the minimum complexity of passwords (3 out of four character types (upper, lower, number, special) by default) : update the system property named "validatepasswordextrastronger.min_complexity", a integer is expected (min 1, max 4)

- Translate messages for other languages : Go to System UI > Messages and translate all messages starting with "validatepasswordextrastronger." in required languages

-----------------------------------------------------------------------------------------------------------------------------------------
Included in this update set
---------------------------------------------------------------------------------
- Installation Exist named "ValidatePasswordExtraStronger"

- Messages in English 

- System Properties for Easy Configuration
