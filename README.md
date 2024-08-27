#Watson x scedule displayer bot 

This bot is trained to display any schedule that is given to it while knowing the current time and day. Note that this version is displaying my school schedule, but with some effort, you can make it display your own schedule.



#Process of making the bot:

1. First, I created the action by pressing "New Action" in the Action tab.
2. Then, I added a step to verify the user's classes.
3. Next, I counted the number of periods in a day and added each period as a step.
4. After that, I input each period into the bot.
5. I then specified the day and time for each period.
6. I ironed out some bugs after doing that.
7. Finally, I implemented user testing.


#learnings:


Some of the learnings I discovered during the process of making this bot are interesting, to say the least, and they include:

* You cannot import datasets for the bot to train on; you will have to manually hard code them into the actions.
* Always pay attention to the order of your actions, as it will determine the flow of the bot.
* For custom messages, either go to the Preview tab and select the second option, or go to the third tab to disable the home screen. Then, go to Action, set   it by Assistant, and go to Greet Customer. Finally, change the description of that action to your welcome message.
* It’s best to have only one action in your bot at most.

I struggled to get the bot to even show the welcome message, as it was my very first time using this software. Due to that, it took me a considerable amount of time to manage the bot, but I eventually finished it.

# extra links 


these links will also be given. 


link to preview th bot: https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Fau-syd.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fupx-7c08e759-3502-4cc2-a483-bb8afe69a624%3A%3A9e54e3a9-59f7-4c50-b8fe-10968bf384bb&integrationID=7525c892-ccac-434d-aed9-17c02955639f&region=au-syd&serviceInstanceID=7c08e759-3502-4cc2-a483-bb8afe69a624

link to a drive folder showing a flowchart of the bot, and a video showing futher proof of creation:

https://drive.google.com/drive/folders/1A8HswId3i9SADNeXkYF-LyuhXsYg9kN_?usp=sharing
