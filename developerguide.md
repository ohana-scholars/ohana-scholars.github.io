## Developer Guide
Install meteor from the [Meteor API Docs](https://docs.meteor.com/install.html) page.

  To copy, change, or modify our web application, first go to [the repository](https://github.com/ohana-scholars/ohana-scholars-application), clone ohana-scholars-application by clicking "Code" and choosing "Open with GitHub Desktop", name your new repository, and use the IDE of your choice.

  Next open terminal and navigate to the /app directory and run `meteor npm install` to install the necessary files.

  Then run `meteor npm run start` and the webpage should be running at [http://localhost:3000](http://localhost:3000). bellow is an example of what terminal should show.

```
PS C:\Users\caspa\github\ohana-scholars-application\app> meteor npm run start

> meteor-application-template-react@ start C:\Users\caspa\github\ohana-scholars-application\app
> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.development.json

[[[[[ C:\Users\caspa\github\ohana-scholars-application\app ]]]]]

=> Started proxy.
=> Started HMR server.
=> Started MongoDB.                           
I20230424-19:18:17.978(-10)? Creating the default user(s)
I20230424-19:18:17.987(-10)?   Creating user admin@foo.com.
I20230424-19:18:18.052(-10)?   Creating user fool@foo.com.
I20230424-19:18:18.117(-10)?   Creating user john@foo.com.
I20230424-19:18:18.181(-10)? Creating default data.
I20230424-19:18:18.182(-10)?   Adding: Basket (john@foo.com)
I20230424-19:18:18.193(-10)?   Adding: Bicycle (john@foo.com)
I20230424-19:18:18.195(-10)?   Adding: Banana (admin@foo.com)
I20230424-19:18:18.196(-10)?   Adding: Boogie Board (admin@foo.com)
I20230424-19:18:18.199(-10)? Adding Courses.
I20230424-19:18:18.199(-10)?   Adding: Software Engineering I
I20230424-19:18:18.207(-10)?   Adding: Algorithms
I20230424-19:18:18.208(-10)?   Adding: Intro to the Study of Language
I20230424-19:18:18.210(-10)?   Adding: Beginning Filipino
I20230424-19:18:18.211(-10)?   Adding: Philippine Popular Culture
I20230424-19:18:18.213(-10)?   Adding: Composition I
I20230424-19:18:18.214(-10)?   Adding: Organic Chemistry I
I20230424-19:18:18.216(-10)? Adding Student.
I20230424-19:18:18.216(-10)?   Adding: John Doggo
I20230424-19:18:18.225(-10)?   Adding: Admin Doggo
I20230424-19:18:18.227(-10)?   Adding: April Fools
I20230424-19:18:18.231(-10)? Adding Emails.
I20230424-19:18:18.231(-10)?   Adding: Schedule Study Session (john@foo.com)
I20230424-19:18:18.241(-10)? Creating default sessions.
I20230424-19:18:18.242(-10)?   Adding: undefined (john@foo.com)
I20230424-19:18:18.251(-10)? Adding reputation.
I20230424-19:18:18.251(-10)?   Adding reputation: 9/10 by admin@foo.com
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.
   ```
