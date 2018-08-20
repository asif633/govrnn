# govrnn

Code has been deployed on heroku free server. The server sometime goes to auto sleep when not used. So in that case multiple refresh of url will help. This problem happens only when no one used the app for several minutes. This problem will not happen when you are using the app.

For govrnn website https://evening-gorge-22549.herokuapp.com
For govrnn admin https://evening-gorge-22549.herokuapp.com/admin
For admin you can use username: govrnn@admin.com password: 123456

For govrnn website if register does not work you can use username: koel@gmail.com password: past309#

## Present Situation
Admin Side:
1. Admin can add new sentiment, references of that sentiment, attachments of that sentiment, polls of that sentiment and news of that sentiment using single interface tabs. Tabs can be enabled and move forward. Means one first has to submit sentiment details -> references, attachments -> polls -> news. There are no validation on fields what so ever. So if you leave fields as empty there will be empty database fields also. When adding references, attachments and polls please ensure clicking + sign after filling out entry fields.
2. Admin can add, update, delete categories.
3. Admin can add, update, delete rss feed sources which are used to read news.
4. Presently no update of sentiments, references, attachments, polls, news etc. Will be added in future.

Home Site:
1. Sentiments and its details can be viewed. No verdict icon on top of single sentiment.
2. User can register, login.
3. User can add opinion on sentiment. When clicking on agree or disagree with sentiment; there is not any visible change whether you clicked agree/ disagree will be fixed soon.
4. User can response to sentiment. User can reponse to an opinion.
5. User can rebut a response. All rebuts visible when clicking on rebuts link.
6. Rebuts can't have more rebuts.
7. The chart of agree/ disagree percentage is working with sentiment.
8. Like, Dislike, Views, Share etc. on opinion is not available, so clicking them will not change anything.
9. No chart for agree disagree on opinion.
10. Lazy loading or Pagination loading of news is definitely a must for server as well as client side (loading spinner). In future will e added.
