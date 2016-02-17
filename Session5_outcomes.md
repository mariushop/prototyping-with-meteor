#Session 5 Outcomes

In our final session we deployed our app for
 - Android
 - iOS
 - web (both testing & production environments)

For testing environment we used the free *.meteor.com* domain, to which we deployed with ``meteor deploy [appnamehere].meteor.com``. For production, we used a Digital Ocean server and the "meteor up" (``mup``) node package.

We recapped our knowledge on Meteor and implemented a functionality for tracking user presence, which was the missing piece in our goal to make a fully functional, real-time, channel-based chat app.


### Packages used to make latChat:

 * [bootstrap](https://atmospherejs.com/twbs/bootstrap) for responsive UI
 * [accounts-ui](https://atmospherejs.com/meteor/accounts-ui) for user management out-of-the-box
 * [check](https://atmospherejs.com/meteor/check) for checking arguments in functions (always check your arguments and drink your milk, children!)
 * [meteor toys](https://atmospherejs.com/meteortoys/allthings) for checking what data is on the client and what Session variables hold
 * [user presence](https://atmospherejs.com/tmeasday/presence) for deploying
 * [mup](https://github.com/arunoda/meteor-up) for deploying to production (Node package)

I had great fun building stuff with you.
Make fast prototypes, make me proud.

Congratulations, everybody!
