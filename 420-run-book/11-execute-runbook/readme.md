# Runbook Execution

This article explain about how to execute run book in Event Manager.

The article is based on the the following

- RedHat OpenShift 4.6 on IBM Cloud (ROKS)
- Watson AI-Ops 3.1.0

## Steps

Whenever an event created in event manager, the event manager flags the event if the event attribute matches to the trigger condition of any of the runbook stored in event manager.

You can see the dot under `Runbook` column for the `Rating Pod Down` event.

Click on the event record

<img src="images/image-11.png">

On the right side, you will have list of actions.

Click on `Launch Runbook`

<img src="images/image-12.png">

It opens up the Runbook page.

Click on `Start Runbook`

<img src="images/image-13.png">

It contains 1 step only.

Click on `Run`

<img src="images/image-14.png">

Step executed and status is successful.

Click on `Complete`

<img src="images/image-15.png">

Give feedback about the runbook.

Click on `Runbook Worked`

<img src="images/image-16.png">

Click on `Execution`

<img src="images/image-17.png">

You can see the execution history.

<img src="images/image-18.png">