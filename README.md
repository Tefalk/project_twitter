# project_twitter
Pull stuff useful for weight management from twitter.
The twitter aspect of this project has been suspended until I decide what to do about my privacy settings.
However I am currently developing a "MyNetDiary"based solution that I have ultimately moved to use Perl as a parser.

My first iteration was to base an implementation on the approach documented in a coding rainbow youtube video.
While this worked to the extent that I was able to print tweets containing a keyword specified via a "q" parameter in the code. I was not able to print my own tweets, possibly due to a privacy setting.
The basic process is to exit the "p5 server" that will likely be running in a terminal window, then "cd" to the "project twitter" subdirectory of the "collections" folder, then run "node bot.js".

Description of using git to make changes to the Heroku code

Commit your code (after making changes by editing bot.js, this github version is not current, see project_twitter folder).
$ git add .
$ git commit -am "commiting the code"
Send to heroku!
$ git push heroku master

When done with twitter, go back to the collection directory and execute "p5 server".


This process has now been implemented as a dyno in Heroku and may be executed from its website. It may be necessary to go to the "more" drop down menu to "restart all dyno".
