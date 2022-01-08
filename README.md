# Future-Ready-Talent-Final-Project-Chatbot
Build an Chatbot using Microsoft Azure Technology.

Chatbots are nothing new. In fact, they have been around in some form since the '60s. But those chatbots were nothing like what we have today with machine learning (ML) algorithms, which allow them to learn how to interact with users more effectively over time. Many companies are competing with their own variants to stand out from the pack, like Microsoft with its Azure platform.

This guide covers setting up a chatbot using Azure Bot Service.

<b>###########Creating the Basic Bot##############</b>
<br>Create your account and log in to Azure Portal.
![image](https://user-images.githubusercontent.com/64722488/148644885-06c13762-c261-436a-ba2f-72a214f69ca4.png)

<br><br>

Click AI + Machine Learning on the left, then the Web App Bot icon and fill in the required information. If you haven't set up any other Azure services, most of these fields will be blank.<br>

Click Create new to create a resource group. You can have one resource group with the free plan. Resource groups are containers that hold related resources such as apps that share a lifecycle.


![image](https://user-images.githubusercontent.com/64722488/148644973-b6381991-cda2-4de7-b462-cffa90833046.png)

![image](https://user-images.githubusercontent.com/64722488/148645068-6e403c17-92e1-4014-935e-8c386a4cbe1d.png)
<br>

Next, set up a Bot template. Choose whether the bot's SDK language will be C# or Node.js and whether it will be an Echo Bot or a Basic Bot. For anything other than a bot that echoes back the user's messages, choose Basic Bot.

![image](https://user-images.githubusercontent.com/64722488/148645095-2d74e4f3-260b-4a9d-9057-a0418ee117ab.png)
<br>
View more samples will take you to the Bot Framework samples repository where you can see examples of chatbots you can create with custom code.


![image](https://user-images.githubusercontent.com/64722488/148645138-9fc9331c-af13-4728-98c5-b4c37d2bc08f.png)
<br>
To create your QnA Bot, you will first need to deploy the basic bot in Azure and create a knowledge base (KB) for it.
<br><br>
You also need to create an account for Language Understanding (LUIS), which is a cloud API service. Choose its location and an App service plan, and click Create.
<br><br>
The Location is related to where the resource group is hosted, meanwhile the Luis App Location relates to where you will author and publish the knowledge base.
<br><br>
There are three main regions and each have separate keys and Luis portal URLs. Use eu.luis.ai for Europe, luis.ai for US and au.luis.ai for Australia. You can export and import apps to different regions, but that is less important for the purposes of just a chatbot hosted on a page. Host where you want to target a user base.

![image](https://user-images.githubusercontent.com/64722488/148645219-6e133764-c321-4b02-a870-45d55e393fda.png)
<br>
You will get a notification when your basic bot is deployed. From there it needs to be turned into a QnA Bot.
![image](https://user-images.githubusercontent.com/64722488/148645251-cba9a054-3acb-4030-9b3b-0f4d634f1079.png)
Click on your bot's name in the All resources menu to test it in a web chat
<br>
![image](https://user-images.githubusercontent.com/64722488/148645280-3c94d7f0-9af3-4592-83e9-f5bb98309044.png)

