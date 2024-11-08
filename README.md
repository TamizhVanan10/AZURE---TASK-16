# AZURE---TASK-16

### Step 1: Sign in to the Azure Portal

Go to the Azure Portal.

Sign in with your Azure account.

## Step 2: Create a New Logic App

In the left-hand navigation pane, select Create a resource.

In the search bar, type Logic App, and then select Logic App from the results.

Click Create.

Fill in the necessary details:

Subscription: Choose your Azure subscription.

Resource Group: Choose an existing resource group or create a new one.

Logic App Name: Provide a name for the Logic App.

Region: Select the region where you want to deploy the Logic App.

Click Review + Create, and then click Create once validation passes.

## Step 3: Define the Trigger

Once the Logic App is deployed, go to the Resource page for your Logic App.

Click on Logic App Designer under the Development Tools section.

You will be prompted to choose a trigger. A trigger starts the Logic App workflow. Common triggers include:

When an HTTP request is received

When a new email arrives (for Outlook or Gmail)

When a new file is added to OneDrive/SharePoint

When an event is logged in an Azure Monitor or Application Insights.

Select a trigger that suits your scenario. For example, if you want to start the logic app when an email arrives:

Choose Outlook > When a new email arrives.

Sign in to your account if prompted and set any trigger parameters (e.g., Folder, Filter).

## Step 4: Add Actions

After defining the trigger, click New Step to add actions.

You can search for various connectors and actions, such as:

Sending an email (e.g., Send an email (V2)).

Writing data to a database (e.g., Insert row in SQL Server).

Sending data to another system (e.g., HTTP to make an API call).


Search for Send an email (V2) (Outlook).

Specify the recipient, subject, and body of the email.'

Configure any other actions required, such as adding conditions or loops (e.g., Condition, For each).

## Step 5: Configure Advanced Features (Optional)

Conditions: Add conditional logic to decide what happens next based on a condition.


## Step 6: Test the Logic App

Once your Logic App is configured, you can test it by performing the trigger action (e.g., sending an email if you chose an email trigger).

To monitor the progress and view execution details:

Go to the Overview page of your Logic App.

Under Runs history, you can see all past runs.

Click on a specific run to see the details and diagnose issues.

## Step 7: Save and Deploy the Logic App

Once you’re happy with the Logic App configuration, click Save at the top.

Your Logic App will now be active and will automatically run whenever the trigger condition is met.

## Step 8: Monitor and Manage

Go to the Monitor section in the Logic App resource to view execution history
.
Use Run history to see whether your Logic App executed successfully or encountered any errors.

You can also set up alerts to notify you if the Logic App encounters failures.

## Step 9: (Optional) Modify or Update the Logic App

If you need to modify or extend your Logic App later, return to the Logic App Designer.

You can update the trigger, add new actions, or change existing logic as needed.
