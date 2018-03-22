# Seventh Week

## Work

I've merged the callback interfaces so it's a lot easier to deal with for everyone, optimized the threads using synchronize to wait and notify after each game is played and also fixed the resetting functionality so multiple games can be played.

Time spent: 3 hours.

Finished the interface description which describes the functions and uses of every class within the design documentation.	

Time spent: 2 hours.

## Group issues

Last week there was an issue with one of our group members pushing code that broke the build. As this member has only pushed two things, the other with a similar issue, and has had little to no contact with me regarding architecture I felt it better to bring it up in the meeting the following morning. Having informed him that there was an issue I was met with a hostile response refusing to acknowledge that he was responsible for the build breaking which I find completely arrogant and shows an inability to take criticism. 

Since nothing had been achieved regarding this issue during the meeting I decided to find out what was wrong with the code and was displeased to find that the memeber wasted their time and resources turning a trivial task that could have been resolved with a few lines of code into several functions containing over 90 loops. This was also for something that wasn't in the design specification or provided extra functionalities as this is the only instance in the program where random letter generation is needed. On top of this there was other parts that needed work as the program wasn't in a fully-functional state at this time.


