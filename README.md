# group_chat


Must have the following:
* login(could be just pick nickname or full signup process)
* cant be 2 people with same nickname
* chat room with the whole history
* an input to type messages
* messages must show the sender
* Bot youtube or giphy:
  * Giphy:
    * serach gif and show it.
  * Youtbe
    * that search on youtube(using api) with format:
    * /youtube song_name/artist
    * must place a youtube embed player with first result
 
 
 
Tech that must be used, front end:
* JS - Backbone
* HTML/CSS bootstrap



Backend:
* Whatever you like(we do like python so!)


Platform:
* Run on heroku free plan, or whereever you like but reachable from anywhere.

Must have tests, just few but tests... 

# To apply to basestone

* fork this repo
* create a PR with the implementation and URL to checkit

# URL Where is deploy

https://cmduquerchatgroup.herokuapp.com/

The application isn't running correctly on this site. I have a problem with the tomcat configuration.

You can run the application on your local machine using the next steps:
* Download netbeans https://netbeans.org/downloads/ , you must select the second option java ee.
* Install netbeans.
* After you install netbeans select file > Open project and search for the chat group project.
* Righ click on the root project and then select run.


# To run locally do

```
mvn package
java -jar target/dependency/webapp-runner.jar --port 9000 target/*.war
```
