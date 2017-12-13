# EBSPCA-CiviCRM
CRM for SPCA
Nims and Associates
Rick Banghart (rbanghart@nimsassociates.com)

December 12, 2017

Allow an owner to register for a training class (Event) with pet. Entry form must accept owner name and info, pet name and info

Submitting form should:
1. Create Contact (Individual) based on owner info
2. Create Contact (Individual->animal) based on pet info
3. Create relationship Owner-Pet between owner and pet
4. Create Participant record based on owner info
5. Create Participant_Add record based on pet info

Feb 17, 2017
Setting benchmark target. Display an entry form for an event where age is restricted to, say, 14 and over. Validate form with (Event_Date - DOB >= 14) years.  
