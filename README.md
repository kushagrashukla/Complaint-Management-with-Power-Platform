# Microsoft-Power-Platform-Demo
This is the demo I created during my internship at Microsoft. The demo shows how the technologies of Power Platform can be used to automate traditional complaint management processes. This demo was built using the following Microsoft Licenses - 
i) Office E3
ii) Dynamics 365 Customer Engagement 
iii) Power Platform
iv) Power Virtual Agent

The following files represent the relevant components of Power Automate, Power App and Power Virtual Agent used to create the demo.

1) File name 'Case' represents the topic created in Power Virtual Agent used to trigger conversations.
2) File name 'Check case status' is a flow that returns the status of the case from Microsoft Dynamics.
3) File name 'Customer Cases App' is a power app using Common Data Services entities to interact with the registered cases in Dynamics.
4) File name 'Pepper' is the exported Power Virtual Agent. Pepper is the name of the bot
5) File name 'Retrieve Case' is a flow that checks if the input case number is registered in Dynamics.
6) File name 'Send an email when a case is resolved' is a flow that sends an email to the customer with the survey link when the case is closed in Dynamics.
