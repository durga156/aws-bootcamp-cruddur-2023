# Week 0 — Billing and Architecture

## Required Homework 

### Summary
1. Created my Github repository as per instructions shared. This is the 1st time I'm using Github, so I learnt a bit about markdown file, how to insert a hyperlink and an image in the week0.md file. I also added Gitpod button on my Github page.

2. I created an Eventbridge rule for service health issues and this is the JSON from my rule

```
{
  "detail": {
    "eventTypeCategory": ["issue", "accountNotification", "scheduledChange"]
  },
  "source": ["aws.health"],
  "detail-type": ["AWS Health Event"]
}
```
3. I created a logical design using Lucid chart (again this is my first time with Lucid chart) and here is what I did -
 [Crudder design](https://lucid.app/lucidchart/a18d7514-4933-4a07-a2ee-8af360b3ffdd/edit?beaconFlowId=E556E2EC3C2FB24C&invitationId=inv_423e038c-d19c-41e3-8c8d-c3e4e4c00991&page=0_0#)

4. I created an IAM user, gave that IAM user access to Billing information. 

5. I set up MFA for Root AWS Account.
