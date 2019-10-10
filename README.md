# homework

First make sure you have mongod running in the background, and that you have the enron dataset in the database.

Clone this repo, then:

```
cd in-class
cd todo
npm install
npm run dev
```

At this point you should be able to go to:

http://localhost:3000/api/emails/peter.blackmore@compaq.com


And get back json data.

1. Copy that same route (line 34 to 39), but instead of taking sender as a param take text (i.e the field we want to filter by now is the text of the email, rather than the sender) as a param.  The param should be used to do a contains query with.

2. Copy that same route and instead of taking sender take two params, one called start and one called limit. Query the data, but then page based on the start and limit params. e.g if I pass 50 for start and 20 for limit, I should only get back 20 docs, but it should be starting from the 50th doc 


