# DayPlanner

This DayPlanner will help you organize your day, with easy color coded assignments. There are three colors: grey means the past, red means current, and green means the future. 

Once the time has pass and the area becomes grey it becomes a read only. I just added a clear all function where when you click on it a confirm box will pop up asking if you really want to clear all. If you confirm, it will clear your whole inbox along with any saved data.  


My take on the assignment:
This DayPlanner seemed simple to code when psuedocoding but I actually encountered a couple of hurdles when coding. I tried to make one click event listener for all the buttons, but I would need a new key for each text. I thought of just having all 9 rows save to an array no matter which button you clicked but I don't think the intent was that since it'll save everything even if you didnt want to. At the end, I added an eventlistener to each button and stored it on a prefinded key. 

I tried to use as much jQuery as I could but when referencing textarea through the for loop doesnt seem to like it, you have to call it for example $(p:first) instead of just p[i]. I might of went at this the wrong way but I still learned a lot about jQuery as I was coding. Overall this homework was a nice and easy assignment and a different pace from code quiz where it was a lot of moving parts at once and sometimes you get lost in your own code.