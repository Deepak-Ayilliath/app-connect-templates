To refer to these instructions while editing the flow, open [the github page]() (opens in a new window).

## Prerequisites

1. Click **Create flow** to start using the template.
2. Connect to your [JIRA account](https://www.ibm.com/docs/en/app-connect/cloud?topic=apps-jira)
3. Connect to your [Salesforce account](http://ibm.biz/ach2salesforce)
4. To start the flow, click the ellipses on the top right. This opens the options menu [&#8942;]. We can then click **Start flow**.

## Using the template

1. Click **Create flow** to start using the template.
2. Click each node to review its configuration. If necessary:
   - Connect to your [Salesforce account](https://developer.ibm.com/integration/docs/app-connect/how-to-guides-for-apps/use-ibm-app-connect-salesforce/).
   - Connect to your [JIRA account](https://www.ibm.com/docs/en/app-connect/cloud?topic=apps-jira).
3. In the conditional node in between the JIRA node and the Salesforce node, check to see if status (i.e., "$Trigger.fields.status.name") is "Closed".
4. To start the flow, click the ellipses on the top right. This opens the options menu [&#8942;]. We can then click **Start flow**.