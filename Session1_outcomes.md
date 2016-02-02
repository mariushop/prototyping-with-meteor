#Session 1 Outcomes

What happened:
 - we assessed the value of prototyping in *testing* assumptions, ideas, UI, functionalities;
 - we defined scope, basic functionalities and UI representation for a *chat app* named latChat (see image below);
 - we created an Meteor app and managed to
   - alter the style of the UI;
   - understand where the code runs (Server, Client);
   - use Session variables to set a default value for a variable, get it, set it;
   - explore Meteor templating system, learning about helpers, events, template inclusion, data passing to templates (mostly what **doesn't work**. By the way, we were looking for: [template inclusion with data](http://guide.meteor.com/blaze.html#inclusion));

Then the code editor crashed and we started all over again. After restart, we marched on:

- we created an input that would capture user input;
- fiddled around with an event that would catch the changing value (settled on `event.currentTarget.val()` as a getter of the input value);
- created a Session variable, set its value to the inputs value, and displayed in the template by getting its value in a helper (Sorry, Tomi, we did that in your absence, I think);
- watched in delight how the template updated as we typed in the input.

Thank you Georgiana, George, Zoli for typing away our suggestions and your enthusiasm; exquisite random function for simulating editor crashing, Zoli! I was impressed you actually implemented a nice interface for it.
Tomi and Calin, I apreciate you squized this into your schedule. 
Nice job, everybody, see you in session 2.


![img_0831](https://cloud.githubusercontent.com/assets/4264640/12757296/24837b50-c9e0-11e5-8fc6-d7eb7653b108.JPG)




