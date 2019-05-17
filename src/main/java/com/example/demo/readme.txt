A brief summary of how to use this program:

Basically, logging in as the average user (joe/password) allows you to see localhost:8080/
(the base website available to every avergae user). However, if they type in the url address bar
localhost:8080/admin, they get a forbidden error.

As an admin (me), using login (doyle/password), I am able to see localhost:8080/admin. However, I must @{/admin}
in the url bar to see the admins-only page. Otherwise, when I log in, I just seem the same page as average joe.