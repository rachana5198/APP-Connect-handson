# APP-Connect-handson

### Overview
In this lab, you will create a simple application flow using IBM App Connect. You will create a basic application flow for both event driven flows and flows for API.
### Steps to register for IBM Cloud
Go to [IBM Cloud](https://cloud.ibm.com/login)
If you are a existing user, login using your credentials. If you are new user, register for IBM cloud and login.
![](img/picture1.png)
### Setup an APP Connect service
1. Lets go to [IBM Cloud Catalog](https://cloud.ibm.com/catalog) and search for App Connect.

![](img/picture2.png)

2. Click on the service App Connect to instantiate it on IBM cloud.

![](img/picture3.png)

3. Click on ```create```

![](img/picture4.png)

4. Launch the service by clicking ```Launch App Connect```

![](img/picture5.png)

### Creating event driven flows

1. After launching the dashboard, click on New. (Rename your flow, if needed)
To create a new event driven flow, ```New -> Event-driven flow```

![](img/picture6.png)

2. To add applications to your flow, Click on '+' and select applications that you want to add to your flow. Here, we are creating a simple flow to send emails at some interval of time.

![](img/picture7.png)

3. To be able to schedule events, there is a tool called scheduler in the toolbox. To add this to your flow, ```+ -> Toolbox -> Scheduler```

![](img/picture8.png)

4. Configure the scheduler component according to your preferences. Here I am creating a flow that sends email for every one minute.

![](img/picture9.png)

5. To add the next node to the flow, click on '+'. Here, we are adding email component so that we will be able to send emails at scheduled time. To do this, ```+ -> Applications -> Gmail -> Create email```

![](img/picture10.png)

6. Connect the account using which you want to automate this task(preferably your gmail account).
To connect your account, ```Click on gmail node -> Connect```. This will redirect you to gmail login page, finish the login and permissions and refresh the IBM App connect page, then you should be able to see your account in the drop down.

![](img/picture11.png)

7. Configure the email node with your details and content.

![](img/picture12.png)

8. To start the flow, click start from the right corner of the screen.

![](img/picture13.png)

9. Once the flow starts and the dashboard shows the status 'Running' that means the event flow has started. To cross check, go to your email and see if there is a new email.

![](img/picture14.png)

This is how event driven flows work, scroll down to see some sample flows in Sample flows section.

### Creating flows for API

1.

![](img/picture15.png)

2.

![](img/picture16.png)

3.

![](img/picture17.png)

4.

![](img/picture18.png)

5.

![](img/picture19.png)

6.

![](img/picture20.png)

7.

![](img/picture21.png)

8.

![](img/picture22.png)

9.

![](img/picture23.png)

10.

![](img/picture24.png)

11.

![](img/picture25.png)

12.

![](img/picture26.png)

13.

![](img/picture27.png)

14.

![](img/picture28.png)

15.

![](img/picture29.png)

16.

![](img/picture30.png)

17.

![](img/picture31.png)

### Integration servers with APP connect

### Import and export flows

### Sample flows
1. Use the For Each node and JSONata to process high-priority issues.
![](img/sf1.png)
2. Create new leads in ```Marketo``` by capturing lead names and details in ```Slack```
![](img/sf2.png)
3. For large ```Salesforce``` opportunities, send an email and create an ```Asana``` task
![](img/sf3.png)
4. At regular intervals, extract ```Salesforce lead details``` and upload ```Box files``` with CSV output.
![](img/sf4.png)
5. Create ```NetSuite ERP``` and Stripe products from ```Asana tasks``` to launch a ```Salesforce Pardot campaign```.
![](img/sf5.png)
6. Build an API to create or update leads in ```Salesforce``` based on a ```Google Sheets spreadsheet```.
![](img/sf6.png)
