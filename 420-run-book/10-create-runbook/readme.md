# Runbook Creation

1. Go to event manager -> Create Integration --> Automation --> Script --> Configure 
2. Copy the public SSH key into each target system where script has to be executed. 
3. Go to Automation -> Runbooks --> New Automation --> Create a script based automation by copying/typing the required commands. Optionally give the target system IP and username with which script has to be executed in target system --> Save the automation.
4. Go to Library --> New Runbook --> Give name, desc etc and select "Add automation step" and add 5. script automation created in previous step.

This article explain about how to create run book in Event Manager.

The article is based on the the following

- RedHat OpenShift 4.6 on IBM Cloud (ROKS)
- Watson AI-Ops 3.1.0

## Steps

In the event manager click on `Automation --> Runbook`

<img src="images/image-11.png">

We are going to create a Runbook which has some automation scripts.

Click on `Automation --> New Automation`

<img src="images/image-12.png">

Being, it is first time, we need to configure Integrations to connect from Event Manager to the target system, from where the script is going to get executed.

Click on `Configure`

<img src="images/image-13.png">

You are in Integrations page.

Click on `Configure`

<img src="images/image-14.png">

ssh into the target system, from where 

<img src="images/image-15.png">
<img src="images/image-16.png">
<img src="images/image-17.png">
<img src="images/image-18.png">
<img src="images/image-19.png">
<img src="images/image-20.png">
<img src="images/image-21.png">
<img src="images/image-22.png">
<img src="images/image-23.png">
<img src="images/image-24.png">
<img src="images/image-25.png">
<img src="images/image-26.png">
<img src="images/image-27.png">
<img src="images/image-28.png">
<img src="images/image-29.png">
<img src="images/image-30.png">
<img src="images/image-31.png">
<img src="images/image-32.png">
<img src="images/image-33.png">
<img src="images/image-34.png">
<img src="images/image-35.png">
<img src="images/image-36.png">
<img src="images/image-37.png">
<img src="images/image-38.png">
<img src="images/image-39.png">
<img src="images/image-40.png">
<img src="images/image-41.png">
<img src="images/image-42.png">
<img src="images/image-43.png">
<img src="images/image-44.png">
<img src="images/image-45.png">

