#Session 4 Outcomes

Changing channels in our chat app didn't worked *exactely* the way we wanted. We could switch channels, but instead of getting just the messages for the selected channel, we got the sum of all messages on all channels.

By using `Template.subscribe` and `Template.autorun`, we got the behaviour we were after:

```javascript
Template.comments.onCreated(function () {
  var self = this;

  // Use self.subscribe with the data context reactively
  self.autorun(function () {
    var dataContext = Template.currentData();
    self.subscribe("comments", dataContext.postId);
  });
});
```
Then we organized our code in `client`, `server` and `lib` folders, properly separating code into easy-to-maintain chunks.

It was time to tackle a Meteor application boilerplate: [Void](https://github.com/SachaG/Void), by Sacha Greif. We installed the `iron:router` package and understood how routing works on the client.

Good job, everyone!



### Some useful resources:

 * [Meteor Docs](http://docs.meteor.com/#/full/quickstart) for full Meteor API;
 * [Meteor Guide](http://guide.meteor.com) for best practices when using Meteor.


