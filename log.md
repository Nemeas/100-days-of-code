# 100 Days Of Code - Log

### Day 1: 18.07.2018 (my birthday actually =)
**Todays Progress**: Creating the project files. Trying to land what expectations I should have for the final product.

**Thoughts:** I am writing this on day 4 actually, since I didn't really decide to do the 100DaysOfCode until now. I have had the idea for this app for a while, just havent had the energy nor the will to do anything about it, until I downloaded and started reading "Crusing hyper-casual games" by Trey Smith.

**Link to work:** [Numbers](https://github.com/Nemeas/Numbers)

### Day 2: 19.07.2018
**Todays progress**: Getting something on screen. Just a list of hardcoded numbers that change color when beeing pressed.

**Thoughts:**: It's been a while since I coded any java, but it's slowly coming back to me.. Also, the new Android Studio seems better than and more snappy than the one I used a long time ago when it was still in beta.

### Day 3: 20.07.2018
**Todays progress**: Getting a single stage of the game "ready". Testing out my reference a bit to get some inspiration.

**Thoughts**: When learning coding we used java, and after getting a job I have been mostly in the .NET universe. Revisiting java now, feels like a step back. There are a lot of problems I have had to solve in different (using more code) ways than I would have if I were coding C#.

### Day 4: 21.07.2018
**Todays progress**: Getting the different states of the game to behave as one would expect. Also, levels are complete and numbers no longer overlap.

**Thoughts**: Things are progressing faster than expected, getting a feeling that this might actually turn into a game at some point. Still missing a lot of things around the game, like score, lvls, balancing difficulty, animations, graphics.. but the game-logic is more or less in place.

### Day 5: 22.07.2018
**Todays progress**: No progress today, just Android Studio trouble.. Did make an attempt to create a positive/negative feedback when completing / failing a stage, animating an image, to no success.

**Thoughts**: StackOverflow to the rescue!

### Day 6: 23.07.2018
**Todays progress**: Made the animation work!!

**Thoughts**: I am sitting here at 11.30 PM, just finished the one hour of work I'm supposed to do today, and thinking that tomorrow is going to be tough... Still doing the log, and the tweet, but I am wondering if there will be days without any coding at all..

### Day 7: 24.07.2018
**Todays progress**: No progress in the form of a commit =(

**Thoughts**: Trying out the android Ad thingie, looking at the documentation, reading, coding, getting confused, not knowing what I'm doing.. I get this feeling a lot.. Most of what is in the documentation is things I have no clue what means.. Usually I just try googleing the problem before turning to the documentation. This usually pushes me in the right direction. Propably going to do some more googleing tomorrow.. 

### Day 8: 25.07.2018
**Todays progress**: Successfully added ads between each lvl of the game and learned how the whole ads thingie works. 

**Thoughts**: Interesting how easy it is to implement. Also awsome of team google to make so detailed and updated step-by-step guides of how to implement the stuff. Easy and fun to see something that just works right out of the box!

### Day 9: 26.07.2018
**Todays progress**: Makes it possible to complete one lvl, see the ad, and then start playing the next lvl. Also refactoring and structuring a lot of code.

**Thoughts**: I got the exact amount of work I expected done today! And I would like to call the new feature "play-next-lvl". I am thinking that the game should perhaps make use of the Google Play Games to keep track of lvl, highscores etc, at least I believe I can use it for that.. I have no idea how I'm supposed to implement it, nor how it works, so this would be awsome exercise to learn something new.

### Day 10: 27.07.2018
**Todays progress**: No real progress, just playing around with different types of activities/fragments/dialogs to see what works for a "congrats! you did well, tap here to play the next lvl"-message.

**Thoughts**: I don't feel like today was really productive. I got nowhere with the dialog, didn't really feel like this was the correct path, so I guess that I'll try making the message like an Activity next, fullscreen and all, more like my reference; Peak.

### Day 11: 28.07.2018
**Todays progress**: Added a visualisation of the time remaning of the lvl. Also just comitted the next-lvl dialog, even if it don't really work that well, it covers the happyday scenario.

**Thoughts**: I am wondering if I should throw in a new element to the game. Now that the timer is visible, I would like to add a visual cue to random numbers, telling the user that this is a special number (not push this button, allways push this button last/first ?). The cue should indicate that there is some kind of reward attached to the number, like add 6 seconds to the timer, and what action to take. For now the only data I have is the timer and a counter counting completed and failed stages in a lvl... 

I do want this game to be released in some form on Google Play, so I should perhaps just make the game playable before starting to add all kinds of cool and complicating features.. I tend to get too troublesome ideas, setting my standards waaay too high, and never completing a project. If there is one thing I have learned from coding professionally it is three simple letters: MVP! Featuers can be added on later, but making the core functionality is priority 1.

### Day 12: 29.07.2018
**Todays progress**: Added a bit of a delay before each lvl giving the player time to get ready for the next lvl.

**Thoughts**: There are lots of animations needed to get things to look smooth. Haven't really noticed that before in apps, but without them everything feels so off..

### Day 13: 30.07.2018
**Todays progress**: Reading up on Google Play Games.

**Thoughts**: There is a lot to take in.. not really shure what I am reading, or what I want from this service, or what this service can do.. Will continue to do some research.

### Day 14: 31.07.2018
**Todays progress**: No coding progress today, got the app installed on my physical phone, and did some testing. Turns out there is a couple of things that needs more attention than beeing able to log into the game using Google Play Games.

**Thoughts**: I'm thinking the gameplay is ok, but it looks like there is something wrong with the positioning. Also need to add a splash-screen, with perhaps some local highscore (to begin with), and a button to start the game. It's a bit annoying that it just starts when starting the game, no time to prepare..

### Day 15: 01.08.2018
**Todays progress**: Got all the bugs I found when testing on the physical device sorted out and pushed!

**Thoughts**: Only thing missing now is the start-screen, and perhaps some graphics... Also, no progress is beeing tracked, so I don't think the login with Google Play Games is necessary per now. Need to figure out what I'm going to track first..

### Day 16: 02.08.2018
**Todays progress**: Fixing more bugs related to if you press the back-button on the phone when the game has started, etc. Also added a startGameScreen, including a placeholder image and a button that says "Play".

**Thoughts**: It's getting there. I'm happy I started testing the game on my physical phone.. there is so many things that can happen!

### Day 17: 03.08.2018
**Todays progress**: Fixing even more bugs related to outside influence (turning off the screen), but this made me add an "pause"-feature =)

**Thoughts**: Bugs, bugs, bugs, bugs.. so much to think about.. But I think I have something that workes better now than it did yesterday, so thats a win! I need to figure out how to make the player progress.. I want this to be done using some kind of algorithm.. taking the score over time, and creating a lvl of difficulty appropriate to the players current state.

### Day 18: 04.08.2018
**Todays progress**: Trying to make the difficulty in the game interesting.. ended up with a frame that will do the job, but not the implementation.

**Thoughts**: I did a couple of attempts here, but none felt good when playing. My mind also wandered towards ML, but I have no idea where to start, and I think perhaps this might be overkill for my first game.. I don't want to maintain a list of hardcoded game-difficulty-setup, I want some kind of algorithm to just make it happen, in a good way..

Also I need to figure out how to lvl a player. I don't know what to use.. I can't really just say that, ok, you finished the first stage with 20 wins, so you are now lvl 2! congrats! Hm.. then the difficulty should increase, so it would be more difficult to reach 20 wins.. hm.. I might be on to something here..

Also I was thinking that if you could manage, lets say 5 stages with over 15 (win-fail) you get an achievement, and this continues for 10, 15 etc.

### Day 19: 05.08.2018
**Todays progress**: Trying out a way to set the number of numbers based on a players lvl.

**Thoughts**: Still missing some way of modifying the min-max range. I want the player to have a set min-max based on the lvl, but it should be tweeked if the player suddenly fails a lot, to make it a wee bit easyer, and the range should be increased as the player progress.

Just had an idea.. Of how to increase difficulty without having to just tweek the min-max. The size of the buttons could decrease as the player progress, and even better; move. They can float around, or even better; "flow" using the accelerometer, so that they suddenly seem to "float on water".

### Day 20: 06.08.2018
**Todays progress**: Refactoring code to make it less chaotic!

**Thoughts**: It took some time, but I eventually figured out that the only way this state-machine was going to not bug so much was to refactor out as much as possible to try to create some kind of single-responsibility-thingie, and it worked! The bug no longer is.

Have to test more now that there are less bugs. Also I'm wondering if I should create some kind of dev-hack to set the lvl, because now I have to play several stages in order to lvl enough to play on the more advanced lvls.

### Day 21: 07.08.2018
**Todays progress**: Added login with google, and retrieving the profile-image from the object returned to display on screen.

**Thoughts**: I am thinking of removing the increase in difficulty, and add a leaderboard with points beeing wins - loss.. not shure yet.. Perhaps I should start with that.. or even easyer, display the highscore on the startScreen, and just saving it locally.. Then release the game to some betatesters, see what's up, and THEN perhaps setup a highscore-list.. somewhere..

### Day 22: 08.08.2018
**Today's progress**: Branched off a playable version of the game to start the release process.

**Thoughts**: Looks like there are some things that don't really fit together.. need more time..

### Day 23: 09.08.2018
**Todays progress**: Got the APK uploaded, but now I need testers..

**Thoughts**: Perhaps I'll ask twitter for help here..

### Day 24: 10.08.2018
**Today's progress**: Gotten a few testers, pressing publish!

**Thoughts**: What happens next..

### Day 25: 11.08.2018
**Todays progress**: Waiting for testers to install and give feedback.

**Thoughts**: What to do while waiting..

### Day 26: 12.08.2018
**Todays progress**: Trying to figure out how leaderboards work.

**Thoughts**: There is a lot to take in here.. I both love and hate the way the different resources are linked, I have like 50 tabs open in Chrome, all originated from some resource.. I'm never going to get through all this..

### Day 27: 13.08.2018
**Todays progress**: Added login again.

**Thoughts**: So I removed the login from the alpha to make it a pure on-device kind of game.. noone played it, so I'm going to add a leaderboard! And now I need the login again.. Doing it as automatic as possible, no user interaction needed, unless it's the first time.

### Day 28: 14.08.2018
**Todays progress**: Added leaderboard!!!

**Thoughts**: So... that was easy... once I got to the correct resource, there was like 3 lines of code.. and it looks amazing!

### Day 29: 15.08.2018
**Todays progress**: Created a new alpha-version!

**Thoughts**: I hope everything works perfect!! Then I'll be able to just push this alpha to beta!

### Day 30: 16.08.2018
**Todays progress**: Fixing bugs

**Thoughts**: There is a reason that we have alpha before beta before release!.. Turns out only I can login, and only with my dev-account... I have no idea what's going on...

### Day 31: 17.08.2018
**Todays progress**: Reading a lot! and adding the alpha-testers as testers in the testingPlace..

**Thoughts**: Turns out that for a person to test the game, I need to manually type the email into a group of testers where I can manage the releases of the game.. I ALSO HAVE TO ADD THE EMAIL IN THE list in the TestingPlace of the Google Play Console for the testers to be able to actually login to the game... This has taken me 2! TWO!! days to realize!!!

### Day 32: 18.08.2018
**Todays progress**: Adding the correct SHA1 to firebase, downloading the updated google-services.json and testing the new signed apk before releasing a new alpha, to make shure the login works..

**Thoughts**: There is a difference between running in debug-mode vs. installing the signed apk, and runnning that. It's more troublesome, and you get no debug-info, but for testing, it's gold!

### Day 33: 19.08.2018
**Todays progress**: Waiting for alphas to test and collecting bugs on the fly.

**Thoughts**: Leaderboard.. why you no work allways?!

### Day 36: 22.08.2018
**Todays progress**: ...

**Thoughts**: I am starting to think that this leaderboard-thing is not worth the effort.. I have read and tried one hundred and fifty six million and four different "oh, you just have to do these 15 steps exactly as I write them"s and nothing has worked.. 

After getting some distance from the project, I wonder if there might be a problem with the way I access the leaderboard, or perhaps the way I retrieve the logged in user.. or perhaps that I just use an old version of some API, and that this is fixed in later versions..

I am currently using the way to retrieve users as described on the android official sites. I have also followed exactly the way to implement the leaderboard as described on the official android sites..

It's wiered that everything works perfect when I am in debug.. Some say that every problem they had with the leaderboard went away when setting the game out in production.. Perhaps it's worth a try.. It's either that or remove the whole thing.. Just have the local highscore.. 

### Day 42: 28.08.2018
**Todays progress**: After more or less just giving up, I have spent a couple of days writing the whole thing all over again, using an example https://github.com/playgameservices/android-basic-samples/blob/master/TypeANumber, to no avail... leaderboards still don't work.. also added a score counter in the game-play section, and a back-button on the "congrats! this is your score"-dialog. 

**Thoughts**: So instead of using seperate Activities for each scene, I now use Fragments, which are more like components in angular, so it's something I am used to, so the whole refactoring didn't take long. I was hoping that since I was using seperate Activities and the login was its own activity, and the show-leaderboard-button was on some other activity, the user-login-thing would be wrong, but no.. Still won't show the leaderboard after submitting a score..

### Day 44: 30.08.2018
**Todays progress**: Adding vibration on fail, fixing some bugs after refactoring to using fragments.

**Thaughts**: Still going nowhere with the Leaderboard-problem.. I have no idea what to do..

### Day 45: 31.08.2018
**Todays progress**: Leaderboards are a go! Turns out that all I needed was to bump the minSDK version? Had to do this to add the vibration on fail.

**Thaughts**: I.. am.. soo.. content! Now all that's missing is fixing one (or more) bugs, and it will be ready for open beta.
