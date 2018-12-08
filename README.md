# How to Deploy an MRE SDK App to Heroku

* Fork this project
* In Heroku, create new a new app, say `mankindforward-mre-test1`
* Set remote for your new app:
 `heroku git:remote -a mankindforward-mre-test1`
* Push and deploy your app
  * `git push heroku master`
* Configure the SDK App url in Altspace:
   * `ws://mankindforward-mre-test1.herokuapp.com:80`
