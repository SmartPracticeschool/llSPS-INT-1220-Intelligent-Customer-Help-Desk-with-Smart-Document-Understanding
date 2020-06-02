 "Intelligent Customer Help Desk With Smart Document Understanding"

● Project Summary :-
In this developer code pattern,we use the typical customer care chatbot experience but instead of relying on predefined response,our dialog will provide a hook that can call out to other IBM Watson services for additional sources of information.In our case,it will be an owner manual that has been updated into Watson Discovery.
The typical customer care chatbot can answer simple questions,such as store locations and hours,direction,and maybe even making appointments.when question falls outside of the scope of the pre-determined question isn't valid or offer to speak to a real person.
In this code pattern,we walk you through a working example of a web app that utilizes multiple Watson services to create a better customer care experience.
Using the Watson Discovery Smart Doument Understanding(SDU) feature,we will enhance the Discovery model so that queries will be better focused to only search the most relevant information found in a typical owner's manual
Using Watson Assistant,we will use a standard customer care dialog to handle a typical conversation between a customer and a company representative.when a customer question involves operation of a product,the Assistant dialog will communicate with the Discovery service using a webhook.
The webhook will be created by defining a web action using IBM Cloud Function. 

In summary,this code pattern will:
‣ Create a customer care dialog skill in Watson Assistant
‣ Use Smart Document Understanding to build an enhanced Watson Discovery collection
‣ Create an IBM Cloud Function web action that allow Watson Assistant to post queries to Watson Discovery

• Project Requirements :-
‣ Pre Defined customer care dialog
‣ Owner's manual

• Functional Requirement :-
‣IBM Cloud Function
‣IBM Watson Assistant
‣IBM Watson Discovery
‣Node red

• Technical Requirement :-
‣Python

• Project Deliverables :-
The code pattern provide excellent results.The chatbot provide answer to queries which fall out of pre determined questions 

• Project Schedule :-
‣4 week 
