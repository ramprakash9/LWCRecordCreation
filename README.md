# LWCRecordCreation
Component overrides the new button functionality of SObject.
As of today we have Idea Posted : https://ideas.salesforce.com/s/idea/a0B8W00000Gdh53UAB/override-standard-button-using-lightning-web-component-lwc
We cannot override standard new button directly from lwc .
We have to create a wrapper Aura component that will invoke the LWC . 
In the repository oppLWCAura is Wrapper Aura Component. 
gAS_OpportunityCreation is LWC component . That has form structure . It allows user to fill opportunity Details.
