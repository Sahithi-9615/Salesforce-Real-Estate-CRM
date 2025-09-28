# Phase 3: Data Modeling & Relationships

## Objects
### Standard Objects
- Lead
- Contact
- Opportunity

### Custom Objects
- Property__c
- Visit__c

## Fields
### Property__c Fields
- Location__c: Text
- Type__c: Picklist (Apartment, Villa, Commercial)
- Price__c: Currency
- Status__c: Picklist (For Sale, Sold, Under Negotiation)

### Visit__c Fields
- Date__c: Date
- Time__c: Time
- Property__c: Lookup to Property__c
- Lead__c: Lookup to Lead
- Assigned_Agent__c: Lookup to User

## Relationships
- Opportunity to Property (Lookup)
- Lead to Visit (Lookup)
