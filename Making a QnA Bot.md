to<b>Create a Knowledge Base</b>
<br><br>
A knowledge base (KB) is the information hub the chatbot will scan for relevant information when answering questions. 
<br>Head over to qnamaker.ai to start this process.<br>
![image](https://user-images.githubusercontent.com/64722488/148645449-f26dcfd1-7f4a-49df-8195-f8bf580056fc.png)
Click Create a knowledge base and follow the prompts.<br><br>

Do not forget to Create a QnA service in step one and connect it to your KB in step two before creating the KB fully.
![image](https://user-images.githubusercontent.com/64722488/148645481-535de47e-5529-4259-834d-a4ab2344ebca.png)
<br><br>
A new tab will appear, but go back to the KB creation tab.

After deploying and connecting your QnA service, go through the rest of the KB setup prompts and populate your KB with documents or a URL.

Screenshot
![image](https://user-images.githubusercontent.com/64722488/148645511-589a1518-1717-49d5-8cf9-bc5c476c07be.png)

Enable the multi-turn extraction from URLs, .pdf or .docx files option.<a> This option </a>allows your chatbot to ask follow-up questions. It also allows the chatbot to scan entire pages for later feedback to the user.

Under the Default answer text box, pick any answer you want your bot to use if it cannot find an answer.

After a couple other basic prompts, you will be given a Chit-chat option for you to tailor your bot to fit a particular style of language or mood.
![image](https://user-images.githubusercontent.com/64722488/148645808-9c78a3ca-78b2-4b05-96e7-94a3428493f9.png)<br><br>
Next, click Create your KB to see the contents of your KB in three sections: Context, Question, and Answer.
![image](https://user-images.githubusercontent.com/64722488/148645829-540cc387-a123-40e3-9988-4344be40799b.png)
Under the question section you can add your own phrasing, add follow-up prompts to make your bot more unique, and direct your chatbot to provide a link to another page if it can't find an answer.<br>
![image](https://user-images.githubusercontent.com/64722488/148645843-5a202cd3-b9b7-42f7-a4a7-6c7dcd4c1987.png)
<br><br>
To start training your bot, click Save and train or Test. Before training, you will have to save.

Training your bot basically means saving any preferences you have added and helping the algorithm learn what you desire from the bot during interactions. The more examples you give, the more effective it will become.

Once you are satisfied with your bot, click PUBLISH. This will move the content from the test to production index in Azure search. You will have access to it via QnA Maker service. You will see a block of code you can copy and use later on your site or messenger for the HTTP request.

Click View.
![image](https://user-images.githubusercontent.com/64722488/148645880-19b0f11d-98a6-453c-8346-98f1900c5a9e.png)
Click Test in Web Chat in the Azure Bot services directory and ask the bot questions. At this point, the bot and KB should be connected.

You can go back to the QnA Maker website to edit your questions, answers, and follow-up questions. You can even add access control and tags to your QnA service, which are useful if you have more than one person running bot service and want to know who is running each bot.

It is worth including as many alternative questions as possible and different ways they can be asked so your chatbot can learn to better understand users and find answers.
