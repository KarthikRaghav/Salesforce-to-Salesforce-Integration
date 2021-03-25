## Success Metrics

1. Integrating two Salesforce environments to sync data between the two instances.
2. One Salesforce instance can be used as a Source and another Salesforce instance can be used as the destination.
3. Records can be transferred from source to destination by mapping desired objects and their respective fields in both the source and destination instances.
4. Not only allows us to transfer records from source to destination instances but also allows us to edit the values of the records which were transferred.
5. The changes made to the records in the source instance will be replicated in the records in the destination instance.

# Risks

1. Because updates to shared records are processed asynchronously and retried if a sync fails, they don't appear in the connected organization right away.
2. Data is copied between orgs, can increase data storage requirement for the receiving org.
