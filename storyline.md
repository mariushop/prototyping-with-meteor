#A tale of tales


You are a young and bright developer with a sharp mind for mathematics and a little too much passion for roulette. This night in particular, after winning for 2 hours straight at the local casino, you feel like you just cracked the roulette's "code". However, you get distracted for a moment and all your chips are gone a moment later. Determined to get it all back in one hand, you borrow money from Bambalore, a shady Mob guy you know. You lose that money.

Running for your life, a month later you get hired at a software shop, in a small town in Tirol, Austria. The shop uses Meteor and on the interview you sweared it's nothing you can't pick up in a week. Your boss used Cobol when she was young so every now and then she expects you to explain to her how you do the things you do.

Things are far from cool: being the new kid in town gets you a desk on the hallway, under a red hidrant, so everybody coming in or going out can see your display. It's drafty and the ancient code editor you're forced to use has a 50% chance to crash every ten minutes or so, losing all your code, forcing you to rewrite it.

Ah,  immigrant life! By the end of the first day, your boss drops by and lets you know you have to deliver a chat app pronto. "I expect to see it by the end of the week, 'mkay?" she says, retreating into her big-windowed office from where you can see the misty Alps.

Next day, session one of your work on the chat app goes by and sure enough, you made good progress: you decided the app is gonna be called **latChat**, you installed Meteor and poked around a basic app. At one point in the morning the boss showed up and asked you to change the background of the interface, make an incrementer start from 2 and then to jump a 2 step on every click of a button. You did good and your relief is obvious: on your way home you walk lightly, the air is sweet and you feel like you're gonna master this thing, after all.

A day later, you write: "Dear diary, I'm sure there's something shady about the girl that sits on the front desk. Her hair is looking too yellow to be true and everytime I salute her she has the symptoms of a stroke. I guess she doesn't like me very much. On the professional side, it's the second day I'm working on this app. I got the messages into the database, although I'm not really sure how I save them on the client and they appear on the server too. I guess the database likes me very much, or something. I'm worried about not getting the "UserName is typing" message quite right. I'll deal with that tommorow. Good night, dear diary."

Day three: you had your first demo and... nailed it! Although you had approximately 30 minutes to achieve something, you got to having user accounts and message saving/displaying by the time you presented it. Now it's time to move on to a more secure way of getting your data from server to clients.  You learn about the Publications and Subscriptions. Day three lets you wondering if there's a way to subscribe to data right in the template where you will display it. Oh, and that nasty code editor bug that made you lose all your code: apparently gone.

Day 4: Yes! There **is** a way to subscribe to data right inside your template. Moving on, you discover routing with Iron Router, which lets you wait for data before rendering a template and setting the data context reactively. Also, you get to secure some leaking parts of your app, removing `autopublish` and `insecure` packages. Your app looks like a mature one.

It's the final day. This is it. Will you deliver?
Your boss walks up to you, bad tempered as always and expecting to see the app finished. You spent your last couple of hours working like crazy on the last feature (displaying user presence) and deploying the app on a server. 
"Let me see the chat app", she says, sitting in your chair.
Your hands sweating, you fire up a web browser and there it is, the chat app! While your boss is clicking away, signing up and sending messages, you pull up an Android device and fire up the mobile build on it. Silently, you put the phone on the desk, next to the keyboard. She looks up startled and then she understands. You implemented an Android app, too!
But you're not done, yet. From your other pocket you produce an iPhone, with the app running on it.
"Great job", she exclaims. "You're hired as a permanent!"
"No, thanks", you reply, full of yourself. "I realised that I'm very good at stuff. I bought a ticket to my hometown. I'll fight Bambalore and win and then I'll practice coding on my own rules. Goodbye."
