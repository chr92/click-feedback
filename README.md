Click Feedback
=============

What is this?
-------------

I've really struggled to find a decent system out there that collects one-click feedback from users in emails, then allows you to measure feedback over time. I'm building my dream solution in Meteor.

Also, the existing solutions out there are ridiculously expensive. I'm talking $50 per 100 responses or something. Why? no idea.

How will it work?
-----------------

You define a bunch of paramaters, and the symbols you need to include to pass them into the URL. E.g. {{customer.id}}. When you send an email to customers, these paramaters are filled.

The user clicks a link, and voila, their response is collected. There'll also be a simple textbox for any further feedback.

On the admin end, you can see some nice chart.js graphs and the raw feedback for your downloading pleasure. As I'm building this for myself the stats will focus on what I need out of them.

Finally, you'll be able to get a weekly email of the stats across your team.

Finally
-------

I'm making it open source so hopefully lots of people can benefit from using it. If you see something that sucks feel free to fix it.

Todos
-----

- [ ] Feedback Collection
- [ ] Admin Page
- [ ] Snippet Generator
- [ ] Charts 
- [ ] Email Reports
- [ ] Sexy Looks